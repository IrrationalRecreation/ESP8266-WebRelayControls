# ESP8266-WebRelayControls

This is a program that has two main features:

* control GPIO pins from a simple web interface
* permits timed control such that selected GPIO pins will return to a predefined state after a preset period

The program was written to control some 12v pumps and LED lighting, such that they could turn-off automatically after a preset period so they would not be left on by accident and that the solar battery supply would run down.

The default settings and times are hard-coded. Future versions may change this.

It has been tested on a cloned Wemos D1.  
There are likely subtle bugs but it works for my purposes.
