# Salary-Prediction
Predicting Individual's Salary

In this project, we will work on US census data. The goal is to determine whether a person makes over $50K. The dataset was extracted from the 1994 US census data.The data is stored in a tab separated value file, and each line represents a person.

This dataset contains categorical values. Most of the algorithms we learn in class can only handle numeric values and so we need to create a new variable (dummy variable) for every unique value of the categorical variables. To convert the categorical variable into dummy/indicator variables, we will use pandas.get_dummies.
