# Diabetes Risk Prediction (KNN)

## Overview
This project builds a **K-Nearest Neighbors (KNN)** classifier to predict the likelihood of diabetes based on diagnostic measurements. It uses Python, Pandas, Matplotlib, and Scikit-Learn within a Google Colab environment.

---

## Dataset Overview
- **Dataset:** Pima Indians Diabetes Dataset (`diabetes.csv`)  
- **Rows:** 768  
- **Features:**  
  - Pregnancies: Number of times pregnant  
  - Glucose: Plasma glucose concentration (2-hour test)  
  - BloodPressure: Diastolic blood pressure (mm Hg)  
  - SkinThickness: Triceps skin fold thickness (mm)  
  - Insulin: 2-hour serum insulin (mu U/ml)  
  - BMI: Body mass index (weight in kg / height in m²)  
  - DiabetesPedigreeFunction: Diabetes pedigree function  
  - Age: Age in years  
- **Target:** Outcome (0 = no diabetes, 1 = diabetes diagnosis)  

---

## Tech Stack & Libraries
- Python  
- Pandas (data handling & EDA)  
- Scikit-Learn (train-test split, KNN classifier, evaluation)  
- Matplotlib (visualization)  

---

## Workflow & Steps
1. Load dataset using Pandas  
2. Verify missing values and duplicates (none found)  
3. Separate features (X) and target (y)  
4. Perform 80-20 train-test split (`random_state=42`)  
5. Train KNN classifier (`n_neighbors=3`)  
6. Evaluate predictions with accuracy score  
7. Visualize Glucose vs. BMI scatter plot categorized by outcome  

---

## Results & Accuracy
- **Test Set Size:** 154 rows  
- **Model Accuracy:** ~64.93%  

---
## About
A machine learning project implementing KNN in Python to analyze and predict diabetes risk using diagnostic health measurements.
