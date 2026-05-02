# Day 24 - Random Forest Classification and Regression

Today I trained Random Forest models for both classification and regression on the Travel dataset, and improved them with hyperparameter tuning.

---

## Key Learnings

- Learnt how to build **Random Forest** models for both **classification** and **regression** tasks
- Built a **Random Forest Classifier** to predict **ProdTaken** from the Travel dataset
- Used a **ColumnTransformer** with **OneHotEncoder** and **StandardScaler** for preprocessing
- Evaluated classification performance using **Confusion Matrix, Classification Report, and Accuracy Score**
- Performed **Hyperparameter Tuning** with **RandomizedSearchCV** for the classifier
- Built a **Random Forest Regressor** to predict **TotalVisiting**
- Wrapped preprocessing and regression inside a **Pipeline** for cleaner model training
- Evaluated regression performance using **R2 Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)**
- Performed **Hyperparameter Tuning** for the regressor using **RandomizedSearchCV** with cross-validation
