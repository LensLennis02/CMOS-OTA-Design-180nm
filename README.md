# 180nm CMOS Two-Stage Operational Transconductance Amplifier (OTA)

This project covers the full analog design flow of a high-performance, two-stage OTA using **Cadence Virtuoso** in a **180nm CMOS process**.

## 📑 Project Overview
The amplifier is designed to operate with a **1V supply voltage** and is biased by an integrated **BANBA (Bandgap)** voltage and current reference. The design targets low-voltage analog systems such as data converters and analog filters where low power and high gain are required.

### Key Specifications:
| Parameter | Value |
| :--- | :--- |
| **Technology** | 180nm CMOS |
| **Supply Voltage** | 1V |
| **DC Loop Gain** | 88.84 dB |
| **Phase Margin** | 61.38° |
| **GBW** | 3.902 MHz |
| **Power Consumption** | 431.7 µW |

---

## 🛠️ Design Stages
1. **Schematic Design:** Implementation of an NMOS differential input stage combined with a Class AB output stage to achieve high swing and power efficiency.
2. **Dimensioning:** Detailed noise analysis for Signal-to-Noise Ratio optimization and Miller compensation to ensure frequency stability.
3. **Robustness Analysis:** * **PVT Corners:** Validation across multiple process corners (TT, FF, SS, SF, FS) and temperature ranges.
   * **Monte Carlo:** Extensive 1000-run simulations to account for process and mismatch variations.
4. **Physical Layout:** Full-custom layout using **Common Centroid** matching techniques for the differential pair to minimize systematic offset and mismatch.
5. **GDS Flow:** Completion of the physical design, resulting in a layout ready for fabrication.

---

## 🖼️ Visual Results

**Final Layout (GDSII Ready)**
![Final Layout](https://raw.githubusercontent.com/LensLennis02/CMOS-OTA-Design-180nm/main/Total_layout.png)

**Stability Analysis (Bode Plot)**
![Bode Plot](https://raw.githubusercontent.com/LensLennis02/CMOS-OTA-Design-180nm/main/Bode%20both.png)

**Total System Schematic**
![Total System Schematic](https://raw.githubusercontent.com/LensLennis02/CMOS-OTA-Design-180nm/main/Total%20scheme.png)


---

## 📂 Repository Contents
> [!IMPORTANT]
> **Full Report Access:** Due to the detailed nature of the design and EDA tool configurations, the full PDF report is kept in a restricted repository. 
> 
> **To request access for recruitment or review purposes:**
> 1. Contact me via **LinkedIn**: [lorenzo-lena-92523b311](https://www.linkedin.com/in/lorenzo-lena-92523b311)
> 2. Or send an **Email**: Lori.le2002@gmail.com

> **Note:** Schematic and layout database files are not included due to confidentiality and NDA restrictions.
