# ML-project

1- preprocessing:

Ameen(70%): Data ingestion & memory-savvy joins , Cleaning & Imputation , Encoding ,  Feature scaling , Dimensionality & collinearity , Imbalanced data handling

Ayham(30%): Exploratory Data Analysis , Feature engineering , Time-aware splitting

2- Task A:

Ameen(40%): Logistic Regression , K-Nearest Neighbors classifier , Random Forest classifier

Ayham(60%): Support Vector Machine , Decision Tree classifier , Gradient boosting classifier(XGBoost) , some enhancing on data splitting

3- Task B:

the target we choose : days-to-next-order

Ameen(60%): K-Nearest Neighbors Regressor , Decision Tree Regressor , Random Forest Regressor , some enhancing on data splitting

Ayham(40%):  Linear Regression , Support Vector Regressor , Gradient boosting regressor (XGBoost)

4- Evaluation metrics:

Ameen(60%): Regression , Model comparison

Ayham(40%): Classification

5- Required visualizations & plots:

Ameen(50%): SHAP , Residual vs predicted plots , residual histograms & Q-Q plots , Learning curves , Interactive plot , Correlation heatmap and feature correlation scatter grids 

Ayham(50%): Decision boundary plots , Confusion matrices & normalized confusion matrices , ROC curves and PR curves , Calibration plot 


6- Cross-validation & hyperparameter tuning:

nested cross-validation: Standard Nested Cross-Validation involves random shuffling , which breaks the chronological order of user transactions. 
This would introduce data leakage , allowing the model to train on future orders to predict past ones.
Therefore , we replaced it with a time-aware validation strategy to strictly preserve the temporal sequence and simulate real-world predictive conditions.

Ameen(50%): validation curves , GridSearchCV

Ayham(50%): GridSearchCV , early stopping(XGBoost)

7- Robustness & stress tests:

Ameen:  class imbalance handled via resampling and compering

8- Decision boundary requirement:

Ayham