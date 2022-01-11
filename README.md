# MechaCar_Statistical_Analysis

# Purpose
The goal of this challenge was to use R to discover which variables predict the MPG for vehicle prototypes, collect summary statistics on the PSI of suspension coils, determine if manufacturing lots are statistically different from the mean population, and finally design a study to compare the MechaCar performance against vehicles from other manufacturers.

# Linear Regression to Predict MPG

![Linear Regression to Predict MPG](https://user-images.githubusercontent.com/88119288/149023652-ce16ffe2-fc5d-42c2-b5a0-4f987c496151.PNG)

The variables provided show a non-random effect to the mpg values in the dataset.

The slope of the linear model would not be considered to be zero. The p-value is 5.35E-11, this demonstrates that the results of the analysis are significant and so, the null hypothesis must be rejected.

This model does predict the mpg of the MechaCar prototype since the R-squared value is .7149 indicating that the model is 71% accurate.

# Summary Statistics on Suspension Coils

The variance of all manufacturing lots in total is 62.29 which meets the specification of the design specifications.
![Deliverable 2-Total Summary](https://user-images.githubusercontent.com/88119288/149025302-327ebaca-e676-4a0d-8ba5-f4f3d109f529.PNG)

Lots 1 and 2 meet the design specification, since the variance, 0.98 and 7.47 are less than 100; as for lot 3, it does not meet the specifications of the design since the variance is 170.2.
![Deliverable 2- Lot Summary](https://user-images.githubusercontent.com/88119288/149025320-ea8a343b-33c6-44f9-9e0a-e34cdb3766d0.PNG)

# T-Test Results

T-test:
![T-test](https://user-images.githubusercontent.com/88119288/149026058-66cd56a6-aa6e-4449-bd1d-fec0526aea74.PNG)

Lot 1:
![L1](https://user-images.githubusercontent.com/88119288/149026066-e87bcaa6-31fa-4bf9-9b0c-a88dc0163afd.PNG)

Lot 2:
![L2](https://user-images.githubusercontent.com/88119288/149026081-c3b8d4d3-0e8e-4a42-b4ee-16c9d5db51e2.PNG)

Lot 3:
![L3](https://user-images.githubusercontent.com/88119288/149026090-c41b49d3-1a22-47c5-9d0d-d86664cf4291.PNG)
 
Lot 1 T-test shows that they are not statistically different from the population mean, and the p-value (1) is not low enough to reject the null hypothesis.

Lot 2 T-test shows that they are not statistically different from the population mean, and the p-value (.607) is not low enough to reject the null hypothesis.

Lot 3 T-test shows that they are slightly statistically different from the population mean, with a low p-value (0.0417) to reject the null hypothesis.

# Study Design: Mechacar vs Competition

Metrics: I would design a statistical study to analyze the performance of MechaCar's mpg against the competition.

Null Hypothesis: MechaCar vehicles do not have statistically significant higher safety ratings in comparison to other vehicles.

Alternate Hypothesis: MechaCar vehicles do have statistically significant higher safety ratings than other vehicles.

Statistical Test:I would use a two-sample T-test to for this analysis since that allows us to test the relationship in both directions.

Data: For the analysis, the data needed to run the statistical test would be prices of competing vehicles as well as their safety ratings for a better comparison.
