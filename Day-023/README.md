# Day 23 - Decision Trees (Classifier and Regressor)

Today I implemented and evaluated Decision Tree models for both classification and regression, explored tree pruning techniques, and improved model performance using hyperparameter tuning.

---

## Key Learnings

- Learnt about **Decision Trees** for both classification and regression tasks
- Built and evaluated a **Decision Tree Classifier** on the Iris dataset and a **Decision Tree Regressor** on the Diabetes dataset
- Understood how decision trees build recursive binary splits and visualized tree structure using **plot_tree()**
- Learnt about **overfitting** in decision trees and implemented **Post Pruning** using **max_depth** parameter to prevent it
- Evaluated classification performance using **Accuracy, Confusion Matrix, and Classification Report (Precision, Recall, F1-score)**
- Evaluated regression performance using **R2 Score, MSE, and MAE**
- Performed **Hyperparameter Tuning** using **GridSearchCV** with cross-validation for both models
- Tuned key hyperparameters: **criterion, splitter, max_depth, and max_features**
- Compared pre-pruning vs post-pruning techniques to optimize tree structure and generalization
