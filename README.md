# 🧮 IoT Calculator

An IoT Calculator is a custom-made device built using Embedded Systems and IoT technology. It combines a traditional calculator with smart features such as wireless connectivity, cloud integration, calculation history storage, and AI-based assistance.

Built using ESP32, Keypad Module, Display Module, and Cloud Services.

---

## 🚀 Features

- Basic Mathematical Operations
  - Addition
  - Subtraction
  - Multiplication
  - Division

- IoT Connectivity
  - WiFi Communication
  - Bluetooth Support

---

## 🛠 Components Used

### Hardware
- ESP32 Development Board
- 4x4 Matrix Keypad
- LCD/OLED Display
- I2C Module
- Jumper Wires
- Breadboard
- Battery Supply

### Software
- Arduino IDE
- Embedded C/C++
- Firebase Database
- REST API

---

## 📂 Project Structure

IoT-Smart-Calculator/

├── Arduino_Code/

└── README.md


---

## 🔌 ESP32 Connections

LCD I2C:

VCC → 5V  
GND → GND  
SDA → GPIO21  
SCL → GPIO22


Keypad:

R1 → GPIO13  
R2 → GPIO12  
R3 → GPIO14  
R4 → GPIO27  

C1 → GPIO26  
C2 → GPIO25  
C3 → GPIO33  
C4 → GPIO32


---

## ⚙️ Working Process

1. User enters calculation using keypad

2. ESP32 reads the input

3. Microcontroller processes the calculation

4. Result is displayed on LCD/OLED

5. Data is uploaded to cloud

6. User can view calculation history remotely


---

## 📱 Dashboard Features

- View Previous Calculations
- Device Status Monitoring
- Usage Analytics
- Cloud Data Storage

---

## 🔮 Future Enhancements

- Voice Calculator
- AI Math Solver
- Camera Based Equation Solver
- Mobile Application
- Scientific Calculator Mode
- Graph Plotting

---

## 🎯 Applications

- IoT Learning Project
- Smart Education Device
- Embedded System Project
- Engineering Project
- AI Integrated Calculator


---

## 🚀 Installation

Clone repository:

git clone <repository-link>


Open Arduino IDE:

Upload:

SmartCalculator.ino


Install Libraries:

- LiquidCrystal_I2C
- WiFi
- Firebase ESP Client
- ArduinoJson


---

## 👨‍💻 Developer

Sazid Sheikh


---

⭐ If you like this project, give it a star!
