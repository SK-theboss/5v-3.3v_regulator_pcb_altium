# 5V to 3.3V Voltage Regulator PCB (Altium)

This repository contains the Altium Designer files for a simple **voltage regulator circuit** that steps down 5V to 3.3V using a linear regulator IC. This circuit is commonly used to power 3.3V logic devices (e.g., ESP32, sensors) from a standard 5V supply.

---

## 🔧 Project Description

This voltage regulator circuit uses the **AMS1117-3.3** linear voltage regulator to convert a 5V input to a stable 3.3V output. It includes decoupling capacitors on both input and output for stability and noise reduction.

---

## ⚙️ Features

- AMS1117-3.3 Linear Regulator
- 5V Input, 3.3V Output (fixed)
- Compact, single-sided PCB layout
- Through-hole or SMD component support
- Input/Output screw terminals or header pins

---

## 📁 Files Included

| File/Folder                                | Description                            |
|-------------------------------------------|----------------------------------------|
| `PowerConverter.PrjPcb`                   | Altium PCB project file                |
| `PowerConverter.SchDoc`                   | Schematic design                       |
| `PowerConverter.PcbDoc`                   | PCB layout                             |
| `PowerConverter.PrjPcbStructure`          | Project structure metadata             |
| `README.md`                               | This documentation file                |

---

## 🖥️ Preview

_Schematic View_

![image](https://github.com/user-attachments/assets/a6dc6050-1491-4ebc-bd04-1b698022d7ec)


_PCB Layout_

![image](https://github.com/user-attachments/assets/7405952b-d682-4010-bf8e-74e53c730a44)



---


## 📦 Bill of Materials (BOM)

| Component    | Value / Part         | Quantity |
|--------------|----------------------|----------|
| U1           | AMS1117-3.3          | 1        |
| C1 (Input)   | 10µF (Electrolytic)  | 1        |
| C2 (Output)  | 10µF (Electrolytic)  | 1        |
| CN1, CN2     | 2-pin screw terminal / header | 2    |
| PCB          | Custom Altium Layout | 1        |

---

## 🧾 License

This project is open-source under the [MIT License](LICENSE).

---

## 🙌 Credits

Designed by Senthilkumaran K, using **Altium Designer**  
Suitable for beginner electronics, embedded systems, and power supply design projects.

---
