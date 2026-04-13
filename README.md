**Heart Disease Clinical Prediction System**

End-to-End Machine Learning Project | Python · Scikit-Learn · Pandas

Developed a diagnostic support tool using Logistic Regression to predict heart disease risk with 80% accuracy. Analyzed medical features like cholesterol and heart rate to identify key risk indicators and provided a real-time predictive system for clinical decision support.

**Project Objective**

To build a reliable binary classification model that predicts the presence of heart disease using 13 clinical features. The goal is to achieve high generalization (low gap between training and testing scores) to ensure the model works on new, unseen patients.

**Model Stability: "Good Fit" Verified**

The model achieved 85% Training Accuracy and 80% Testing Accuracy.



**Key Predictors Identified**

Using correlation analysis, features like Chest Pain Type (cp) and Maximum Heart Rate (thalach) showed the strongest relationship with heart disease.

heart_disease_project/

│
├── data/
│    HEART DESEASE DATA.csv          ← Raw medical dataset

│
├── python/
│    heart_disease_model.ipynb       ← Complete Colab workflow

│
├── README.md                         ← Project documentation



**Performance Summary**

Algorithm: Logistic Regression

Accuracy: 80% (Test Set)

Optimization: Stratified split used to ensure clinical fairness in both training and testing sets.
