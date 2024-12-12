---
title: "Automatic Power Factor Improvement System"
excerpt: "Designed and implemented a system to optimize power factor automatically, using Arduino Uno and a capacitor bank.<br/><img src='/images/PowerFactorImprovement.png' width='600'>"
collection: projects
---

This project aims to improve the power factor of inductive loads using an Arduino Uno-based control system and a capacitor bank. The system continuously monitors the power factor and dynamically adjusts capacitance to ensure near-unity power factor, reducing losses in the transmission line.

### Features
- **Dynamic Power Factor Correction:** Real-time adjustment of capacitors to improve the power factor.
- **Hardware Integration:** Involves Arduino Uno, transformers, Op-Amps, and capacitor banks for accurate measurement and correction.
- **Software Simulation:** Circuit simulated in Proteus and code developed using Arduino IDE.
- **Energy Efficiency:** Reduces transmission losses by maintaining a high power factor.

### Implementation Details
- **Arduino Uno:** Measures phase angle and power factor, controls the capacitor bank, and displays output on an LCD.
- **Proteus Simulation:** Designed the circuit including transformers, XOR gates, and zero-detection circuits for precise measurement.
- **Capacitor Bank Control:** Used relays to connect capacitors dynamically based on system requirements.
- **Power Factor Algorithm:** An algorithm in Arduino optimally switches capacitors to maintain the desired power factor.

### Challenges Faced
- Determining transformer inductance values for accurate voltage and current measurements.
- Implementing error-free open-circuit detection.
- Debugging and adding delays to stabilize the correction algorithm.

### Future Prospects
- Adding more capacitors for finer adjustment.
- Transitioning to Arduino Mega for expanded control capabilities.

### Project Report
[Download the full project report (PDF)](/files/PFC_Project_Report.pdf)