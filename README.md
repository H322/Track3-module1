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



### Questions

#### Question 1

####  Business understanding:
#### What is the relation between Job Satisfaction Rating and Country? 
#### This analysis helps us understand which regions have the highest Job Satisfaction Rating, and by looking into the detalis of the work conditions (work hours, holidays, ... ) we can find more about the features that affect Job Satisfaction Rating.

#### Data understanding:
#### Here we have some statistics of the data and numerical fetures
<img width="836" alt="Screenshot 2023-07-24 at 9 59 22 AM" src="https://github.com/H322/DS-Project/assets/24464579/3c78f3e4-fe4b-4727-b5ea-c41374ef6e08">


In JobSatisfaction_Country.ipynb notebook we want to find the relation between Job Satisfaction Rating and Country:

<img width="1084" alt="Screenshot 2023-07-24 at 12 06 50 AM" src="https://media.github.ibm.com/user/399125/files/85b529a0-20dd-43ef-a740-82684ce80d9b">

#### Question 2

#### Business understanding:
#### This analysis helps us understand what aspects correlate well to CareerSatisfaction, and by looking into the detalis of those aspects we can find more about the features that affect CareerSatisfaction.

In CareerSatisfaction.ipynb notebook we want to investigate how well can we predict an individual's CareerSatisfaction? What aspects correlate well to CareerSatisfaction:

<img width="520" alt="Screenshot 2023-07-24 at 12 08 58 AM" src="https://media.github.ibm.com/user/399125/files/026126f9-8b2c-4082-85fd-8c25acc8e127">


As we expected CareerSatisfaction is highly correlated with JobSatisfaction and then with salary.

We fitted a linear regression to predict the CareerSatisfaction. The fitted model can explain about 38 percent of the variance.

This analysis helps us understand what aspects correlate well to CareerSatisfaction, and we found that 'JobSatisfaction', 'HoursPerWeek', 'Salary' and 'StackOverflowSatisfaction' are important features that impact the CareerSatisfaction. 

#### Question 3
In HoursPerWeek.ipynb notebook we want to investigate how well can we predict an individual's HoursPerWeek? What aspects correlate well to HoursPerWeek?:

We chose JobSeekingStatus, EmploymentStatus and HomeRemote columns are important categorical features to predict HoursPerWeek.

JobSatisfaction, HoursPerWeek, Salary, StackOverflowSatisfaction, and CareerSatisfaction are numerical features used to predict HoursPerWeek.

We fitted a linear regression to predict the HoursPerWeek. The fitted model can explain about 9 percent of the variance. By only including numerical variables we can get better results that shows the numerical features that we used are more related to predict HoursPerWeek. 

### Acknowledgements
For this project we Stack Overflow Annual Developer Survey: https://insights.stackoverflow.com/survey/2017#developer-profile-_-specific-developer-types
