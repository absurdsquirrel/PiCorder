# PiCorder
Prototype tricorder built around a Raspberry Pi
## Inspiration
The tricorder, as it appears in Star Trek, is a handheld device with multiple different types of sensors. It is reprogrammable, and interfaces wirelessly with other nearby computer systems. It allows the user to gather data about their local environment, identify and locate sources of electromagnetic radiation, and is otherwise an endlessly useful piece of technology.
## Design Goals
### Packed with sensors
The PiCorder should have as many sensors built into it as possible, with available connections to expand the available sensor suite.
### Field Programmable
The PiCorder's interface should be dynamic, allowing the user to select from available sensor inputs, and displaying the output in a useful way.
### ???
TBD
## Hardware
The current prototype is assembled with the following components:
- Raspberry Pi 3B
- Pi prototyping HAT
- Waveshare 4.3 inch HDMI LCD touch screen
- USB power bank (any with 2 outputs will do) (TODO: replace this with a LiPo battery and charging circuit)
- GT-U7 GPS receiver module
- Active GPS antenna
- NooElec Nano 3 SDR
- MPU-9250/6500 combined magnitometer & accelerometer
- BME280 atmospheric sensor
- mini BT keyboard (until the PiCorder interface is built)
- LD1117 linear voltage regulator (stepdown Pi 5v to 3.3v)
## ???
TBD
