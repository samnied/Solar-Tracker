# Solar-Tracker
<!-- ABOUT THE PROJECT -->
## About The Project
The SolarTracker was designed for
It consists of a...

<!-- GETTING STARTED -->
## Getting Started
The SolarTracker can be operated in three diferent modes
### manual
Use the onboard rotary encoder to control the pan and tilt of the SolarTracker.
The current angle aswell as the voltages from the LDR-sensors and the solar cell are displayed on the 2.4 inch TFT-display.
### automatic
In automatic mode the SolarTracker will automaticly track the brightest spot and follow it.
### remote
In remote mode one can control the SolarTracker over I2C to modify the servos and read the sensor values.
Take a look at [Getting started with ](#bbc-microbit) to operate the SolarTracker in remote mode with the BBC Micro:Bit.

<!-- BBC MICROBIT -->
## BBC Micro:bit
To control the SolarTracker with BBC Micro:bit inlcude the [SolarTracker-Library](https://github.com/samnied/pxt-solarTracker) as makecode extension.
<!-- TECHNICAL DETAILS -->
## Technical Details
The SolarTracker consists of an ESP32 microcontroller using [LVGL](https://lvgl.io/) as graphics library
