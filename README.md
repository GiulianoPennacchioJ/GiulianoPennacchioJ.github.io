# Giuliano Pennacchio – Flight Dynamics & Mission Analysis Portfolio

This repository contains the source code of my personal portfolio website:

🔗 https://GiulianoPennacchioJ.github.io

---

## About

This portfolio presents my work in **Flight Dynamics, Mission Analysis, and State Estimation for space applications**, with a technical focus on:

- High-fidelity orbit propagation and perturbation analysis
- Interplanetary trajectory design and launch window optimization (Porkchop Plots)
- Regional satellite constellation design and coverage optimization (Walker Delta)
- High-fidelity vehicle dynamics & telemetry state processing
- Orbit determination and recursive state estimation (Batch Least Squares & EKF)
- Numerical simulation using GMAT, MATLAB/Simulink, and Python

The projects are structured to showcase a complete space mission life-cycle engineering capability:

**Orbit Propagation & Mission Analysis → Trajectory Design & Constellation Optimization → Ground Track & 3D Geospatial Visualization → Vehicle Dynamics & Telemetry Processing → Orbit Determination & State Estimation**

---

## Featured Technical Projects

### High-Fidelity Orbit Propagation and Perturbation Analysis
Development of a numerical propagation framework for LEO spacecraft including comparison between 2-body and perturbed models, long-term trajectory divergence assessment and sensitivity analysis.

### Interplanetary Launch Window Analysis (Porkchop Plot Solver)
Numerical tool written in Python to optimize Earth-to-Mars interplanetary transfers by solving Lambert's problem across date grids, generating characteristic energy ($C_3$) and $\Delta V$ insertion profiles.

### LEO Walker Delta Constellation Optimization 
Design framework evaluating revisit times, access slots, and geometric coverage over custom regional Areas of Interest (e.g., Mediterranean) using pure numerical arrays in NumPy.

### Multi-Constellation Orbit & Ground Track Visualizer
Analytical propagation engine utilizing SGP4/SDP4 models on TLE datasets across LEO, MEO, GEO, and IGSO regimes. Features TEME-to-ITRS sidereal coordinate transformations, 2D equirectangular map generation, kinematic speed profiles, and interactive 3D KML trajectory exports for Google Earth Pro.

### F1 Telemetry & Vehicle Dynamics Analysis Toolkit
Telemetry processing engine for high-speed vehicle dynamics analysis, featuring uniform spatial grid resampling ($\Delta s = 1.0\text{ m}$), Savitzky-Golay state filtering, non-linear aerodynamic force estimation ($F_z$, $F_x$, $L/D$), $G\text{-}G$ friction circle mapping, and ERS hybrid clipping evaluation.

### Batch Orbit Determination and Covariance Analysis `[In Progress]`
Implementation of a Batch Least Squares estimator using simulated range and range-rate observations, including residual analysis, convergence assessment and covariance evaluation.

### Real-Time Orbit Determination & Extended Kalman Filter (EKF)
High-fidelity MATLAB/Simulink framework for real-time spacecraft orbit determination and nonlinear state estimation. It processes absolute orbital dynamics, handles GNSS data assimilation, enforces $3\sigma$ covariance consistency, and executes real-time Fault Detection, Isolation, and Recovery (FDIR) using Mahalanobis distance metrics ($D_M^2$) and Normalized Innovation Squared (NIS) consistency checks against $\chi^2$ distribution limits.

### MSc Thesis – LiDAR-Based Pose Estimation of Non-Cooperative Space Targets
Performance analysis of the OBB-TM algorithm for LiDAR-based pose acquisition in lost-in-space conditions, with emphasis on robustness, symmetry handling and estimation accuracy.

---

## Technical Focus

### Flight Dynamics & Mission Analysis
- Orbit propagation & Perturbation modeling  
- Interplanetary transfer design (Lambert solvers)  
- Constellation architecture & Coverage analysis  
- Maneuver budgeting  

### Estimation, Dynamics & GNC/AOCS
- Batch Least Squares  
- Extended Kalman Filtering (EKF)  
- Vehicle dynamics & Telemetry processing  
- Covariance analysis & Sensor fusion  
- Nonlinear attitude and orbit dynamics  

### Tools
- GMAT  
- Python (NumPy, SciPy, Matplotlib, SGP4, Astropy, Poliastro, FastF1, GeoPandas, Plotly)  
- MATLAB & Simulink (Simscape)  
- Git/GitHub · LaTeX  

---

© Giuliano Pennacchio