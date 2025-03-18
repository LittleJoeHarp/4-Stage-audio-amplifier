# 4-Stage-audio-amplifier

## Overview
This project involves the design and implementation of an **audio amplifier** with the following key specifications:
- **Supply Voltage:** 0 to 5V
- **Input Small Signal Voltage:** 10–40mV peak-to-peak
- **Gain:** 500 (Pre-amp and Gain stage)
- **Frequency Range:** Audible Range (20Hz to 20kHz)
- **Power Output:** 1.5W
- **Filter:** Should not attenuate the input signal
- **Power Amplifier:** Should not provide voltage gain
- **Load Resistance:** 10Ω

## Project Stages
### 1. Pre-Amplifier
- Provides initial amplification to the input signal.
- Uses a **common-emitter differential amplifier** for high input/output impedance and good noise performance.
- Prevents noise from overpowering the weak input signal.

### 2. Gain Stage
- Implemented using a **Common-Emitter (CE) amplifier** for high current and voltage gain.
- Ensures proper signal amplification before reaching the filtering and power stages.

### 3. Filter Stage
- A **low-pass filter** is used to remove unwanted high-frequency components.
- An **active band-pass filter** is recommended for better performance.

### 4. Power Amplifier
- Implemented using a **Class AB amplifier** for improved efficiency and reduced crossover distortion.
- Balances the benefits of **Class A (low distortion) and Class B (high efficiency)**.
- Ensures **linearity** and minimal power loss.


## Conclusion
This audio amplifier project successfully integrates **pre-amplification, signal gain, filtering, and power amplification** stages while minimizing distortion and optimizing efficiency. The **Class AB power amplifier** ensures superior performance by balancing **low distortion and power efficiency**.

---

