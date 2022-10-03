# MechaCar Statistical Analysis
## Linear Regression to Predict MPG

The variable that provided the highest level of non-random variance to the MPG values was Vehicle Length and Ground Clearance with a p-value of 2.60e-12 and 5.21x10-8 respectively.

![Screen Shot 2022-10-02 at 6 12 58 PM](https://user-images.githubusercontent.com/107026442/193485744-528f2d4b-af6d-4838-8313-24c4503cc018.png)

The slope of the linear model can not be considered to be zero, as the p-value of 5.35x10-11 which is much smaller than commonly observed alpha level of 0.05. This means that the relationship between our variables and the miles per gallon are considered statistically significant and it is highly unlikely these variables have occurred due to simple random chance.

![Screen Shot 2022-10-02 at 6 14 23 PM](https://user-images.githubusercontent.com/107026442/193485809-16ec41a2-bfdc-44db-b120-4a3874a83088.png)


The predicted mpg of the MechaCar prototype shows the multiple r-squared value of 0.7149 this indicates that the model is 71% accurate. This is a relatively decent r-squared value. In some fields this would be considered a poor metric and in other fields 60% is the require minimum this is because its indicating that the variation is not predicated with a high degree of accuracy.

<img width="570" alt="Screen Shot 2022-10-01 at 4 15 50 PM" src="https://user-images.githubusercontent.com/107026442/193485894-6bd46ed1-1735-4134-a827-b2a5b1e93727.png">


## Summary Statistics on Suspension Coils

In the total summary,the variance of all three lots does not exceed the 100 pounds per square inch (PSI) with a variance of 62 PSI. However in the lot summary, the lots have variance metrics of 0.97, 7.47, and 170.29 respectively. Even though the manufacturing data meets the maximum requirements its clear lot 3 does not pass alone and should be further investigated. 

<img width="433" alt="Screen Shot 2022-10-01 at 5 09 32 PM" src="https://user-images.githubusercontent.com/107026442/193486002-65daa41e-6139-4cbe-8b9b-1bc1153c10a7.png">

<img width="433" alt="Screen Shot 2022-10-01 at 5 10 40 PM" src="https://user-images.githubusercontent.com/107026442/193486006-fa39a6a1-de90-4a52-be07-520ed09d9250.png">


## T-Tests on Suspension Coils
Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.



The Suspension Coils Cumulative T-test shows that all 3 lots are not statistically different from the population mean of 1500, and the p-value is not low enough (0.0603) for us to reject the null hypothesis.

<img width="502" alt="Screen Shot 2022-10-01 at 6 33 42 PM" src="https://user-images.githubusercontent.com/107026442/193486044-f72d6c73-da78-4dd1-a44c-71354e9d3e6a.png">


Lot 1 shows that they are not statistically different from the population mean of 1500, and the p-value is not low enough 1 for us to reject the null hypothesis.

<img width="542" alt="Screen Shot 2022-10-01 at 6 33 51 PM" src="https://user-images.githubusercontent.com/107026442/193486049-dbaa843c-dd0b-48f9-81c9-4fec386ab164.png">


Lot 2 shows that they are not statistically different from the population mean, and the p-value is not low enough (0.6072) for us to reject the null hypothesis.

<img width="539" alt="Screen Shot 2022-10-01 at 6 34 00 PM" src="https://user-images.githubusercontent.com/107026442/193486055-548130a0-b5b7-4063-aa03-2993eedeadf5.png">


Lot 3 shows that they are statistically different from the population mean, and the p-value is just low enough (0.0417) for us to reject the null hypothesis.

<img width="532" alt="Screen Shot 2022-10-01 at 6 34 10 PM" src="https://user-images.githubusercontent.com/107026442/193486066-cbefad6e-9011-4815-ac41-913281d0ee55.png">


## Study Design: MechaCar vs Competition
An important statistical study on how the MechaCar performs against competition is beneficial but it would be more beneficial to see how MechaCar performs against in competitors overtime. Because wear-and-tear is the highest contributor to reduced MPG or the need for frequent maintenance, reduced safety, and degrading interior or exterior materials. It would be useful to see the longevity of MechaCars against its competitors. We would have to consider many metrics that are important in our evaluation such as city and highway fuel efficiency, horse power, maintenance cost, safety rating, and interior and exterior design, intial price.

We will be comparing these metrics above to competing models at other companies. The null hypothesis will be that these metrics are similar and the alternative hypothesis is that MechaCar out-preforms or under-preforms competing models of its rivals. We will be conducting a multiple linear regression. A multiple linear regression is a regression model that estimates the relationship between a quantitative dependent variable and two or more independent variables using a straight line. Comparing each variable from both MechaCar and all competitors will give a clear indication if MechaCar is out or under performing overtime. A random sample of 500 MechaCars, and 500 of each competitor will display a clear distribution of data. If outliers exist. I would increase this number to 1,000 of each type to reduce any skews that may exist in the dataset. 
