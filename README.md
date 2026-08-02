# Personalized Well-Being Prediction

This repository contains the analysis code accompanying the manuscript:

**Explainable N-of-1 digital phenotyping reveals heterogeneous well-being patterns related to burnout among ICU clinicians: An observational study** 

## Overview

This repository provides the complete analysis workflow used in the study, including:

- Data preprocessing
- Personalized machine learning models
- Linear mixed-effects model
- Residual diagnostics
- SHAP analyses
- Consensus clustering
- Burnout analyses
- Construct validity analyses
- Sensitivity analyses using ordinal outcomes

## Repository contents

- `personalized_wellbeing_analysis.ipynb` – Main analysis notebook
- `dummy_longitudinal_data.csv` – Synthetic longitudinal dataset for demonstrating the prediction analyses
- `dummy_mbi_data.csv` – Synthetic burnout dataset
- `dummy_two_factor_data.csv` – Synthetic dataset used for construct validity and CFA analyses

## Data availability

The datasets included in this repository are **synthetic** and are provided solely to demonstrate the analysis workflow. They do not contain data from study participants.

Because of participant privacy and ethical restrictions, the original study data are not publicly available. De-identified data may be available from the corresponding author upon reasonable request and subject to institutional and ethical approval.

## Software

The analyses were performed in Python and R.

Major Python packages include:

- pandas
- numpy
- scikit-learn
- scipy
- statsmodels
- xgboost
- shap
- matplotlib

R packages include:

- lavaan
- dplyr
- readr

## Citation

If you use this code, please cite the associated manuscript.

