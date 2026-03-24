# Smart Home System using ESP32 (Workshop Project)

## Overview
This project is a prototype smart home system developed during a hands-on workshop. It demonstrates IoT-based monitoring and alert systems using ESP32 and multiple sensors.

## Features
- Real-time temperature monitoring (DHT11)
- Intruder detection using IR sensor (buzzer + LED alert)
- Light intensity detection using LM393
- Mobile dashboard using Blynk IoT

## System Architecture
The ESP32 collects data from sensors and sends it to the Blynk IoT platform for visualization and alerts.

## System Logic

- IR sensor detects intrusion → triggers buzzer and red LED
- LM393 detects light intensity → updates light status
- DHT11 sends temperature data to Blynk dashboard
- ESP32 acts as central controller handling all sensor inputs and outputs
  
## Note
This project was implemented as part of a guided workshop. The firmware was pre-provided during the session, and this repository focuses on system understanding, hardware integration, and implementation.

## Demo
https://drive.google.com/file/d/1FT2YwVOwMKIHKKyxvbSLAIagAqQyXjr5/view?usp=drivesdk

## Documentation

- [Components](docs/ Components.md)
- [System Architecture](docs/System Architecture.md)
- [Working](docs/ Working.md)

## Learning Outcomes
- Sensor interfacing concepts
- IoT architecture using ESP32
- Cloud dashboard integration (Blynk)
- Team-based hardware development

## Limitations

- Firmware not self-developed
- Limited automation logic
- Sensor accuracy depends on calibration

## Future Work (Planned Development)

- Write custom ESP32 firmware
- Add relay-based automation
- Implement threshold-based decision logic
- Expand to multi-room monitoring system

## Team
- Asutosh
- Ayush
- Deepak
- Mukul
