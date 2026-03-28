# es player - open source encrypted stream player for android

#version: 2026-03-28-1

binary files are on google drive, because I cannot upload file through browser, if it is bigger than 25MB:

https://drive.google.com/drive/folders/171E1WYpe6Zb2JOSm_ZnVV77P7e6InS6w?usp=sharing

**Android**

**ES player** - open source clearkey encrypted dash stream player for android 

Download es_player.apk to install on android

- supports clearkey 1 and multiple keys encrypted dash streams
- written in flutter, uses mediakit
- beta version
- does not support widevine

**how to use**

- tap: pause, show playlist, and icons for: prev channel, channels list, settings, next channel
- up on remote/swipe from up to down: prev channel
- down on remote/swipe from down to up/dpad down: next channel
- left on remote/swipe from left to right: show channel list
- right on remote/swipe from right to left: show settings

on the settings screen:
- swipe right - go back to play screen
- pull down - update currently selected list

-you can put URLS to your playlist in Documents/esplayer.txt, so you do not have to type them in manually: 
Documents/esplayer.txt content: 
http://mysite1.com/list1.m3u  
http://mysite2.com/list2.m3u  


-you can search playlist, and save the result to new playlist


-you can put local playlists files in Documents folder, and esplayer will add them. 
(this is also used for saving search to new playlist)  

local_playlist_example.m3u:  
#EXTM3U
#EXTINF:-1,stream 1
http://website.com/list.m3u
#EXTINF:-1,stream 2
http://website2/list.m3u

-you can add playlist(s): http://www.something.../play.m3u from settings screen

-from the channellist you can switch playlists or update them
-added support for subtitles, more settings.

todo:
- make version for pc, using flutter + webkit + shaka

**ver**

2026-03-28-1
- working on improving android tv ui.

2026-03-22-1  
- added support for subtitles
- more settings
- remote support (to test)

2026-03-17-1
- first version

---

**"encryptionstream_test_server_single_and_multi_keys"** - mini server for testing player apps that can play encrypted streams

#version: 2026-03-21-1

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

2026-03-21-1  
- added tests for user agent and referrer

2026-03-17-1
- added text to video

2026-03-15-1
- updated docs 
