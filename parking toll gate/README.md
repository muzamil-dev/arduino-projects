# Automatic Parking/Toll Gate Project

This project provides a practical demonstration of:
- Distance sensing using ultrasonic technology
- Servo motor control
- A real world toll/parking gate

## Components I used in the project:
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- Breadboard & Jumper Wires

## Software I used:
- VSC
- PlatformIO extention

## How this works:
The Ultrasonic Sensor continuously detects for any objects in front of it. When an object is detected in front of the sensor, in this case a toy car, the Arduino sends a signal that this is a vehicle approaching to the servo motor. The servo motor rotates and raises the gate arm. Once the vehicle passes the gate, the sensor closes again.

## Circuit Blueprint

![Parking Gate Blueprint](https://github.com/muzamil-dev/arduino-projects/blob/main/parking%20toll%20gate/parking_toll_blueprint.png)
