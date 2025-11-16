# House Prices Prediction – Ames Housing Dataset

End-to-end machine learning project predicting house sale prices using **Linear Regression** and **Random Forest Regressor**.

---

## Goal
Predict the sale price of homes based on 80+ features from the Ames Housing Dataset.

Dataset: Public Ames Housing version (train & test combined).

---

## What This Project Covers

- Load and inspect the dataset  
- Analyze target distribution  
- Explore feature relationships (scatter plot, correlation heatmap)  
- Split data into train/test sets  
- Preprocess numeric and categorical features  
- Train Linear Regression & Random Forest models  
- Evaluate using MAE, RMSE, R²  
- Compare models in a summary table  
- Error analysis on largest prediction errors  
- Visualize true vs predicted prices  

---

## About Model Files

The trained Random Forest model is **not included in this repository**  
because its `.joblib` file exceeds GitHub’s 25MB upload limit.  

The model can be recreated automatically by running the notebook.

---

## Model Performance (Example)

| Model               | MAE     | RMSE    | R²    |
|--------------------|---------|---------|--------|
| Linear Regression  | 16,034  | 29,635  | 0.890  |
| Random Forest      | **15,799** | **26,732** | **0.911** |

The **Random Forest** achieved the best performance (lowest RMSE).

---

## Key Insights
- Features like `OverallQual`, `GrLivArea`, `GarageCars`, and `TotalBsmtSF` show strong relationships with `SalePrice`.
- Random Forest captures nonlinear patterns better than Linear Regression.

---

## Tech Stack
Python · pandas · scikit-learn · matplotlib · joblib

---

## How to Run

`pip install -r requirements.txt`

`jupyter notebook HousePricesProject.ipynb`

## Author: 
Akerke Absalykova

Data Science Portfolio 2025
