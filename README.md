### Low-Power
Lightweight low power library for Arduino with Atmega328PB support.

Version: 1.70

Devices Supported:
* ATMega168
* ATMega328P
* ATMega328PB
* ATMega32U4
* ATMega2560
* ATMega256RFR2
* ATSAMD21G18A

####Notes:
External interrupt during standby on ATSAMD21G18A requires a patch to the <a href="https://github.com/arduino/ArduinoCore-samd">Arduino SAMD Core</a> in order for it to work. Fix is provided by this particular <a href="https://github.com/arduino/ArduinoCore-samd/pull/90">pull request</a>.
