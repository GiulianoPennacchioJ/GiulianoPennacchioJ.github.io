# Giuliano Pennacchio – Flight Dynamics & Mission Analysis Portfolio

This repository contains the source code of my personal portfolio website:

🔗 https://GiulianoPennacchioJ.github.io

---

## About

This portfolio presents my work in **Flight Dynamics, Mission Analysis, and State Estimation for space applications**, with a technical focus on:

- High-fidelity orbit propagation and perturbation analysis
- Interplanetary trajectory design and launch window optimization (Porkchop Plots)
- Regional satellite constellation design and coverage optimization (Walker Delta)
- Orbit determination and recursive state estimation (Batch Least Squares & EKF)
- Numerical simulation using GMAT, MATLAB/Simulink, and Python

The projects are structured to showcase a complete space mission life-cycle engineering capability:

**Orbit Propagation & Mission Analysis → Trajectory Design & Constellation Optimization → Orbit Determination & State Estimation**

---

## Featured Technical Projects

### High-Fidelity Orbit Propagation and Perturbation Analysis
Development of a numerical propagation framework for LEO spacecraft including comparison between 2-body and perturbed models, long-term trajectory divergence assessment and sensitivity analysis.

### Interplanetary Launch Window Analysis (Porkchop Plot Solver) `[Active Coding]`
Numerical tool written in Python to optimize Earth-to-Mars interplanetary transfers by solving Lambert's problem across date grids, generating characteristic energy ($C_3$) and $\Delta V$ insertion profiles.

### LEO Walker Delta Constellation Optimization `[Active Coding]`
Design framework evaluating revisit times, access slots, and geometric coverage over custom regional Areas of Interest (e.g., Mediterranean) using pure numerical arrays in NumPy.

### Batch Orbit Determination and Covariance Analysis `[In Progress]`
Implementation of a Batch Least Squares estimator using simulated range and range-rate observations, including residual analysis, convergence assessment and covariance evaluation.

### Extended Kalman Filter for Nonlinear Orbit Estimation `[In Progress]`
Design and implementation of an EKF for recursive orbit estimation, including nonlinear dynamics modeling, covariance propagation and Q/R tuning analysis.

### MSc Thesis – LiDAR-Based Pose Estimation of Non-Cooperative Space Targets
Performance analysis of the OBB-TM algorithm for LiDAR-based pose acquisition in lost-in-space conditions, with emphasis on robustness, symmetry handling and estimation accuracy.

---

## Technical Focus

### Flight Dynamics & Mission Analysis
- Orbit propagation & Perturbation modeling  
- Interplanetary transfer design (Lambert solvers)  
- Constellation architecture & Coverage analysis  
- Maneuver budgeting  

### Estimation & GNC/AOCS
- Batch Least Squares  
- Extended Kalman Filtering (EKF)  
- Covariance analysis & Sensor fusion  
- Nonlinear attitude and orbit dynamics  

### Tools
- GMAT  
- Python (NumPy, SciPy, Matplotlib)  
- MATLAB & Simulink (Simscape)  
- Git/GitHub · LaTeX  

---

© Giuliano Pennacchio