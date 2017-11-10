# Maslow-MegaShield-Teensy3.5-3.6-Carrier
Carrier board to connect a Teensy 3.5 or 3.6 to a Maslow MegaShield motor control board
======================


Layout

![Layout](/BoardLayout.tif)

Schematic

![Schematic](/Schematic.tif)

======================

Notes:

 Most of the pin assignments match the Arduino Mega. IN5 & IN6 were changed so that they would be PWM capable (for a different project). The AUX pins were re-arranged for convenience of layout. The board version detection was not implemented, as that would tie up four more gpio pins. 
 
 There is provision to choose the voltage used for the encoders, either the 5V from the USB connection or the 3V3 regulated by the Teensy. It is strapped for 3V3, and that seems to work well on the Teensy 3.5 I've tested. The Teensy 3.6 would be damaged by using more than 3V3 in its inputs.

 The JTAG parts are not tested.
