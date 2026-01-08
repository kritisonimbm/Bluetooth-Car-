# Bluetooth Controlled Robotic Car Using Arduino

## Objective
To design and implement a **Bluetooth-controlled robotic car** using an **Arduino microcontroller**, enabling wireless control of motor movement via a mobile device.

---

## Components Used
- Arduino UNO
- Bluetooth Module (HC-05 / HC-06)
- Motor Driver Module (L298N / L293D)
- DC Motors
- Robot Chassis
- Battery / Power Supply
- Jumper Wires

---

## Working Principle
- A mobile phone sends control commands through Bluetooth.
- The Bluetooth module receives these commands and transfers them to the Arduino via serial communication.
- Arduino processes the received data and generates appropriate control signals.
- The motor driver drives the DC motors based on these signals, resulting in forward, backward, left, or right movement of the car.

---

## Control Flow
-Mobile App → Bluetooth Module → Arduino → Motor Driver → DC Motors
---

## Software & Communication
- Arduino IDE used for programming
- Serial communication between Arduino and Bluetooth module
- Command-based motor control logic

---

## Learning Outcomes
- Understanding of Bluetooth-based wireless communication
- Interfacing Bluetooth modules with Arduino
- Motor control using driver circuits
- Embedded system programming basics

---

## Future Enhancements
- Speed control using PWM
- Obstacle detection using ultrasonic sensors
- Voice control integration
- Android app customization

---

## Author
**Kriti Soni**  
B.E. Electronics & Communication Engineering  
MBM University, Jodhpur

