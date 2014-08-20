PI BUFFER
==========

**Author**: Emilio Guernik, Buenos Aires, Argentina.

**Licence**: as-is

**Date**: 02-JUN-2013

Info
-----
Pi Buffer is a simple raspberry pi gpio protection bufffer, inspired in adafruit rpi breakout board.
It uses a 3 state octal buffer (74hc244) as seen on gertboard gpio protection stage. 

Usage
------
* pins 15, 16, 18 and 22 are buffered outputs. 
* pins 3, 5, 7, 11 are buffered inputs.
* The rest of the pins are just normally routed. (PLEASE see schematic for more details)

Pros
-----
* Its a very simple design
* board is small and fits well in your breadbord

Cons
-----
* Lack of flexibility. Only the listed pins have protection and you cannot change them. This is to mantain the simplicity of the board.
