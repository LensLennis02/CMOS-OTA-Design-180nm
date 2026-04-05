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


**Final Layout (GDSII Ready)** ![TITOLO_IMMAGINE_LAYOUT](PLACEHOLDER)

**Stability Analysis (Bode Plot)** ![TITOLO_IMMAGINE_BODE](PLACEHOLDER)

**Total System Schematic** ![TITOLO_IMMAGINE_SCHEMATIC](PLACEHOLDER)

---

## 📂 Repository Contents
* `ANALOG_VLSI_project_Demarchi_Lena.pdf`: Full technical report including hand calculations, simulation plots (Bode, THD, PSRR, CMRR), and layout snapshots.

> **Note:** Schematic and layout database files are not included due to confidentiality and NDA restrictions.
