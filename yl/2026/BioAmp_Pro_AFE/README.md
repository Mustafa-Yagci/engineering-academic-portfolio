# UniPa BioAmp Pro — Precision Biopotential Analog Front-End (AFE) 🔬

**Institution:** Università degli Studi di Palermo (UniPa)  
**Curriculum Domain:** Electronics & IoT for Biomedical Applications  
**Designer:** Mustafa Yağcı  
**ECAD Suite:** KiCad 8 (100% 0 ERC / 0 DRC Compliance)

---

## 📌 Architectural Overview

The **UniPa BioAmp Pro** is an ultra-low-noise, high-precision biomedical instrumentation analog front-end designed for surface biopotential acquisition (ECG / EMG / EEG). It resolves microvolt-level electrophysiological signals in the presence of severe common-mode mains interference and electrode half-cell DC offsets.

### ⚡ Core Circuit Blocks

1. **Precision Instrumentation Amplifier Input Stage:**
   - Ultra-low-noise instrumentation amplifier topology providing $>100\\text{ dB}$ Common-Mode Rejection Ratio (CMRR).
   - High input impedance ($>10\\text{ G}\\Omega$) buffering to eliminate electrode-skin contact impedance imbalances.
2. **Active Driven-Right-Leg (DRL) Feedback:**
   - Active common-mode sense and inverting feedback circuitry driving the body reference electrode to suppress 50 Hz powerline hum by an additional $>30\\text{ dB}$.
3. **4th-Order Active Filtering Chain:**
   - 4th-order active Sallen-Key bandpass filter ($0.5\\text{ Hz} - 150\\text{ Hz}$) tailored for diagnostic-grade ECG and high-frequency EMG bursts.
   - Twin-T 50 Hz notch filter with active bootstrapping for sharp powerline interference rejection.
4. **Mixed-Signal PCB Layout & Shielding:**
   - Guard rings surrounding high-impedance biopotential traces.
   - Partitioned analog star-grounding plane to eliminate return current ground loops.
   - Strict mixed-signal layout constraints with **100% 0 ERC (Electrical Rules Check) and 0 DRC (Design Rules Check) errors**.
