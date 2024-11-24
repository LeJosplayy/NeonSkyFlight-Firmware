# NeonSkyFlight 🚀  
*Advanced Flight Firmware based on MultiWii*

NeonSkyFlight is an open-source project designed to provide cutting-edge firmware for drones and UAVs. Building on the legacy of MultiWii, NeonSkyFlight modernizes drone control systems with advanced microcontroller platforms, customizable configurations, and enhanced usability.

---

## Features ✨
- **Modern Microcontroller Support**: Works seamlessly with Arduino boards and other Atmel AVR platforms.
- **Highly Customizable**: Adjust flight parameters, add sensors, and expand functionality with ease.
- **MultiWii Compatibility**: Retains compatibility with MultiWii, enabling smooth migration.
- **User Interface (UI) Support**: Includes a GUI for real-time drone control and monitoring.
- **Mission Planner Integration**: Plan and execute automated flight missions with precision.

---

## Getting Started 🚁

### Prerequisites
1. **Hardware**:
   - Compatible Microcontroller (e.g., Arduino Uno or Atmel AVR boards)
   - Sensors (e.g., gyroscope, accelerometer, compass)
   - Motors and ESCs for your drone
   
2. **Software**:
   - [PlatformIO](https://platformio.org/) for building and uploading firmware
   - Arduino IDE (optional, for quick tests)
   - [NeonSkyFligtGUI](https://github.com/LeJosplayy/NeonSkyFlight) for for route and task automation

---

### Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/LeJosplayy/NeonSkyFlight-Firmware.git
   cd NeonSkyFlight
2. **Configure your Drone**:
   ```bash
    config.h
3. **Upload Firmware: Modify the configuration file (platformio.ini) to match your microcontroller and board:**:
   ```bash
    [env:uno]
    platform = atmelavr
    board = uno
    framework = arduino

