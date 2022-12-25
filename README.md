# WheelTimeClock
A clock that looks like the instrument cluster of a motorcycle.

The clock is the size and shape of a motorcycle instrument cluster.  It has two separate faces.  One is for the hours and is styled like a speedometer, and one is for the minutes and is styled like a tachometer.  It keeps very accurate time using the power line frequency as a reference, but also has battery backup.

The guts of the clock consist of an AVR / Arduino board, two 9g servos, they power system, an external AC wall wart power transformer, and status lights.  The housing is a four inch PVC pipe coupling.

Inspiration
My son and I love motorcycles.  I have an unhealthy fascination with time and clocks.  So I wanted to make a clock for my son that looks like a motorcycle instrument cluster.  This is it.

Features
The clock normally keeps time based on the power line frequency.  The power line frequency is -- on average -- VERY accurate.  That is a story in itself that I won't go into.  But it is a fascination story.  In any case, clocks based on power line frequency are very accurate.  This one will auto adapt to either 50 or 60 Hz power.  If the power fails, it falls back to its crystal oscillator, which isn't as accurate but close enough for short time periods.  It has a battery backup to keep time (but not display it ) during power outages.  The status lights emulate turn signal lights, high beam, and oil pressure lights.  They indicate, respectively, seconds tick, PM, and alarm on.  The alarm makes a motorcyle revving sound.


