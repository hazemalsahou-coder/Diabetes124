🩺 Diabetes Prediction using Machine Learning

📌 Project Overview

This project focuses on predicting diabetes using machine learning models trained on the Pima Indians Diabetes Dataset which I got from Kaggle.
The goal is to build and compare multiple classification models and evaluate their performance using different metrics.

This project is part of my journey into Machine Learning and AI in Healthcare.

---

📊 Dataset

The dataset contains medical diagnostic measurements such as:

- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Diabetes Pedigree Function
- Age
- Outcome (0 = Non-diabetic, 1 = Diabetic)

---

⚙️ Workflow

1. Data Preprocessing

- Loaded dataset using Pandas
- Defined features (X) and target (y)
- Split data into training and testing sets

2. Models Used

The following machine learning models were trained and compared:

- Logistic Regression
- Random Forest
- Decision Tree
- K-Nearest Neighbors (KNN)
- XGBoost

---

📈 Model Evaluation

Models were evaluated using:

- Accuracy Score
- Cross Validation (5-Fold)
- Confusion Matrix
- Classification Report
- ROC-AUC Score

---

🏆 Best Model Performance

- Best ROC-AUC Score: 0.81
- Logistic Regression achieved competitive and stable performance across metrics.

---

🔍 Feature Importance

Using Random Forest, the most important features for diabetes prediction were:

- Glucose
- BMI
- Age
- Diabetes Pedigree Function

---

📊 Results Summary

Model| Accuracy| CV Score
Logistic Regression| ~0.75| ~0.77
Random Forest| ~0.72| ~0.76
Decision Tree| ~0.74| ~0.71
KNN| ~0.66| ~0.72
XGBoost| ~0.72| ~0.74

---

📌 Key Insights

- Glucose level is the strongest predictor of diabetes.
- Ensemble models improve stability.
- ROC-AUC shows good discrimination ability (~0.81).

---

🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- XGBoost

---

🚀 Future Improvements

- Hyperparameter tuning (GridSearchCV)
- Use of deep learning models
- Deployment using Streamlit or Flask
- Handling class imbalance techniques

---
Author:Hazem Aljasem Alsahou

This project is part of my learning journey in Machine Learning and AI applied to healthcare.
