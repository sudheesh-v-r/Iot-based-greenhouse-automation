
# IoT Based Smart Greenhouse Automation Using Arduino

## Project Overview

This project demonstrates the design and implementation of an automated greenhouse monitoring and control system. It aims to help farmers manage essential environmental factors such as temperature, humidity, soil moisture, and light intensity, which are critical for plant growth and productivity. By employing sensors and the Internet of Things (IoT), the system reduces the need for constant manual monitoring and helps maintain optimal climatic conditions for crops.

## System Features

* 
**Automated Monitoring**: Real-time acquisition of data from various environmental sensors.


* 
**Intelligent Control**: Automatically triggers actuators (pump, fan, etc.) based on sensor data comparison with desired states.


* 
**IoT Connectivity**: Utilizes NodeMCU for internet connectivity, allowing for remote surveillance via the Blynk app.



## Hardware Components

The system is built using the following core components:

* 
**Microcontroller**: Arduino Uno (Atmega328).


* 
**IoT Module**: NodeMCU ESP8266 for Wi-Fi connectivity.


* **Sensors**:
* 
**Soil Moisture Sensor**: Measures the volumetric water content in the soil.


* 
**DHT11 Sensor**: Measures both humidity and temperature.


* 
**LDR (Light Dependent Resistor)**: Measures light intensity.




* **Actuators & Drivers**:
* 
**L293D**: Motor driver IC to control the DC pump and fan.


* 
**DC Water Pump**: For automated irrigation.


* 
**DC Fan**: For temperature and humidity regulation.


* 
**LED Strip**: For supplemental lighting.


* 
**Relay**: Used to switch electrical circuits.





## System Design

The system follows a three-step operational process:

1. 
**Data Acquisition**: Sensors collect environmental data.


2. 
**Processing**: The Arduino compares sensor readings with preset thresholds to decide necessary actions.


3. 
**Actuation**: The system triggers the appropriate component (e.g., turning on the pump if soil is dry).



## Software

* 
**Platform**: Arduino IDE.


* 
**Communication**: Utilizes the Blynk app for remote monitoring via a smartphone.



