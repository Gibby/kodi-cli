"kodi-cli" and its simple GTK3 frontend
=======================================

Kodi/XBMC bash script to send Kodi commands using JSON RPC. It also allows sending youtube videos to Kodi. The GTK3 frontend simpliefies sending YouTube links and controling basic aspects of playback withing X, as for example seeking by clicking on the progress bar.

![GTK3 frontend screenshot]
(https://github.com/elpraga/kodi-cli/blob/master/send_YouTube_link_to_Kodi-screenshot-playing_from.png?raw=true)

#Usage

`kodi-cli -[p|i|s|(y|q) youtbe URL/ID|t "text to send"|o "youtube title"]`

#Arguments
```
 -d Decrement the volume on Kodi
 -f toggle fullscreen
 -g go to specified percentage of the video
 -h showing this help message
 -H Host to control(Defaults to local host)
 -i interactive navigation mode. Accept keyboard keys of Up, Down, Left, Right, Back,
 	Context menu and information
 -n play next item in current playlist
 -o play youtube video directly on Kodi, use the name of video (this option depends on using mps-youtube)
 -p Play/Pause the current played video
 -P Port on host to control(Defaults to 8080
 -q queue youtube video to the current list, use either URL or ID (of video); use instead of -y
 -r retreive the percentage of the total time that has been played already
 -s stop the playback
 -t 'text to send'
 -u increment the volume on Kodi
 -U User to connect to kodi as(Defaults to none)
 -W Password to use when connecting to kodi(Defaults to none)
 -y play youtube video; use either URL or ID (of video)
 -z suspend the system with Kodi

```

#Dependencies
for the "-o" option to work you'll need to install [mps-youtube](https://github.com/np1/mps-youtube)

#Version
1.1
