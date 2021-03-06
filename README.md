## Video Overview

[![Video Overview](https://github.com/TemporarilyOffline/RadioProgrammingCable/blob/master/Thumbnail.png)](https://youtu.be/kiiE1W67dvw)



## Chirp Programming Cable

You'll need a few parts.  Your radio may be progammed in a variety of ways.  I'm going 
to go over how to connect to the Baofeng handheld radios and the Kenwood Mobile Radios.
This will probably work well for other radios.  If you figure out an additional radio, 
please update this page.

You probably have most of these parts on hand already:

* FTDI USB-TTL Breakout Board:  https://www.amazon.com/gp/product/B075N82CDL
* Audio Cables for Baofeng: https://www.amazon.com/gp/product/B00291N83O
* RJ-45 for Kenwood: https://www.amazon.com/gp/product/B00788M8IO
* Jumper Leads: https://www.amazon.com/gp/product/B07GD2BWPY
* Shrink Tubing: https://www.amazon.com/gp/product/B072PCQ2LW

## Chirp Software

Get it here:  https://chirp.danplanet.com

I was able to get this to work with Chirp-Daily-20171204 on OSX.

## Kenwood TM-281 (and others)

* Red - Pin 5 - RXD
* Yel - Pin 2 - TXD
* Blk - Pin 6 - GND

<img height="150" alt="Kenwood Cable" src="https://github.com/TemporarilyOffline/RadioProgrammingCable/blob/master/Kenwood Cable.jpg">   

## Baofeng UV-5R+ (and others)

This radio uses 3.5MM + 2.5MM Stereo Jacks.  These jacks have metal probes that have separations by an insulator.  These are called Tip, Ring and Sleeve.  In my case, inside of the cables are red, white and bare wires.

These ohm out as follows - Its the same on both cables:

* Tip - Red
* Ring - White
* Sleeve - Bare

On the 2.5MM plug, wire the white/ring to receive and the bare/sleeve wire to ground.

On the 3.5MM plug, wire the bare/sleeve to transmit.

<img height="150" alt="Baofeng Cable" src="https://github.com/TemporarilyOffline/RadioProgrammingCable/blob/master/Baofeng Cable.jpg">   



