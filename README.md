# LoRaWAN-Based Street Light Control System

## Overview
This project implements a **LoRaWAN-based Street Light Control System** to enable remote monitoring and control of street lights. It leverages **LoRaWAN (Long Range Wide Area Network)** technology for efficient and low-power communication, making it suitable for smart city applications.

## Features
- **Remote Control & Automation**: Allows turning street lights on/off remotely.
- **Energy Efficiency**: Reduces power consumption by enabling dynamic control based on real-time conditions.
- **LoRaWAN Communication**: Uses long-range and low-power communication for reliable data transfer.
- **Real-time Monitoring**: Provides status updates and fault detection.
- **Scheduled Operations**: Supports predefined schedules for automatic lighting control.
- **Scalability**: Can be expanded to control multiple street lights in a citywide network.

## System Architecture
The system consists of:
- **LoRa Nodes**: Each street light is connected to a LoRa-enabled microcontroller for data transmission.
- **LoRa Gateway**: Collects data from nodes and forwards it to the cloud.
- **Network Server**: Manages communication between devices and applications.
- **Web Dashboard / Mobile App**: Allows users to control and monitor street lights remotely.

## Components Used
- **Microcontroller**: ESP32 / Arduino + LoRa Module (SX1276/SX1278)
- **LoRa Gateway**: Raspberry Pi with LoRa concentrator or commercial LoRa gateway
- **Cloud Platform**: The Things Network (TTN) / ChirpStack for LoRaWAN network management
- **Sensors**: LDR (Light Dependent Resistor) for ambient light detection, Current Sensors for power monitoring
- **Power Supply**: Solar panel or AC mains supply

## Installation & Setup
### 1. Hardware Setup
- Connect LoRa modules to microcontrollers.
- Interface sensors and relays for light control.
- Deploy LoRa gateway in a strategic location for optimal coverage.

### 2. Software Setup
- Flash the firmware onto the microcontroller (Arduino/ESP32).
- Configure the LoRaWAN parameters (DevEUI, AppEUI, AppKey) in TTN or ChirpStack.
- Deploy the backend server and web dashboard for remote access.

### 3. Deployment
- Mount the LoRa nodes on street lights.
- Ensure proper network coverage and connectivity.
- Test the control and monitoring functionality.

## Usage
- Access the web dashboard or mobile app to monitor and control street lights.
- Configure schedules and automation rules.
- Monitor real-time power consumption and fault alerts.

## Future Enhancements
- Integration with AI for predictive maintenance.
- Advanced analytics for energy optimization.
- Expansion to smart traffic lights and other urban infrastructure.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests to improve the project.

## License
This project is licensed under the **MIT License**.

## Contact
For queries or support, contact info2ashika@gmail.com
