# Day 27 - XGBoost (Classifier and Regressor)

Today I implemented and evaluated XGBoost models for both classification and regression on the cleaned Travel dataset, and improved them using hyperparameter tuning.

---

## Key Learnings

- Learnt how to build **XGBoost** models for both **classification** and **regression** tasks
- Built a **XGBoost Classifier** to predict **ProdTaken** from the cleaned Travel dataset
- Evaluated classification performance using **Confusion Matrix, Accuracy, Precision, Recall, and F1-Score**
- Performed **Hyperparameter Tuning** for the classifier using **RandomizedSearchCV**
- Tuned key classifier hyperparameters such as **gamma, learning_rate, max_depth, grow_policy, reg_alpha, reg_lambda, and sampling_method**
- Built an **XGBoost Regressor** to predict **TotalVisiting** from the cleaned Travel dataset
- Wrapped preprocessing and regression inside a **Pipeline** for cleaner model training
- Evaluated regression performance using **R2 Score, Mean Absolute Error (MAE), and Mean Squared Error (MSE)**
- Performed **Hyperparameter Tuning** for the regressor using **RandomizedSearchCV**
- Tuned key regressor hyperparameters such as **n_estimators, learning_rate, max_depth, criterion, and loss**
