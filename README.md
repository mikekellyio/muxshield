# Mux Shield II
### DEV-11723 
from https://www.sparkfun.com/products/11723

Description: Sometimes you’ve got way too many inputs, or outputs… or both. How are you going to get them all connected to your Arduino? The Mux Shield, that’s how. The Mux Shield II from Mayhew Labs is an upgrade on their previous Mux Shield which makes it possible to route up to 48 analog and digital inputs or digital outputs to and from your Arduino board.

The Mux Shield II improves on the original by moving all of the I/O pins to the end of the board, thus allowing you to add one big connector and hook up a ribbon wire or similar cable solution. This also gets the pins out of the way so that the Mux Shield can be in the middle of a stack, with a shield on top of it, and you can still get to the I/O pins. The pins are arranged into three rows of sixteen and each row can be individually set as a digital input, a digital output or an analog input from the Arduino sketch! Further increasing the flexibility of the board, Mayhew Labs added solder jumpers to the bottom of the board that allow you to shut off this software control feature and “hard wire” the functionality of each row, freeing up the associated Arduino pins for other shields in the stack.

The Mux Shield uses TI 74HC4067 analog multiplexers (mux’s) for input functionality and TI 74HC595 shift registers for output functionality. Don’t worry if that’s jibberish to you, the included Arduino library wraps it up and makes it very easy-to-use.

The shield comes without any headers so be sure to pick up some stackable shield headers!

Features:

* Control up to 48 Pins from your Arduino!
* Multiple modes:
  * Analog Input
  * Digital Input
  * Digital Output
* Solder Jumpers for Hard-Wired Mode Select
* Arduino Library and Example Code Available

### Documents:
available at: https://www.sparkfun.com/products/11723

* User Guide
* Schematic
* Datasheet (74HC4067)
* Datasheet (74HC595)
* Arduino Library <== This github repo
