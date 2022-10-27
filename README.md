# Cardiovascular-disease-analysis

The purpose of this project is to predict whether a person has cardiovascular disease or not.

### Features:
- Age | Objective Feature | age | int (days)
- Height | Objective Feature | height | int (cm) 
- Weight | Objective Feature | weight | float (kg) 
- Gender | Objective Feature | gender | categorical code 
- Systolic blood pressure | Examination Feature | ap_hi | int 
- Diastolic blood pressure | Examination Feature | ap_lo | int 
- Cholesterol | Examination Feature | cholesterol | 1: normal, 2: above normal, 3: well above normal 
- Glucose | Examination Feature | gluc | 1: normal, 2: above normal, 3: well above normal 
- Smoking | Subjective Feature | smoke | binary 
- Alcohol intake | Subjective Feature | alco | binary 
- Physical activity | Subjective Feature | active | binary 
- Presence or absence of cardiovascular disease | Target Variable | cardio | binary

### Analysis:
- Import the dataset
- Perform basic data cleaning
- Exploratory data analysis
- Upsample the data to balance the dataset
- Split the data into train and test sets
- Perform Logistic Regression, Feature selection, Ridge Regression and Lasso Regression
