# 3D Time-of-Flight (ToF) Scanning System

## Overview

Developed a microcontroller-based 3D scanning system using a Time-of-Flight (ToF) sensor and stepper motor to scan and map the surrounding environment.

The system rotates the ToF sensor through 360° while collecting distance measurements. The measurements are transmitted to MATLAB for processing and 3D visualisation.

> **Note:** Source code is not included in this repository due to course/project restrictions.

## Features

- 360° environmental scanning
- Time-of-Flight distance measurement
- Stepper motor control
- I2C communication with the ToF sensor
- UART data transmission
- MATLAB-based data processing and visualization
- 3D visualization of the scanned environment

## System Architecture

The system consists of three main components:

### Microcontroller

The microcontroller coordinates the scanning process by:

- Controlling the stepper motor
- Communicating with the ToF sensor using I2C
- Collecting distance measurements
- Transmitting scan data to MATLAB through UART

### ToF Sensor

The ToF sensor measures the distance between the sensor and surrounding objects. Distance measurements are collected at different angular positions as the sensor rotates.

### MATLAB

MATLAB receives the scan data through UART and processes the measurements to generate a 3D visualization of the scanned environment.

## How It Works

The scanning process follows these steps:

1. The stepper motor rotates the ToF sensor to a specific angular position.
2. The ToF sensor measures the distance to the surrounding environment.
3. The microcontroller retrieves the measurement using I2C.
4. The measurement and corresponding position information are transmitted to MATLAB using UART.
5. MATLAB processes the measurements and converts them into spatial coordinates.
6. The process repeats across the scanning range to generate a 3D representation.

## Technologies

- **Embedded C**
- **MATLAB**
- **I2C**
- **UART**
- **ToF Sensor**
- **Stepper Motor**
- **Microcontroller**

## Project Results

The completed system was able to perform 360° scanning while collecting distance measurements and generate a 3D representation of the surrounding environment.

## Documentation

The project report contains additional information about the system design, implementation, testing, and results.

[View the Project Report](ToF_Scanner_Report.pdf)

## Skills Demonstrated

- Embedded systems development
- Sensor interfacing
- I2C communication
- UART communication
- Stepper motor control
- Real-time data acquisition
- MATLAB data processing
- 3D data visualization

## Source Code

The source code is not included in this repository due to course/project restrictions. This repository provides documentation and an overview of the system design and implementation.
```
