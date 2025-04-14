# Quantum States through Wigner Function Reconstruction

## 🧠 Inspiration  
Quantum noise is more than randomness—it's a hidden canvas of nature. Inspired by the complex structures within quantum uncertainty, we aimed to turn ambiguity into clarity by decoding meaningful quantum states from aesthetically rich noise landscapes.

## ⚙️ What It Does  
- Generates Wigner functions of quantum states  
- Simulates their evolution under noise and dissipation  
- Reconstructs density matrices from distorted phase-space observations  

This enables us to model, analyze, and visualize quantum systems affected by real-world imperfections.

## 🛠️ How We Built It  
- Built robust noise-correction pipelines for experimental data  
- Applied least-squares and convex optimization for density matrix recovery  
- Performed quantum state reconstruction using displaced parity measurements  
- Simulated Wigner functions and open system dynamics with [dynamiqs](https://github.com/qgrad/dynamiqs) (powered by JAX)  

## 🚧 Challenges We Ran Into  
While we set up a full pipeline for fidelity analysis and reconstruction, we didn’t have enough time to compute all density matrices before submission.

## 🏆 Accomplishments We’re Proud Of  
- Successfully simulated quantum states with complex Wigner functions  
- Visualized phase-space evolution under dissipation  
- Developed a robust foundation for future extensions into real experimental integration  

---
