Logistic Regression: Churn Prediction
This project demonstrates how to use Logistic Regression to build a binary classification model that predicts customer churn using a real-world dataset.

📌 Objectives
Understand and apply logistic regression for binary classification.

Preprocess and normalize data for machine learning.

Train and evaluate a logistic regression model using scikit-learn.

Interpret model performance using metrics such as log-loss.

Visualize key insights from the dataset.

🗂 Dataset
The dataset used in this project is publicly available at ChurnData.csv above.

This dataset includes features such as customer account length, international plan, number of calls, charges, and a binary churn label (1 = churned, 0 = retained).

🛠 Technologies Used
Python 3

Pandas for data manipulation

NumPy for numerical operations

Matplotlib for data visualization

Scikit-learn for model training, preprocessing, and evaluation

🚀 Steps Performed
Data Loading & Inspection
Load data directly from a remote URL, inspect for nulls and structure.

Feature Selection
Select relevant features for the logistic regression model.

Preprocessing

Convert categorical to numerical (if any).

Normalize features using StandardScaler.

Train-Test Split
Data split into training and testing sets using train_test_split.

Model Training
Logistic regression model trained with sklearn.linear_model.LogisticRegression.

Prediction & Evaluation

Predictions made on test data

Log-loss metric used to evaluate prediction confidence.

Visualization
Generate plots to analyze feature importance and model results (if applicable).

📈 Evaluation Metric
Log Loss: Used to evaluate probabilistic classification performance, especially suitable for imbalanced datasets.
