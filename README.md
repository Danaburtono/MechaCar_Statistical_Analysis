#MechaCar Statistical Analysis
## Linear Regression to Predict MPG

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

The variable that provided the highest level of non-random variance to the MPG values was Vehicle Length and Ground Clearance with a p-value of 2.60e-12 and 5.21x10-8 respectively.

Is the slope of the linear model considered to be zero? Why or why not?

The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11 which is much smaller than commonly observed alpha level of 0.05. This means that the relationship between our variables and the miles per gallon are considered statistically significant and it is highly unlikely these variables have occurred due to simple random chance.

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

The predicted mpg of the MechaCar prototype shows the multiple r-squared value of 0.7149 this indicates that the model is 71% accurate. This is a relatively decent r-squared value. In some fields this would be considered a poor metric and in other fields 60% is the require minimum this is because its indicating that the variation is not predicated with a high degree of accuracy.

## Summary Statistics on Suspension Coils
The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

In the total summary,the variance of all three lots does not exceed the 100 pounds per square inch (PSI) with a variance of 62 PSI. However in the lot summary, the lots have variance metrics of 0.97, 7.47, and 170.29 respectively. Even though the manufacturing data meets the maximum requirements its clear lot 3 does not pass alone and should be further investigated. 

## T-Tests on Suspension Coils
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.

The Suspension Coils Cumulative T-test shows that all 3 lots are not statistically different from the population mean of 1500, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.

Lot 1 shows that they are not statistically different from the population mean of 1500, and the p-value is not low enough 1 for us to reject the null hypothesis.

Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis.

Lot 3 shows that they are statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis.

## Study Design: MechaCar vs Competition
An important statistical study on how the MechaCar performs against competition is beneficial but it would be more beneficial to see how MechaCar performs against in competitors overtime. Because wear-and-tear is the highest contributor to reduced MPG or the need for frequent maintenance, reduced safety, and degrading interior or exterior materials. It would be useful to see the longevity of MechaCars against its competitors. We would have to consider many metrics that are important in our evaluation such as city and highway fuel efficiency, horse power, maintenance cost, safety rating, and interior and exterior design, intial price.

We will be comparing these metrics above to competing models at other companies. The null hypothesis will be that these metrics are similar and the alternative hypothesis is that MechaCar out-preforms or under-preforms competing models of its rivals. We will be conducting a multiple linear regression. A multiple linear regression is a regression model that estimates the relationship between a quantitative dependent variable and two or more independent variables using a straight line. Comparing each variable from both MechaCar and all competitors will give a clear indication if MechaCar is out or under performing overtime. A random sample of 500 MechaCars, and 500 of each competitor will display a clear distribution of data. If outliers exist. I would increase this number to 1,000 of each type to reduce any skews that may exist in the dataset. 
