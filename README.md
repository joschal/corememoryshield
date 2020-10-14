# Core Memory Shield Software

This is a modified version of the Arduino control software for the [Core Memory Shield](http://jussikilpelainen.kapsi.fi/wordpress/?p=213) by Jussi Kilpelainen.

The code was modified to be more readable and therefore accessible to a wider audience. The original version used direct port manipulation via registers. This method to control an Arduino's I/O is computationally fast, but difficult to read and understand.

This version uses `digitalRead()`and `digitalWrite()` instead. Pins are explicitly addressed and manipulated, making it easier to understand, what happens in the code and which pins are used.

 
