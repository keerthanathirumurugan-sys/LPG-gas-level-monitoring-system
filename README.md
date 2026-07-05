# LPG-gas-level-monitoring-system
An Arduino-based embedded system that monitors LPG cylinder gas levels in real time using a Load Cell, HX711 amplifier, and I2C LCD display.
# Smart LPG Gas Level Monitoring System Using Load Cell and Arduino

## Overview

This project is designed to monitor the LPG gas level in a cylinder by measuring its weight using a Load Cell sensor. The measured value is processed using the HX711 amplifier and an Arduino microcontroller, then displayed on a 16×2 I2C LCD. The system helps users monitor gas levels accurately and avoid unexpected cylinder depletion.

## Features

* Real-time LPG gas level monitoring
* Accurate weight measurement using a Load Cell
* HX711 amplifier for signal processing
* Arduino-based control system
* 16×2 I2C LCD for live display
* Simple, reliable, and cost-effective design

## Components Used

* Arduino Uno
* Load Cell Sensor (30 kg)
* HX711 Load Cell Amplifier Module
* 16×2 I2C LCD Display
* Connecting Wires
* Breadboard
* LPG Cylinder (for testing)

## Working Principle

The Load Cell placed beneath the LPG cylinder measures its weight. The HX711 module amplifies the sensor signal and sends it to the Arduino. The Arduino calculates the cylinder weight and displays the current gas level on the LCD in real time.

## Applications

* Homes and apartments
* Hotels and restaurants
* Commercial kitchens
* Small industries using LPG cylinders

## Future Enhancements

* IoT-based mobile application for remote monitoring
* SMS/Email alerts for low gas levels
* Automatic gas refill booking
* Gas leakage detection integration
* Cloud-based data logging and analytics

## Technologies Used

* Arduino IDE
* Embedded C/C++
* Electronics and Sensors
* Load Cell Technology
* HX711 Interface

