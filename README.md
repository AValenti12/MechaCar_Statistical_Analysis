# MechaCar_Statistical_Analysis

# Overview
The purpose of this project was to review production data for insights that would help the manufacturing team.

## Linear Regression to Predict MPG (Deliverable 1)

Results:

![regressionlmfunction](https://user-images.githubusercontent.com/88061345/141659521-45040637-421b-4f3f-bba7-b4e160ef2000.PNG)




![summarylm](https://user-images.githubusercontent.com/88061345/141659534-008772ae-7c15-43bc-8710-07d820ffb19b.PNG)


- The vehicle length and ground clearance are statistically unlikely to provide random amounts of variance to the linear model. We can then say the vehicle length and ground clearance do impact the miles per gallon. 
- The p-Value is 5.35e-11 which is much smaller than the assumed significance level. (The assumed significance level is 0.05%)This means the slope of our linear model is not zero. We can then in turn, reject our null hypothesis.
- The multiple linear regression will predict 71% of the mpg observations since the R-squared is approximatly 0.71.


## Summary Statistics on Suspension Coils (Deliverable 2)

![total_summary](https://user-images.githubusercontent.com/88061345/141660022-7907b735-d68e-438b-bcff-9916c7db2a4e.PNG)

![lotsummary](https://user-images.githubusercontent.com/88061345/141660031-cb5947d9-2ed1-492a-86db-a0704f04c6ef.PNG)

 Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
 
 The overall variance for all three lots is 62.29 PSI, which meets the design specifications. Lot 1 has a variance of 0.98 PSI. Lot 2 has a variance of 7.47 PSI. Lot 3 shows a variance of 170.29. Lot 1 and 2 are below the design specification requirements. Lot 3 is outside of the design specifications.
 
 
 
 ## T-Test on Suspension Coils (Deliverable 3)
 
 ![ttest](https://user-images.githubusercontent.com/88061345/141660378-46e284bb-3a87-4017-ba54-194d2dee0c8f.PNG)

 
 P-Value for Lot 1 is 1 which is above our significance level of 0.05; fail to reject null hypothesis.
 
 P-Value for Lot 2 is 0.06 which is above our significance level of 0.05; fail to reject null hypothesis.
 
 P-Value for Lot 3 is 0.04 which is below our significance level of 0.05; reject null hypothesis.
 
 
 ## Study Design: MechaCar vs Competition
 
 Another statistical study that can be performed to determ MechCar's standing against competitors is linear regression on emessions. 
 
 Metrics used would be vehicle emissions. 
 Null Hypothesis would be MechaCar Produces equal or more emissions than competitors.
 Alternative Hypothesis would be MechaCar produces less emissions than competitors.
 T Tests can be ran between MechaCar and individual competitors to show direct comparisons.
 In order to complete this study, emission information would be needed from competitors and MechaCar.
 
