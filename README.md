# Diabetes-Predictor-WebApp
A web application to predict diabetes based on diagnostic measurements.

## Table of Contents
- Introduction
- Objective
- Dataset
- Features
- Results

## Introduction
Diabetes is a group of metabolic disorders characterized by high blood sugar levels over a prolonged period. Symptoms include frequent urination, increased thirst, and increased hunger. If left untreated, it can lead to serious complications such as cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

## Objective
The objective of this project is to predict whether a patient has diabetes based on certain diagnostic measurements. The dataset used consists of several medical predictor variables and one target variable, Outcome. Predictor variables include the number of pregnancies the patient has had, BMI, insulin level, age, etc.

## Dataset

The dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. All patients in this dataset are females at least 21 years old of Pima Indian heritage.

<b>Dataset url : </b> https://www.kaggle.com/uciml/pima-indians-diabetes-database

### Details about the Dataset:
- Pregnancies: Number of times pregnant
- Glucose: Plasma glucose concentration after 2 hours in an oral glucose tolerance test
- Blood Pressure: Diastolic blood pressure (mm Hg)
- Skin Thickness: Triceps skin fold thickness (mm)
- Insulin: 2-Hour serum insulin (mu U/ml)
- BMI: Body mass index (weight in kg/(height in m)^2)
- Diabetes Pedigree Function: Diabetes pedigree function
- Age: Age (years)
- Outcome: Class variable (0 or 1)

## Features
- Logistic Regression: 72.08% accuracy
- K Nearest Neighbors: 78.57% accuracy
- Support Vector Classifier: 73.38% accuracy
- Naive Bayes: 71.43% accuracy
- Decision Tree: 68.18% accuracy
- Random Forest: 75.97% accuracy
  
From the above comparison, we can observe that K Nearest Neighbors achieves the highest accuracy of 78.57%.

![image](https://github.com/user-attachments/assets/78dd53d4-f0b8-49d6-85be-faec4ae84b73)
<br>
![image](https://github.com/user-attachments/assets/7d499903-291e-4d18-aee6-5665326a7cec)
<br>
![image](https://github.com/user-attachments/assets/ffbac984-da21-4101-afdd-e481f356a9e6)
<br> <br>

## Results
The prediction engine provides optimal performance with the right dataset and efficient training of the classifier models. The implemented prediction engine can predict the presence of diabetes with varying accuracies for different models.
