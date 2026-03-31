# Explainable AI for ESG-Driven Financial Risk Analysis

## Overview
This project explores the relationship between **Environmental, Social, and Governance (ESG) factors** and **financial risk** using machine learning and explainable AI techniques.

Unlike traditional black-box models, this system emphasizes **interpretability**, enabling a deeper understanding of how ESG dimensions influence:

- Short-term volatility risk  
- Long-term return-based risk  

---

## Key Contributions
- Decomposed ESG into **Environmental, Social, and Governance components**  
- Modeled **dual financial risks** (volatility and returns)  
- Implemented **LightGBM** for predictive modeling  
- Applied **SHAP (Explainable AI)** for interpretability  
- Performed **sector-wise interaction analysis**  

---

## Tech Stack
- **Programming Language:** Python  
- **Libraries & Tools:** LightGBM, Scikit-learn, Pandas, NumPy  
- **Explainability:** SHAP (Shapley Additive Explanations)  
- **Domain:** Financial Data Analysis  

---

## Dataset Description

### Financial Data
- Daily stock prices (S&P 500 companies)  
- Features include:
  - Closing Price  
  - Daily Returns  
  - Volatility  
  - Cumulative Returns  

### ESG Data
- ESG Risk Score  
- Environmental Risk Score  
- Social Risk Score  
- Governance Risk Score  
- Controversy Score  
- Sector and Industry  

---

## Feature Engineering

### Financial Features
- **Daily Return:** Log returns  
- **Volatility:** Standard deviation of returns  
- **Cumulative Returns:** Long-term performance indicator  

### ESG Features
- Composite ESG score  
- Individual ESG dimensions (Environmental, Social, Governance)  

---

## Methodology

### Risk Modeling
Two distinct financial risks were modeled:

**1. Volatility Risk (Short-Term)**  
- Based on standard deviation of returns  
- Binary classification: Low Risk / High Risk  

**2. Return-Based Risk (Long-Term)**  
- Based on cumulative returns  
- Binary classification  

---

### Model Architecture
- LightGBM classifiers  
- Separate models for each risk type  
- Stratified train-test split  
- Standardized feature scaling  

---

### Explainable AI
- SHAP (Shapley Additive Explanations)  
- Global and local interpretability  
- Feature importance analysis  
- ESG dimension-level insights  

---

## Results

### Volatility Risk Model
- Accuracy: ~58%  
- ESG factors show limited influence on short-term volatility  

### Return-Based Risk Model
- Accuracy: ~64%  
- ESG factors demonstrate stronger influence on long-term returns  

---

## Key Insights
- **Governance risk** is the most influential factor overall  
- **Environmental risk** significantly impacts long-term returns  
- **Social risk** varies across sectors  
- ESG acts as a **long-term structural risk indicator** rather than a short-term predictor  

---

## Explainability Insights
- ESG dimensions are **not equally important**  
- Sector context significantly affects ESG impact  
- Explainable AI reveals **hidden structural relationships** in financial risk  

---

## My Contributions
- Designed and implemented the machine learning pipeline  
- Performed ESG decomposition and feature engineering  
- Developed LightGBM-based predictive models  
- Applied SHAP for interpretability and analysis  
- Conducted financial risk interpretation and insights extraction  

---

## Research Paper
Full research paper available here:  
[Download Research Paper](./ESG_Risk_Analysis_Research_Paper.pdf)


---

## Acknowledgements
- ESG Finance Research  
- Explainable AI methodologies  
- Financial Risk Modeling frameworks  
