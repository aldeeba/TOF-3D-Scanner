# 3D Time-of-Flight (ToF) Scanning System

## Overview

Developed a microcontroller-based 3D scanning system that uses a
Time-of-Flight (ToF) sensor mounted on a stepper motor to measure
and reconstruct a surrounding environment.

The system rotates the ToF sensor through 360° while collecting
distance measurements. The measurements are transmitted to MATLAB,
where they are processed and converted into a 3D representation
of the scanned environment.

> **Note:** Source code is not included in this repository due to
> course/project restrictions.

---

## Project Features

- 360° environmental scanning
- 64 distance measurements per rotation
- 5.625° angular resolution
- Time-of-Flight distance measurement
- Stepper motor control
- I2C communication
- UART serial communication
- MATLAB data acquisition and visualization
- 3D reconstruction of scanned environments
- Clockwise and counterclockwise scanning
- Start/stop push-button control
- LED status indicators

---

## System Architecture

The system consists of four main components:



