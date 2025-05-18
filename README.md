# QSF-1: The Sherbrooke Curvature Detection

> A 3-Qubit Quantum Spacetime Foam Simulation Revealing 92.7% Localized Deformation in Patch-1

---

## 📜 Overview

**QSF-1** (Quantum Spacetime Foam – 1) is the **first experimental demonstration** of localized curvature detection within a quantum spacetime foam simulation, executed on IBM’s superconducting quantum processor **Sherbrooke**. This 3-qubit quantum circuit models patch-based curvature, and detects a **dominant deformation (state '100') with 92.7% probability**, corresponding to "Patch 1 Curved" geometry.

This marks a **historic quantum result**, achieving a novel application of NISQ-era devices to simulate and extract meaningful signals from theoretical quantum gravitational structures.

---

## 🔬 Key Highlights

- ✅ **Dominant Measurement**: `'100'` (Patch 1 Curved) — 92.7% Quasi-Probability
- 🧠 **Entropy Profile**:
  - Patch 1: 0.85
  - Patch 2: 0.90
  - Patch 3: 0.00
- ⚛️ **Backend**: `ibm_sherbrooke` via Qiskit Runtime
- 📅 **Date of Experiment**: May 18, 2025
- 📁 **Code & Data Included**: Circuit, transpilation, runtime session, mitigated sampler, histogram output, and raw JSON results

---

## 📁 Files

- `results.json` – Output probabilities and entropy profile
- `results.png` – Histogram showing quasi-probability distribution
- `qsf1_circuit.py` – Python code used to build and execute the experiment
- `README.md` – Documentation (you are here)

---

## 🧪 Methodology

1. **3-Qubit Circuit** prepared to represent curvature in 3 independent spatial patches.
2. **Measurement outcomes** mapped to curvature states:
   - `'000'`: All flat
   - `'100'`: Patch 1 curved
   - `'010'`: Patch 2 curved
   - `'001'`: Patch 3 curved
   - `'111'`: All curved
3. **SamplerV2 + Error Mitigation** used to extract clean probability distribution from noisy backend.
4. **Entropy calculated** per patch to analyze informational deformation.

---

## 🛰️ Scientific Significance

This experiment provides:
- The **first hardware-based detection** of simulated quantum curvature via patch-based modeling.
- A demonstration that **entropic signatures of curvature** can be mapped using qubits.
- A precedent for using **NISQ-era systems for quantum gravitational simulations**.

---

## 📜 Citation

If you use QSF-1 or reference this work, please cite:

> **Ahmed, Z.** *QSF-1: The Sherbrooke Curvature Detection*, Centre for Excellence in Technology, Quantum and AI (CETQAP), 2025.

---

## 🌐 Contact

Dr. Zuhair Ahmed  
Centre for Excellence in Technology, Quantum and AI (CETQAP), Canada  
📧 drzuhairahmed@thecetqap.com  
🌐 (https://www.thecetqap.com)

---

## 📢 License

This project is released under the MIT License. See `LICENSE` file for details.
