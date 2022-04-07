# MechaCar_Statistical_Analysis
## Overview
* The purpose of this analysis was to use R to perform a statistical analysis on data that looked at the MechaCar prototype.

## Linear Regression to Predict MPG
* Both vehicle length and vehicle ground clearance provided a non-random amount of variance to the mpg values in the dataset. While, vehicle weight,  AWD, and spoiler angle all have p-Values that point to a random amount of variance to mpg values.

* The slope of this linear model is not considered to be zero because of the p-value of = 0.0000000000535 which is smaller than the significance level of 0.05. Therefore, the results are statistically significant to allow the rejection of the null hypothesis.

* The linear model has a multiple r-squared value of 0.7149 and an adjusted R-squared value of that 0.6825 which means that approximately 72% to 68% of all mpg predictions can be determined by this linear model. Therefore,  the model can predict mpg of MechaCar prototypes successfully.

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/mpg_data_pvalue.png)

## Summary Statistics on Suspension Coils

* **Overview of all lots:**
* The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch.

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png)

* **Lot Summary:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

* When looking at overall variance of the 3 lots, the coil variance is at 62.29 PSI, which is within the standard of the 100 PSI requirement.
* Additonally, when deep diving into the individual overview of the lots we can see that lot 3's variance sticks out as a red flag. The data shows that their variance is sitting at 170.29 PSI which is higher than the 100 PSI requirement and causing the overall variance PSI to shoot up.

## T-Tests on Suspension Coils

* **Total t-test overview:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/total_t-test.png)

* The results of the total t-test show that there is a p-value of 0.06028 which is slightly higher than the significance level of 0.05. Therefore, there is not enough evidence to reject the null hypothesis and that the presumed population of 1500 is statisically similar to the true mean of 1498.78.

* **Lot 1 t-test:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/lot1_t-test.png)

* **Lot 2 t-test:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/lot2_t-test.png)

* **Lot 3 t-test:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/lot3_t-test.png)

* After taking a microview at the lots individually, we can see that lot 1 and 2 are in similar scenarios where we cannot reject the null hypthosesis with both of their p-values sitting above the significance level.
* Lot 3 however is telling a different story, their p-value is at 0.04168 which is lower than the significance level of 0.05. This statistically means that we need to reject the null hypothesis and assume that the sample mean and the presumed population mean are different.

## Study Design: MechaCar vs Competition
* To determine how MechaCar is performing against their competition, we will collect data on multiple levels to determine what features consumers value most and then collect data on the top 3 features consumers value to determine where MechaCar can improve their product offerings by identifying opportunities where the competition is out pacing them and to determine if those metrics are directly linked to greater sales. 
* Firstly, surveys need to be conducted to determine which metrics are of the highest importance to consumers today.
* Survey on Consumer Metrics:
    * cost
    * fuel efficiency
    * fuel type
    * horse power
    * maintenance cost
    * safety rating
    * warranty
* Second, once the top consumer metrics have been identified, we will finish our hypthesis:
   * Null Hypothesis: MechaCar is performing above its competition of key consumer metrics.
   * Alternative Hypothesis: MechaCar is NOT performing above its competition of key consumer metrics.

* Thirdly, Quanatative industry data will then be extracted and cleaned on the key consumer metricss to determine how MechaCar compares from public sources.

* Lastly, once the data is ready for analysis there will be a liner regression test performed on all metrics to determine if there is a correlation between higher sales and higher performance of key consumer metrics.


