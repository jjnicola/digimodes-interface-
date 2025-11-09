# digimodes-interface

Digimodes interfaces for old analog transcievers without VOX functionality. It requires to be powered to activate the PTT while sending audio from computer.
The first transistor in the schematic amplifies the audio signal. The following is the rectifier diode on filters. This diode must be a germanium diode because its 0.3volts threshold voltage.

This was design specially for an Icom IC-725 to be connected in the mic connector, which provides an 8 volts low current (max 10mA) outout in one of the pins. It can be also used in the ACC1 connector, which provides also a 13.8v output. I checked the Yaesu FT-80c and it should work as well since it provides all input/outputs for this 
If your transciever doesn't have a Vcc output, you can use a 9v battery.

Special thanks to LU5VV for all the support and the initial desing.

LU6VJN

![alt text](https://github.com/jjnicola/digimodes-interface-/blob/main/Alto%20-%20Roe.png)
