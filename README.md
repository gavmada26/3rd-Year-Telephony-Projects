# Telephony - Technical Documentation & Code Implementation 📞

## Overview
This repository contains the comprehensive technical documentation and source code developed for the **3rd-year Telephony Systems** course. The project bridges theoretical telecommunication principles with practical software implementations, focusing on network architectures, signaling protocols, and traffic engineering.

The repository is structured around two main technical reports, each detailing specific telecommunication models, mathematical approaches, and the corresponding algorithmic solutions.

## 📂 Repository Structure

* `DOCUMENTATIE_TELEFONIE_1_GAVRILAS_MADALIN.pdf`: Analysis and simulation of analog telephony call progress tones, pulse dialing, and DTMF signaling.
* `DOCUMENTATIE_TELEFONIE_2_GAVRILAS_MADALIN.pdf`: Implementation and evaluation of uniform/non-uniform Pulse Code Modulation (PCM) and adaptive Delta Modulation algorithms.
* `src/`: Contains the source code snippets and scripts extracted from the documentations.

---

## 📄 Project 1: Analog Telephony Tones & DTMF Signaling

### Key Concepts Analyzed:
* **Telephone Tone Generation:** Modeled and analyzed fundamental call progress tones (dial tone, busy tone, ring tone, ringback tone) in the time and frequency domains. 
* **Address Signaling Techniques:** Implemented and compared legacy pulse dialing with modern Dual-Tone Multi-Frequency (DTMF) address signaling.
* **Signal Processing & Filtering:** Applied Fast Fourier Transform (FFT) for spectral analysis. Added controlled Gaussian white noise to simulate channel interference, and implemented digital filters (Lowpass, Highpass, Bandpass, Butterworth, Elliptic) to clean the signals.

### Code Implementation Highlights:
The code associated with this section focuses on generating interactive MATLAB GUIs to simulate call signaling, analyze signal-to-noise ratios (SNR), and visualize the spectral impact of noise and digital filters on DTMF tones. 
* **Language/Tool:** MATLAB
* **Key feature:** Time-frequency analysis and GUI-based telecommunication signal simulation.

---

## 📄 Project 2: Pulse Code Modulation (PCM) & Delta Modulation

### Key Concepts Analyzed:
* **Pulse Code Modulation (PCM):** Detailed the implementation of uniform and non-uniform PCM, evaluating A-law and μ-law companding techniques as defined by the ITU-T G.711 standard.
* **Delta Modulation:** Analyzed fixed Delta Modulation alongside adaptive Delta Modulation algorithms. Specifically implemented the Song and Jayant algorithms for dynamic step-size adaptation based on signal slopes.
* **Quantization Error & SNR Evaluation:** Evaluated quantization noise across different bit depths and signal types (sine, triangle, voice). Plotted comparative Signal-to-Noise Ratio (SNR) curves to assess the encoding efficiency of uniform versus non-uniform PCM.

### Code Implementation Highlights:
This section contains scripts dedicated to quantizing continuous analog signals into discrete digital codes, computing the resulting Root Mean Square (RMS) quantization error, and visualizing the signal companding process interactively.
* **Language/Tool:** MATLAB
* **Key feature:** Digital signal encoding and adaptive quantization algorithms.

---

## 🛠️ Technologies & Tools Used
* **Programming Languages:** MATLAB
* **Protocols & Standards Analyzed:** DTMF, ITU-T G.711 (A-law / μ-law)
* **Concepts:** Digital Signal Processing, Fast Fourier Transform (FFT), Quantization, Companding, Adaptive Delta Modulation, Telephony Tones.

---

## 👨‍💻 Author
**Mădălin Gavrilaș** 

*Technical University of Cluj-Napoca (UTCN)*, *Faculty of Electronics, Telecommunications and Information Technology (ETTI)*
