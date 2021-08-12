# Stroke Prediction

# About the project

Stroke is the leading cause of long-term disability. Stroke occurs when the blood supply to a person’s brain is interrupted. According to Centers for Disease Control and Prevention, stroke is the leading cause of death for Americans. Every year, more than 795,000 people in the united states have a stroke. Stroke can occur at any age. But certain things can increase the risk of having a stroke. It can beprevented if one can identify or predict the risk of stroke in its early stage. Doctors believe that poor lifestyle and some factors like hypertension, diabetes, High BMI are the reasons for increased numbers in stroke.The main reasons why one gets stroke are hereditary, age and gender, health conditions like having high blood pressure, heart disease, and diabetes.As per the doctor’s suggestions, stroke can be prevented by maintaining physical fitness, taking hygiene food and prescribed medicines. Data Mining plays a crucial role in predicting health diseases. Clear prognosis of stroke helps us inform decisions and to mitigate risk of stroke.

Because of the significant role of stroke in health condition and death, it is considered a public health risk with considerable economic implications. Therefore, it is in the interest of the stakeholders tohave actionable knowledge regarding prevention. Data mining models can be usedto inform diagnosis based on other health data. They could help find trends and patterns in the greater populations where conventional clinical methods are not feasible. The use of data mining models in the present day for the classification of diseases is growing rapidly, not only because ofthe substantial amount of available data generated by healthcare devices and systems, but also because of the magnitude of available computational resources for statistical analysis and processing. They may prove helpful for better diagnosis and cost optimization. In conjunction withpatient outreach techniques, the use of prediction models to categorize acceptable patient data canbe effective ways for health center providers to recognize and assist patients at high risk of undiagnosed stroke.

The goal of my project is to classify the most risk factors for stroke and estimating overall risk and to build a Logistic Regression model (as our target variable is binary) on a health dataset to predict stroke. We are going to explore on how different attributes/factors related to patient’s health, and socio-economic conditions leads to stroke. The outcome of this project can be useful for virtually very stakeholder in the healthcare system including doctors, health insurance companies, healthcare providers, and policy makers

# Data Source and Data Description

The analysis seeks to predict the stroke using logistic regression. The analysis dataset was retrieved online from kaggle: https://www.kaggle.com/fedesoriano/stroke-prediction-dataset.

The dataset is used to predict whether a patient is likely to get stroke based on factors like gender, age, various diseases, and smoking status. It contains 5111 observations and 12 variables.The attributes in the dataset are:

1 Id:Patient Unique identifier Interval

2 gender:Describes the gender of the patient:Male, Female, and Other

3 Age: Describes the age of the patient 

4 hypertension: Is the patient hypertensive? 0: Patient doesn't have hypertension 1: Patient has hypertension

5 heart_disease: Does patient have heart disease? 0: Patient doesn't have heart disease 1: Patient has heart disease

6 ever_married: Is the patient married? Yes: Patient is married No: Patient is not married

7 work_type: Describes the patient work status: Govt_Job, Private, Children, Self-employed,and Never_worked

8 residence_type: Describes patient type of residence: Rural, Urban 

9 avg_glucose_level:  Describes patient average glucose level

10 bmi: Describes patient Body Mass Index 

11 smoking_status: Does patient smoke? Formerly smoked, never smoked, smokes 

12 stroke: Occurrence of stroke? 0: Patient doesn't have a stroke 1: Patient had a stroke
