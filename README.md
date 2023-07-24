# DS-project1

[![License](https://img.shields.io/badge/License-Apache_2.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python](https://img.shields.io/badge/Language-Python-blue.svg)](https://python.org/)

## Overview

This repo contains a Jupyter notebook to analyze the Developer Survey dataset. 

## Contents

The project contains the following:

notebook/                             - Jupyter notebook

├── JobSatisfaction_Country.ipynb     - Relation between Job Satisfaction Rating and Country

├── CareerSatisfaction.ipynb          - Predict an individual's CareerSatisfaction

├── HoursPerWeek.ipynb                - Predict an individual's HoursPerWeek

├── DS-Project.ipynb                  - including all 3 questions


## Libraries

Libraries/

├── numpy                             - Adding support for large, multi-dimensional arrays and matrices

├── pandas                            - Library for the Python programming language for data manipulation and analysis

├── matplotlib                        - Plotting library for the Python programming

├── sklearn                           - A machine learning library

├── ImputingValues                    - Library for imputing missing values

├── seaborn                           - A Python data visualization library



## Questions

### Question 1

In JobSatisfaction_Country.ipynb notebook we want to find the relation between Job Satisfaction Rating and Country:

<img width="1084" alt="Screenshot 2023-07-24 at 12 06 50 AM" src="https://media.github.ibm.com/user/399125/files/85b529a0-20dd-43ef-a740-82684ce80d9b">

### Question 2
In CareerSatisfaction.ipynb notebook we want to investigate how well can we predict an individual's CareerSatisfaction? What aspects correlate well to CareerSatisfaction:

<img width="520" alt="Screenshot 2023-07-24 at 12 08 58 AM" src="https://media.github.ibm.com/user/399125/files/026126f9-8b2c-4082-85fd-8c25acc8e127">


As we expected CareerSatisfaction is highly correlated with JobSatisfaction and then with salary.

We fitted a linear regression to predict the CareerSatisfaction. The fitted model can explain about 38 percent of the variance.

### Question 3
In HoursPerWeek.ipynb notebook we want to investigate how well can we predict an individual's HoursPerWeek? What aspects correlate well to HoursPerWeek?:

We chose JobSeekingStatus, EmploymentStatus and HomeRemote columns are important categorical features to predict HoursPerWeek.

JobSatisfaction, HoursPerWeek, Salary, StackOverflowSatisfaction, and CareerSatisfaction are numerical features used to predict HoursPerWeek.

We fitted a linear regression model with L2 and L1 regularization to prevent overfitting problem and can interperate the relation between the taget variable and independent variables. The r-squared score for our model is:  0.0961797787407.
