## Background
Alzheimer's Disease (AD) is a progressive neurodegenerative disorder that affects millions globally whose main sysptoms includes memory loss, cognitive decline, and functional impairment. It is predictied that the prevalence of such disease will triple by 2050. Therefore, under this background, a reliable and accurate way to diagnose AD in an early phase would be rather critical and strongly needed to enable timely interventions that can slow disease progression, improve patient outcomes, and reduce caregiver burdens (Alzheimer’s Disease International, 2022).

## Research Introduction
This research aims to leverage popular machine learning techniques to make predictions on the early diagnosis of AD. Our dataset contains two parts training and test. Both of them have 35 columns/variables that correspond to different metrics of patients' personal background and health condition, such as age, gender, Body Mass Index (BMI), and alcohol consumption.

There are 1504 observations/patients in the training set and 645 observations/patients in the test set. Our goal is to fit various models with the training set, select and keep only siginificant and the most relevant variables in our models, tune and optimize models, and finally obtain a model that shows a good performance on predicting whether a patient from the test set will develop AD based on the selected variables.

## Technical Summary
**Models utilized in this research:**
  - Logistic Regression
  - Support Vector Machine (SVM)
  - Quadratic Discriminant Analysis (QDA)
  - Dicision Tree
  - Random Forest
  - Gradient Boosting

**Feature Selection Metrics:**
  - Akaike Information Criterion (AIC)
  - Bayesian Information Criterion (BIC)
  - Least Absolute Shrinkage and Selection Operator (LASSO)

**Model Evaluation Metrics**
  - ROC curve with AUC
  - Calibration Curve
  - Confusion Matrix
  - Confidence Interval

## Research Results
Our final tuned Gradient Boosting model demonstrates a strong performance on the diagnosis of AD, with an accuracy of **95.88%** on the training set and **94.894%** on the test set.

Also, our model identifies 5 key predictors among 35 variables as follows:
- **MMSE**: a well-established cognitive assessment tool
- **Functional Assessment**: evaluating patients’ abilities in daily tasks;
- **Memory Complaints**: a self-reported symptom of cognitive decline
- **Behavioral Problems**: indicators of changes in personality or behavior
- **ADL**: assessing functional independence

