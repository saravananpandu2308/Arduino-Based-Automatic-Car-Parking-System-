# Autonomous Parallel Parking System

## Overview
The Autonomous Parallel Parking System is an Arduino-based project that automatically detects a suitable parking space and performs parallel parking without human intervention. The system uses an ultrasonic sensor to measure the distance to obstacles, a servo motor for steering control, and an LCD display to provide real-time parking status.

## Features
- Automatic parallel parking
- Obstacle detection using ultrasonic sensor
- Servo motor-based steering control
- Real-time status display on LCD
- Simple and low-cost implementation
- Improved parking accuracy and safety

## Components Used
- Arduino UNO
- HC-SR04 Ultrasonic Sensor
- Servo Motor
- 16×2 LCD Display
- DC Motor
- Breadboard
- Connecting Wires
- Power Supply

## Working Principle
1. The ultrasonic sensor continuously measures the distance to nearby obstacles.
2. The Arduino UNO processes the sensor data.
3. When sufficient parking space is detected, the Arduino controls the servo motor and DC motor to perform the parking maneuver.
4. The LCD displays system status such as *Searching, **Parking, and **Parked*.

## Circuit Connections
### Ultrasonic Sensor
- VCC → 5V
- GND → GND
- TRIG → Pin 9
- ECHO → Pin 10

### Servo Motor
- VCC → 5V
- GND → GND
- Signal → Pin 6

### LCD Display
- RS → Pin 7
- E → Pin 8
- D4 → Pin 11
- D5 → Pin 12
- D6 → Pin 13
- D7 → A0
- VCC → 5V
- GND → GND

## Advantages
- Reduces driver effort
- Improves parking accuracy
- Prevents collisions
- User-friendly operation
- Low-cost implementation
- Suitable for smart vehicle applications

## Applications
- Smart vehicles
- Driver assistance systems
- Autonomous parking systems
- Smart transportation

## Future Enhancements
- Camera-based parking assistance
- AI-based object detection
- Mobile app monitoring
- IoT integration
- Fully autonomous vehicle implementation

## Conclusion
This project demonstrates an efficient and affordable autonomous parking solution using Arduino. It enhances safety, convenience, and parking accuracy while providing a strong foundation for future intelligent transportation systems.

## Author
*Saravanan P*  
B.E. Electrical and Electronics Engineering  
Adhiparasakthi College of Engineering
