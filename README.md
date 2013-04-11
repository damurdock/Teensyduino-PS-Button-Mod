##Teensyduino PS Button Mod

###Introduction
This file is a modified usb.c library for Teensyduino that allows you to use the "PS button" when making custom USB controllers for the Sony PS3.

###Installation
To install, simply install the latest Teensyduino and replace the existing usb.c file with this one. This file will be located in different places, depending on your OS. 
Windows: /Arduino_Install_dir/hardware/teensy/cores/usb_hid/usb.c
Linux: /Arduino_Install_dir/hardware/teensy/cores/usb_hid/usb.c
OSX: /Applications/Arduino/Contents/Resources/Java/hardware/teensy/cores/usb_hid/usb.c
Note that future Teensyduino revisions may break compatibility. If that happens, file a bug report and I'll get on it.

###Usage
Using this library is just as simple as using the unmodified Teensyduino library. There is a button reference included in this repo (taken from my PS2-USB project). The PS button is mapped to button number 13.

###Credits 
Obviously, this uses code provided by PJRC and licensed under MIT. This project also uses code from the UnoJoy project (unojoy.com) and would not have been possible without their assistance. Unojoy is licensed under GPLv3, a copy of which has been provided.