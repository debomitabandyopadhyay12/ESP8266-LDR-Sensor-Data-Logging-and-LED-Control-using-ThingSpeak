Project Overview
This project involves using an ESP8266 microcontroller to read data from an LDR (Light Dependent Resistor) sensor, send the data to a ThingSpeak channel, and control an LED based on the sensor data. The ESP8266 connects to a WiFi network, communicates with ThingSpeak to log sensor data, and retrieves data to make decisions for LED control.

Components Required
ESP8266 (e.g., NodeMCU)
LDR Sensor
LED
Resistors (appropriate values for LDR and LED)
Breadboard and Jumper Wires
Power Supply (e.g., USB cable)
Libraries Used
ESP8266WiFi.h: Enables WiFi functionality on the ESP8266.
WiFiClient.h: Provides the client functionality for WiFi connections.
ThingSpeak.h: Enables interaction with the ThingSpeak API.
Circuit Diagram
LDR Sensor: Connect one end to the 3.3V pin and the other end to the A0 (analog input) pin with a pull-down resistor to GND.
LED: Connect the positive leg (anode) to D1 (digital output) through a current-limiting resistor, and the negative leg (cathode) to GND.
