# MechaCar_Statistical_Analysis

# Overview

## Linear Regression to Predict MPG

<img width="862" alt="Linear Regression to Predict MPG" src="https://user-images.githubusercontent.com/95826875/162326399-48720fc9-f07f-4cbe-91a5-dde88026940a.png">

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  Variables which provided a non-random amount of variance to the mpg values in the dataset are Vehicle Length and the Ground Clearance. As shown in the image above, linear regression model resulted in p-values of 2.60e-12 and 5.21e-8 respectively, suggesting that vehicle length and vehicle ground clearance have a significant impact on mpg.
  
- Is the slope of the linear model considered to be zero? Why or why not?

  The slope of the linear model cannot be considered zero as he p-Value for this model is 5.35e-11, which is much lower than the significance level of 0.05%, and thus the null hypothesis must be rejected.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?

  The R-squared value of this linear model is 0.7149 which shows approx 71% accuracy of this model and suggests that 71% of the time the model will predict mpg of MechaCar prototypes effectively.



## Summary Statistics on Suspension Coils

_total_summary dataframe_

<img width="336" alt="total_summary" src="https://user-images.githubusercontent.com/95826875/162330262-b8a2f7a3-5b3e-4ce5-96c0-b0756ee9954e.png">

_lot_summary dataframe_

<img width="492" alt="lot_summary" src="https://user-images.githubusercontent.com/95826875/162330267-d2279248-f2f0-4caa-a53a-41d7f879d4f5.png">

- Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

  The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Now, Lot1 and Lot2 doesn't exceed the 100 pounds per square inch whereas Lot3 exceeds the design specifications.



## T-Tests on Suspension Coils

_Summary of the t-test results across all manufacturing lots_

<img width="439" alt="T-Tests on Suspension Coils" src="https://user-images.githubusercontent.com/95826875/162326506-c52eed5e-8e91-4eaf-a0c1-2394f783ff06.png">

In the above summary of all manufacturing lots, p-value is 0.06028 which is not low enough to reject the null hypothesis. The mean of all three manufacturing lots is 1498.78, which is statistically similar to the presumed population mean of 1500.


_Summary of the t-test results across individual manufacturing lots_

<img width="596" alt="T-Tests on Suspension Coils all" src="https://user-images.githubusercontent.com/95826875/162326516-88576320-8535-4e03-a3b9-821b689e2e5a.png">

In the above summary of the individual manufacturing lots:

- p-value of Lot1 is 1 which is not lower enough than the significance level of 0.05 to reject the null hypothesis. The mean of the manufacturing Lot1 is 1500, which is the actual presumed population mean of 1500.

- p-value of Lot2 is 0.6072 which is not lower enough than the significance level of 0.05 to reject the null hypothesis. The mean of the manufacturing Lot2 is 1500.2, which is quite statistically similar to the presumed population mean of 1500.

- p-value of Lot3 is 0.04168 which is lower than the significance level of 0.05 to reject the null hypothesis. The mean of the manufacturing Lot3 is 1496.14, this sample mean and the presumed population mean are not statistically different.



## Study Design: MechaCar vs Competition
