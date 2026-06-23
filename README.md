# Diabetes124
Diabetes Prediction Using Logistic Regression

Project Overview

This project predicts whether a patient has diabetes using Machine Learning.

The model is trained on the Pima Indians Diabetes Dataset and uses several medical measurements such as glucose level, blood pressure, BMI, insulin level, age, and pregnancy count.

Dataset Features

- Pregnancies
- Glucose
- BloodPressure
- SkinThickness
- Insulin
- BMI
- DiabetesPedigreeFunction
- Age

Target Variable

- Outcome
  - 0 = Non-Diabetic
  - 1 = Diabetic

Machine Learning Model

The project uses:

- Logistic Regression
- Balanced class weights to reduce class imbalance effects
- Custom classification threshold (0.395)

Workflow

1. Load the diabetes dataset
2. Split data into training and testing sets
3. Train a Logistic Regression model
4. Predict diabetes probability
5. Apply custom threshold (0.395)
6. Evaluate model performance

Libraries Used

numpy
pandas
scikit-learn

Results

Accuracy

68.83%

Confusion Matrix

[[63 41]
 [ 7 43]]

Classification Report

Precision (Diabetes): 0.51
Recall (Diabetes): 0.86
F1-score (Diabetes): 0.64

The model achieves high recall for diabetic patients, making it useful when identifying positive cases is more important than minimizing false positives.

Run the Project

Clone the repository:

git clone https://github.com/your-username/diabetes-prediction.git

Install dependencies:

pip install pandas numpy scikit-learn

Run the notebook or Python script.

Future Improvements

- Data preprocessing and normalization
- Hyperparameter tuning
- Cross-validation
- Comparison with Random Forest and XGBoost
- Deploy as a web application using Streamlit

Author

Hazem Alsahoo

Medical Student interested in Artificial Intelligence and Medical AI.
