# Salary-Prediction-Portfolio
Salary Prediction Project (Python)

Predicting Salaries based on Job Postings

# Business Perspective
    This predictions will be of interest to company's finance department planning the budget for coming fiscal-year, for job portals like     "LinkedIn","Glassdoor", "Indeed" to provide an estimate of salary based on qualification and years of experience of job seeker, Insurance   Companies to design the pension plans for employers that can help them maximize the profit.

# Details about project
    In this case study, the predictor variables are - jobType, degree, major, industry, yearsExperience and milesFromMeteropolis and target   variable (also known as response variable) is "salary". With the given dataset, the target variable is almost normally distributed.       
  However, while performing the Exploratory Data Analysis, at first it seems like there are outliers but further investigating it we prove   that they are not the outliers. The performance metric used is Mean Square Error (MSE). The model is considered best if it has low MSE. 
    
    We used average salaries based on jobType as our baseline model and achieved MSE of 963.92 on training set. Build model using Linear     Regression, Polynomial Regression with only interaction terms, Stochastic Gradient Descent and Ridge Regression. After tuning parameters,   we found that Polynomial Regression with interaction terms only performed best (MSE equivalent to 353.97) on traing set using 10-fold     
  cross validation.

# Technologies
Python - version 3.6.5
Numpy - version 1.14.3
Pandas - version 0.23.0
Sklearn - version 0.19.1
Matplotlib - version 2.2.2
Seaborn - version 0.8.1

# Outcome
    After performing Exploratory Data Analysis and Feature Engineering on categorical variables, Polynomial Regression works best for given   dataset.

# Contact
    Created by @pmehta27 - please feel free to contact me, thank you for your time!
