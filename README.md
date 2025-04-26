---
title: "Lung Cancer Survival Dashboard"
output: DashboardTest1
---

# Lung Cancer Survival Dashboard

This interactive dashboard provides survival analysis visualizations and models based on clinical and biological data from lung cancer patients.  
It was built using R and the `flexdashboard`, `survival`, `survminer`, and `plotly` packages.

## Project Overview

- **Kaplan-Meier Survival Curves**  
  Visualizes survival probabilities over time, stratified by MHC-II expression status.

- **Cox Proportional Hazards Model**  
  Displays hazard ratios (HR) for clinical factors such as stage at diagnosis, MHC-II status, and smoking history (pack years).

- **Interactive Features**  
  Hover over plots to see detailed information (e.g., time points, survival probability, hazard ratios, confidence intervals).
