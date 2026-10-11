# Biomedical IoT & Wearable Biosensing Research 🩺📡
**Institution:** Università degli Studi di Palermo (UniPa)  
**Department:** Dipartimento di Ingegneria  
**Curriculum:** M.Sc. in Electronics Engineering  
**Academic Year:** 2026  
**Author:** Mustafa Yağcı  

---

## 📌 Research Domains & Methodological Frameworks

### 1. Contactless Radar Vital Signs Monitoring
* **Architecture:** Non-invasive, contactless continuous cardio-respiratory sensing using CW/FMCW micro-Doppler radar.
* **Signal Processing:** Phase demodulation, DC-offset compensation, chest displacement separation into respiratory excursion (0.1–0.5 Hz) and ballistocardiographic heartbeats (0.8–2.5 Hz).

### 2. Cuffless Blood Pressure (BP) Estimation via Pulse Transit Time (PTT)
* **Architecture:** Dual-channel synchronized acquisition combining Electrocardiogram (ECG) and Photoplethysmogram (PPG).
* **Moens-Korteweg Formulation:** Mathematical extraction of Pulse Transit Time ($PTT$) and Pulse Wave Velocity ($PWV$) mapped to systolic/diastolic blood pressure via calibrated vascular elasticity curves.

### 3. Surface EMG (sEMG) Muscle Fatigue Spectral Analysis
* **Architecture:** Multi-channel surface biopotential acquisition targeting active muscular groups.
* **Spectral Dynamics:** Sliding-window Fast Fourier Transform (FFT) computing instantaneous Mean Frequency (MNF) and Median Frequency (MDF) spectral downward shift as quantitative metrics for muscle fatigue onset.

---
*Note: Hardware front-end biopotential conditioning, high CMRR instrumentation amplification, and Driven-Right-Leg circuitry are detailed in the companion hardware module: [BioAmp Pro AFE](../BioAmp_Pro_AFE/README.md).*
