# MechaCar_Statistical_Analysis

### Purpose
•	We have to analysis the production data with our knowledge of R to help the MechaCar’s manufacturing team to improve the production. Two data set has to be compared  to perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
•	We’ll also make a summary of statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots
•	We’ll be running t-tests to determine if the manufacturing lots are statistically different from the mean population.

### Result

Mechacar file is read and an RScript is written for a linear regression model to be performed on all six variables.
 r squared value. In this case, it is at 0.7022 which means that out of 100 instances, this model would approximately predict the mpg of the MechaCar correctly 70 times. So, the model would be considered effective.
 
 ![png_Mod15del1](https://github.com/Ruma-T/MechaCar_Statistical_Analysis/blob/main/Resources/Mod15del1.PNG
)


 
The suspension coil’s data is read and compared to get total summary and lot summary.
It also shows the following PSI metrics for each lot: mean, median, variance, and standard deviation.

![png_Mod15%20ch](https://github.com/Ruma-T/MechaCar_Statistical_Analysis/blob/main/Resources/Mod15%20ch.PNG)









![png_Mod15ch2](https://github.com/Ruma-T/MechaCar_Statistical_Analysis/blob/main/Resources/Mod15ch2.PNG)









Performed t-tests to determine if all manufacturing lots and each lot individually are statistically different from the population mean of 1,500 pounds per square inch.

![png_Mod15ch3](https://github.com/Ruma-T/MechaCar_Statistical_Analysis/blob/main/Resources/Mod15ch3.PNG)




### Study Design: MechaCar vs Competition
## What metric or metrics are you going to test? 
 I would like to test on horsepower.
## What is the null hypothesis or alternative hypothesis?
 Null Hypothesis is that all of the cars in the same class have the same horsepower. 
 The Alternative Hypothesis is that horsepower is  not same for all the cars.
## What statistical test would you use to test the hypothesis? And why?
I would be doing an ANOVA test to complete this analysis .
## What data is needed to run the statistical test?
horsepower (the "hp" column) will be our dependent, measured variable
number of cylinders (the "cyl" column) will be our independent, categorical variable.


