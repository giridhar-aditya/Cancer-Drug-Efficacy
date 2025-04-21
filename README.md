# Cancer Drug Efficacy Prediction using MVLR

## 📌 Overview
This project uses a **Multivariate Linear Regression (MVLR)** model to predict the **efficacy of cancer drugs** based on genomic and molecular features of cancer cell lines. The model aims to support personalized medicine by forecasting drug response from biological data.

## 🧬 Data & Features
- **Inputs**: Gene expression, copy number variation, mutation status, and other molecular descriptors.
- **Target**: Drug response metrics (e.g., IC50 values).

## 🧠 Model
- **Algorithm**: Multivariate Linear Regression (OLS)
- **Libraries**: `sklearn`, `pandas`, `numpy`, `matplotlib`, `seaborn`
- **Metrics**: R² Score, RMSE

## 📈 Workflow
1. Load and preprocess the dataset
2. Split into training and testing sets
3. Fit the MVLR model
4. Evaluate predictions
5. Visualize results (scatter plots, residuals)

## 🛠️ Usage
1. Install dependencies:
   ```bash
   pip install -r requirements.txt
