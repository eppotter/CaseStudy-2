# CaseStudy-2

## Youtube Link:

## Project Summary:

For this project, I was tasked with performing an exploratory data analysis on an employee statistic data set with the goal of identifying key factors in employee
attrition, finding important relationships between the attributes, and constructing a classification and linear regression model for select metrics.

In my analysis, I constructed two main aggregate metrics: Overall Satisfaction and Involvement Score. Overall Satisfaction is an average of Job Satisfaction,
Environment Satisfaction, Work Life Balance, and Relationship satisfaction. Involvement Score is an average of Job Involvement, Training Times Last Year, and Stock
Option Level. These two metrics were derived in order to better understand general employee satisfaction with their workplace, and the level of which an employee 
was involved and committed to their job. It was found that these two scores, along with age, were the top three identifying factors when it came to employee
attrition.


Three major relationships were found and presented in my analysis: Attrition rate and job role, satisfaction trends and demographics, and overall employee
satisfaction and employee position factors. It was found that sales representatives have the highest attrition rate, younger employees (especially males) have the
highest attrition, and jobs that pay the most and have the highest position rating are not necessarily heavily correlated with safisfaction!


In the construction of a classificaion model to predict attrition in an employee, I attempted to use a kNN approach but found that the model consistently had low 
specificity, regardless of metric combination. To solve this, I used a Naive Bayes probability-based model and constructed a model with 87.53% sensitivity and 
62.14% specificity.


To create a linear regression model to predict monthly income, I analyzed the scatter plots of each metric in comparison to monthly income and created a model with 
the three most likely candidates. I then created a loop to test the regression model performance with all combinations of three metrics, and identified a better 
model which uses Job Level, Age, and Department identifier. This model had an RMSE of 1386.75, which is well below the 3000 cutoff.


Lastly, I ran a classification and regression dataset against each of their corresponding models and included the results in this repository.
