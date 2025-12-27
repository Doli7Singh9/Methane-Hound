# Methane-Hound
An IoT-enabled rover for real-time methane gas detection and geospatial hotspot mapping in landfill environments.

## Overview
Methane-Hound is a low-cost, rover-based environmental monitoring system designed to detect methane gas leaks and visualize emission hotspots using GPS-tagged sensor data and geospatial interpolation.

The system integrates:
- MQ-4 methane sensor
- ESP32 with FreeRTOS
- GPS-based geotagging
- Cloud telemetry (Firebase)
- Python-based geospatial heatmap generation

## Problem Statement
Manual methane monitoring in landfills is unsafe, inconsistent, and lacks spatial accuracy. Industrial solutions are expensive and inaccessible for continuous monitoring.

Methane-Hound addresses this gap by providing an automated, scalable, and affordable methane detection platform.

## System Architecture
**Data Flow:**
MQ-4 Sensor → ESP32 (FreeRTOS) → Firebase Cloud → Python Analytics → Heatmap

## Hardware Components
- ESP32-WROOM-32 (Primary controller)
- ATmega328P Pro Mini (Rover control)
- MQ-4 Methane Gas Sensor
- BMP280 Temperature & Pressure Sensor
- NEO-6M GPS Module
- L298N Motor Driver
- Tracked Rover Chassis
- 18650 Li-ion Battery Pack

## Software Stack
- Arduino IDE (ESP32 + ATmega)
- FreeRTOS
- Google Firebase Realtime Database
- Python (Pandas, Matplotlib, SciPy)
- VS Code

## Results
- Real-time methane data logging
- GPS-tagged sensor fusion
- RBF-based geospatial interpolation
- Heatmap-based hotspot visualization

## Future Work
- Autonomous GPS waypoint navigation
- LoRaWAN long-range telemetry
- Multi-gas detection
- Wind-aware gas source localization

## Repository Structure
See folder structure above.

## License
MIT License

