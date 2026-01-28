
📌 Project Overview

This project analyzes the Instacart Market Basket dataset to predict:

Task A (Classification): Whether a user will reorder a specific product in their next order.

Task B (Regression): Days until the user places the next order.

The project includes full EDA, feature engineering, multiple machine learning models, hyperparameter tuning, and model explainability.

📂 Dataset

Instacart Online Grocery Shopping Dataset (Kaggle)
Includes: orders, products, aisles, departments, and user purchase history.

⚙️ Methodology

1. Data Preprocessing & EDA
Data cleaning and memory-efficient joins

Missing value analysis and outlier handling

Temporal analysis (hour, day, recency, frequency)

2. Feature Engineering
User-level features (order count, reorder ratio, recency)

Product-level features (popularity, reorder rate)

User–Product interaction features

Time-based features

3. Models Implemented
Classification:
Logistic Regression, KNN, SVM, Decision Tree, Random Forest, XGBoost

Regression:
Linear Regression, SVR, KNN Regressor, Random Forest, XGBoost

4. Evaluation
Classification: AUC, F1, Precision, Recall, PR Curve

Regression: MAE, RMSE, R²

Cross-validation and hyperparameter tuning

SHAP for model explainability

🛠 Tech Stack

Python

Pandas, NumPy

Scikit-learn

XGBoost / LightGBM

Matplotlib, Seaborn, Plotly

SHAP

👥 Team Members

Ameen Nasaireh || Ayham Smadi


🎯 Key Results

Best classification model: XGBoost (Accuracy = 0.74070)

Best regression model: Random Forest (RMSE = 3.92510)