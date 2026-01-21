# ReneWind — Neural Network–Based Failure Prediction

## Executive Summary
Wind energy operations depend on high equipment availability, where unexpected turbine generator failures lead to costly downtime and reactive maintenance. This project applies neural network–based classification models to predict wind turbine generator failures using sensor data, enabling proactive maintenance planning and improved operational reliability.

The work emphasizes minimizing false negatives to ensure failures are identified early, supporting cost-efficient maintenance strategies in wind energy production.

---

## Business Objective
Develop a predictive classification system that:
- Identifies potential turbine generator failures before breakdown
- Minimizes false negatives to reduce unplanned downtime
- Supports proactive maintenance and cost reduction strategies

The objective is to improve **reliability and maintenance decision-making**, not simply to maximize model accuracy.

---

## Data Overview
- Sensor-based operational data from wind turbine generators
- Mixed numeric features representing equipment performance signals
- Binary classification target indicating failure vs. normal operation
- Class imbalance reflecting the rarity of failure events

---

## Analytical / Technical Approach

### 1. Data Preparation
- Data cleaning and preprocessing of sensor signals
- Handling of missing values and normalization of inputs
- Feature preparation suitable for neural network architectures

### 2. Modeling Strategy
- Baseline classification models for comparison
- Feedforward neural network implementation
- Selection and tuning of activation functions
- Iterative model refinement to balance sensitivity and stability

### 3. Evaluation Methodology
- Performance evaluation focused on:
  - Recall and false-negative reduction
  - Confusion matrix analysis
  - Overall classification reliability
- Model selection based on operational impact rather than accuracy alone

---

## Key Findings
- Neural network models effectively capture nonlinear relationships in sensor data.
- Minimizing false negatives significantly improves maintenance readiness.
- Proper activation function selection materially impacts classification performance.
- Neural networks provide meaningful gains over simpler models when tuned correctly.

---

## Limitations
- Model performance depends on sensor data quality and coverage.
- Rare failure events limit the volume of positive-class examples.
- The system is designed for **decision support**, not autonomous maintenance actions.

---

## Next Steps
- Incorporation of temporal and sequential modeling approaches
- Cost-sensitive optimization aligned with maintenance economics
- Integration into predictive maintenance workflows
- Ongoing retraining as new operational data becomes available

---

## Repository Structure
- `notebooks/` — Data exploration, neural network modeling, and evaluation
- `README.md` — Project overview, methodology, and findings
---

## View Modeling
[![Open In GitHub](https://img.shields.io/badge/Open%20in-GitHub-black?logo=github)](https://github.com/CGM-AIML/Exploratory-Data-Analysis/blob/main/Exploratory_Data_Analysis_Notebook_Christopher_Gonzalez_Mejias.ipynb)
---

## Project Context
This project was completed as part of the **Introduction to Neural Networks** course in the  
**UT Austin / Great Learning Post Graduate Program in AI & ML (2025–2026)** and has been refactored for **portfolio-grade presentation**.

[View FoodHub Project in ePortfolio](https://www.mygreatlearning.com/eportfolio/christopher-gonzalez-mejias)  
