# 🦽 Voice Controlled Wheelchair Prototype

A voice-operated motorized wheelchair prototype built using Arduino Uno, controlled via Bluetooth voice commands from a smartphone. Also features obstacle detection for safety.

---

## 📌 Overview

This project aims to assist physically disabled individuals by allowing them to control a wheelchair using voice commands sent via Bluetooth from a mobile app. An ultrasonic sensor provides real-time obstacle detection to prevent collisions.

---

## 🛠️ Components Required

| Component | Quantity |
|-----------|----------|
| Arduino Uno | 1 |
| L293D Motor Driver Shield (mounted on Arduino) | 1 |
| HC-05 Bluetooth Module | 1 |
| Ultrasonic Sensor (HC-SR04) | 1 |
| Servo Motor | 1 |
| DC Motors | 4 |
| Battery Pack | 1 |
| Jumper Wires | As required |
| Wheelchair Frame / Chassis | 1 |

---

## ⚙️ How It Works

1. **Voice Input** — User speaks a command (Forward, Backward, Left, Right, Stop) into a Bluetooth terminal app on their smartphone.
2. **Bluetooth Transmission** — HC-05 module receives the command and sends it to the Arduino serially.
3. **Arduino Processing** — Arduino reads the command and drives the DC motors via the L293D motor driver accordingly.
4. **Obstacle Detection** — The ultrasonic sensor continuously measures distance in front. If an obstacle is detected within a threshold (e.g., 20 cm), the wheelchair stops automatically.
5. **Steering** — A servo motor is used for directional steering control for ultrasonic sensor 

---



## 💻 Voice Commands

| Command | Action |
|---------|--------|
| "forward" | Move forward |
| "backward" | Move backward |
| "left" | Turn left |
| "right" | Turn right |
| "stop" | Stop all motors |

---



## 📱 App Used

**Bluetooth Terminal App** (Android) — Any free Bluetooth serial terminal app from the Play Store can be used to send voice/text commands to the HC-05 module.

---

## 🔧 Tools & Technologies

- Arduino IDE
- Embedded C
- L293D Motor Driver
- HC-05 Bluetooth Serial Communication
- Ultrasonic distance sensing (HC-SR04)

---

## 🚀 Future Improvements

- Add a mobile app with dedicated voice recognition buttons
- Integrate gyroscope for smoother turning
- Add speed control using PWM
- Add a buzzer alert when obstacle is detected
- Upgrade to gesture or eye-tracking control

---

## 👤 Author

Dinesh Jakate 
B.Tech Electronics Engineering | D Y Patil College of Engineering Akurdi   
📧 dineshjakate14@gmail.com  
