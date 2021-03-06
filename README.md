# MechaCar_Statistical_Analysis

## Project Overview:

The goal of this project was to use R to build a statistical analysis of MechaCar vehicles and compare them to competitors.

## Resources:

**Main Challenge File:** [MechaCarChallenge](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/MechaCarChallenge.RScript.R)

**Software:** RStudio and R


## Linear Regression to Predict MPG:

![Deliverable 1](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%201.png)

The figure above shows the summary of the linerar regression for the MecaCar mgp.

*	Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
	*	When taking a look at the variables/coefficients. The vehicle length and the vehicle ground clearance are most likely to provide non-random amounts of variance to the mpg values in the dataset. Conversely, the vehicle weight, spoiler angle, and the AWD indicate a random amount of variance due to the p-values.  
*	Is the slope of the linear model considered to be zero? Why or why not?
	*	The slope would be condidered as zero since it is a very small decimal.  
*	Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
	* The linear model has a r^2 value of 0.7149. This means that roughly 71% of all mpg predictions will be determined by this model. In summation, this model does predict mpg of MechaCar prototypes effectively. 


## Summary Statistics on Suspension Coils:

Total Summary:
![Deliverable 2.1](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%202.1.png)


Lot_Summary:
![Deliverable 2.2](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%202.2.png)

*	The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
	*	When looking at the overally total summary we can see that the variance for all manufacturing lots is ~62.3 which is below the thershold for the design specification of the suspension coils.
	*	Lots 1 & 2 seem to have a small amount of variance at 0.98 and 7.47.respectivly. However, with Lot 3 we see a variance of 170.29 which is well over the design specification threshold.
	*	The overall variance is skewed by the two small variance of Lots 1 & 2. As you can see in the charts above, only Lots 1 & 2 meet the design specifications for the suspension coils.


## T-tests on Suspension Coils:

T-test for All Lots:
![Deliverable 3.1](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.1.png)
*	We can see that the p-value for all lots is 0.06 (> than the common significance level of 0.05). The mean of all lots is statistically similar to the population mean of 1500.

T-test for Lot 1:
![Deliverable 3.2](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.2.png)
*	The p-value for Lot 1 is 1. This is not considered statistically significant. Lot 1 is reflective of the population mean.

T-test for Lot 2:
![Deliverable 3.3](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.3.png)
*	The p-value for Lot 2 is 0.61. This is not considered statistically significant. Lot 2 is reflective of the population mean.

T-test for Lot 3:
![Deliverable 3.4](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.4.png)
*	The p-value for Lot 3 is 0.042 This is considered statistically significant as it is belove the common significance level of 0.05. This lot needs to be looked at more closely as it does not appear to meet quality standards.

## Study Design: MechaCar vs Competition:

*	Write a short description of a statistical study that can quantify how the MechaCar performs against the competition. In your study design, think critically about what metrics would be of interest to a consumer: for a few examples, cost, city or highway fuel efficiency, horse power, maintenance cost, or safety rating.
	*	What metric or metrics are you going to test?
		*	One way to compare against competition would be to take a look at both the safety rating and the horse power in order to determine how safe MechaCar is vs other competitor vehicles.
	*	What is the null hypothesis or alternative hypothesis?
		*	The null hypothesis would be that the mean of the safety rating is zero. The alternative hypothesis would be that the mean of the safety rating is not zero.
	*	What statistical test would you use to test the hypothesis? And why?
		*	I would probably look into running a multiple linear regression summary to show how the variousl variables impact the safety ratings of MechaCar vs other vehicles.
	*	What data is needed to run the statistical test?
		*	I would need a sample for both MechaCar along with a competitor or a set of competitors depending on what you wanted to compare to. This dataset would need both safety ratings and the horse power.
