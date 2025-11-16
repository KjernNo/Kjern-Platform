# Kjern Platform

The official development platform for all Kjern hardware products.  
Our mission: **Norwegian electronics, built by enthusiasts for enthusiasts.**

This repository contains public documentation, high-level architecture, product overviews, development roadmaps, and (soon) open-source firmware and SDK components for the Kjern ecosystem.

Kjern builds compact, modern, developer-friendly electronics for makers, students, engineers, and hobbyists. All boards are designed in Norway and built for reliability, usability, and openness—while still protecting proprietary hardware designs.

---

## 🚀 Current Hardware Lineup

### **Kjern-32u4HID-C**  
**Arduino-compatible ATmega32u4 microcontroller** with USB-C and native HID support.

- ATmega32u4 @ 16 MHz  
- USB-C data + power  
- Native HID (keyboard, mouse, gamepad, custom HID)  
- 32 KB flash (4 KB bootloader), 2.5 KB SRAM  
- Compact 29 × 15 mm form factor  
- Works with Windows, Linux, macOS  
- Sleek black PCB with white silkscreen  

This is the first production board and is available after proper testing, and final design order.

---

### **Kjern-32u4** *(Coming Soon)*  
General-purpose ATmega32u4 development board with expanded I/O.

- Full GPIO support  
- Multiple analog & digital I/O pins  
- JST-PH 2-pin connector for external battery power  
- USB-C for power and data  
- Main microcontroller for future Kjern expansions  
- Designed for embedded control, prototyping, and sensors

Currently in design validation.

---

### **Kjern-C2** *(Under Consideration)*  
Dual-port Li-Po charger powered by the efficient TPD4056 IC.

- Two independent Li-Po chargers  
- **800 mA per port (1.6 A total)**  
- Total power rating: **8 W**  
- Two JST-PH connectors  
- Resettable polyfuse for safety  
- LED indicators: charging / full  
- Ideal for multi-cell projects, IoT devices, and portable systems  

Community interest will determine production.

---

## 📚 Documentation

Documentation is located in the `docs/` directory:

- [`overview.md`](docs/overview.md) — full ecosystem overview  
- [`roadmap.md`](docs/roadmap.md) — current and future development plans  
- `block-diagrams.png` (to be added)

---

## 🧩 Firmware & SDK (Coming Soon)

Kjern aims to open-source **parts or all** of its firmware over time.  
The following components are planned:

### **Firmware**
- ATmega32u4 low-level drivers  
- USB-C & HID support  
- Power management logic  
- Peripheral libraries  
- Bootloader enhancements  

### **SDK**
- Arduino-compatible libraries  
- C/C++ headers  
- Python tooling (optional)  
- Example applications  
- HID templates (keyboard, mouse, MIDI, custom devices)

Our open-source model ensures developers can build freely without exposing proprietary hardware designs.

---

## 🔒 Hardware Protection

To prevent unauthorized cloning, the following will remain closed-source:

- Schematics & PCB layout  
- BOM (Bill of Materials)  
- Manufacturing files  
- Test & calibration firmware  

This repo focuses on developer-facing documentation and software only.

---

## 🛠 Project Goals

- Create a coherent ecosystem of microcontrollers, chargers, and accessories  
- Support makers with accessible, high-quality hardware  
- Provide open firmware components for customization  
- Maintain a professional, trusted platform built in Norway  
- Encourage community feedback and iteration  

---

## 📫 Contact

**Email:** kontakt@kjern.no  
**Location:** Bergen, Norway  
**Website:** https://kjern.no  

© 2025 Kjern. All rights reserved.  
Made with ❤️ in Norway.
