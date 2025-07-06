# 🚗 Bluetooth Controlled Car

This project demonstrates a Bluetooth-controlled car built using an **Arduino Uno**, **HC-05 Bluetooth module**, and an **L298N motor driver**. It allows users to control the movement of the car wirelessly using a smartphone app, showcasing a practical application of embedded systems, wireless communication, and robotics.

---

## 🔧 Features

- **Wireless Bluetooth Control** via HC-05 module.
- **Arduino Uno** microcontroller as the control unit.
- **L298N Motor Driver** to manage dual DC motors.
- **Bidirectional movement**: Forward, Backward, Left, Right, and diagonal movement.
- **Speed control** using predefined levels.
- **Compact, lightweight design**.
- **User-friendly app interface** for control.
- **Educational value** for learners in embedded systems, robotics, and IoT.

---

## 📦 Components Used

| Component                   | Quantity |
|----------------------------|----------|
| 300 RPM DC Gear Motor      | 4        |
| Wheels                     | 4        |
| Cardboard Chassis          | 1        |
| Arduino UNO                | 1        |
| HC-05 Bluetooth Module     | 1        |
| 3.7V Rechargeable Li-ion Battery | 3 (in series) |
| L298N Motor Driver         | 1        |
| Male/Female Jumper Wires   | 19       |
| Breadboard (400 pts)       | 1        |
| Arduino IDE (Software)     | 1        |
| Bluetooth Control App      | 1        |

---

## ⚙️ Circuit Connections

### Motor Driver (L298N) → Arduino:
- IN1 → Pin 5  
- IN2 → Pin 6  
- IN3 → Pin 10  
- IN4 → Pin 11

### Bluetooth Module (HC-05) → Arduino:
- VCC → 5V  
- GND → GND  
- TX → RX (Pin 0)  
- RX → TX (Pin 1)

### Power:
- Li-ion battery pack (connected in series) supplies power via `Vin`.

---

## 💻 Arduino Code (File Given)

The Arduino listens for characters sent from the Bluetooth app and performs movement accordingly:


