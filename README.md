# VOC, Humidity and Temperature Sensor Board
The board includes two sensors from Sensiron:
- **SGP41-D-R4** VOC and NOx sensor,
- **SHT41** temperature and humidity sensor.
The sensor data is accessible via UART interface. The voltage level is 5V, but the input is 3.3V compatible. A TXU0202 level shifter is used.
The sensor board is intended to be used with other Sensiron sensors (like SPS30 and SFA30). The 5V interface was chosen so that a central controller can use the same interface type to connect to any of the sensors.
## Image of the assembled board
TODO
## Repository structure
- bom: interactive bom and csv
- gerbers: manufacturing files
- pdf: pdf output of schematic