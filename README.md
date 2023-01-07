# WheelTimeClock
**A clock that looks like a tach and speedometer from a 70s motorcycle.**

The clock is the size and shape of a motorcycle instrument cluster.  It has two dials.
The left one is for hours and is styled like a speedometer, and the right one is for
 minutes and is styled like a tachometer.  It keeps very accurate time using the power
 line frequency as a reference.

The guts of the clock consist of an Arduino nano, two 9g servos, the power system and
time reference circuit, an external AC wall wart power transformer, and status lights.
The housing is a four inch PVC pipe coupling.

##Inspiration
My son and I love motorcycles.  I have an unhealthy fascination with time and clocks.
So I wanted to make a clock for my son that looks like a motorcycle instrument cluster.
This is it.

##Features
The clock normally keeps time based on the power line frequency.  The power line
frequency is -- long term -- VERY accurate.  That is a story in itself that I won't go
into.  But it is a fascinating story.  In any case, clocks based on power line
frequency are very accurate.  This one will auto adapt to either 50 or 60 Hz power.
At least it "should."  I don't have access to a 50 Hz mains outlet.  I plan to add
battery backup eventually, but not for the first version.  The status lights
emulate turn signal lights, high beam, and oil pressure lights.  They indicate,
respectively, seconds tick, PM, and alarm on.  I plan to add the alarm later.  It will
make a motorcyle revving sound.


