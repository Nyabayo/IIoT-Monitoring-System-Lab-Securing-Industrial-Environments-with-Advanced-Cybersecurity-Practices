# IIoT Cybersecurity Lab

## Overview
This project demonstrates the design and implementation of an Industrial Internet of Things (IIoT) monitoring system for Precision Manufacturing Inc., aimed at improving machine performance, predicting failures, reducing downtime, and enhancing energy efficiency. 

The system is designed with cybersecurity in mind, ensuring secure data transmission, encryption, access control, and other essential cybersecurity measures for IIoT devices in a manufacturing environment.

## Objective
- Monitor critical machine parameters, including temperature, vibration, power consumption, and uptime.
- Automate predictive maintenance actions, such as sending alerts when thresholds are exceeded and scheduling maintenance.
- Provide engineers with remote monitoring via an IIoT dashboard.
- Implement cybersecurity practices such as AES-256 encryption, TLS/SSL communication, Role-Based Access Control (RBAC), and Firmware Over-the-Air (FOTA) updates.

## Requirements
1. **Sensors and Actuators:**
   - Thermocouple Temperature Sensor
   - Accelerometer (Vibration Sensor)
   - Current Sensor
   - Industrial Relays

2. **Edge Device:**
   - Industrial Raspberry Pi or NVIDIA Jetson Nano
   - ESP32 Microcontroller

3. **Connectivity:**
   - Wi-Fi for real-time cloud connectivity
   - MQTT Protocol for secure data transmission
   - LoRaWAN for long-range communication (optional)

4. **Processing & Storage:**
   - Edge Computing with Raspberry Pi/Jetson Nano
   - Cloud Storage (AWS IoT Greengrass or Azure IoT Edge)
   - PostgreSQL or AWS DynamoDB for historical data storage

5. **Security Measures:**
   - AES-256 Encryption for data protection
   - TLS/SSL Encryption for cloud communications
   - Role-Based Access Control (RBAC)
   - FOTA for firmware updates

6. **User Interface:**
   - IIoT Dashboard built with React.js and Python (Flask or FastAPI) for backend

## Template Link
You can view and copy the template used for this lab here: [IIoT Lab Template](https://docs.google.com/document/d/1gAkFlK7Cnzrff1RsJ6xZxxOkod-sspE6grSZTNO529w/copy)

