# Academic Engineering Portfolio & Laboratory Archive 🎓⚡
### Complete Undergraduate (B.Sc.) and Graduate (M.Sc.) Engineering Practicum & Research
**Author:** **Mustafa Yağcı**  
**Institutions:** [Università degli Studi di Palermo (UniPa)](https://www.unipa.it) | [Eskişehir Osmangazi University (ESOGÜ)](https://www.ogu.edu.tr)  
**Profile:** [linkedin.com/in/-mustafa-yagci](https://www.linkedin.com/in/-mustafa-yagci) | [github.com/yotova](https://github.com/yotova)

---

[![ESOGÜ ABET Accredited](https://img.shields.io/badge/B.Sc.-ESOG%C3%9C%20(ABET%20Accredited)-003366?style=for-the-badge&logo=academia)](#)
[![UniPa M.Sc. Candidate](https://img.shields.io/badge/M.Sc.-Universit%C3%A0%20di%20Palermo-8B0000?style=for-the-badge&logo=google-scholar)](#)
[![Vivado & RTL](https://img.shields.io/badge/FPGA-Xilinx%20Vivado%20%7C%20Verilog%20%7C%20VHDL-E05A47?style=for-the-badge&logo=amd)](#)
[![KiCad 8](https://img.shields.io/badge/PCB-KiCad%208%20(0%20ERC%20%2F%200%20DRC)-314CB6?style=for-the-badge&logo=kicad)](#)
[![PSIM & Power](https://img.shields.io/badge/Power-PSIM%20%7C%20State--Space-2E8B57?style=for-the-badge)](#)
[![LabVIEW](https://img.shields.io/badge/DAQ-LabVIEW%20Virtual%20Instrumentation-FFCC00?style=for-the-badge&logo=nationalinstruments&logoColor=black)](#)
[![TIA Portal PLC](https://img.shields.io/badge/Automation-Siemens%20TIA%20Portal%20V17-006464?style=for-the-badge&logo=siemens)](#)

---

## 📌 Executive Overview

This repository provides an open-source, reproducible catalog of my physical laboratory investigations, hardware bringing-up reports, ECAD simulations, and automated test instrumentation frameworks developed across my academic curriculum:

1. **Undergraduate Level (ESOGÜ, 2021 – 2024):** 20+ laboratory experiments spanning foundational DC/AC circuit theory, transistor-level analog amplification, Verilog HDL / Mealy FSM digital modeling, MATLAB/Simulink closed-loop PID control, industrial Siemens PLC ladder automation, semiconductor microfabrication, and pulse Doppler radar systems.
2. **Graduate Level (UniPa, 2025 – 2026):** Advanced engineering research across switched-mode DC-DC converter stability (65-page PSIM & benchtop differential probing study), discrete closed-loop voltage regulators / RF mixers / PLLs (15-page Applied Electronics report), automated LabVIEW virtual DAQ & 16-bit SAR ADC dynamic testing suites (65-page measurement framework + complete `.vi` codebase), and precision biomedical analog front-end (AFE) architectures.

---

## 🗂️ Repository Architecture

```text
academic-engineering-portfolio/
│
├── lisans/                               <- Undergraduate Practicum (ESOGÜ, B.Sc. in Electrical & Electronics Eng.)
│   ├── 2021/
│   │   └── Devre_Analizi/                <- Resistor networks, Ohm's law, Kirchhoff's KCL/KVL nodal analysis
│   ├── 2022/
│   │   ├── Devre_Analizi/                <- RC step response & time-constant transient dynamics
│   │   ├── Sayisal_Sistemler_ve_Verilog/ <- TTL gate characteristics, Decoders/MUX, Adders, FSM, Xilinx ISE & Verilog
│   │   └── Analog_Elektronik/            <- Diode I-V, BJT biasing & Q-point, Common-Emitter amp, JFET saturation amp
│   ├── 2023/
│   │   ├── Kontrol_Sistemleri/           <- MATLAB control tools, State-Space, PID tuning, Bode stability, Root Locus
│   │   └── PLC_Endustriyel_Otomasyon/    <- Siemens TIA Portal, Interlocking, TON/TOF timers, CTU/CTD counters, SFC
│   └── 2024/
│       ├── PLC_Endustriyel_Otomasyon/    <- Analog sensor scaling (NORM_X / SCALE_X), multi-motor factory sequence
│       ├── Haberlesme_Sistemleri/        <- GNU Octave digital channel modeling & Fourier spectral filtering
│       ├── Yari_Iletken_Uretim/          <- 700nm SiO2 thermal oxidation & 250nm RIE trench etching modeling
│       ├── Radar_Sistemleri/             <- Pulse Doppler radar equation, PRF, and target Doppler velocity detection
│       └── Guc_Elektronigi/              <- Single-phase thyristor rectifier & RL inductive load benchtop analysis
│
└── yl/                                   <- Graduate Research (UniPa, M.Sc. in Electronics Engineering)
    ├── 2025/
    │   └── Applied_Electronics/          <- Discrete negative-feedback regulators, RF mixers, and PLL lock dynamics
    └── 2026/
        ├── Industrial_Electronics/       <- 65-Page SMPS study: Buck/Boost CCM/DCM, state-space PI, benchtop oscilloscope probing
        ├── Measurement_and_Automation/   <- 65-Page Virtual DAQ suite, 16-bit SAR ADC SNR/SINAD/ENOB/THD testing & LabVIEW VIs
        ├── Biomedical_IoT/               <- Contactless radar vital signs, cuffless BP (ECG+PPG), and smart EMG fatigue roadmaps
        └── BioAmp_Pro_AFE/               <- Precision Biopotential AFE architecture (CMRR >100 dB, DRL active suppression)
```

---

## 🔬 Master Chronological Laboratory Directory

### 🎓 Graduate Studies (Università degli Studi di Palermo)

| Year | Course / Domain | Research / Experiment Topic | Tools & Instrumentation | Key Deliverable |
| :--- | :--- | :--- | :--- | :--- |
| **2026** | **Industrial Electronics** | Switched-Mode DC-DC Buck/Boost CCM/DCM Characterization, State-Space Averaging, PI Bode Stability & Physical Benchtop Switching Ringing Probing | PSIM, Differential Probes, DSO | [Mustafa_Yagci_LABORATORY_REPORT.pdf](yl/2026/Industrial_Electronics/Mustafa_Yagci_LABORATORY_REPORT.pdf) *(65 Pages)* |
| **2026** | **Electronic Measurement** | Virtual DAQ Architecture, Nyquist-Shannon Sampling, 16-bit SAR ADC Dynamic Characterization (SNR, SINAD, ENOB, THD) & GUM Uncertainty | LabVIEW, 16-bit DAQ, FFT/DFT | [Lab_Report_Mustafa_Yagci.pdf](yl/2026/Measurement_and_Automation/Lab_Report_Mustafa_Yagci.pdf) *(65 Pages + VIs)* |
| **2026** | **Biomedical Engineering** | Precision Biopotential Analog Front-End (AFE), Active Driven-Right-Leg (DRL), Notch & Sallen-Key Bandpass Filtering | KiCad 8, LTspice | [BioAmp Pro Documentation](yl/2026/BioAmp_Pro_AFE/README.md) |
| **2026** | **Biomedical IoT** | Contactless Radar Respiration Detection, Cuffless PTT Blood Pressure, and Surface EMG Muscle Fatigue FFT Analysis | Radar, Photoplethysmography | [Biomedical IoT Roadmaps](yl/2026/Biomedical_IoT/) |
| **2025** | **Applied Electronics** | BD139 Closed-Loop Negative Feedback Voltage Regulators, Tuned LC RF Frequency Mixers, and Phase-Locked Loop (PLL) Dynamics | LTspice, Spectrum Analyzer | [Mustafa_Yagci_Report.pdf](yl/2025/Applied_Electronics/Mustafa_Yagci_Report.pdf) *(15 Pages)* |

---

### 🏛️ Undergraduate Studies (Eskişehir Osmangazi University)

| Year | Discipline | Laboratory / Experiment Topic | Methodology & Hardware | Deliverable Link |
| :--- | :--- | :--- | :--- | :--- |
| **2024** | **Power Electronics** | Controlled Single-Phase Half-Wave Thyristor Rectifier with Inductive RL Load & Freewheeling Diode | Benchtop Oscilloscope, SCR, R-L load | [Exp 4 Report](lisans/2024/Guc_Elektronigi/2024-12-08_Guc-Elektronigi_Exp4_Tristorlu-Dogrultucu-ve-RL-Enduktif-Yuk-Osiloskop.pdf) |
| **2024** | **Semiconductor Fab** | Deal-Grove 700 nm Thermal $SiO_2$ Oxidation Modeling & 250 nm RIE Trench Deep Reactive Ion Etching | Microfabrication Physics, RIE | [Fab Report](lisans/2024/Yari_Iletken_Uretim/2024-11-27_Yari-Iletken-Uretim_Odev2_700nm-SiO2-Buyutme-ve-250nm-Derin-Etching.pdf) |
| **2024** | **Radar Systems** | Pulse Doppler Radar Architecture, Ambiguity Function, PRF Selection, and Coherent Target Velocity Detection | Radar Math, Doppler Processing | [Radar Architecture](lisans/2024/Radar_Sistemleri/2024-12-22_Radar-Sistemleri_Darbe-Doppler-ve-Hedef-Tespit-Mimarisi.docx) |
| **2024** | **PLC Automation** | Analog Voltage/Current Input Calibration (`NORM_X` / `SCALE_X`) & Multi-Station Motor Interlocking | Siemens S7-1200, TIA Portal V17 | [Lab 7–8 Reports](lisans/2024/PLC_Endustriyel_Otomasyon/) |
| **2024** | **Communications** | GNU Octave / MATLAB Channel Simulation, Bandpass Filtering, and Spectral Sinc Reconstruction | GNU Octave, Fast Fourier Transform | [Exp 8 Report](lisans/2024/Haberlesme_Sistemleri/2024-05-16_Haberlesme-Sistemleri_Exp8_Octave-Sinyal-Adaptasyon-ve-Filtreleme.pdf) |
| **2023** | **Control Systems** | Complete 7-Stage Practicum: Transfer Functions, State-Space ($A, B, C, D$), Closed-Loop PID Tuning, Bode Stability Margin, Root Locus, and 2nd-Order Transient Response | MATLAB / Simulink Control Toolbox | [Exp 1–7 Reports](lisans/2023/Kontrol_Sistemleri/) |
| **2023** | **PLC Automation** | Digital Inputs/Outputs, Memory Merker Bits, Set/Reset Latches, TON/TOF Timers, CTU/CTD Counters, and SFC Conveyor Automation | Siemens TIA Portal V17, Ladder Logic | [Lab 1–6 Reports](lisans/2023/PLC_Endustriyel_Otomasyon/) |
| **2022** | **Digital Systems** | Complete 9-Stage Practicum: TTL Logic Gates, Decoders, Multiplexers, Adders/Subtractors, Synchronous Counters, Xilinx ISE Spartan FPGA Synthesis, and Verilog HDL Mealy FSM Modeling | Xilinx ISE, Spartan FPGA, Verilog HDL | [Exp 1–9 Reports](lisans/2022/Sayisal_Sistemler_ve_Verilog/) |
| **2022** | **Analog Electronics** | Semiconductor Diode $I-V$ Characterization, BJT DC Biasing & $Q$-Point Thermal Stability, Common-Emitter Amplifier, and N-Channel JFET $A_v pprox 20$ Gain Amplifier | Curve Tracer, Benchtop DMM, DSO | [Exp 1–5 Reports](lisans/2022/Analog_Elektronik/) |
| **2022** | **Circuit Analysis** | 1st-Order RC Circuit Transient Response, Step Input Excitation, Natural/Forced Dynamics, and $	au = RC$ Time-Constant Extraction | Benchtop DSO, Signal Generator | [Exp 5 Report](lisans/2022/Devre_Analizi/2022-01-03_Devre-Analizi_Exp5_RC-Devresi-Basamak-Yaniti-ve-Zaman-Sabiti.pdf) |
| **2021** | **Circuit Analysis** | Fundamental Resistive Networks, Ohm's Law Verification, and Experimental KCL / KVL Nodal Voltage Analysis | Precision Multimeter, DC Power Supply | [Exp 1–2 Reports](lisans/2021/Devre_Analizi/) |

---

## 🛠️ Engineering Toolchain & Laboratory Hardware

| Domain | Software & Simulation Tools | Physical Laboratory Instruments |
| :--- | :--- | :--- |
| **EDA & Circuit Simulation** | KiCad 8, PSIM, LTspice, Cadence Virtuoso, MATLAB / Simulink | High-Bandwidth Digital Storage Oscilloscopes (DSO), Differential Voltage Probes |
| **Digital Design & FPGA** | Xilinx Vivado, Xilinx ISE, ModelSim, Verilog HDL, VHDL, SystemVerilog | FPGA Development Boards (Spartan, Artix), Multi-Channel Logic Analyzers |
| **Industrial Automation** | Siemens TIA Portal V17 (Ladder Diagram, SFC, FBD) | Siemens S7-1200 PLC, 24V Industrial Relays, Optical Sensors, Pneumatic Actuators |
| **Test & Measurement** | National Instruments LabVIEW Virtual DAQ Environment | LCR Meters, Benchtop 6.5-Digit DMMs, RF Spectrum Analyzers, Signal Generators |

---

## 📜 Academic Integrity & License

All laboratory reports, circuit schematics, simulation models, and virtual instrument codes contained in this repository were authored by **Mustafa Yağcı** as part of academic coursework and research at ESOGÜ and UniPa. Distributed under the [MIT License](LICENSE) for educational and research reference.
