# mechacar_statistical_analysis
## Linear Regression to Predict MPG

![linear regression](https://github.com/Tyfox1206/mechacar_statistical_analysis/blob/main/images/linear%20regression.PNG)

Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
mpg, vehicle lenght, and ground cleareance provided a non-random amount of variance. 

Is the slope of the linear model considered to be zero? Why or why not?
The slope is considered to be non-zero. while some of coefficients are close to zero there are none that are zero. 

Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
yes the r squared is 0.7149, this shows that dataset is effective.

## Summary Statistics on Suspension Coils
![total summary](https://github.com/Tyfox1206/mechacar_statistical_analysis/blob/main/images/total_summary.PNG)
shows mean, median, variance, and SD of all the lots.

![lot summary](https://github.com/Tyfox1206/mechacar_statistical_analysis/blob/main/images/lot_summary.PNG)
break down of each lot showing mean, median, variance, and SD of all the lots

The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?
the total variance is 62 which is less then 100 so the total meats the condition. Lot 1 and 2  are also below 100 at 0.9 and 7.4 respectively while lot 3 is at 170 which over the 100 variance requirement.

## T-Tests on Suspension Coils

For all the lots the p-value is above the normal significance level so the two means are similar. Likewise lots 1 and 2 are also above the normal significance level so the means are similar. only lot 3 is below the normal significance level so the means are different. 
