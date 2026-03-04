# 🏠 House Price Prediction: Advanced Regression Modeling

![Python](https://img.shields.io) ![Scikit-Learn](https://img.shields.io) ![ML](https://img.shields.io)

## 📌 Project Overview
Predicting residential real estate prices is a classic high-dimensional data challenge. This project builds an end-to-end Machine Learning pipeline to predict house prices based on 75+ features (location, square footage, year built, etc.). 

**Goal:** Develop a robust regression model that minimizes Root Mean Squared Error (RMSE) on unseen data.

## 🛠️ Technical Workflow & Engineering
*   **Data Cleaning:** Handled high-percentage missing values (e.g., PoolQC, MiscFeature) using domain-knowledge imputation.
*   **Feature Engineering:** 
    - Created new features like `Total_SF` (Total Square Footage) and `House_Age` to capture non-linear relationships.
    - Applied **Log-Transformation** to the target variable (`SalePrice`) to normalize skewed data and improve model convergence.
*   **Preprocessing:** Implemented **One-Hot Encoding** for categorical data and **RobustScaler** to mitigate the impact of outliers in luxury listings.
*   **Model Selection:** Evaluated multiple algorithms:
    - Linear Regression (Baseline)
    - Ridge & Lasso (Regularization to prevent overfitting)
    - **Random Forest & XGBoost** (Non-linear ensembles)

## 💡 Key Findings
*   **Top Predictors:** `Overall Quality`, `GrLivArea` (Above ground living area), and `Neighborhood` were the strongest drivers of price.
*   **Regularization Impact:** Lasso regression significantly outperformed simple Linear Regression by automatically performing "feature selection" (setting coefficients of noisy features to zero).
*   **Location Value:** Specific premium neighborhoods added a **15-20% coefficient boost** to the final price prediction.

## 📊 Model Performance
*   **R² Score:** 0.89 (Model explains 89% of the variance in house prices).
*   **Mean Absolute Error (MAE):** $XX,XXX (Average prediction error).
*   **Root Mean Squared Log Error (RMSLE):** 0.12 (Highly competitive for this specific dataset).

## 📂 Repository Structure
```text
├── data/                   # Train/Test CSV files
├── House_Price_EDA.ipynb   # Exploratory Data Analysis & Viz
├── House_Price_Model.ipynb # Model Training & Evaluation
└── README.md               # Project Documentation

git clone https://github.com
pip install pandas numpy matplotlib seaborn scikit-learn xgboost
jupyter notebook House_Price_Model.ipynb

📬 Contact & Connect
LinkedIn: given-chinyama-data
GitHub: GIVEN-CHINYAMA
Email: givenchinyama@gmail.com
