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
*	Insert text

T-test for Lot 1:
![Deliverable 3.2](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.2.png)
*	Insert text

T-test for Lot 2:
![Deliverable 3.3](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.3.png)
*	Insert text

T-test for Lot 3:
![Deliverable 3.4](https://github.com/matthubb17/MechaCar_Statistical_Analysis/blob/main/Module%2015_Deliverable%203.4.png)
*	Insert text




