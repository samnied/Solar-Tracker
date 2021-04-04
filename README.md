# Solar-Tracker
<img src="https://github.com/samnied/Solar-Tracker/blob/main/SolarTracker_1.jpg" width="300"/>

<!-- ABOUT THE PROJECT -->
## About The Project
The SolarTracker was designed for the [Smartfeld Photonics Workshops](https://www.smartfeld.ch/photonik-und-daten/).
Check out [Smartfeld](https://www.smartfeld.ch/smartes-konzept/) for detailed information about the workshops.

<!-- GETTING STARTED -->
## Getting Started
The SolarTracker can be operated in three different modes
### manual
Use the onboard rotary encoder to control the Pan and Tilt angle of the SolarTracker.
The current angle aswell as the voltages from the LDR-sensors and the solar cell are displayed on the 2.4 inch TFT-display.
### automatic
In automatic mode the SolarTracker will automaticly track and follow the brightest spot.
### remote
In remote mode one can control the SolarTracker over I2C to modify the servos and read the sensor values.
Take a look at [BBC Micro:bit ](#bbc-microbit) to operate the SolarTracker in remote mode with the BBC Micro:Bit.
<!-- TECHNICAL DETAILS -->
## Technical Details
* The SolarTracker consists of an [ESP32](https://www.espressif.com/en/products/socs/esp32) microcontroller using [LVGL](https://lvgl.io/) as graphics library.
* The PCBs are manufacutred by [JLCPCB](https://jlcpcb.com/)
* All the wooden parts are made of laser cutted 3mm MDF
* The SolarTracker supports OTA(over the air updates), however it is still in experimental state at the moment

<!-- BBC MICROBIT -->
## BBC Micro:bit
To control the SolarTracker with BBC Micro:bit inlcude the [SolarTracker-Library](https://github.com/samnied/pxt-solarTracker) as makecode extension.
<img src="https://github.com/samnied/Solar-Tracker/blob/main/MakeCodeExtension.gif" width="700"/>

