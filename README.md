# Quantum Cipher: BB84 Quantum Key Distribution Simulation

A **Python-based simulation** of the **BB84 Quantum Key Distribution (QKD)** protocol — one of the earliest and most secure quantum cryptography methods.  
This project demonstrates qubit encoding, measurement, basis comparison, and shared key generation using **Qiskit**, along with **Bloch sphere visualizations** of quantum states.

---

## Features
- Step-by-step **BB84 protocol simulation**
- Random qubit generation for **Alice** and **Bob**
- Basis matching and bit comparison
- Bloch sphere visualization of qubit states
- Final shared secret key generation

---

## BB84 Overview
1. **Alice** sends qubits to **Bob** encoded randomly in two bases: Rectilinear (`+`) and Diagonal (`×`).
2. **Bob** measures each qubit using a random basis.
3. They **publicly compare bases** (not the bit values).
4. Bits where the bases matched form the **shared secret key**.

---

## Quick Start

**1. Clone the repository**
```bash
git clone https://github.com/your-username/quantum-cipher.git
cd quantum-cipher
```

**2. Install dependencies**
```bash
pip install -r requirements.txt
```

**3. Run the simulation**
```bash
python bb84_simulation.py
```


---


## Simulation Outputs

### 1. Bloch Sphere Visualization
<img src="qc_images/bs1%20output.png" alt="BS1 Output" width="300">
<img src="qc_images/bs2%20output.png" alt="BS2 Output" width="300">
<img src="qc_images/bs3%20output.png" alt="BS3 Output" width="300">
<img src="qc_images/bs5%20output.png" alt="BS5 Output" width="300">
<img src="qc_images/bs6%20output.png" alt="BS6 Output" width="300">


### 2. Final Shared Secret Key
<p align="center">
  <img src="qc_images/ss%20output.png" alt="SS_Output" width="900">

</p>


---

## References

 [BB84 Quantum Key Distribution - Wikipedia](https://en.wikipedia.org/wiki/BB84)  
 [IBM Quantum Cloud Documentation](https://quantum.cloud.ibm.com/docs/en/)

