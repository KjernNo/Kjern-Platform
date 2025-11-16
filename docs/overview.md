# Kjern Platform Overview

The Kjern Platform is a growing ecosystem of compact, developer-friendly electronic boards designed in Norway. The platform is built around reliability, modern connectivity, and ease of use, with a strong focus on open firmware and accessible development workflows.

This document provides a detailed overview of the three core hardware products that currently make up the Kjern ecosystem:  
- Kjern-32u4HID-C  
- Kjern-32u4  
- Kjern-C2

Hardware design files (schematics, PCB, BOM) are intentionally not published. This documentation is high-level and developer-oriented.

---

## 1. Kjern-32u4HID-C

The Kjern-32u4HID-C is a compact, USB-C microcontroller based on the ATmega32u4, fully compatible with the Arduino ecosystem. Its built-in HID functionality makes it ideal for custom input devices, automation projects, and embedded control.

### **Key Features**
- **USB-C** for both power and data  
- **Native HID support** (keyboard, mouse, gamepad, custom)  
- Fully **Arduino-compatible**
- ATmega32u4 at 16 MHz  
- 32 KB Flash, 2.5 KB SRAM  
- Compact 29 × 15 mm PCB  
- Works on Windows, Linux, macOS

### **Use Cases**
- Macro pads  
- Custom keyboards  
- Game controllers  
- Media controllers  
- Automations & shortcuts  
- Sensor interfaces via HID  
- MIDI controllers

This board is the first released device and represents the start of the Kjern ecosystem.

---

## 2. Kjern-32u4 (Coming Soon)

The Kjern-32u4 expands on the Kjern-32u4HID-C by offering full GPIO support for more advanced prototyping and embedded applications. It is designed as a versatile general-purpose microcontroller board.

### **Key Features**
- Multiple analog input pins  
- Multiple digital I/O pins  
- JST-PH 2-pin connector for battery or external supply  
- USB-C for power and communication  
- ATmega32u4 microcontroller  
- Designed for sensors, embedded control, and more complex projects

A 3D render of the board exists; the final design may change before production.

---

## 3. Kjern-C2 Dual Li-Po Charger (Under Consideration)

The Kjern-C2 is a potential future product that provides dual-port Li-Po charging using the TPD4056 IC. It is designed for makers who need multi-battery charging capabilities with proper safety protection.

### **Key Features**
- 2 × Li-Po charging channels  
- **800 mA per channel** (1.6 A total)  
- **8 W total power**  
- Two JST-PH connectors  
- Resettable polyfuse for safety  
- LED charge indicators (charging / full)  
- Reliable power handling for a wide range of Li-Po batteries

Community interest and feedback will guide whether this product enters production.

---

## 4. Platform Vision

The Kjern ecosystem aims to offer:

- Microcontrollers for input devices, automation, and embedded projects  
- Power modules like the C2 for battery-based designs  
- Open-source firmware components that enable customization  
- A consistent API across boards  
- Developer-friendly documentation  
- Accessible hardware at fair prices  

The long-term plan is to build a complete ecosystem where each Kjern product complements the others.

---

## 5. Openness & Protection

Kjern commits to open-sourcing firmware components where feasible, allowing developers to build custom applications with minimal friction. However, certain aspects will remain closed to ensure product integrity:

### **Open:**
- Firmware (partial or full, depending on module)  
- Arduino libraries  
- Example code  
- Developer documentation  

### **Closed:**
- Schematics  
- PCB files  
- BOM  
- Production testing tools

This hybrid model balances community empowerment with business sustainability.

---

If you have suggestions or want to contribute feedback, feel free to open an issue or contact us directly.
