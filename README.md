TimerOneThree
=============

The arduino TimerOne library adapted for ATmega1284P and extended for Timer3

The arduino TimerOne library described at http://playground.arduino.cc/Code/Timer1 is the starting point for this lib. In the original library that can be found at http://code.google.com/p/arduino-timerone/downloads/list the pwm pins are (sort of) hard-coded to fit to the ATmega168P / 328P (the chip of the Uno R3 board). I simply changed them to the pin settings of the ATmega1284P using maniacbug's pinout. Then I doubled the code and adapted it to timer3 of the ATmega1284P and it's pins.
