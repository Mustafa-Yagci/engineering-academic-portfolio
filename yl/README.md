# Graduate Engineering Laboratory & Research Archive (UniPa, 2025 – 2026) 🎓

**Institution:** [Università degli Studi di Palermo (UniPa)](https://www.unipa.it) — Department of Engineering  
**Degree Program:** M.Sc. in Electronics Engineering (Specialization: Electronic Programmable Systems & Bioelectronics)  
**Student:** Mustafa Yağcı (Matricola: `0830177`)

---

## 📂 Graduate Research Modules by Year

### 📅 2025
- **`Applied_Electronics/`**:
  - **Comprehensive 15-Page Study:** Discrete negative-feedback voltage regulation utilizing BD139 power transistors, Q2 discrete error amplifiers, and BZX79C5V1 Zener references ($S_{Vi}$ line regulation, $S_{IL}$ load regulation, $r_z$ dynamic resistance).
  - Tuned LC tank RF frequency multipliers and nonlinear active mixers (IF decomposition, intermodulation distortion).
  - Phase-Locked Loop (PLL) transfer dynamics: VCO tuning gain ($K_{VCO}$), capture range, lock range, and frequency tracking.
  - **File:** [Mustafa_Yagci_Report.pdf](Applied_Electronics/Mustafa_Yagci_Report.pdf)

### 📅 2026
- **`Industrial_Electronics/`**:
  - **Comprehensive 65-Page Industrial Electronics Investigation:** DC-DC Buck, Boost, and Isolated converter topologies under Continuous (CCM) and Discontinuous (DCM) conduction modes; power semiconductor loss budgets (MOSFET conduction/switching, diode reverse recovery).
  - State-Space Averaging derivation; analog closed-loop PI compensator synthesis in PSIM achieving $>55^\circ$ phase margin and $\sim 500\text{ rad/s}$ bandwidth.
  - Peak-current hysteresis control and full-bridge bipolar PWM inverters with overmodulation ($m_a > 1$) harmonics.
  - **Physical Benchtop Probing (pp. 56–65):** Laboratory oscilloscope differential probe measurements of parasitic inductance switching ringing and voltage spikes across hardware MOSFET switches.
  - **File:** [Mustafa_Yagci_LABORATORY_REPORT.pdf](Industrial_Electronics/Mustafa_Yagci_LABORATORY_REPORT.pdf)
- **`Measurement_and_Automation/`**:
  - **Comprehensive 65-Page Virtual Instrumentation Suite:** Modular multi-channel virtual DAQ architecture developed in LabVIEW; Nyquist-Shannon sampling limits, anti-aliasing filter constraints, and spectral leakage behavior.
  - Automated 16-bit SAR ADC dynamic characterization computing **SNR, SINAD, ENOB, and THD** using Hanning/Flat-top windowed DFT power spectral density estimation; GUM-compliant uncertainty budget.
  - Complete collection of executable LabVIEW Virtual Instruments (`.vi` files) included in `LabVIEW_VIs/`.
  - **File:** [Lab_Report_Mustafa_Yagci.pdf](Measurement_and_Automation/Lab_Report_Mustafa_Yagci.pdf)
- **`Biomedical_IoT/`**:
  - Research roadmaps covering Contactless Radar vital sign monitoring, Cuffless Blood Pressure estimation via Pulse Transit Time (PTT) combining ECG and PPG, and Surface EMG muscle fatigue spectral analysis using sliding-window FFT.
- **`BioAmp_Pro_AFE/`**:
  - Precision Biopotential Analog Front-End (AFE) instrumentation design (KiCad 8, 4-layer PCB, 100% 0 ERC / 0 DRC verified, CMRR $>100\text{ dB}$, active Driven-Right-Leg 50 Hz mains suppression, 4th-order active Sallen-Key filtering).
