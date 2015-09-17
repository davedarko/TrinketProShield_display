# TrinketProShield_display
Shield for trinket pro to feature a bubble display and lm75

I created this project, inspired by the events in Texas, 
where a 9th grade kid called Ahmed got arrested for bringing a clock as a hardware project to school.

It is a shield for an adafruit trinket pro, based on an atmega238p with vusb.

An additional temparature sensor in the form of the LM75 can be added to this bubble display shield.
The atmega32p is capable of driving up to 40mA per pin, so with the display needing 5mA per element of a digit,
it should be fine, since it will be a pulsed signal and there are 8 elements max.

For more details see:
http://hackaday.com/2015/09/16/why-you-should-build-a-clock-for-social-good-this-week/
https://hackaday.io/project/7690-trinket-pro-bubble-display-shield
