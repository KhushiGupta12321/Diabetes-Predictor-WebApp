# Diabetes-Predictor-WebApp

Diabetes, is a group of metabolic disorders in which there are high blood sugar levels over a prolonged period. Symptoms of high blood sugar include frequent urination, increased thirst, and increased hunger. If left untreated, diabetes can cause many complications. Acute complications can include diabetic ketoacidosis, hyperosmolar hyperglycemic state, or death. Serious long-term complications include cardiovascular disease, stroke, chronic kidney disease, foot ulcers, and damage to the eyes.

This dataset is originally from the National Institute of Diabetes and Digestive and Kidney Diseases. Several constraints were placed on the selection of these instances from a larger database. In particular, all patients here are females at least 21 years old of Pima Indian heritage.

## Objective
The objective of the dataset is to predict whether or not a patient has diabetes, based on certain diagnostic measurements included in the dataset. The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on.

<b>Dataset url : </b> https://www.kaggle.com/uciml/pima-indians-diabetes-database

## Details about the dataset:
The datasets consists of several medical predictor variables and one target variable, Outcome. Predictor variables includes the number of pregnancies the patient has had, their BMI, insulin level, age, and so on. <br>
•	Pregnancies: Number of times pregnant <br>
•	Glucose: Plasma glucose concentration a 2 hours in an oral glucose tolerance test <br>
•	Blood Pressure: Diastolic blood pressure (mm Hg) <br>
•	Skin Thickness: Triceps skin fold thickness (mm) <br>
•	Insulin: 2-Hour serum insulin (mu U/ml) <br>
•	BMI: Body mass index (weight in kg/(height in m)^2) <br>
•	Diabetes Pedigree Function: Diabetes pedigree function <br>
•	Age: Age (years) <br>
•	Outcome: Class variable (0 or 1) <br>

## RESULTS
The Prediction Engine provides an optimal performance with the right dataset and efficient training of the classifier models considering all aspects and a lot of learning from the previous experiences. The implemented Prediction Engine is capable of predicting the presence of Diabetes with an accuracy of, <br>

• Logistic Regression: 72.07792207792207 <br>
• K Nearest neighbors: 78.57142857142857 <br>
• Support Vector Classifier: 73.37662337662337 <br>
• Naive Bayes: 71.42857142857143 <br>
• Decision tree: 68.18181818181817 <br>
• Random Forest: 75.97402597402598 <br> <br>

 From the above comparison, we can observe that K Nearest neighbors gets the highest accuracy of 78.57 %.

![image](https://github.com/user-attachments/assets/78dd53d4-f0b8-49d6-85be-faec4ae84b73)
<br>
![image](https://github.com/user-attachments/assets/7d499903-291e-4d18-aee6-5665326a7cec)
<br>
![image](https://github.com/user-attachments/assets/ffbac984-da21-4101-afdd-e481f356a9e6)
<br> <br>

## Conclusion
The objective of the project was to develop a model which  could identify patients with diabetes who are at high risk of hospital admission. Prediction of risk of hospital admission is a fairly complex task. Many factors influence this process and  the outcome. There is presently a serious need for methods that can increase healthcare institution’s understanding of   what   is   important   in   predicting   the   hospital   admission   risk.   This   project   is   a   small contribution to the present existing methods of diabetes detection by proposing a system that can be used as an assistive tool in identifying the patients at greater risk of being diabetic. This project achieves this by analyzing many key factors like the patient’s blood glucose level,   body   mass   index,   etc.,   using   various   machine   learning   models   and   through retrospective analysis of patients’ medical records. The project predicts the onset of diabetes in   a   person   based   on   the   relevant   medical   details   that   are   collected   using   a web application. When the user enters all the relevant medical data required in the online web application,  this  data  is  then   passed  on   to   the   trained   model   for   it   to   make  predictions whether the person is diabetic or nondiabetic. The model makes the prediction which is fairly good and reliable.
