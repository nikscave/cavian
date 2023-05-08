# Cavian
(Eurorack) DIY Gate/Trigger sequencer using Teensy 4.1 and Novation Launchpad Mini

Overview of all features now on [YouTube](https://www.youtube.com/watch?v=9b2nG33aL-s)

Steps:

1. Install [Teensyduino](https://www.pjrc.com/teensy/td_download.html)
2. Solder headers to the USB Host section of the Teensy (+5v, D-, D+, GND)
5. Connect Novation Launchpad mini (tested on Mk1, Mk2 should be ok) to the USB Host headers. 
3. Load Cavian HEX (1.2.2 is latest version as at 8th May 2023) file using the [Teensy Loader](https://www.pjrc.com/teensy/loader.html)
4. Outputs 4 to 11 are used for output triggers/gates. Teensy outputs around 3.5v, plenty for most modules. 
5. Add Temp/Swing(Random probability) encoders as per schematic.
6. Add reset/clock in/outs as per schematic (when you decide to add them)
7. If you add a eurorack 12v to 5v regulator, please share any details and I'll include in here :-) I run mine on USB only.
8. The svg template is how I remember which buttons do which. Post it notes or a sharpie on the LED's will work also :-)


![Launchpad](https://nikscave.github.io/Launchpad_Cavian.JPG)
![Teensy41](https://nikscave.github.io/Teensy41_Cavian.JPG)
![Module](https://nikscave.github.io/Cavian_Module.JPG)
