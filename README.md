# heart-diseass-prediction-e
# Heart Disease Prediction &amp; Risk Modelling  ## Overview An end-to-end machine learning project to predict cardiovascular disease risk  from clinical patient data. Built as part of my MSc Data Science dissertation  at Coventry University, 
# Heart Disease Prediction & Risk Modelling

## Overview
An end-to-end machine learning project to predict cardiovascular disease risk 
from clinical patient data. Built as part of my MSc Data Science dissertation 
at Coventry University, achieving a grade of 75%.

## Dataset
- **Source:** Kaggle (Cleveland Heart Disease dataset)
- **Features:** 13 clinical attributes including age, sex, chest pain type, 
  resting blood pressure, cholesterol, fasting blood sugar, ECG results, 
  max heart rate, and exercise-induced angina
- **Target:** Binary classification — presence or absence of heart disease

## Tools & Libraries
- Python, Pandas, scikit-learn, Matplotlib

## Methodology
1. **Data Cleaning & EDA** — handled missing values, explored feature 
   distributions and correlations using Pandas and Matplotlib
2. **Feature Scaling** — applied normalisation to prepare data for 
   distance-sensitive models
3. **Model Training & Evaluation** — trained and compared four classification 
   algorithms:
   - Logistic Regression
   - Random Forest
   - Decision Tree
   - K-Nearest Neighbours (KNN)
4. **Results** — best model achieved **87% accuracy**; models evaluated on 
   accuracy, precision, recall and F1-score

## Key Finding
Random Forest produced the strongest overall performance, with the most 
clinically relevant features being chest pain type, maximum heart rate 
achieved, and number of major vessels coloured by fluoroscopy.

## File Structure
