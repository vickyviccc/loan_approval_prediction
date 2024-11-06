# loan_approval_prediction
 This project is my solution for the Loan Approval Prediction Kaggle competition. The objective is to predict loan approval outcomes based on applicant data using machine learning models.


Table of Contents:
Dataset
Project Structure
Features and Approach
Model Performance
Results


Dataset:
The dataset can be accessed from the Kaggle competition page: Loan Approval Prediction.

The dataset includes:
train.csv: The training set with features and the target variable, indicating loan approval status.
test.csv: The test set with features only, without the target variable.
sample_submission.csv: A sample submission file for Kaggle.

Project Structure:
notebook - Contains Jupyter notebooks with data exploration, preprocessing, model training, and evaluation.
README.md - Project description and documentation.
submission.csv - Final predictions formatted for Kaggle submission with the Loan_ID and Loan_Status columns.


Features and Approach: 

Data Preprocessing:
Handling missing values thoughtfully to avoid introducing bias.
Encoding categorical variables using techniques like one-hot encoding.
Feature scaling for numerical variables to improve model performance.

Model Training:
Trained various models, including Logistic Regression, Decision Trees, and Gradient Boosting Machines.
Hyperparameter tuning with Grid Search and Optuna for optimization.
Utilized Isolation Forest for outlier detection to improve data quality.
Model Performance
The model achieved significant accuracy and precision in predicting loan approval status, with evaluation metrics like accuracy, precision, recall, and F1 score.

Results:
The final predictions are saved in submission.csv, formatted for Kaggle submission with the Loan_ID and Loan_Status columns.
