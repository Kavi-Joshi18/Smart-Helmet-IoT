# Smart Helmet - IoT Based Wearable Safety Technology

## Overview

Smart Helmet is an IoT-based wearable safety system designed to improve two-wheeler rider safety by ensuring helmet compliance, detecting accidents, and providing emergency assistance.

The system uses ESP32-based wireless communication between a helmet module and a bike module to enable intelligent safety features.

## Problem Statement

Two-wheeler accidents often lead to severe injuries due to delayed emergency response and lack of safety compliance. This project aims to provide a smart safety solution that can detect accidents and assist riders during emergencies.

## Key Features

- Helmet wear detection
- Accident detection using motion sensors
- Emergency SOS button
- Real-time location tracking
- Wireless communication between helmet and bike module
- Vehicle ignition control based on helmet usage

## Technologies Used

### Hardware
- ESP32 WROOM
- MPU6050 Accelerometer and Gyroscope
- GPS Module
- ESP-CAM
- Capacitive Touch Sensor
- Buzzer
- Li-ion Battery

### Software
- Arduino IDE
- Embedded C
- MIT App Inventor
- ESP-NOW Wireless Communication
# System Architecture

## Overview

The Smart Helmet consists of two interconnected modules:

1. Helmet Module
2. Bike Module

The modules communicate wirelessly using ESP-NOW protocol.

## Helmet Module

Components:
- ESP32 WROOM controller
- MPU6050 accelerometer and gyroscope
- Capacitive touch sensor
- ESP-CAM
- SOS push button
- Buzzer

Responsibilities:
- Detect helmet usage
- Monitor rider movement
- Detect accidents
- Trigger emergency alerts

## Bike Module

Components:
- ESP32 controller
- GPS module
- Wireless relay

Responsibilities:
- Receive helmet status
- Control ignition system
- Provide location information

## Communication

Helmet Module ↔ ESP-NOW ↔ Bike Module