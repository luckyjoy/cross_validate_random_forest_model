### Random Forest Tuning & Cross-Validation

In this exercise, you will learn how to construct and validate a **Random Forest** ensemble model using **scikit-learn** in Python. By the end of this activity, you will understand how to effectively tune a Random Forest model and evaluate its performance.

**Note:** The notebook is split into two parts, each with a corresponding instructional video. You can start with Part 1, or if you're already familiar with the concepts, you can skip to Part 2.

### Topics covered:
- **Importing necessary libraries**: Learn to set up your Python environment for modeling.
- **Encoding categorical features**: Use one-hot encoding (dummy variables) to handle categorical data.
- **Stratified splitting**: Ensure consistent class distribution during the data split.
- **Fitting the model**: Train a Random Forest model with the prepared dataset.
- **Hyperparameter tuning using GridSearchCV**: Optimize the model by tuning key parameters:
  - `max_depth`
  - `max_features`
  - `min_samples_split`
  - `n_estimators`
  - `min_samples_leaf`
- **Model evaluation**: Evaluate the model’s performance using metrics like **precision**, **recall**, and **F1 score**.

### Learning Goals:
- Understand the importance of hyperparameter tuning in Random Forest models.
- Apply **GridSearchCV** for automatic hyperparameter tuning and cross-validation.
- Evaluate model performance using multiple metrics to ensure the best model is chosen.

