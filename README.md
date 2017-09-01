flora-pulse-neopixels
=====================

Integration of Adafruit Flora with Pulse Sensor Amped and NeoPixel.  Pulse sensor displays heartbeat on the Flora's onboard NeoPixel.  The BPM value is represented on an external NeoPixel, varying from green (low) to red (high).


Prerequisites
-------------

- Arduino IDE >=1.6
- [Adafruit board support package for Arduino](https://learn.adafruit.com/adafruit-arduino-ide-setup/arduino-1-dot-6-x-ide)
- [NeoPixel Arduino library](https://learn.adafruit.com/adafruit-neopixel-uberguide/arduino-library-installation) 


Installation
------------

Clone the repository, open _flora-pulse-neopixels.ino_ in Arduino IDE (>=1.6), Upload to Flora.


Connections
-----------

The Pulse Sensor is connected as follows:

| Pulse Sensor Wire | Flora Pin | Description   |
|:------------------|:---------:|:--------------|
| Black             | GND       | Ground        |
| Red               | VBATT     | 5VDC          |
| Purple            | #12       | Analog signal |

The external NeoPixel is connected as follows:

| NeoPixel Pin | Flora Pin | Description   |
|:-------------|:---------:|:--------------|
| -            | GND       | Ground        |
| +            | VBATT     | 5VDC          |
| Arrow In     | #6        | Comms         |


License
-------

MIT License

Copyright (c) 2017 GenieMob

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR 
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, 
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE 
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER 
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, 
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN 
THE SOFTWARE.
