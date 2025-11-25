# 🧬 Integrating Genomic Pathway and Clinical Modeling for Mortality Prediction in Breast Cancer

This repository explores a machine learning framework to predict **mortality risk in breast cancer patients** by integrating **clinical variables** (e.g., age, tumor stage, treatment history) with **genomic pathway activity** derived from gene expression data. The goal is to build a more accurate, interpretable, and biologically grounded prognostic model than clinical features alone.

The main analysis is implemented in:  
📄 **[Final_DS_pipeline.ipynb](Final_DS_pipeline.ipynb)**

> ⚠️ **Important**: The notebook file currently returns a GitHub session error when viewed online (e.g., "You signed in with another tab..."). This typically indicates a rendering issue or access problem—not necessarily missing content. The notebook may still be valid locally or in raw form. Please download the `.ipynb` file to inspect or run it.

---

## 📌 Project Overview

Breast cancer outcomes vary widely due to molecular heterogeneity. While clinical models provide baseline risk estimates, they often miss key biological drivers of aggressiveness. This project aims to:

- Extract pathway-level signals from transcriptomic data (e.g., using MSigDB gene sets)
- Merge these signals with clinical metadata
- Train and validate machine learning models for binary mortality prediction
- Interpret model behavior using feature importance or SHAP values

This integrative approach supports **precision oncology** by linking molecular mechanisms to clinical outcomes.

---

## 📁 Repository Structure /
├── Final_DS_pipeline.ipynb # Main Jupyter notebook (may require local download to view)
└── README.md # This file
