# 🧪 Inorganic Semiconductor Bandgap Prediction

A machine learning project focused on predicting the bandgap energy of inorganic semiconductors using material descriptors. This project leverages regression models to accelerate materials discovery and support electronic device design.

## 🚀 Overview

Bandgap energy is a critical property that determines the electrical conductivity and optical behavior of semiconductors. Traditional methods for calculating bandgaps (e.g., DFT) are computationally expensive. This project uses ML models trained on curated datasets to predict bandgap values efficiently and accurately.

## 🧠 Objectives

- Predict bandgap energy from chemical and physical descriptors
- Compare performance across multiple regression models
- Enable fast screening of candidate materials for electronics and photovoltaics
- Provide interpretable insights into feature importance

## 📂 Project Structure
- data/ # Raw and processed datasets
- notebooks/ # Jupyter notebooks for EDA and modeling
- src/ # Source code for preprocessing and training 
- models/ # Saved model files 
- results/ # Evaluation metrics and plots 
- README.md # Project overview 
- requirements.txt # Python dependencies


## 📊 Dataset

- Source: Materials Project / Open Quantum Materials Database (OQMD)
- Format: CSV with descriptors such as atomic number, electronegativity, density, etc.
- Target: Bandgap energy (in eV)

## 🧪 Models Used

- Linear Regression
- Random Forest Regressor
- Gradient Boosting (XGBoost)
- Support Vector Regression
- Neural Networks (optional extension)

## 📈 Evaluation Metrics

- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)
- R² Score
- Feature importance via SHAP

## 📌 Key Results

- Best model: XGBoost with R² ≈ 0.89 and MAE ≈ 0.21 eV
- Top features: Electronegativity, atomic radius, density
- Visualizations: Residual plots, feature importance charts
