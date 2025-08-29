# Speceye 👓✨
Smart assistive glasses for the visually impaired, powered by **ESP32** and **Raspberry Pi Zero 2 W**, written entirely in **C++**.

---

## 📖 Overview
**Speceye** is a wearable smart glasses project designed to assist visually impaired individuals in navigating their surroundings.  
The system uses **ESP32** and **Raspberry Pi Zero 2 W** working together through shared C++ modules to provide real-time assistance.

---

## 🛠️ Hardware
- **ESP32** – Handles sensors, input, and communication.
- **Raspberry Pi Zero 2 W** – Performs higher-level processing and feedback generation.
- **Smart Glasses Frame** – Hosts sensors, small display/audio output, and vibration feedback.

---

## 📂 Project Structure
speceye/
├── esp32/ # C++ code for the ESP32
├── pi2/ # C++ code for the Raspberry Pi Zero 2 W
└── common/ # Shared C++ files used by both devices

---

## 🚀 Features
- Built fully in **C++** for portability and performance.
- Modular design:
    - **ESP32**: sensor reading, wireless communication.
    - **Raspberry Pi Zero 2 W**: data processing and user feedback.
    - **Common**: shared C++ classes/utilities for cross-device communication.
- Designed with accessibility in mind.

---

## ⚡ Getting Started
### Prerequisites
- ESP32 toolchain (Arduino IDE, PlatformIO, or ESP-IDF with C++ enabled).
- Cross-compilation setup for Raspberry Pi Zero 2 W.
- CMake (recommended for building both ESP32 and Pi codebases).

### Setup
1. Build and flash the ESP32 code from the `esp32/` folder.
2. Cross-compile the Pi code from `pi2/` and deploy to Raspberry Pi Zero 2 W.
3. Ensure both devices share the same `common/` C++ files.
4. Connect via Wi-Fi, Bluetooth, or serial as configured in your project.

---

## 🤝 Contributing
Contributions are welcome! Open an issue or pull request to improve code, hardware integration, or documentation.

---

## 📜 License
This project is licensed under the MIT License – see the [LICENSE](LICENSE) file for details.

