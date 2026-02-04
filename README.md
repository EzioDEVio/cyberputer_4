# 📟 Cyberputer 4: The Ultimate M5Stack & Pi 4 Hybrid

![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Status](https://img.shields.io/badge/status-Active-success)

**Cyberputer 4** is a high-performance, modular cyberdeck that bridges the gap between the **M5Stack Cardputer** ecosystem and the raw power of the **Raspberry Pi 4**. 

Designed for security researchers, makers, and cloud engineers, this build integrates a custom power delivery system, LoRa communication, and a fully 3D-printed modular enclosure.

---

## 🚀 Features

* **Dual-Core Logic:** Combines the ESP32-based Cardputer (input/comms) with a Raspberry Pi 4 (heavy lifting).
* **LoRa Enabled:** Integrated M5Stack LoRa module for off-grid messaging and long-range data transmission.
* **Custom Power System:** 3000mAh LiPo battery with a 5V/3A boost converter to handle the Pi 4's peak power demands.
* **Multi-OS Support:** Rapid SD card swapping for **Kali Linux** (Pen-testing), **RetroPie** (Gaming), or **Raspberry Pi OS** (DevOps/Cloud tasks).
* **Custom 3D-Printed Enclosure:** Designed in Fusion 360 with a focus on ergonomics and cooling.

---

## 🛠️ Hardware Manifest

| Component | Description |
| :--- | :--- |
| **SBC** | Raspberry Pi 4 Model B |
| **Input/Display** | M5Stack Cardputer |
| **Wireless** | M5Stack LoRa Module (attached to Cardputer) |
| **Power** | 3000mAh Li-ion + 5V/3A Boost Converter |
| **Cooling** | Integrated Passive/Active cooling slots in the 3D design |
| **Storage** | High-speed MicroSD for OS Swapping |

---

## 📂 Repository Structure

* `/STLs`: 3D printable files for the Cyberputer 4 chassis.
* `/Schematics`: Wiring diagrams for the boost converter and battery integration.
* `/Config`: Useful scripts for setting up the Cardputer as a HID controller or serial terminal for the Pi 4.

---

## 📸 Media & Demo

* **YouTube Shorts:** [Insert Link to your Short here!]
* **Printables:** [Insert Link to your STL collection here!]

---

## 🔧 Installation & Usage

1.  **Print the Enclosure:** Use the files in the `/STLs` folder. (Recommended: PETG or PLA+ for heat resistance).
2.  **Wiring:** Connect the 3000mAh battery to the Boost Converter. Ensure the 5V/3A output is stable before connecting to the Pi 4 GPIO or USB-C port.
3.  **Flash your OS:** Choose your flavor (Kali, RetroPie, etc.) and insert the SD card into the side-loading slot.
4.  **Connect Cardputer:** Link the Cardputer via Bluetooth or Serial to act as the primary interface.

---

## 🤝 Contributing

This project is open-source. If you have suggestions for better power management or enclosure modifications, feel free to fork and PR!

## 📜 License

Distributed under the MIT License. See `LICENSE` for more information.

---
*Developed by **Ezio** - Cloud/DevOps Engineer & Maker*
