For a project specifically utilizing Logistic Regression for heart disease prediction, your README.md should highlight why this algorithm was chosen and provide details on feature scaling, as Logistic Regression is sensitive to feature magnitude.

## Heart Disease Prediction using Logistic Regression 🫀
Project Overview
This project implements a Logistic Regression model to predict the probability of a patient having heart disease. Logistic Regression was selected because it is a robust baseline for binary classification, providing clear probabilistic outputs and interpretable feature coefficients.

Problem Statement
World health organizations estimate that millions of deaths occur annually due to cardiovascular diseases. Early prognosis through data-driven systems can help identify high-risk patients and encourage lifestyle changes to reduce long-term complications.

Dataset & Features
The model is trained on the 

* Demographic: Age, Sex.
* Clinical: Chest Pain Type (cp), Resting Blood Pressure (trestbps), Serum Cholesterol (chol), Fasting Blood Sugar (fbs).
* Physical: Max Heart Rate (thalach), Exercise Induced Angina (exang), Oldpeak, and Thalassemia.
* Target: 0 = No Disease, 1 = Heart Disease. 

Implementation Steps

   1. Data Exploration (EDA): Analysing correlations between health metrics like cholesterol and age.
   2. Feature Scaling: Applied StandardScaler to ensure all features contribute equally to the logistic cost function.
   3. Model Training: Using the LogisticRegression class from [Scikit-Learn]
   4. Evaluation: Calculating accuracy, precision, and recall to ensure the model effectively identifies positive cases.

Results
The Logistic Regression model achieved:

