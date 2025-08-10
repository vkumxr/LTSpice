# LTSpice Simulations

This repository contains a collection of **LTSpice circuit simulations** for various communication and signal-processing concepts.  
Each project includes LTSpice schematic files (`.asc`), simulation setups, and analysis results.

---

## 📂 Simulations

### 1. RC Pre-emphasis & De-emphasis
- **Pre-emphasis:** Boosts high-frequency components to improve signal-to-noise ratio during transmission.  
- **De-emphasis:** Restores the original frequency balance after reception.  
- Includes transient and AC analysis plots.

### 2. RL Pre-emphasis & De-emphasis
- **Pre-emphasis:** Uses the inductor’s frequency-dependent reactance to amplify higher frequencies.  
- **De-emphasis:** Attenuates boosted high frequencies to recover the original signal.  
- Adjustable resistor and inductor values to explore different time constants.

### 3. AM Modulation & Demodulation
- **Modulation:** Varies the amplitude of a carrier signal based on the message signal.  
- **Demodulation:** Uses an envelope detector to retrieve the original message from the carrier.  
- Includes time-domain and frequency-domain analysis.

### 4. Universal Filter using OP AMP (AD744)
- Implements a **universal active filter** using the **AD744 op-amp** in LTSpice.  
- Capable of **low-pass**, **high-pass**, and **band-pass** responses by selecting appropriate output nodes.  
- Includes transient and AC analysis to verify frequency response.  
- Adjustable resistor and capacitor values for tuning cut-off frequencies and quality factor.

---

## 🛠 Requirements
- [LTSpice](https://www.analog.com/en/resources/design-tools-and-calculators/ltspice-simulator.html) (any recent version)

---

## 🚀 Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/vkumxr/LTSpice.git
