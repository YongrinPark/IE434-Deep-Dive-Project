# Code Notebooks

This folder contains all Jupyter notebooks used throughout the IE 434 Deep Dive Project.  
Each notebook corresponds to one of the project milestones and follows the workflow from data extraction to deep learning modeling and feature importance analysis.

## 📘 Notebook Overview

### 1. `Baseline Learning.ipynb`
Implements baseline machine learning models (primarily Ridge Regression).  
Includes data loading, preprocessing, model training, and baseline evaluation metrics.  
Used as the benchmark model for comparing deep learning performance.

### 2. `Deep Learning.ipynb`
Trains feed-forward neural networks (Dense models) using the cleaned working dataset.  
Explores nonlinear modeling, activation functions, loss curves, and model tuning.

### 3. `Deep Learning_weather.ipynb`
Adds weather-related external variables to the feature set.  
Tests whether temperature, wind speed, humidity, and precipitation improve model accuracy.  
Results show minimal predictive benefit.

### 4. `Feature Importance (Results).ipynb`
Computes feature importance using:
- Ridge Regression coefficients  
- Permutation importance  

Provides visualizations and final interpretation of which features most strongly drive Illinois LMP.

---

## ▶ Notebook Execution Order

To reproduce the project workflow:

1. **Data_Extraction.ipynb** (optional if `.pkl` files already present)  
2. **Baseline Learning.ipynb**  
3. **Deep Learning.ipynb**  
4. **Deep Learning_weather.ipynb** (optional experiments)  
5. **Feature Importance (Results).ipynb**

---

## 🧩 Dependencies

All not
