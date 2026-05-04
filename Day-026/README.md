# Day 26 - Gradient Boosting (Classifier and Regressor)

Today I implemented Gradient Boosting models for both classification and regression on the cleaned Travel dataset, and improved them using hyperparameter tuning.

---

## Key Learnings

- Learnt how to build **Gradient Boosting** models for both **classification** and **regression** tasks
- Built a **Gradient Boosting Classifier** to predict **ProdTaken** from the cleaned Travel dataset
- Used a **ColumnTransformer** with **OneHotEncoder** and **StandardScaler** for preprocessing categorical and numerical features
- Evaluated classification performance using **Confusion Matrix, Accuracy, Precision, Recall, and F1-Score**
- Performed **Hyperparameter Tuning** for the classifier using **RandomizedSearchCV**
- Tuned key classifier hyperparameters such as **loss, learning_rate, n_estimators, criterion, and max_depth**
- Built a **Gradient Boosting Regressor** to predict **TotalVisiting** from the cleaned Travel dataset
- Wrapped preprocessing and regression inside a **Pipeline** for cleaner model training
- Evaluated regression performance using **R2 Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)**
- Performed **Hyperparameter Tuning** for the regressor using **RandomizedSearchCV**
- Tuned key regressor hyperparameters such as **n_estimators, learning_rate, and loss**
