# EE793 Course Project Cryptanalysis of the Learning With Errors (LWE) Problem using MILP

## 📌 Overview
This project formulates the **secret recovery problem in Learning With Errors (LWE)** as a **Mixed Integer Linear Program (MILP)**.  
By modeling modular arithmetic and bounded noise constraints, the attack attempts to recover the secret vector efficiently under restricted parameters.  
This was implemented as part of the **EE793: Topics in Cryptology** course at IIT Bombay.

## ⚡ Objectives
- Reformulate the LWE problem as a MILP with linearized constraints.  
- Implement a practical cryptanalysis solver in Python.  
- Evaluate attack feasibility across parameter ranges.  

## 🛠️ Methodology
- **MILP Formulation:** Encoded modular equations with noise bounds.  
- **Solver Implementation:** Used Python + `PuLP` solver for feasibility checking.  
- **Parameter Variation:** Tested across secret sizes, modulus values, and error widths.  

## 📊 Results
- Successfully **recovered binary secrets** for **low-dimensional (n ≤ 25)** LWE instances.  
- Demonstrated feasibility of MILP-based attacks in **restricted noise regimes**.  
- Showed **rapid increase in solver complexity** with higher dimensions, confirming hardness assumptions.  
- Provided empirical evidence on the trade-off between **dimension size** and **noise width**.
- The Results, Code and Report are uploaded in the repository.
