# MechaCar_Statistical_Analysis

# Overview

## Linear Regression to Predict MPG

<img width="862" alt="Linear Regression to Predict MPG" src="https://user-images.githubusercontent.com/95826875/162326399-48720fc9-f07f-4cbe-91a5-dde88026940a.png">

- Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

  Variables which provided a non-random amount of variance to the mpg values in the dataset are Vehicle Length and the Ground Clearance. As shown in the image above, linear regression model resulted in p-values of 2.60e-12 and 5.21e-8 respectively, suggesting that vehicle length and vehicle ground clearance have a significant impact on mpg.
  
- Is the slope of the linear model considered to be zero? Why or why not?

  The slope of the linear model cannot be considered zero as he p-Value for this model is 5.35e-11, which is much lower than even an extreme level of significance (0.05%), and thus the null hypothesis must be rejected.

- Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?



## Summary Statistics on Suspension Coils

- The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

<img width="297" alt="total_summary" src="https://user-images.githubusercontent.com/95826875/162326437-d0c9b3ed-0d62-45c8-949d-fb388b8604a2.png">

<img width="404" alt="lot_summary" src="https://user-images.githubusercontent.com/95826875/162326447-c95ff227-4e2e-4fae-a408-5a69b78015ce.png">


## T-Tests on Suspension Coils

- Briefly summarize your interpretation and findings for the t-test results. Include screenshots of the t-test to support your summary.


<img width="439" alt="T-Tests on Suspension Coils" src="https://user-images.githubusercontent.com/95826875/162326506-c52eed5e-8e91-4eaf-a0c1-2394f783ff06.png">

<img width="596" alt="T-Tests on Suspension Coils all" src="https://user-images.githubusercontent.com/95826875/162326516-88576320-8535-4e03-a3b9-821b689e2e5a.png">


## Study Design: MechaCar vs Competition

- Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.

- In your description, address the following questions:

 What metric or metrics are you going to test?
 
 What is the null hypothesis or alternative hypothesis?
 
 What statistical test would you use to test the hypothesis? And why?
 
 What data is needed to run the statistical test?
