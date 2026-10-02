# LDR-Based Live Light Monitoring Using OLED

## Project Overview

This project uses an ESP32, an LDR (Light Dependent Resistor), and an SSD1306 OLED display to monitor light intensity in real time.

## Components Used

* ESP32 Development Board
* LDR / Photoresistor Sensor
* SSD1306 OLED Display (128x64)
* Jumper Wires

## Technologies Used

* Arduino C++
* Wokwi Simulator
* SSD1306 OLED Library
* Adafruit GFX Library

## Working Principle

The LDR detects changes in surrounding light. The ESP32 reads the sensor's analog value and displays the live reading and a light-level category on the OLED screen.

## Features

* Real-time light-level monitoring
* OLED-based data display
* Low, medium, and bright light classification
* Virtual circuit simulation using Wokwi

## Circuit Connections

* LDR AO → ESP32 GPIO 34
* OLED SDA → ESP32 GPIO 21
* OLED SCL → ESP32 GPIO 22
* VCC → 3.3V
* GND → GND

## Simulation

Wokwi Project Link: PASTE_YOUR_WOKWI_LINK_HERE

## Result

The ESP32 reads the LDR sensor value and displays the live light-level reading on the SSD1306 OLED display.
