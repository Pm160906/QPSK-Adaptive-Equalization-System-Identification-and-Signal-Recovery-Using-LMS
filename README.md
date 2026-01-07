# QPSK Adaptive Equalization: System Identification and Signal Recovery Using LMS

This project investigates the impact of channel impairments and inter-symbol interference (ISI) on QPSK-modulated signals and demonstrates adaptive equalization using the Least Mean Squares (LMS) algorithm for signal recovery.

The system is modeled and simulated using GNU Radio and MATLAB, focusing on system identification and adaptive filtering in distorted communication channels.

---

## 📌 Project Overview

In practical communication systems, transmitted signals are often distorted due to multipath propagation, noise, and channel imperfections. These distortions lead to ISI, which degrades signal quality and increases bit error rate.

This project:
- Models a multipath channel with severe ISI  
- Implements QPSK modulation and demodulation  
- Applies LMS-based adaptive equalization for system identification  
- Recovers the original signal by minimizing error iteratively  

---

## ⚙️ Technologies Used

- **GNU Radio**
- **MATLAB**
- **Digital Signal Processing (DSP)**
- **Adaptive Filters (LMS Algorithm)**
- **Software Defined Radio (SDR) Concepts**

---

## 🧠 Key Concepts

- QPSK Modulation & Demodulation  
- Inter-Symbol Interference (ISI)  
- Multipath Channel Modeling  
- Adaptive Filtering  
- System Identification  
- Constellation Diagram & Eye Diagram Analysis  

---

## 🔬 Implementation Details

- QPSK symbols are generated and passed through a simulated multipath channel.
- Channel taps are designed to introduce controlled ISI.
- An LMS adaptive filter is used to estimate the channel response.
- The equalizer updates its weights iteratively to minimize the error between the received and desired signals.
- Performance is analyzed using:
  - Constellation diagrams
  - Eye diagrams
  - Error convergence plots

---

## 📊 Results

- Severe ISI causes constellation spreading and eye closure.
- After LMS equalization, constellation points become more compact and eye opening improves.
- The adaptive equalizer successfully converges and recovers the transmitted signal.

---

## 📁 Repository Structure
 
├── software defined communication systems  x  modeling, simulation & analysis.pdf                # ppt
├── sdcsxmsa.grc                                                                                  # GNU Radio flowgraph
├── QPSK Adaptive Equalization – System Identification and Signal Recovery Using LMS.pdf          # Project report
└── README.md
