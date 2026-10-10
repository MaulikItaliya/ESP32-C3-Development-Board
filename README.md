<div align="center">

# 📶 ESP32-C3 Development Board

**Custom 4-layer Wi-Fi & Bluetooth LE development board with USB Type-C and an inverted-F antenna, designed in Altium Designer and assembled by hand.**

![Altium](https://img.shields.io/badge/Altium_Designer-A5915F?style=for-the-badge)
![ESP32-C3](https://img.shields.io/badge/ESP32--C3-E7352C?style=for-the-badge&logo=espressif&logoColor=white)
![PCB](https://img.shields.io/badge/PCB-4--Layer-2C5364?style=for-the-badge)
![USB-C](https://img.shields.io/badge/USB-Type--C-1E3A5F?style=for-the-badge)
![Status](https://img.shields.io/badge/Status-Built_&_Tested-4CAF50?style=for-the-badge)

<br/>

<img src="ESP32-C3_Hardware%20Images/3D_Front_side.png" width="45%" alt="ESP32-C3 board, 3D front view"/>
<img src="ESP32-C3_Hardware%20Images/3D_Back_side.png" width="45%" alt="ESP32-C3 board, 3D back view"/>

</div>

---

## 📌 Overview

This project is a custom **4-layer ESP32-C3 development board** designed in **Altium Designer**. The goal was to gain practical experience in the full hardware workflow: schematic capture, PCB layout, manufacturing preparation, hand assembly and bring-up. The design follows the ESP32-C3 datasheet and the Espressif hardware design guidelines.

The board was manufactured and then assembled by hand to validate the complete design workflow.

📄 **[Download the schematic & PCB design PDF →](Harware%20design%20PDF/ESP32_RF-Board_PCB_%26_Schemetic.pdf)**

---

## ✨ Features

| Area | Implementation |
|---|---|
| **MCU** | ESP32-C3, Wi-Fi and Bluetooth LE |
| **Interface** | USB Type-C |
| **Power** | 3.3 V supply with decoupling and power filtering |
| **RF** | Inverted-F antenna with antenna keep-out region |
| **PCB** | 4-layer stack-up with ground-plane optimization |
| **User I/O** | Reset and Boot buttons, status LED |
| **Programming** | Programming and debug interface |
| **Verification** | Design Rule Check (DRC) passed before fabrication |

<!-- TODO: add board size, regulator part number, USB programming method and layer stack (e.g. Signal / GND / Power / Signal) to the table above. -->

---

## 🔬 Hardware Design Process

```mermaid
flowchart LR
    A["Schematic<br/>capture"] --> B["Component<br/>selection"]
    B --> C["4-layer PCB<br/>layout"]
    C --> D["DRC &<br/>manufacturing rules"]
    D --> E["Fabrication"]
    E --> F["Hand assembly"]
    F --> G["Bring-up &<br/>testing"]
```

- Created the complete schematic in Altium Designer, based on the ESP32-C3 reference design
- Designed a compact 4-layer PCB with proper power distribution and decoupling
- Routed the USB differential pair
- Applied the RF antenna keep-out recommendations
- Configured design rules for manufacturing and hand soldering
- Ran Design Rule Checks before fabrication

---

## 🖼️ PCB Preview

### 2D Layout

| Top Layer (L1) | Bottom Layer (L4) |
|:---:|:---:|
| <img src="ESP32-C3_Hardware%20Images/2D_L1.png" width="100%" alt="PCB top layer L1"/> | <img src="ESP32-C3_Hardware%20Images/2D_L4.png" width="100%" alt="PCB bottom layer L4"/> |

### 3D Render

| Front Side | Back Side |
|:---:|:---:|
| <img src="ESP32-C3_Hardware%20Images/3D_Front_side.png" width="100%" alt="3D front side"/> | <img src="ESP32-C3_Hardware%20Images/3D_Back_side.png" width="100%" alt="3D back side"/> |

---

## 🛠️ Assembly

The PCB was assembled manually by hand soldering:

- ESP32-C3 module
- USB Type-C connector
- Passive components
- Power supply circuitry
- Headers and supporting components

<!-- Optional: add a photo of the assembled board, e.g. ![Assembled board](ESP32-C3_Hardware%20Images/Assembled.jpg) -->

---

## ✅ Testing & Bring-up

| Check | Status |
|---|:---:|
| Visual inspection | ✅ |
| Continuity testing | ✅ |
| Power rail verification | ✅ |
| USB connectivity | ✅ |
| ESP32-C3 programming | ✅ |
| Basic functional testing | ✅ |

<!-- Optional: add measured results, e.g. 3.3 V rail voltage, current draw, Wi-Fi / BLE test. -->

---

## 📂 Repository Structure

```
ESP32-C3-Development-Board/
├── ESP32-C3_Hardware Images/
│   ├── 2D_L1.png               # PCB top layer
│   ├── 2D_L4.png               # PCB bottom layer
│   ├── 3D_Front_side.png       # 3D render, front
│   └── 3D_Back_side.png        # 3D render, back
├── Harware design PDF/
│   └── ESP32_RF-Board_PCB_&_Schemetic.pdf   # Schematic and PCB design document
└── README.md
```

---

## 🎓 Skills Demonstrated

![Schematic](https://img.shields.io/badge/Schematic_Capture-1E3A5F?style=flat-square)
![Layout](https://img.shields.io/badge/PCB_Layout_(4_layers)-1E3A5F?style=flat-square)
![Power](https://img.shields.io/badge/Power_Supply_Design-1E3A5F?style=flat-square)
![USB](https://img.shields.io/badge/USB_Routing-1E3A5F?style=flat-square)
![RF](https://img.shields.io/badge/RF_Layout-1E3A5F?style=flat-square)
![Placement](https://img.shields.io/badge/Component_Placement-1E3A5F?style=flat-square)
![DRC](https://img.shields.io/badge/Design_Rules_&_DRC-1E3A5F?style=flat-square)
![Soldering](https://img.shields.io/badge/Hand_Soldering-1E3A5F?style=flat-square)
![Debug](https://img.shields.io/badge/Hardware_Debugging-1E3A5F?style=flat-square)

---

## 📝 Disclaimer

This is a learning and portfolio project, based on publicly available documentation, manufacturer reference designs and hardware design guidelines. Its purpose is to demonstrate practical PCB design, layout, assembly and hardware validation skills. It is not a certified or production-ready product.

---

## 👤 Author

**Maulik Italiya**: Embedded Hardware & Systems · M.Sc. Embedded Systems Design, Hochschule Bremerhaven

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/maulik-italiya/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/MaulikItaliya)
