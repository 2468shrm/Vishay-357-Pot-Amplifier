# Vishay-357-Pot-Amplifier

A unity-gain amplifier circut for the Vishay 357 series potentiometers. It mounts
on the back of the pot.

J1 Configures the voltage across the potentiometer, it allows for forward and
reverse adaption.
- Forward:  1-3 and 4-6
- Reverse:  3-5 and 2-4

J2 uses a socket header (female) to allow use of purchased FRC PWM cable to
connect between sensor and roboRIO.

J2 also provides power to the sensor. The circuit works with a VDD of 3.3V
to 5V, so this works with roboRIO as well as Feather and 3.3V MCU solutions.

![Top View](https://github.com/2468shrm/Vishay-357-Pot-Amplifier/blob/main/Images/Top.png?raw=true)

![Back View](https://github.com/2468shrm/Vishay-357-Pot-Amplifier/blob/main/Images/Back.png?raw=true)

![Iso View](https://github.com/2468shrm/Vishay-357-Pot-Amplifier/blob/main/Images/Iso.png?raw=true)