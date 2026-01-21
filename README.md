# ReneWind — Predictive Maintenance Neural Network Pipeline

## Executive Summary
Wind energy operations rely on high equipment availability, where unexpected turbine generator failures lead to costly downtime, reactive maintenance, and lost production. This project implements a neural network–based predictive maintenance pipeline to identify wind turbine generator failures from sensor data, enabling earlier intervention and improved operational reliability.

Beyond introducing neural networks, this work represents a transition from isolated model experimentation to **end-to-end pipeline design**, with explicit emphasis on decision support, false-negative minimization, and real maintenance impact.

---

## Business Objective
Develop a predictive maintenance classification pipeline that:
- Detects potential turbine generator failures before breakdown
- Prioritizes minimizing false negatives to reduce unplanned downtime
- Supports proactive maintenance scheduling and cost reduction

The objective is to improve **reliability and maintenance decision-making**, not to optimize accuracy in isolation.

---

## Data Overview
- Sensor-based operational data from wind turbine generators
- Numeric features representing equipment performance and operating conditions
- Binary classification target indicating failure vs. normal operation
- Strong class imbalance reflecting the rarity of failure events in production systems

---

## Analytical / Technical Approach

### 1. Data Preparation
- Data ingestion, validation, and preprocessing of sensor signals
- Handling of missing values and normalization of continuous inputs
- Feature preparation tailored for neural network architectures

### 2. Pipeline & Modeling Strategy
- Establishment of baseline classification models for comparison
- Design and implementation of a feedforward neural network
- Experimentation with activation functions and network configuration
- Iterative refinement to balance sensitivity, stability, and generalization

This project marks the first instance where modeling decisions are treated as **pipeline components**, not standalone experiments.

### 3. Evaluation Methodology
- Evaluation focused on operational relevance, including:
  - Recall and false-negative reduction
  - Confusion matrix–driven failure analysis
  - Overall classification reliability under imbalance
- Model selection guided by maintenance impact rather than accuracy alone

---

## Key Findings
- Neural networks effectively capture nonlinear relationships in turbine sensor data.
- Prioritizing recall materially improves maintenance readiness and failure detection.
- Activation function choice has a significant effect on model sensitivity.
- Properly tuned neural networks provide meaningful gains over simpler classifiers in this domain.

---

## Limitations
- Model performance depends heavily on sensor data quality and coverage.
- Rare failure events constrain the number of positive-class examples.
- The pipeline is designed for **decision support**, not autonomous maintenance execution.

---

## Next Steps
- Incorporation of temporal and sequential modeling approaches
- Cost-sensitive optimization aligned with maintenance economics
- Integration into predictive maintenance and monitoring workflows
- Continuous retraining as new operational data becomes available

---

## Repository Structure
- `notebooks/` — End-to-end predictive maintenance pipeline implementation, including preprocessing, neural network modeling, and evaluation
- `README.md` — Project overview, methodology, findings, and pipeline framing

---

## View Modeling
[![Open In GitHub](https://img.shields.io/badge/Open%20in-GitHub-black?logo=github)](
https://github.com/AIneuroForge/ReneWind-Neural-Networks/blob/main/notebooks/INN_ReneWind_Main_Project_Chris_Gonzalez_Mejias.ipynb
)

---

## Project Context
This project was completed as part of the **Introduction to Neural Networks** course in the  
**UT Austin / Great Learning Post Graduate Program in AI & ML (2025–2026)** and has been **refactored to reflect the transition from academic modeling to professional pipeline development**.

🔗 [View Personal Loan Project in ePortfolio](https://www.mygreatlearning.com/eportfolio/christopher-gonzalez-mejias)
