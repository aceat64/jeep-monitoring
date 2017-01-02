# Raspberry Pi Jeep Monitoring System

This system is designed for monitoring or interacting with various functions of my specific Jeep Wrangler, such as the dual battery system and the IHS (Internal High-Speed) CAN bus. All information is available via an API, for consumption by mobile devices or Android headunits on my Jeep's local wifi network.

## Features
- Voltage monitoring of two batteries, for dual battery systems.
- Current monitoring via a shunt resistor, tweaking the code may be required depending on your specific shunt resistor.
- Status of the battery isolator, a 12V digital input.
- Accelerometer, for determining vehicle tilt.
- GPS header, for external GPS module.
- CAN Bus transciever.

## License
All schematics, circuit board design files and documentation are released under the [Creative Commons Attribution-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-sa/4.0/).

All source code is releaed under the [GNU General Public License version 3](https://www.gnu.org/licenses/gpl-3.0-standalone.html).
