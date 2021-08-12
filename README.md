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

# Problem Statement or Hypothesis

This project is mainly focused on predicting out whether a patient is likely to get stroke based on factors like gender, age, body mass index, average glucose level and various diseases like hypertension, heart diseases, and smoking status. The main objective is to explore the factors affecting the stroke. 

Relationships:

• Is there any significant relationship between stroke and various diseases.

• Is there any significant relationship between stroke, body mass index and average glucose level.

• Is there any significant relationship between a stroke and socio-economic and demographic factors like gender, age, resident type, marital status, work type.

Effect:

• To what extent does socio economic and demographic factors affect stroke?

• What are the main factors that affect stroke?

# KPIs

To evaluate analytical approach, one should define analytical metrics that match with the business objectives and processes. In this case, the business goal is to find the likelihood of patient with stroke rather than missing a truly positive case (i.e. a person with stroke) which would be significantly more expensive than misidentifying a negative case. If a person with stroke is not identified, their condition would not be treated and therefore it might result in severe consequences for the patient and healthcare system. Recall score is choosen as as one of the key performance indicator (KPI). False positive rate, which is equal to 1 − 𝑆𝑝𝑒𝑐𝑖𝑓𝑖𝑐𝑖𝑡𝑦, is the metric that should be minimized to avoid false positive identifications. To achieve both business goals, I use area under the receiver operating characteristic curve (ROC AUC) as other key performance indicators.

# Steps

Throughout the analysis i have used Excel and SPSS for model building and evaluation: The analysis can be handled in various steps:

1. Data Acquisition and pre-processing 

2. Modeling

3. Evaluation/ Validation 

4. Data driven Insights.

• In the first step, we collect data and clean it and then we will be describing the appropriate statistical measures according to the nature of each variable using Explanatory Data Analysis and Correlation Analysis will be performed to examine the relations between different variables.

• Then we model a Binary Logistic Regression and evaluate to what extent different factors in the dataset affect stroke

## Data Preprocessing steps

1.Missing values

2.Outliers

3.Normality

4.Correlation

5.Pearson chi-squared test of independence

# Files


# Summary

In this project, a binary logistic regression model is built to identify patients with stroke using their health, socio-demographic data. Stroke is the leading cause of long-term disability. Early identification of stroke by healthcare professionals can help physicians and patients start treatment earlier to prevent or reduce serious consequences. The exploratory data analysis revealed interesting patterns. Through the analysis, I found that hypertension and heart diseases have significant affect on stroke and also I observed high stroke rate for people of age above 45.The resident_type factor did not have effect on stroke. The analysis showed that people who are married are more likely to get stroke which might be due to their health issues, personal life pressures and tensions and also both male and female are equally likely to get stroke. We had more female observations than male so this might be one cause of results showing not much variation among gender. The risk of those who previously smoked over nonsmokers getting stroke was high. This might be due to an abrupt change in the body's chemical intake.Also observed patients with body mass index above 30 and average glucose level >170mg/dl are more likely to get stroke. I have chosen sensitivity score and ROC AUC as key performance indicators because missing a positive case can be significantly more expensive than mis-identifying a negative case. The model achieved a sensitivity of 77.64% . The rate of actual positive increase exponentially up to approximate 0.4 rates of false-positive where it tended to a constant of about 0.9. The overall classification accuracy based on the model was 92.8%.I believe that in order to explain more variations in stroke apart from the factors considered in the project ,having information related to other risk factors for instance, diabetes, drinking habit , and diet can also be used in the future to make more accurate predictions. 
