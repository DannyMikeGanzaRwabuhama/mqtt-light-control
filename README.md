# MQTT Light Control

A simple web-based application to control a simulated IoT light using MQTT.

## Overview
- **Web Interface (`index.html`):** A webpage with "Turn ON" and "Turn OFF" buttons that publishes commands to an MQTT topic via WebSockets.
- **Simulated IoT Device (`light_simulation.py`):** A Python script that subscribes to the same topic and prints the light's status.

## Requirements
- Python 3.x
- `paho-mqtt` library (`pip install paho-mqtt`)
- A modern web browser

## How to Run
1. Run the Python simulation:
   ```bash
   python light_simulation.py
