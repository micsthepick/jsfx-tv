# jsfx-tv

Play Composite B&W patterns out of your pc's soundcard! *(Designed and tested on PAL components, NTSC can be prepared on request?)

## setup:
Copy files to \<REAPER install dir\>/Effects
Configure to use WASAPI/ASIO/lossless:
* non-dsd version: set samplerate to 192000 and highest bit depth you can
* dsd version: set samplerate to 176400 and to 24bits (will not work unless these settings are exactly represented in the top right when reaper is running)
connect your pc to the RCA port (yellow) of the TV with a typical stereo 3.5 to RCA cable
ensure that the TV is tuned to the correct RCA port

some theoretical stuff:

max amount of samples per line in non-dsd version is about 6-7

dsd version has a much greater capability, due to having an effective samplerate in MHz but will require some tuning to get it to display properly, and some further development to get patterns to display properly

Usefull information in the making of this project:

https://en.wikipedia.org/wiki/Composite_video  
https://en.wikipedia.org/wiki/Direct_Stream_Digital  
https://en.wikipedia.org/wiki/PAL
http://martin.hinner.info/vga/pal.html

https://en.wikipedia.org/wiki/Component_video  
https://en.wikipedia.org/wiki/YPbPr  
(component version coming soon?)
