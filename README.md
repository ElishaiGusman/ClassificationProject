# Employee Leaving Prediction

This project aims to predict employee leaving (whether an employee will leave or not) using machine learning techniques. 

### Preface

The dataset includes various features such as age, education, experience, city, gender, and more. Multiple machine learning models, including Logistic Regression, K-Nearest Neighbors (KNN), and Random Forests, are trained and optimized to predict the **LeaveOrNot** target variable.

The project includes feature preprocessing, model training, hyperparameter optimization using Optuna, and meta-modeling to combine predictions from multiple models to enhance performance.

### Project Overview

The main objective of this project is to predict employee leaving using a dataset with multiple features. The workflow includes:

1. **Data Loading and Preprocessing**
2. **Feature Engineering**: Various features like *Age*, *Education*, *Gender*, *City*, etc., are explored to understand their impact on the target variable (**_LeaveOrNot_**).
3. **Model Training**: Logistic Regression, KNN, and Random Forest models are trained and evaluated.
4. **Model Optimization**: The models are optimized using techniques like cross-validation and Optuna for hyperparameter tuning.
5. **Meta-Modeling**: A final model is created using a meta-learning approach to combine predictions from individual models and improve overall performance.
6. **Performance Evaluation** F1-scores and ROC AUC are used to evaluate model performance on the test data.
