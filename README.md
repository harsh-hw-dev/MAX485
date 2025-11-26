# 🔌 TTL to RS485 Converter | MAX485

A compact and reliable **TTL to RS485 communication module** designed in **Altium Designer** using the **MAX485CSA** transceiver IC. Built for **robust, noise-immune, long-distance serial communication** in industrial and embedded applications.

---

## ✨ Features
- ✅ MAX485-based **RS485 Transceiver**
- ✅ **TTL UART Interface** (RO, RE, DE, DI)
- ✅ **5V Single Supply Operation**
- ✅ **Half-Duplex Communication**
- ✅ **Differential Signal with High Noise Immunity**
- ✅ **On-board Power LED Indicator**
- ✅ **Biasing & Termination Resistors Included**
- ✅ **Compact, Industry-Ready Design**

---

## 🧠 Applications
- Industrial Automation  
- PLC Communication  
- Embedded Systems  
- Sensor Networks  
- Long-Distance Serial Data Transmission  

---

## 🔌 Pin Configuration

### ✅ TTL Side (P1)
| Pin | Signal | Description |
|-----|--------|-------------|
| 1 | RO | Receiver Output |
| 2 | RE | Receiver Enable |
| 3 | DE | Driver Enable |
| 4 | DI | Driver Input |

### ✅ RS485 Side (P2)
| Pin | Signal | Description |
|-----|--------|-------------|
| 1 | GND | Ground |
| 2 | A | RS485 A Line |
| 3 | B | RS485 B Line |
| 4 | +5V | Power Supply |

---

## ⚙️ Onboard Components
- **U1:** MAX485CSA RS485 Transceiver  
- **R1–R8:** Biasing & Termination Resistors  
- **C1, C2:** Power Decoupling Capacitors  
- **D1:** Power Indicator LED  

---

## 🛠 Designed In
- **EDA Tool:** Altium Designer  
- **Schematic:** Custom Design  
- **Designed By:** Harsh  

---

## 🚀 Usage Notes
- Operates at **5V only**
- Use **DE & RE pins** for direction control
- Supports cable lengths up to **1200m** with proper termination
- Ideal for **industrial noisy environments**

---

## 📁 Repository Structure

---

## 📜 License
This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

## 🤝 Contributing
Found a bug? Have an improvement?  
Feel free to **open an issue or submit a pull request**.

---

## ⭐ Support
If you like this project, don’t forget to **give it a star ⭐ on GitHub!**
