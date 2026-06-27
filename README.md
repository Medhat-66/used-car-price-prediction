# Used Car Price Prediction — Regression

Predicting the selling price of used cars based on their specifications using regression models.

## Results

| Model | R² Score | RMSE |
|---|---|---|
| Linear Regression | 0.817 | 1.77 |
| OLS Regression (Statsmodels) | 0.895 | — |
| Ridge Regression | 0.808 | 1.81 |
| Lasso Regression | 0.827 | 1.72 |
| ElasticNet | 0.811 | 1.80 |

## Dataset
- Vehicle Dataset — Kaggle
- 301 records, 9 columns (Car Name, Year, Selling Price, Kms Driven, Fuel Type...)

## Steps Performed
- **EDA:** Analyzed feature distributions and correlations
- **Outlier Removal:** Removed 8 outliers using IQR method
- **Feature Engineering:** One-Hot Encoding for categorical columns
- **Statistical Analysis:** VIF analysis, Residual Analysis, Normality Testing (Shapiro-Wilk)
- **Hyperparameter Tuning:** Cross-Validation for all models

## Libraries
Python, Pandas, NumPy, Scikit-learn, Statsmodels, Matplotlib, Seaborn
