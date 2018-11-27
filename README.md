**Open DJ (ODJ)**

Open DJ or oDJ project is a project that aims to build a fully open source tabletop mediaplayer like pioneers X/CDJ or Denon SC5000 allowing DJ's to do more with their equipment than just DJ. The goal so far is to build 3 models one CDJ which contains CD/USB/SD card and ethernet/wifi link up connections, one XDJ which contains USB/SD, ethernet connections, wifi & LoRaWAN and a modular model which will start with an USB/SD but is expandable and get it's own development kit. Since this all can be quite complex and we have a tech community with more knowledge than just me, I want to build a community around this. This topic for a relatively simple device will be heavily cross domain. The goal is to provide an Open Source building block for smart clubs. 

**On the hardware side**

Some of the lower level .hdl is already avaible. The architecture is close to a 16bit PDA all though this is limited this enough to represent data, playback audio and such. 

The goal is to get all hardware open source. You can check the upcoming CAD drawings for housing reference and 3D printable parts in .stl files. 

-Bottom bracket
-Bottom housing for the PCB
-Pitch strip  - 15%/30% - wide 100%
-Play button
-Cue button
-Jog wheel
-Touchscreens
-Housing top
-fwd/bck flip

Extra chips and interfaces: LoRaWAN, ethernet, wifi

**Software**

As most of you know, CDJ/XDJ's these days aren't just a circuit board, it's rather easier to build a simplified PDA or an embedded Linux device. The software should be able to read the inputs from the device and give outputs. It should also be able to read and manipulate audio files with certain actions. 

-playback formats: MP3, OGG, WAV untill 16 up to 24 later bit depth 48 Khz, FLAC
-Manipulate: speed, pitch, 
FUTURE 32 or 64 bit version
-Accept: VST's to manipulate 32/64 bit (the VST format is hold by Steinberg)

How to achieve this? 
A simple embedded Linux would provide enough capibilities, we can build on top of extract code from projects like MIXXX or at least gain knowledge from it. 


**Donations to the project**

I will do this project mostly as an artist. I am taking donations I will spend on the development of the project. 

Bunq - iDeal & SoFort
https://bunq.me/rk9

PayPal
https://paypal.me/JoeriJungschlager
