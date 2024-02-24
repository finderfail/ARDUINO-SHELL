ARDUINO SHELL
==============

Simple Arduino shell to work with EEProm

# Full list of supported statements and functions

## System
 format    clear the EEProm
 dump      hex dump of the EEProm
 print     text dump of the EEProm
 record    erase EEProm until '.', buffer fill or reset
 poke A D  poke value D into address a (decimal values)



# Example program

Here are a few example program to get you started...

## User Input


	record
	<something>
	.


# Device Support
## Current
- Arduino - ATMega 168 (~100 bytes available)
- Arduino - ATMega 368 (~1100 bytes available)
- EEProm (via EEProm Library, uses 500 bytes of ROM)


# Links
- [Arduino Microcontroller](http://arduino.cc)

# Licensing

Mike Field based his C port of Tiny Basic on the 68000 Tiny BASIC which carried 
the following license:

~~~
******************************************************************
*                                                                *
*               Tiny BASIC for the Motorola MC68000              *
*                                                                *
* Derived from Palo Alto Tiny BASIC as published in the May 1976 *
* issue of Dr. Dobb's Journal.  Adapted to the 68000 by:         *
*       Gordon Brandly                                           *
*       12147 - 51 Street                                        *
*       Edmonton AB  T5W 3G8                                     *
*       Canada                                                   *
*       (updated mailing address for 1996)                       *
*                                                                *
* This version is for MEX68KECB Educational Computer Board I/O.  *
*                                                                *
******************************************************************
*    Copyright (C) 1984 by Gordon Brandly. This program may be   *
*    freely distributed for personal use only. All commercial    *
*                      rights are reserved.                      *
******************************************************************
~~~

However, Mike did not include a license of his own for his
 version of this. From discussions with him, I felt that the MIT license is
the most applicable to his intent.

I am in the process of further determining what should be done wrt licensing 
further.  This entire header will likely change with the next version 0.16, 
which will hopefully nail down the whole thing so we can get back to 
implementing features instead of licenses.  Thank you for your time.

# MIT License

Copyright (c) 2012-2013

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
