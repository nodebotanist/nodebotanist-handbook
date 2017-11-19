# An example of a journal entry

I learn by doing, and barring that I learn by wtching someone else work. So in this section I'll be placing the notes I took during a November 9th 2017 stream in which I attempted to add the SX1509 GPIO expander to the Johnny-Five Library. I've added some posthumous notes for explanation.

## Pre-Stream

Notes: I gathered some information that would expedite my work mid-stream-- I hate long silences in my stream, so I try to do a little research beforehand. Keyword try.

Datasheet for SX1509: Sparkfun C++ lib for SX1509:

Note: I'll cover this in reverse engineering, but I find libraies written in languages other than the one I'm using very useful when writing new code.

Goals for the stream:

* Get Digital Out working
* Get Digital In working
* Get PWM out working

## During the Stream

Note: I walked the viewers through what I'd be doing that night, and set up the camera to wire up my demo rig; I forgot to collect the materials beforehand, but luckily this was in some weird reality where my shop was organized, so locating the parts went smoothly.

Parts used:

* Arduino Uno \(Note: ease of use with johnny-five was a total factor here\)
* SX1509 Breakout from SparkFun
  * \(Note: I should've explained to viewers that these need soldering and that I had tried many configurations of pin and socket headers before landing on one I liked; this is the kind of info I love to see\)
* 4 pin-to-socket breadboard cables
* 2 pin-to-pin breadboard cables
* 1 LED
  * \(Note: I explained to my viewers that because the SX1509 does 3.3V power, I didn't need a resistor\)



