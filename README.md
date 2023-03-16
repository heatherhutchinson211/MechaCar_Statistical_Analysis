# MechaCar_Statistical_Analysis

## Overview
This project is designed to analyze production data from 50 different prototypes of AutosRU's newest car model, the Mecha Car.  The analysis is performed using RStudio and the dplyr package. A linear regression model is created in order to predict the MPG of the Mecha Car.  Then, summary statistics and t-tests are done on the car's manufacturing data across 3 different lots.  Finally, a statistical study is designed to compare the statistics of the Mecha Car, to cars from other manufacturers.  

## Linear Regression to Predict MPG
A linear regression was performed on the data from the 50 different Mecha Car prototypes. The model analyzes vehicle length, vehicle weight, spoiler angle, ground clearance, AWD capability, and MPG from each prototype. 

Below are the results of the linear regression:

![Linear Regression](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Linear_Regression.png)

A linear regression model was then created to show to p-value and r-squared value, as shown below:

![Values](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Linear_Regression_Summary.png)

### Analysis of Linear Regression Models
**-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?**

Since we used a 95% confidence interval, any variable with a variance less than 0.5 would provide non-random and statistically significant variance.  In this model, mpg, vehicle length and ground clearance were statistically significant.

**-Is the slope of the linear model considered to be zero? Why or why not?**

Although the slopes of osme of the variables were close to 0, none of them were exactly 0, so the slope of the linear model would not be considered 0. 

**-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?**

Considering the data provided, the R-squared value signifies an effective prediction of mpg of the MechaCar.  Still, there may be other factors that would contribute to the mpg of the car, that were not included in the dataset. 

## Summary Statistics on Suspension Coil

A summary statistics table was created to show the weight capabilities of suspension coils from all production lots, as well as each lot individually.  

Below are the results of all production lots:

![Production lots](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/All_Lots.png)

Below are the results from lots 1-3:
![Lots1-3](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lots_1-3.png)

### Analysis of Summary Statistics

**-The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?**

As far as all lots combined, the variance came out to be about 62.  Since 62<100, this manufacturing data meets the design specifications.  However, when analyzing each lot on its own, it is clear that lot 3 does not meet the specifications as its variance is 170.  Lot 1 had a variance of about 1, and lot 2 had a variance of 7; therefore, lots 1 and 2 definitely meet the design specifications. 


## T-Tests on Suspension Coils

I then performed t-tests on the same data in order to determine whether or not the lots were statistically different from the population mean of 1500 pounds per square inch.  This was analyzed among all of the lots together as well as each lot individually. 
Below are the results of the t-test for all lots:

![All Lots](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lots_TTest.png)


Here are the results from lots 1-3, respectively:

![Lot1](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lot1.png)
![Lot2](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lot2.png)
![Lot3](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lot3.png)

It follows from the data that Lots 1 and 2 are statistically significant as they fall within the confidence interval; however, again lot 3 seems to be insignificant. 

## Study Design: MechaCar vs Competition

In the future, it would be beneficial to compare the results of the Mecha Car with cars from competing manufacturers. This analsis could include the above data, as well as highway fuel efficiency, city fuel efficiency, cost, and safety ratings. 

**-What metric or metrics are you going to test?**

I would test the fuel efficiency, cost, safety rating, car length, mpg, and ground clearance of each car.  

**-What is the null hypothesis or alternative hypothesis?**

The null hypothesis would be that if you analyzed the data of each car based on the above factors, no car would be better in quality than another.  The alternative hypothesis would be that if you analyzed the data of each car based on the above factors, one car would be better in quality than the others. 

**-What statistical test would you use to test the hypothesis? And why?**

I would again create a linear regression as well as summary statistics and t-tests to compare models of cars from various manufacturers. 

**-What data is needed to run the statistical test?**

The data that is needed is fuel efficiency, cost, safety rating, car length, mpg, and ground clearance of the MechaCar as well as the other various cars.  There should be a sample of at least 50 in order to provide accurate results. 
