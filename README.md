# Automated Stellar Classification using SDSS DR18

An automated machine learning classifier designed to categorize astronomical objects into Stars, Galaxies, or Quasars based on photometric and spectroscopic features from the Sloan Digital Sky Survey (SDSS) DR18 catalogue.

## 🚀 Project Overview
Manual spectral examination becomes impractical with next-generation sky surveys. This project builds a production-ready, highly accurate supervised learning pipeline utilizing advanced gradient boosting to reliably classify cosmic objects at scale.

## 🛠️ Tech Stack
- **Language:** Python 3.12.4 (3.11+)
- **Data Manipulation:** Pandas, NumPy
- **Machine Learning:** XGBoost, Scikit-learn
- **Visualization:** Matplotlib, Seaborn

## 📋 Expected Deliverables Met
1. **Exploratory Data Analysis:** Handled class imbalances, performed feature filtering (dropping non-physical survey metadata tracking IDs like `obj_ID`, `run_ID`, etc.), and completed dimensional reduction via Principal Component Analysis (PCA).
2. **Model Optimization:** Configured a highly optimized XGBoost Classifier matching strict physical discrimination requirements.
3. **Evaluation Suite:** Generated a comprehensive suite consisting of a Confusion Matrix, Multi-class ROC-AUC curves, and a Top-5 Feature Importance bar chart.

## ⚙️ Setup & Reproducibility
To run this notebook locally, clone the repository and install the dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn xgboost
