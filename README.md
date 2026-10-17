# Academic Engineering Portfolio & Laboratory Archive 🎓⚡
### Undergraduate (B.Sc. @ ESOGÜ — Graduated Apr 2025) & Master's Research (M.Sc. Student @ UniPa — Ongoing)
**Author:** **Mustafa Yağcı**  
**Institutions:** [Università degli Studi di Palermo (UniPa)](https://www.unipa.it) *(M.Sc. Student, Nov 2025 – Present / Ongoing)* | [Eskişehir Osmangazi University (ESOGÜ)](https://www.ogu.edu.tr) *(B.Sc. Graduate, Apr 2025)*  
**Profile:** [linkedin.com/in/-mustafa-yagci](https://www.linkedin.com/in/-mustafa-yagci) | [github.com/Mustafa-Yagci](https://github.com/Mustafa-Yagci)

---

[![ESOGÜ B.Sc. Graduate](https://img.shields.io/badge/B.Sc._Graduate-ESOGÜ_%7C_Apr_2025-003366?style=for-the-badge&logo=academia)](#)
[![UniPa M.Sc. Student](https://img.shields.io/badge/M.Sc._Student-UniPa_%7C_Nov_2025--Present_(Ongoing)-8B0000?style=for-the-badge&logo=google-scholar)](#)
[![TEKNOFEST 2023 3rd Place](https://img.shields.io/badge/TEKNOFEST_2023-3rd_Place_Acceleration_Challenge-FFD700?style=for-the-badge&logo=target&logoColor=black)](#)
[![TEKNOFEST 2023 9th Place](https://img.shields.io/badge/TEKNOFEST_2023-9th_Place_Efficiency_Challenge-4169E1?style=for-the-badge&logo=speedtest)](#)
[![Vivado & RTL](https://img.shields.io/badge/FPGA-Xilinx%20Vivado%20%7C%20Verilog%20%7C%20VHDL-E05A47?style=for-the-badge&logo=amd)](#)
[![KiCad 8](https://img.shields.io/badge/PCB-KiCad%208%20(0%20ERC%20%2F%200%20DRC)-314CB6?style=for-the-badge&logo=kicad)](#)
[![PSIM & Power](https://img.shields.io/badge/Power-PSIM%20%7C%20State--Space-2E8B57?style=for-the-badge)](#)
[![LabVIEW](https://img.shields.io/badge/DAQ-LabVIEW%20Virtual%20Instrumentation-FFCC00?style=for-the-badge&logo=nationalinstruments&logoColor=black)](#)
[![TIA Portal PLC](https://img.shields.io/badge/Automation-Siemens%20TIA%20Portal%20V17-006464?style=for-the-badge&logo=siemens)](#)

---

## 🏆 Honors & Engineering Awards (TEKNOFEST & TÜBİTAK)

| Competition / Event | Category & Award | Team & Role | Technical & Engineering Contribution |
| :--- | :--- | :--- | :--- |
| **TEKNOFEST 2023** | 🥉 **3rd Place — Acceleration Challenge** *(İvmeleme Yarışı 3.lüğü)* | **Mavera Technology Team**<br>*(Motor Driver Lead Designer)* | Designed the custom 100% domestic 3-phase BLDC motor driver, low-loss MOSFET inverter bridge, and high-torque start algorithm, propelling the electric vehicle to **3rd place nationwide** in launch acceleration. |
| **TÜBİTAK / TEKNOFEST 2023** | 🏅 **9th Place — International Efficiency Challenge Electric Vehicle** *(Verimlilik Yarışması 9.luğu)* | **Mavera Technology Team**<br>*(Motor Drive Mentor & Systems Engineer)* | Optimized the regenerative braking algorithms, telemetry bus processing, and independent unipolar PWM commutation, achieving **top-10 national energy efficiency** among competing university teams. |

---

## 📌 Executive Overview

This repository provides an open-source, reproducible catalog of my physical laboratory investigations, hardware bringing-up reports, ECAD simulations, and automated test instrumentation frameworks developed across my academic curriculum:

1. **Undergraduate Level (ESOGÜ, 2021 – 2024 / Graduated April 2025):** 20+ laboratory experiments spanning foundational DC/AC circuit theory, transistor-level analog amplification, Verilog HDL / Mealy FSM digital modeling, MATLAB/Simulink closed-loop PID control, industrial Siemens PLC ladder automation, semiconductor microfabrication, discrete power electronic converters, and the culminating **B.Sc. Capstone Graduation Thesis** (Design and Implementation of an 84V / 40A Sensored 3-Phase BLDC Motor Driver).
2. **Master's Level Studies (UniPa, Nov 2025 – Present / Ongoing M.Sc. Student):** Advanced engineering research across switched-mode DC-DC converter stability (65-page PSIM & benchtop differential probing study), discrete closed-loop voltage regulators / RF mixers / PLLs (15-page Applied Electronics report), and automated LabVIEW virtual DAQ & 16-bit SAR ADC dynamic testing suites (65-page measurement framework + 49 custom `.vi` codebase).

---

## 🗂️ Repository Architecture

```text
academic-engineering-portfolio/
│
├── lisans/                               <- Undergraduate Practicum (ESOGÜ, B.Sc. in Electrical & Electronics Eng.)
│   ├── Bitirme_Tezi/                     <- 🎓 B.Sc. Capstone Degree Thesis: 84V/40A 3-Phase BLDC Motor Driver (Report & Slides)
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
│       └── Guc_Elektronigi/              <- Single-phase thyristor rectifier & RL inductive load benchtop analysis
│
└── yl/                                   <- Ongoing Master's Research (UniPa, M.Sc. Student in Electronics Engineering, Nov 2025 – Present)
    ├── 2025/
    │   └── Applied_Electronics/          <- Discrete negative-feedback regulators, RF mixers, and PLL lock dynamics
    └── 2026/
        ├── Industrial_Electronics/       <- 65-Page SMPS study: Buck/Boost CCM/DCM, state-space PI, benchtop oscilloscope probing
        └── Measurement_and_Automation/   <- 65-Page Virtual DAQ suite, 16-bit SAR ADC SNR/SINAD/ENOB/THD testing & 49 LabVIEW VIs
```

---

## 🔬 Master Chronological Laboratory Directory

### 🎓 Ongoing Master's Studies (Università degli Studi di Palermo — M.Sc. Student, Nov 2025 – Present)

| Year | Course / Domain | Research / Experiment Topic | Tools & Instrumentation | Key Deliverable |
| :--- | :--- | :--- | :--- | :--- |
| **2026** | **Industrial Electronics** | Switched-Mode DC-DC Buck/Boost CCM/DCM Characterization, State-Space Averaging, PI Bode Stability & Physical Benchtop Switching Ringing Probing | PSIM, Differential Probes, DSO | [Mustafa_Yagci_LABORATORY_REPORT.pdf](yl/2026/Industrial_Electronics/Mustafa_Yagci_LABORATORY_REPORT.pdf) *(65 Pages)* |
| **2026** | **Electronic Measurement** | Virtual DAQ Architecture, Nyquist-Shannon Sampling, 16-bit SAR ADC Dynamic Characterization (SNR, SINAD, ENOB, THD) & GUM Uncertainty | LabVIEW, 16-bit DAQ, FFT/DFT | [Lab_Report_Mustafa_Yagci.pdf](yl/2026/Measurement_and_Automation/Lab_Report_Mustafa_Yagci.pdf) *(65 Pages + 49 VIs)* |
| **2025** | **Applied Electronics** | BD139 Closed-Loop Negative Feedback Voltage Regulators, Tuned LC RF Frequency Mixers, and Phase-Locked Loop (PLL) Dynamics | LTspice, Spectrum Analyzer | [Mustafa_Yagci_Report.pdf](yl/2025/Applied_Electronics/Mustafa_Yagci_Report.pdf) *(15 Pages)* |

---

### 🏛️ Undergraduate Studies (Eskişehir Osmangazi University — B.Sc. Degree, Graduated Apr 2025)

| Year | Discipline | Laboratory / Experiment Topic | Methodology & Hardware | Deliverable Link |
| :--- | :--- | :--- | :--- | :--- |
| **2024** | **Capstone Degree Thesis** | **Design & Implementation of a High-Power 3-Phase BLDC Motor Driver (84V / 40A, STM32, 120° Hall Commutation, Unipolar PWM & RC Snubber)** | STM32F103, IRFB4110 MOSFETs, IR2127/IR2101, PSIM, Oscilloscope | [Thesis Report](lisans/Bitirme_Tezi/BLDC_Motor_Driver_Graduation_Thesis_Report.pdf) *(56 Pages)* & [Presentation](lisans/Bitirme_Tezi/BLDC_Motor_Driver_Graduation_Project_Presentation.pdf) *(25 Slides)* \| [README](lisans/Bitirme_Tezi/README.md) |
| **2024** | **Power Electronics** | Controlled Single-Phase Half-Wave Thyristor Rectifier with Inductive RL Load & Freewheeling Diode | Benchtop Oscilloscope, SCR, R-L load | [Exp 4 Report](lisans/2024/Guc_Elektronigi/2024-12-08_Guc-Elektronigi_Exp4_Tristorlu-Dogrultucu-ve-RL-Enduktif-Yuk-Osiloskop.pdf) |
| **2024** | **Semiconductor Fab** | Deal-Grove 700 nm Thermal $SiO_2$ Oxidation Modeling & 250 nm RIE Trench Deep Reactive Ion Etching | Microfabrication Physics, RIE | [Fab Report](lisans/2024/Yari_Iletken_Uretim/2024-11-27_Yari-Iletken-Uretim_Odev2_700nm-SiO2-Buyutme-ve-250nm-Derin-Etching.pdf) |
| **2024** | **PLC Automation** | Analog Voltage/Current Input Calibration (`NORM_X` / `SCALE_X`) & Multi-Station Motor Interlocking | Siemens S7-1200, TIA Portal V17 | [Lab 7–8 Reports](lisans/2024/PLC_Endustriyel_Otomasyon/) |
| **2024** | **Communications** | GNU Octave / MATLAB Channel Simulation, Bandpass Filtering, and Spectral Sinc Reconstruction | GNU Octave, Fast Fourier Transform | [Exp 8 Report](lisans/2024/Haberlesme_Sistemleri/2024-05-16_Haberlesme-Sistemleri_Exp8_Octave-Sinyal-Adaptasyon-ve-Filtreleme.pdf) |
| **2023** | **Control Systems** | Complete 7-Stage Practicum: Transfer Functions, State-Space ($A, B, C, D$), Closed-Loop PID Tuning, Bode Stability Margin, Root Locus, and 2nd-Order Transient Response | MATLAB / Simulink Control Toolbox | [Exp 1–7 Reports](lisans/2023/Kontrol_Sistemleri/) |
| **2023** | **PLC Automation** | Digital Inputs/Outputs, Memory Merker Bits, Set/Reset Latches, TON/TOF Timers, CTU/CTD Counters, and SFC Conveyor Automation | Siemens TIA Portal V17, Ladder Logic | [Lab 1–6 Reports](lisans/2023/PLC_Endustriyel_Otomasyon/) |
| **2022** | **Digital Systems** | Complete 9-Stage Practicum: TTL Logic Gates, Decoders, Multiplexers, Adders/Subtractors, Synchronous Counters, Xilinx ISE Spartan FPGA Synthesis, and Verilog HDL Mealy FSM Modeling | Xilinx ISE, Spartan FPGA, Verilog HDL | [Exp 1–9 Reports](lisans/2022/Sayisal_Sistemler_ve_Verilog/) |
| **2022** | **Analog Electronics** | Semiconductor Diode $I-V$ Characterization, BJT DC Biasing & $Q$-Point Thermal Stability, Common-Emitter Amplifier, and N-Channel JFET $A_v  pprox 20$ Gain Amplifier | Curve Tracer, Benchtop DMM, DSO | [Exp 1–5 Reports](lisans/2022/Analog_Elektronik/) |
| **2022** | **Circuit Analysis** | 1st-Order RC Circuit Transient Response, Step Input Excitation, Natural/Forced Dynamics, and $\tau = RC$ Time-Constant Extraction | Benchtop DSO, Signal Generator | [Exp 5 Report](lisans/2022/Devre_Analizi/2022-01-03_Devre-Analizi_Exp5_RC-Devresi-Basamak-Yaniti-ve-Zaman-Sabiti.pdf) |
| **2021** | **Circuit Analysis** | Fundamental Resistive Networks, Ohm's Law Verification, and Experimental KCL / KVL Nodal Voltage Analysis | Precision Multimeter, DC Power Supply | [Exp 1–2 Practicum](lisans/2021/Devre_Analizi/README.md) |

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

All laboratory reports, circuit schematics, simulation models, and virtual instrument codes contained in this repository were authored by **Mustafa Yağcı** as part of undergraduate studies at ESOGÜ (B.Sc. Graduate) and ongoing master's research at UniPa (M.Sc. Student, Nov 2025 – Present). Distributed under the [MIT License](LICENSE) for educational and research reference.
