# Two-Stage Miller Compensated Operational Amplifier Design

This project involves the design and simulation of a two-stage Miller compensated operational amplifier using LTspice, targeting high gain and stability for analog signal processing applications. The design was implemented using the TSMC 180nm CMOS process.

## ✨ Key Specifications

- **Architecture:** Two-stage Miller compensated OTA
- **Open-Loop Gain:**  
  - First stage: ~43 dB  
  - Combined (two-stage): ~73 dB
- **Phase Margin:** ~60°
- **Gain Bandwidth Product (GBWP):** ~9 MHz
- **Input Common-Mode Range (ICMR):** 0.8 V to 1.6 V
- **Power Consumption:** ~127 µW
- **Common Mode Rejection Ratio (CMRR):** ~60 dB
- **Power Supply:** 1.8 V
- **Load Capacitance:** 10 pF
- **Miller Compensation Capacitance:** 2.2 pF

## 🧪 Simulation Details

- **Tool:** LTspice
- **Technology:** TSMC 180nm CMOS
- **Simulation Type:** Transient, AC analysis, and DC sweep
- **Validation:**  
  - Signal stability and phase margin verified using AC analysis  
  - Gain and bandwidth confirmed via Bode plots  
  - Timing behavior verified through waveform simulations

## 📁 Files Included

- `ota2_pulse_anshuman.asc` – LTspice schematic
- `ota2_sinusoid_Anshuman.asc` – LTspice waveform plotting settings
- `README.md` – Project overview 
- `2-Stage-OTA-Report.pdf` - Contains a detailed report along with calculations

## 📌 Notes

- Ensure the TSMC 180nm model library is properly set up in LTspice before running simulations.
- The compensation was carefully selected to achieve a good trade-off between stability (phase margin) and speed (GBWP).
- Designed for general-purpose analog front-end applications where power and performance are critical.

---

## 📬 Contact

For further queries, feel free to reach out:

- 📧 Email: [anshuman.mondal@iitg.ac.in](mailto:anshuman.mondal@iitg.ac.in)  
- 🔗 LinkedIn: [linkedin.com/in/anshuman2006](https://www.linkedin.com/in/anshuman2006/)

