# Design a Startegy Based on Salary
Predicting Salaries based on Job Postings (Python)

## Business Perspective
These predictions will serve to any company's finance management team planning the company's budget for upcoming fiscal-year and handling expenses needed for employees and other expenditure. For job portals like "LinkedIn","Glassdoor", "Indeed" it'll help to provide an estimate of salary based on qualification and years of experience of job seekers, Insurance Companies to design the pension plans for employers that can help them maximize the profit. These insights are critical from point of view of an aspiring job applicant searching for jobs through any of the above mentioned professional networking & jobs postings.

## Details about project
In this case study, the predictor variables are - jobType, degree, major, industry, yearsExperience and milesFromMeteropolis.
And target variable(aka response variable) is "salary". 

With the given dataset, the target variable is almost normally distributed. 
During the Exploratory Data Analysis it seems like there are outliers present but further investigation proves that thy are not. 

The performance metric used is Mean Square Error (MSE). The model is considered best if it has low MSE. 
We have used average salaries based on "jobType" as our baseline model and achieved MSE of 963.92 on the training set.
I have also built model using:
* Linear Regression
* Polynomial Regression with only interaction terms
* Stochastic Gradient Descent and 
* Ridge Regression. 

After tuning parameters, we found that Polynomial Regression with interaction terms only performed best (MSE equivalent to 353.97) on traing set using 10-fold cross validation.

## Technologies
* Python - version 3.6.5
* Numpy - version 1.14.3
* Pandas - version 0.23.0
* Sklearn - version 0.19.1
* Matplotlib  - version 2.2.2
* Seaborn - version 0.8.1

## Conclusion
After succesfully performing Exploratory Data Analysis and Feature Engineering on categorical variables we found that Polynomial Regression works best for given dataset.

## Contact
Created by [@pmehta27](https://www.linkedin.com/in/pooja-ym-mehta) - Please feel free to contact me, thank you for your time!
