# Day 25 - AdaBoost (Classifier and Regressor)

Today I implemented AdaBoost models for both classification and regression on the Travel dataset, and improved them using hyperparameter tuning.

---

## Key Learnings

- Learnt how to build **AdaBoost** models for both **classification** and **regression** tasks
- Built an **AdaBoost Classifier** to predict **ProdTaken** from the Travel dataset
- Built an **AdaBoost Regressor** to predict **TotalVisiting** from the Travel dataset
- Used a **ColumnTransformer** with **OneHotEncoder** and **StandardScaler** for preprocessing categorical and numerical features
- Wrapped preprocessing and models inside a **Pipeline** for cleaner and safer model training
- Evaluated classification performance using **Confusion Matrix, Accuracy, Precision, Recall, and F1-Score** (visualized with a heatmap)
- Evaluated regression performance using **R2 Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)**
- Performed **Hyperparameter Tuning** with **GridSearchCV** for both models (tuning `n_estimators`, `learning_rate`, and `loss` for the regressor)
- Compared baseline vs tuned models and reported best parameters and metrics
