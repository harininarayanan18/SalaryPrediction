# SalaryPrediction
In this project I have worked on predicting the salary of employees based on various categories such as Job Type, Industry in which they are employed, Educational qualification, etc. It will also take into account the numerical categories like the number of years of experience the employee has and their distance from the nearest metropolitan city. I use various regression algorithms to find the best model. The dataset can be found on Kaggle.

Tools used: Python 3 with machine learning algorithms from sklearn, random forest and xgboost.

## Data Description

#### train_features.csv: 
This file contains 1000000 observations, each one representing an individual job listing, along with 8 features/variables.

#### train_salaries.csv: 
This file contains the salaries for the observations in train_features.csv along with their corresponding identifier.

#### test_features.csv: 
Silimar to train_features for which we need to predict the salaries.

### Features in training data:

jobId (categorical) - A unique identifier for each employee. I will not be using this for analysis but only to merge features with their corresponding salaries from the salaries dataset.
companyId (categorical) - A unique identifier for each company.
jobType (categorical) - Describes the position of the employee, like Junior, Manager, Vice President, CEO, etc.
degree (categorical) - Describes the highest educational qualification of the employee, like High School, Bachelors, Masters, etc.
major (categorical) - Describes the major chosen by the employee in college, like Chemistry, Math, Physics, etc.
industry (categorical) - Describes the industry in which the employee is working, like Auto, Health, Finance, Oil, etc.
yearsExperience (numerical) - Number of years of experience the employee has
milesFromMetropolis (numerical) - Job location's distance from nearest metropolis.

