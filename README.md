# es player - open source encrypted stream player for android

#version: 2026-03-17-1

files are on google drive, because I cannot upload file through browser, if it is bigger than 25MB:

https://drive.google.com/drive/folders/171E1WYpe6Zb2JOSm_ZnVV77P7e6InS6w?usp=sharing

**Android**

**ES player** - open source clearkey encrypted dash stream player for android 

Download es_player.apk to install on android

- supports clearkey 1 and multiple keys encrypted dash streams
- written in flutter, uses mediakit
- beta version
- does not support widevine

**how to use**
- add playlist(s): http://www.something.../play.m3u
- use left right for prev next channel
- tap to pause (you will see icon for channel-list and settings on th bottom, and icons for next and prev channel)
- pull down - show channel-list
- pull up - show settings screen

on the settings screen:
- swipe right - go back to play screen
- pull down - update currently selected list

**es_player_source.zip** - source files for es player

tofix: sometimes it takes too long to add playlist. just click cancel, list should be added anyway.

todo:
- add support for remote
- make version for pc, using flutter + webkit + shaka


**ver**

2026-03-17-1

---

**"encryptionstream_test_server_single_and_multi_keys"** - mini server for testing player apps that can play encrypted streams

#version: 2026-03-17-1

issues posted:

ANDROID:

https://github.com/brunochanrio/DangoPlayer/issues/24

https://github.com/Fredolx/open-tv/issues/317

https://github.com/oxyroid/M3UAndroid/issues/371

https://github.com/AndreyPavlenko/Fermata/issues/686

PC

https://github.com/4gray/iptvnator/issues/656

https://code.videolan.org/videolan/vlc/-/issues/29465

https://github.com/mpv-player/mpv/issues/17063


ANDROID, not open source

also televizo app.

ott navigator can play these files (closed source, no automatic update)

sparkle tv sometimes (closed source, max 3 hours update, current choice)

no desktop pc app (maybe Kodi).


**ver**

2026-03-17-1
- added text to video

2026-03-15-1
- updated docs 
