AY-3-8910 control with Arduino - without the need for a quarz
=============================================================

Credits:
This is combination of code found in this tutorial: 
http://playground.arduino.cc/Main/AY38910
(which is based on this http://kalshagar.wikispaces.com/Arduino+and+a+YMZ294)
and code for generating a 2 MHz clock signal found here:
http://forum.arduino.cc/index.php/topic,62964.0.html

Note: The chip in the breadboard schematic is not correctly rendered, but
I was too stupid to figure out how to change the width of a custom 
40 pin IC in Fritzing.


For information about how to control the various registers of the sound chip
if found this page to be very useful: http://www.samdal.com/svsound.htm
It is actually more correct than the official datasheet (which has some of 
the registers wrong): http://map.grauw.nl/resources/sound/generalinstrument_ay-3-8910.pdf