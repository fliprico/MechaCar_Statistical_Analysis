# MechaCar_Statistical_Analysis

## Overview

In this challenge, we are going to be using our knowledge of R Studio to

* Perform multiple linear regression analysis to identify which variables in the dataset predict the mpg of MechaCar prototypes.
* Collect summary statistics on the pounds per square inch (PSI) of the suspension coils from the manufacturing lots.
* Run t-tests to determine if the manufacturing lots are statistically different from the mean population.
* Design a statistical study to compare vehicle performance of the MechaCar vehicles against vehicles from other manufacturers. For each statistical analysis, you’ll write a summary interpretation of the findings.

## Linear Regression to Predict Miles per Gallon (MPG)

From the summary statics obtained on Linear regression two parameters vehicle length with a p-value of 260e-12 and ground clearance with a p-value of 5.21e-8 contributes to non-random amounts of variance as applied to the mpg values.

The slopes of the variables are shown to be non-zero even though some are close to zero

The model seems to be good predictive power for the MPG as the squared value of r is 0.7149 Coefficients: vehicle length: 6.267 vehicle weight: .001 spoiler angle: .069 ground clearance: 3.546 AWD: -3.411

## Summary Statistics on Suspension Coils

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.
The design specs are respected for all manufacturing lots in total with a global variance of 62.3 psi.
On the lot level, Lot 1 and Lot 2 are into specs with respectively variances of 0.98 and 7.5 psi. The Lot 3 is out of specs with a variance of 170.3 psi.

## T-Test on Suspension Coils

In the first t-test, the sample mean is not statistically different from the population mean of 1500 PSI with a p-value of 0.06. However, when t-tests are done on the individual lots, we can see that, lots 1 and 2 are not statistically different from the population mean with p-values of 1 and 0.6 respectively, lot 3 has a mean which is statistically different from the population mean with a p-value of 0.04.

1. T-test for Lot 1 p-value = 1

![T-Test1](https://user-images.githubusercontent.com/111805716/213970762-5e5172a5-9b29-4bc8-ae26-7efb5a0ac64a.png)

2. T-test for Lot 2 p-value = .6072

![T-Test2](https://user-images.githubusercontent.com/111805716/213970884-77289fb0-dea3-4f90-9fd9-e5016f85e83d.png)

3. T-test for Lot 3 p-value = .04168

![T-Test3](https://user-images.githubusercontent.com/111805716/213970931-5b9e9ce6-644e-47fc-a1d7-96c9ad3f171d.png)

## Study Design: MechaCar vs Competition

For us to evaluate the performance of the MechaCar against the competition, it is essential to assess several other parameters that could be of interest to our client base. These variables include cost, city and highway fuel efficiency, horsepower, safety rating, and carbon waste output.

In our case the null hypothesis would be: each performance metrics is statistically similar between the MechaCar prototype and all vehicle from the other manufacturers.

Multiple linear regression statistical summary would be best metrics to show how the variables impact the safety ratings for MechaCar and their competitors.

For us to generate comprehensive statistical tests, we would need the cost, fuel efficiency, horsepower, safety rating, and carbon waste output data from the MechaCar as well as the MechaCar's competitors.




