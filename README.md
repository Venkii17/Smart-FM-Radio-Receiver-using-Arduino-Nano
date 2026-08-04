# 📻 Smart FM Radio Receiver Using Arduino Nano

> A portable smart FM radio receiver built using Arduino Nano with Bluetooth control, LCD display, manual tuning, and digital FM reception.

![Arduino](https://img.shields.io/badge/Arduino-Nano-blue)
![Embedded](https://img.shields.io/badge/Embedded-Systems-success)
![Bluetooth](https://img.shields.io/badge/HC--05-Bluetooth-blueviolet)
![FM](https://img.shields.io/badge/FM-TEA5767-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

# 📖 Overview

Traditional FM radios offer simple functionality but lack modern user interaction and remote control capabilities. This project presents a Smart FM Radio Receiver built using an Arduino Nano that combines conventional FM reception with digital controls.

The system allows users to tune FM stations manually using potentiometers or remotely using a Bluetooth-enabled mobile application. A 16×2 I2C LCD displays the selected frequency, station information, and volume level, providing a user-friendly interface.

The project demonstrates the integration of embedded systems, wireless communication, and analog audio processing in a compact and portable FM receiver.

---

# 🎯 Objectives

- Design a portable FM radio receiver
- Receive stations between **87 MHz and 108 MHz**
- Display station information on LCD
- Control tuning and volume using potentiometers
- Enable Bluetooth-based remote control
- Learn Arduino-based embedded system design

---

# ✨ Features

✔ Digital FM reception using TEA5767

✔ Bluetooth remote control

✔ Manual tuning using potentiometer

✔ Volume control

✔ LCD display

✔ Portable design

✔ Arduino Nano based

✔ High-quality audio output using LM386 amplifier

---

# 🏗 Block Diagram

```
             FM Antenna
                  │
                  ▼
          TEA5767 FM Module
                  │
                  ▼
            Arduino Nano
        ┌─────────┼──────────┐
        ▼         ▼          ▼
   HC-05      LCD Display   Potentiometers
 Bluetooth                 Frequency/Volume
        │
        ▼
    LM386 Amplifier
        │
        ▼
      Speaker
```

---

# 🧠 Working Principle

1. The TEA5767 module receives FM radio signals through an antenna.

2. Arduino Nano communicates with the TEA5767 using the I2C protocol.

3. Users can tune stations using:

- Potentiometer
- Bluetooth mobile application

4. Another potentiometer controls audio volume.

5. Frequency, station details, and volume are displayed on the 16×2 I2C LCD.

6. Audio output is amplified using the LM386 audio amplifier.

7. The amplified signal is played through the speaker.

---

# 🛠 Hardware Components

| Component | Purpose |
|------------|----------|
| Arduino Nano | Main Controller |
| TEA5767 FM Module | FM Reception |
| HC-05 Bluetooth | Wireless Control |
| LM386 Audio Amplifier | Audio Amplification |
| 16×2 I2C LCD | Display |
| 10K Potentiometers | Frequency & Volume Control |
| Speaker | Audio Output |
| Breadboard | Circuit Assembly |
| Power Supply | System Power |

---

# 💻 Software Used

- Arduino IDE
- Embedded C
- Electronics Bluetooth Controller App

---

# 📂 Project Structure

```
Smart-FM-Radio-Receiver-Using-Arduino-Nano
│
├── README.md
├── LICENSE
│
├── docs
│   ├── Project_Report.pdf
│   └── Presentation.pptx
│
├── images
│   ├── prototype.jpg
│   ├── hardware.jpg
│   ├── block_diagram.png
│   ├── flowchart.png
│   ├── circuit_diagram.png
│   ├── lcd_output.jpg
│   └── bluetooth_control.jpg
│
├── hardware
│   ├── Schematic.pdf
│   ├── Wiring_Diagram.png
│   └── Components.pdf
│
├── software
│   ├── Arduino
│   │      main.ino
│   └── Libraries
│
├── simulation
│   └── wokwi_project
│
└── results
```

---

# 📷 Project Images

## Prototype

(Add image here)

---

## Hardware Setup

(Add image here)

---

## Circuit Diagram

(Add image here)

---

## Block Diagram

(Add image here)

---

## Flowchart

(Add image here)

---

## LCD Output

(Add image here)

---

## Bluetooth Control

(Add image here)

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/Smart-FM-Radio-Receiver-Using-Arduino-Nano.git
```

Open the project in Arduino IDE.

Install required libraries.

Connect Arduino Nano.

Upload the code.

Power the circuit.

Tune FM stations using potentiometers or Bluetooth.

---

# 📊 Results

The developed system successfully:

- Receives FM radio stations
- Tunes frequencies accurately
- Displays station frequency on LCD
- Supports Bluetooth control
- Provides clear audio output through LM386 amplifier
- Allows smooth manual tuning

---

# 📡 Frequency Range

- Minimum Frequency: **87.0 MHz**
- Maximum Frequency: **108.0 MHz**

---

# 📱 Bluetooth Control

The HC-05 Bluetooth module enables users to:

- Tune stations remotely
- Adjust volume
- Control radio using a smartphone

---

# 🌍 Applications

- Educational Projects
- Embedded Systems Learning
- FM Receiver Prototype
- Portable Radio Systems
- Arduino Learning
- Wireless Audio Systems

---

# ⚠ Limitations

- Supports FM radio only
- Bluetooth range is limited
- Requires strong FM signal
- No recording functionality
- Depends on antenna quality

---

# 🔮 Future Scope

- OLED/TFT display
- Digital volume control
- Station memory presets
- Automatic channel scanning
- SD card music playback
- Internet radio integration
- Rechargeable battery support
- Mobile application with advanced controls

---

# 📄 Documentation

The repository includes:

- Project Report
- Source Code
- Circuit Diagram
- Block Diagram
- Flowchart
- Hardware Images
- Simulation
- Presentation Slides

---

# 👨‍💻 Team

- Tilak G P
- Vaishnavi B N
- Vedamurthy A N
- **Venkatesh R Shettar**

Guide

Dr. G. S. Sunitha

Department of Electronics & Communication Engineering

Bapuji Institute of Engineering and Technology

---

# 📜 License

This project is released under the MIT License.

---

## ⭐ If you found this project useful, please consider giving it a Star.
