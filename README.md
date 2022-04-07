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

<img width="336" alt="total_summary" src="https://user-images.githubusercontent.com/95826875/162330262-b8a2f7a3-5b3e-4ce5-96c0-b0756ee9954e.png">

<img width="492" alt="lot_summary" src="https://user-images.githubusercontent.com/95826875/162330267-d2279248-f2f0-4caa-a53a-41d7f879d4f5.png">


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
