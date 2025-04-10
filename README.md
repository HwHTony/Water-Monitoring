# Water-Monitoring
Water Quality Monitoring System - Raspberry Pi Client Project Overview This project aims to use a Raspberry Pi 5B to connect water quality sensors (pH sensor, turbidity sensor, and temperature sensor), collect sensor data, and send the data in JSON format to a Qt server via Socket communication. The project is implemented in three phases:

Sensor Data Reading and Printing: Read sensor data and print it to the terminal.

Socket Communication: Send sensor data to the Qt server via TCP Socket.

JSON Data Packaging: Use the cJSON library to package sensor data into JSON format and send it.

Hardware Requirements Raspberry Pi 5B

pH Sensor: Measures the acidity/alkalinity of water.

Turbidity Sensor: Measures the turbidity of water.

Temperature Sensor (DS18B20): Measures water temperature.

PCF8591 Module: Used to convert analog signals to digital signals.

Jumper Wires, Breadboard, Resistor (4.7kΩ)
