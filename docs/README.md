## Developer Job Life 

<img width="729" alt="Screenshot 2023-07-24 at 12 53 19 AM" src="https://media.github.ibm.com/user/399125/files/223c20fe-211f-40fc-8a86-89e8dac24154">


## Overview

In this blog we want to analyze some important features from the Developer Survey dataset. 



## What are the Countries with high Job Satisfaction Rating?

First we want to find the relation between Job Satisfaction Rating and Country:

<img width="1084" alt="Screenshot 2023-07-24 at 12 06 50 AM" src="https://media.github.ibm.com/user/399125/files/85b529a0-20dd-43ef-a740-82684ce80d9b">


## CareerSatisfaction
In this section we want to investigate how well can we predict an individual's CareerSatisfaction? What aspects correlate well to CareerSatisfaction:

<img width="520" alt="Screenshot 2023-07-24 at 12 08 58 AM" src="https://media.github.ibm.com/user/399125/files/026126f9-8b2c-4082-85fd-8c25acc8e127">


As we expected CareerSatisfaction is highly correlated with JobSatisfaction and then with salary.

We fitted a linear regression to predict the CareerSatisfaction. The fitted model can explain about 38 percent of the variance.

## Hours per Week
In this section we want to investigate how well can we predict an individual's HoursPerWeek? What aspects correlate well to HoursPerWeek?:

We chose JobSeekingStatus, EmploymentStatus and HomeRemote columns are important categorical features to predict HoursPerWeek.

JobSatisfaction, HoursPerWeek, Salary, StackOverflowSatisfaction, and CareerSatisfaction are numerical features used to predict HoursPerWeek.

We fitted a linear regression model with L2 and L1 regularization to prevent overfitting problem and can interperate the relation between the taget variable and independent variables. The r-squared score for our model is:  0.0961797787407.
