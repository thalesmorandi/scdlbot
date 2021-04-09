Version history
===============

0.13.6 (2020-08-03)
-----------------------
* add and handle timeout for youtube-dl get-url and cookies file download
* update requirements

0.13.5 (2020-08-02)
-----------------------
* update requirements

0.13.4 (2020-05-10)
-----------------------
* support tiktok video download/upload
* update requirements

0.13.3 (2020-04-18)
-----------------------
* many cosmetic refinements
* update requirements

0.13.2 (2020-03-25)
-----------------------
* use scdl fork with soundcloud api v2 support
* add support for m.soundcloud links for new scdl fork
* bump requirements

0.13.0 (2020-02-28)
-----------------------
* upgrade to python-telegram-bot version 12
* support photo captions with links
* disable support for edited messages
* replace goo.gl with yandex' clck.ru, shortening works properly again
* refactor a little, remove deprecated configs, start fixing docs

0.12.2 (2020-01-14)
-----------------------
* refined source IP handling

0.12.1 (2020-01-13)
-----------------------
* hotfix for env parsing

0.12.0 (2020-01-13)
-----------------------
* add support for source IPs randomization for downloading from youtube

0.11.0 (2020-01-12)
-----------------------
* add support for cookie file for youtube-dl - it helps with downloading yandex.music from different countries

0.10.0 (2020-01-07)
-----------------------
* use ffmpeg-python for converting instead of RAM-heavy pydub, remove pydub requirement
* update docs and requirements
* many cosmetic and CI fixes

0.9.27 (2019-12-01)
-----------------------
* return timestamp to scdl using some hacks
* don't treat one track's fail as playlist's fail for scdl

0.9.26 (2019-11-30)
-----------------------
* upgrade requirements to use scdl from git
* various deployment and CI/CD improvements

0.9.21-25 (2019-11-04)
-----------------------
* catch scdl 'not streamable' error and add some explanation about youtube '429 too many requests' error
* upgrade requirements
* add python 3.8 support
* various deployment and CI/CD improvements

0.9.20 (2019-10-11)
-----------------------
* upgrade requirements
* add python 3.7 support
* remove pyup
* fix travis pypi access

0.9.19 (2019-02-09)
-----------------------
* edited help message
* upgrade requirements

0.9.18 (2018-09-01)
-----------------------
* upgrade requirements

0.9.17 (2018-05-12)
-----------------------
* upgrade requirements

0.9.16 (2018-03-08)
-----------------------
* markdown in audio captions HOTFIX

0.9.15 (2018-03-03)
-----------------------
* markdown in audio captions

0.9.14 (2018-02-11)
-----------------------
* source is now captions
* more precise help and settings

0.9.13 (2018-02-11)
-----------------------
* short original links in captions
* wait a bit added

0.9.12 (2018-02-11)
-----------------------
* flood is now source
* wait a beet/beat random
* provide youtube video titles in caption
* 200 char caption text wrap

0.9.11 (2018-02-10)
-----------------------
* send tags and time length to Telegram
* extract-artist feature
* wait a beet
* requirements updated

0.9.10 (2017-12-14)
-----------------------
* convert non-mp3 files to mp3
* don't apologize for pictures
* don't allow sc/you links
* some renaming, move get_direct_urls to utils

0.9.9 (2017-12-12)
-----------------------
* serve audios with nginx and send URLs instead of files https://core.telegram.org/bots/api#sending-files

0.9.8 (2017-12-05)
-----------------------
* b0tan logging improvement
* requirements updated

0.9.7.2 (2017-12-05)
-----------------------
* console debug logging

0.9.7.1 (2017-12-05)
-----------------------
* easter egg added

0.9.7 (2017-12-04)
-----------------------
* new telegram logging
* only admins can change settings
* close button in settings

0.9.6 (2017-12-03)
-----------------------
* separate file for utils, botan track refactored
* parse message for markdown text links too
* temporary disable SSL verification for botan (cert expired)

0.9.5.2 (2017-12-03)
-----------------------
* hot fix

0.9.5.1 (2017-12-02)
-----------------------
* fix logging

0.9.5 (2017-12-02)
-----------------------
* settings command
* persistent storage for settings
* refactoring

0.9.4 (2017-11-27)
-----------------------
* exception-driven behavour
* clutter is now flood
* better alerting

0.9.3 (2017-11-22)
-----------------------
* don't spam on second try
* better logging config for different destinations

0.9.2 (2017-11-21)
-----------------------
* more error checking and responding with errors
* much much much polishing and refactoring

0.9.1 (2017-11-20)
-----------------------
* more error checking and responding
* limit youtube-dl time to download
* avoid live downloads
* logging refactor and refinement
* help updates

0.9.0 (2017-11-20)
-----------------------
* return of inline mode as fast download (link is sent to telegram servers for download)
* refactor and refinement
* help updates
* add some spam captions :)

0.8.3 (2017-11-19)
-----------------------
* gc.collect() according to https://github.com/jiaaro/pydub/issues/89#issuecomment-75245610

0.8.2 (2017-11-19)
-----------------------
* cool refinements in logging
* store urls, so button response is faster now

0.8.1 (2017-11-19)
-----------------------
* some logging fixes

0.8.0 (2017-11-19)
-----------------------
* many fixes and workarounds
* alerting & logging

0.7.10 (2017-11-05)
-----------------------
* botanio fix - send user id, not chat id

0.7.9 (2017-11-05)
-----------------------
* botanio fix
* tmpreaper config sample
* clutter fix

0.7.8 (2017-11-04)
-----------------------
* botanio
* maintenance

0.7.7 (2017-09-11)
-----------------------
* maintenance

0.7.6 (2017-09-11)
-----------------------
* SYSLOG_DEBUG env var to disable logging of full messages
* maintenance
* Logentries support

0.7.5.1 (2017-09-03)
-----------------------
* YouTube number remove

0.7.5 (2017-09-03)
-----------------------
* maintenance

0.7.4 (2017-08-03)
-----------------------
* msg_store fixes

0.7.3 (2017-07-20)
-----------------------
* orig_msg_id hotfix and don't send chat action on every link

0.7.2 (2017-07-19)
-----------------------
* Updated requirements

0.7.1 (2017-07-05)
-----------------------
* Hotfix

0.7.0 (2017-07-05)
-----------------------
* Travis CI, tests and docs from cookiecutter

0.6.3 (2017-07-04)
-----------------------

* Back to bandcamp-dl and scdl and download timeouts

0.6.2 (2017-07-04)
-----------------------

* Help message in groups now redirects to PM

0.6.1 (2017-07-03)
-----------------------

* Async run of download/send command
* Link command

0.6.0 (2017-07-02)
-----------------------

* Added text files to sdist
* Bandcamp and SoundCloud-widgets is now downloaded with youtube-dl
* Supported parsing widgets from pages
* Refactor

0.5.1 (2017-07-02)
-----------------------

* New clutter command
* Help refinements
* Some fixes

0.5.0 (2017-06-28)
-----------------------

* Big refactor to class-based
* Syslog support
* Some fixes

0.4.0 (2017-06-15)
-----------------------

* Console script!
* Setup script version improvements
* Ask in groups only, download immediately in private
* Bandcamp: Download links without 'bandcamp' for /dl
* Move TODOs to issues
* Button to destroy music from the Internet

0.3.1 (2017-06-12)
-----------------------

* Markdown to reStructuredText
* Copy tags to parts

0.3.0 (2017-06-10)
-----------------------

* YouTube playlists support
* Split audio by 50 MB size for sending
* Disable privacy mode and ask for download

0.2.0 (2017-06-06)
-----------------------

* Webhooks and async

0.1.0 (2017-06-04)
-----------------------

* First usable and stable version.
