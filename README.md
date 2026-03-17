# Power Distribution Board and DC-DC Converter

## Overview
This project is a **Power Distribution Board (PDB) with integrated DC-DC converter** designed to distribute power from a single input source to multiple loads while providing regulated voltage outputs.

The board is intended for drone: fixed & rotary wing applications.

---

## Features

- Input voltage: **7-30V**
- Output voltage: **5V**
- Maximum output current: **5A**
- DC-DC converter topology: **buck**
- Number of power outputs: **1**
- Protection features:
  - overcurrent / reverse polarity / thermal
- PCB layers: **2**
- PCB dimensions: **36x50.1cm**

---

## Hardware Overview

The board consists of two main functional blocks:

### Power Distribution
The PDB distributes input power to 5 outputs designed for powering external devices such as:

- ESC's
- FC's

### DC-DC Converter
The integrated DC-DC converter regulates the input voltage to a stable output voltage required by connected electronics.

Converter specifications:

- Converter IC: **TPS54560DDAR**
- Switching frequency: **0,1...2,5MHz**
- Efficiency: **[DO UZUPEŁNIENIA]**
- Casing: **HSOP8**

---

<img width="557" height="714" alt="image" src="https://github.com/user-attachments/assets/0dc23a28-c8f5-4e5c-a2ad-b90776dafc35" />
Altium Designer 2D view
![PDB bez komponentów](https://github.com/user-attachments/assets/17969aaa-fec0-4953-b79f-d7ba03aadd25)
Unsoldered physical PCB
