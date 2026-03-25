# CO₂ Solubility Prediction Using Ensemble Machine Learning

**IPTC 2025 Paper:** [DOI: 10.2523/IPTC-25029-MS](https://doi.org/10.2523/IPTC-25029-MS)

## Overview

This repository contains the code and data for my IPTC 2025 paper: *"Comparative Analysis of Parametric and Non-Parametric Machine Learning Models for CO₂ Solubility Estimation."*

The study develops and compares ML models to predict CO₂ solubility in brine — a critical parameter for carbon capture and storage (CCS). The Random Forest model achieved >98% prediction accuracy, outperforming traditional thermodynamic models.

## Key Results

- **Random Forest R² > 0.98**, MAE < 0.077 mol/kg
- **SHAP analysis** identified pressure as the most influential feature
- **Williams plot** confirmed 98% of data within reliable domain
- Model outperformed XGBoost, genetic algorithms, and thermodynamic models (Søreide-Whitson, activity-fugacity)

