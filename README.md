# Digital Health Technologies for Dementia Care: A Systematic Literature Review

[![Authors](https://img.shields.io/badge/Authors-Domenicali,%20Passini,%20Tolomelli-blue)]()
[![Institution](https://img.shields.io/badge/Institution-University%20of%20Bologna-red)]()
[![License](https://img.shields.io/badge/License-MIT-green)](LICENSE)

## 📌 Overview
This systematic literature review investigates the integration of **continuous digital monitoring**, **ambient intelligence**, and **objective digital phenotyping** for early detection and longitudinal health assessment in dementia care. 

## 🛠️ Technological Taxonomy
Our review categorizes solutions into three main pillars:
1. **Wearable Devices:** High-frequency movement and physiological tracking (IMUs, consumer smartwatches, wearable EEG)[cite: 4, 5].
2. **Smart-Home & Ambient Sensing:** Non-intrusive in-home monitoring (PIR sensors, magnetic door contacts) to establish Activities of Daily Living (ADL) baselines[cite: 4, 6].
3. **Predictive Algorithms:** Analytical frameworks (such as deep learning and hybrid models like *HEALNET*) to model disease trajectories[cite: 4, 11, 15].

## ⚙️ Key Engineering Challenges
* **Synthetic vs. Real-World Data:** Heavy reliance on controlled benchmarks (CASAS) or synthetic simulations (*NeuroSense*)[cite: 7, 15, 16].
* **Domain Shift & Adherence:** Vulnerability to unconstrained home environments and compliance barriers caused by cognitive decline[cite: 16].
* **Data Privacy:** Need for Federated Learning (FL) and Differential Privacy to comply with GDPR[cite: 16, 19].

## 📁 Repository Structure
```text
DH_project/
├── .gitignore          # Git exclusion rules
├── LICENSE             # MIT License
├── README.md           # Project documentation
└── docs/               # Research paper
    └── DH_project.pdf  # Systematic literature review manuscript
