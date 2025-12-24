# AMAN Smart Home System - Build Journal

**Total Hours: 4**

**Target: 105 hours for Bambu Lab A1 mini 3D Printer via Flavortown**

---

## December 24, 2025 - 4 hours

### What I'm Building:
A modular smart home ecosystem that uses my existing AMAN-OS as the central control hub. The system will have three modules that communicate wirelessly via Bluetooth (HC-05):

**Module 1 - Smart Plant Care:**
- Soil moisture sensor
- DHT11 (temperature + humidity)
- Water pump with relay
- Auto-watering system

**Module 2 - Room Security:**
- Ultrasonic sensors (entry detection)
- IR sensors (motion detection)
- Buzzer alarm system
- Real-time alerts to AMAN-OS

**Module 3 - Climate Monitor:**
- DHT11 sensors in multiple locations
- Optional fan control
- Temperature/humidity dashboard

All modules report to AMAN-OS LCD display as the central interface.

### Why This Project:
I want to expand my AMAN-OS (which I built earlier) into a full smart home system. I have all the components already (multiple Arduino Unos, sensors, HC-05 modules, water pumps, etc.) so I can start building immediately.

### Today's Work:
- Researched modular smart home architectures
- Planned the three-module system design
- Decided on Bluetooth (HC-05) for wireless communication
- Listed all available components I have
- Sketched rough system diagram on paper
- Decided to build Module 1 (Plant Care) first

### Components Inventory:
- Multiple Arduino Unos (one with USB-C)
- AMAN-OS Nano with 16x2 LCD (already built)
- 2+ HC-05 Bluetooth modules
- DHT11 temperature/humidity sensors
- Multiple ultrasonic sensors
- 4x IR sensors
- Soil moisture sensor
- Water pumps (multiple)
- Motor drivers
- DC motors, servos
- Buzzer, LEDs, breadboards, wires, resistors

### Design Decisions:
- **Why modular?** Each module can work independently and be added/removed without affecting others
- **Why Bluetooth?** HC-05 modules I already have, easier than WiFi for this scale
- **Why plant care first?** Self-contained, uses interesting mix of sensors + actuator (pump), practical application

### Challenges to Solve:
- How to structure the communication protocol between modules and AMAN-OS
- Power supply for each module (USB or battery?)
- Moisture threshold calibration for auto-watering
- AMAN-OS menu system for displaying all modules' data

### Photos:
(Will add component photos and sketches tomorrow when I start building)

### Next Steps:
- Wire up Module 1 breadboard circuit tomorrow
- Write Arduino code for soil moisture + DHT11 + pump
- Test moisture sensor calibration in actual soil
- Implement basic HC-05 communication
- Start AMAN-OS code for receiving Module 1 data

### Learning Goals:
- Wireless sensor networks
- Home automation systems
- Multiple microcontroller coordination
- Practical IoT applications

---
