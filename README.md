# Arduino-KVM-Switch

This is a fully functional keyboard switch (KVM but while only the keyboard),
based on the combination of Arduino UNO + Arduino LEONARDO pro Micro.
Arduino UNO sends data from a connected USB keyboard via SoftwareSerial to 2 Arduino LEONARDOs that emulate the keyboard.

Keyboard is toggled with ScrollLock Key.
I recommend USB cable keyboard.
All SoftwareSerials has baud rate: 38400

Connection Schematics:

![Image description](https://github.com/nathalis/Arduino-KVM-Switch/blob/master/KVM_SCHEMATICS.png?raw=true)

Prototype photo:

![Image description](https://raw.githubusercontent.com/nathalis/Arduino-KVM-Switch/master/Keyboard-prototype.jpg)

> to do mouse/joypad/video switch support...

by Nathalis.

MIT. License
(c)2020
