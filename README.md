# Printrboard-HID-Arduino-IDE-Support
**Printrboard HID Arduino IDE Support for Arduino 1.6ish**

This is an assembly of files taken from PJRC's Teensyduino distribution (https://pjrc.com/teensy/td_download.html) combined with the LUFA HID bootloader and uploader for the Printrboard courtesy of Lincomatic (http://blog.lincomatic.com/?p=548), together with a minor rewrite of the Arduino boards.txt file, to facilitate compatibility with recent versions of the Arduino IDE. It has undergone limited testing with Arduino 1.6.8; notes of your experiences with other versions from 1.5 onwards, either here or on the RepRap wiki would be welcomed.

To use, copy the printrboard folder to your Arduino hardware folder and restart the Arduino IDE. You will also require the HID bootloader on your Printrboard, which is included and can be flashed directly from the IDE (UNTESTED).

Regarding licensing, Teensyduino states "Numerous files covered by various open source licenses are installed by Teensyduino. Nearly all are provided in source code form. Please refer to the comments within each file for copyright and licensing information." The LUFA library is released under the MIT license.
