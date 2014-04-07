hdpov
=====

Hard Drive Persistence of Vision Clock powered by Arduino.

I used these instructions to build the hardware: http://www.instructables.com/id/Hard-Drive-Persistence-of-Vision-HDPOV/

My version used hall effect sensor for the platter revolution detection. 
I placed the magnet opposite of the slot on the platter, not ideal for balance but it works. Can be easily modified.

The original Arduino code in that instructable required a serial connection to a computer to actually draw patterns on the drive. I wanted mine to be standalone so I heavily modified the code to function independently while retaining the interupt driven pattern drawing.

TODO:
RTC Clock
Button controls to cycle modes and set time
