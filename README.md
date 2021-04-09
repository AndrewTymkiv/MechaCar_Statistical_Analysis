# MechaCar Statistical Analysis
---

## Overview
The purpose of this project is to use the R programming language to perform a statistical analysis on the new MechaCars prototype. The analysis uses data from two different data sets regarding miles per gallon, and the suspension coils of the car. I used R to perform a linear regression as well as t-tests for the different production metrics.

---

## Linear Regression to Predict MPG
First, I created the code to read the csv file containing MechaCar mpg data. The next step was to perform a linear regression to see which variables had any relation to the variance of mpg values. The five different variables analyzed were vehicle length, vehicle weight, spoiler angle, ground clearance, and AWD.
- After seeing the linear regression results, I can conclude that vehicle length and ground clearance provide a non-random amount of variance to the mpg values.
- The slope of the linear model is not considered to be 0 since 2 of the independent variables (vehicle length and ground clearance) had an effect on the dependent variable (mpg).
- This linear model can effectively predict the mpg of MecharCar prototypes because of the R-squared value of 0.71.

---

## Summary Statistics of Suspension Coils
For this step, I began with loading in the csv file of the suspension coil data. I wanted to obtain the summary statistics of all cars as well as the summary for each lot of cars to get a more specific summary. 

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 PSI (pounds per square inch). Looking at the total summary, the variance is 76, which is a lot, but still under 100. However, when performing the summary by lot, it becomes evident that very little variance occurs in lot 1 and 2, but lot 3 has a variance of 220, which does not meet the design specifications. 

---

## T-Tests on Suspension Coils

