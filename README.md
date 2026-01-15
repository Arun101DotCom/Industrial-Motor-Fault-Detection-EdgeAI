# Industrial-Motor-Fault-Detection-EdgeAI
Research pipeline for early-stage motor fault detection using time-domain signal processing and Edge AI. Focused on transitioning from static datasets to real-time industrial diagnostics. Designed to integrate with Digital Twin frameworks and heat mapping for advanced predictive maintenance and fleet-based monitoring.

# Industrial Motor Fault Detection using Edge AI
## 📌 Project Overview
This repository contains my ongoing research into **Time-Domain Feature Extraction** and **Machine Learning** for early-stage motor fault detection. The goal is to develop a hardware-efficient pipeline that can identify electromechanical failures before they lead to system downtime.

## 🔬 Current Research Status
I am currently validating a signal processing pipeline that moves away from computationally expensive frequency-domain analysis toward real-time **time-domain classification**.

* **Current Focus:** Feature Engineering (RMS, Kurtosis, Skewness) and classification using Random Forest/SVM.
* **Data Source:** Currently utilizing public vibration and current datasets (e.g., Case Western / Paderborn) for model validation.
* **Current Limitation:** Working with static datasets; looking to transition to real-time industrial testing at the University of Sheffield.

## 🛠 Tech Stack
* **Signal Processing:** MATLAB (Digital Filtering, SNR Analysis).
* **Machine Learning:** Python (Scikit-Learn), Scipy.
* **Hardware Target:** ARM-based Edge devices.

## 🚀 Roadmap
1. [x] Pre-processing scripts for noise reduction.
2. [x] Statistical feature extraction pipeline.
3. [ ] Real-time validation 
4. [ ] Integration into a Digital Twin framework.
