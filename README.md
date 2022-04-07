# MechaCar_Statistical_Analysis
## Overview
* The purpose of this analysis

## Linear Regression to Predict MPG
* Both vehicle length and vehicle ground clearance provided a non-random amount of variance to the mpg values in the dataset. While, vehicle weight,  AWD, and spoiler angle all have p-Values that point to a random amount of variance to mpg values.

* The slope of this linear model is not considered to be zero because of the p-value of = 0.0000000000535 which is smaller than the significance level of 0.05. Therefore, the results are statistically significant to allow the rejection of the null hypothesis.

* The linear model has a multiple r-squared value of 0.7149 and an adjusted R-squared value of that 0.6825 which means that approximately 72% to 68% of all mpg predictions can be determined by this linear model. Therefore,  the model can predict mpg of MechaCar prototypes successfully.

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/mpg_data_pvalue.png)

## Summary Statistics on Suspension Coils

* **Overview of all lots:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/total_summary.png)

* **Lot Summary:**

![goals](https://github.com/Leehudson514/MechaCar_Statistical_Analysis/blob/main/Images/lot_summary.png)

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
