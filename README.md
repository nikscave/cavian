# Cavian
DIY Gate/Trigger sequencer using Teensy 4.1 and Novation Launchpad Mini

Tutorial in the works - find me on [YouTube](https://www.youtube.com/channel/UCJ2dZmSUlZZw6ZqKoc_eHWQ/videos)

Steps:

1. Install [Teensyduino](https://www.pjrc.com/teensy/td_download.html)
2. Solder headers to the USB Host section of the Teensy (+5v, D-, D+, GND)
5. Connect Novation Launchpad mini (tested on Mk1, Mk2 should be ok) to the USB Host headers. 
3. Load Cavian HEX file using the [Teensy Loader](https://www.pjrc.com/teensy/loader.html)
4. Outputs 4 to 11 are used for output triggers/gates. Teensy outputs around 3.5v, plenty for most modules. 
5. On initial launch open serial monitor within Teensyduino. Note down your hardwares unique ID.
6. Join me on [Patreon](http://patreon.com/nikscave) to help me develop this and upgrade for all working/beta features.
7. Have fun!
