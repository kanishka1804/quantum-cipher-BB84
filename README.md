# Quantum Cipher: BB84 Quantum Key Distribution Simulation

A Python-based simulation of the **BB84 Quantum Key Distribution (QKD)** protocol — one of the first and most secure quantum cryptography methods.  
This project demonstrates **quantum bit (qubit) encoding, measurement, and key generation** using **Qiskit** and visualizes the process with **Bloch spheres**.

---

##  Features
-  **Simulates BB84 protocol** step-by-step  
-  **Generates random quantum bits** for Alice & Bob  
-  **Simulates basis matching & bit comparison**  
-  **Bloch sphere visualization** for qubit states  
-  **Final shared secret key generation**  

---

## Quick BB84 Concept
In BB84:
1. **Alice** sends qubits to **Bob** encoded randomly in two different bases (Rectilinear `+` and Diagonal `×`).
2. **Bob** measures each qubit using a random basis.
3. They publicly compare bases (not the actual bits).
4. Bits where bases matched become part of the **shared secret key**.

---


## Simulation Outputs

### 1. Bloch Sphere Visualization
![BS1 Output](qc_images/bs1%20output.png)
![BS2 Output](qc_images/bs2%20output.png)
![BS3 Output](qc_images/bs3%20output.png)
![BS5 Output](qc_images/bs5%20output.png)
![BS6 Output](qc_images/bs6%20output.png)


### 2. Final Shared Secret Key
![SS Output](qc_images/ss%20output.png)

---

## References

 [BB84 Quantum Key Distribution - Wikipedia](https://en.wikipedia.org/wiki/BB84)  
 [IBM Quantum Cloud Documentation](https://quantum.cloud.ibm.com/docs/en/)

