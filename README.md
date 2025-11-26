# Assignment_20.1-Capstone-Initial-Report
Initial report for the Capston project. Cleaned the data, made a baseline model
Project Summary:
This project analyzes a stroke prediction dataset to predict stroke occurance based on patient characteristics such as age, BMI, glucose levels, and lifestyle factors. Exploratory Data analysis was performed, missing values and outliers were handled, and a Random Forest Classification model was developed to create a baseline model and evaluate predictive patterns within the dataset.
Data Cleaning:
Missing values in the BMI column were imputed using the median. Outliers in variables such as BMI and glucose levels were identified. These outliers were kept in the dataset because the individuals who were deemed outliers are the exact population of those that had a stroke. To reduce the skewness, a log transformation was applied. 
Feature engineering was performed by creating age groups and BMI groups to better capture the relationships with stroke occurence. 
Key Findings: 
Higher BMI and high glucose levels are associated with increased stroke risk
Age is a strong predictor of stroke risk as well. 
