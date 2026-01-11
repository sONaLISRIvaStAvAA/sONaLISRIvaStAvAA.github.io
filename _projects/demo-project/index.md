---
layout: post
title: SENTRY-X – Real-Time Intruder Detection System
description: >
  SENTRY-X is a real-time surveillance system integrating Arduino-based
  embedded hardware with Python-based software intelligence to detect,
  verify, and respond to potential intrusions.
skills:
  - Arduino
  - Embedded C++
  - Python
  - Sensors
main-image: /project1.jpg
---

## Overview
SENTRY-X is a real-time intruder detection and monitoring system designed
using an Arduino-based embedded platform and Python-based software logic.
The system continuously monitors its surroundings and provides alerts
when an intrusion is detected.

---

## Problem Statement
Conventional surveillance systems are often expensive and complex.
The goal of this project was to design a **low-cost, real-time intrusion
detection system** using basic sensors and embedded logic that can be
easily deployed and monitored.

---

## System Architecture
The system consists of:
- Sensor module for detecting movement or distance changes
- Arduino microcontroller for data processing
- Serial communication interface
- Python application for visualization and alert handling

The Arduino reads sensor data and transmits it to the Python interface
for further processing and display.

---

## Hardware Components
- Arduino Uno
- Ultrasonic Sensor
- Connecting Wires
- Breadboard
- Power Supply

---

## Software & Logic
- Embedded C++ was used to program the Arduino
- Serial communication was used to transmit sensor data
- Python was used to process incoming data and generate alerts
- Threshold-based logic was implemented to detect intrusions

---

## Working
1. The sensor continuously measures distance values.
2. Arduino processes the readings in real time.
3. When values cross a predefined threshold, the system flags an intrusion.
4. Data is sent via serial communication to the Python application.
5. The Python program visualizes the data and triggers alerts.

---

## Results
- Successfully detected intrusions in real time
- Stable serial communication between Arduino and Python
- Accurate distance-based detection with minimal false triggers

---

## What I Learned
- Practical implementation of sensor interfacing
- Real-time data acquisition using Arduino
- Serial communication between hardware and software
- Debugging embedded systems and handling noisy sensor data
