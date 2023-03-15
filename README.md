# MechaCar_Statistical_Analysis

## Overview
This project is designed to analyze production data from 50 different prototypes of AutosRU's newest car model, the Mecha Car.  The analysis is performed using RStudio and the dplyr package. A linear regression model is created in order to predict the MPG of the Mecha Car.  Then, summary statistics and t-tests are done on the car's manufacturing data across 3 different lots.  Finally, a statistical study is designed to compare the statistics of the Mecha Car, to cars from other manufacturers.  

## Linear Regression to Predict MPG
A linear regression was performed on the data from the 50 different Mecha Car prototypes. The model analyzes vehicle length, vehicle weight, spoiler angle, ground clearance, AWD capability, and MPG from each prototype. 

Below is the results of the linear regression:

![Linear Regression](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Linear_Regression.png)

A linear regression model was then created to show to p-value and r-squared value, as shown below:

![Values](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Linear_Regression_Summary.png)

### Summary of Linear Regression Models
-Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?

-Is the slope of the linear model considered to be zero? Why or why not?

-Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?


## Summary Statistics on Suspension Coil

A summary statistics table was created to show the weight capabilities of suspension coils from all production lots, as well as each lot individually.  

Below are the results of all production lots:

![Production lots](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/All_Lots.png)

Below are the results from lots 1-3:
![Lots1-3](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lots_1-3.png)

### Analysis of Summary Statistics

-The design specifications for the MechaCar suspension coils dictate that the variance of the suspension coils must not exceed 100 pounds per square inch. Does the current manufacturing data meet this design specification for all manufacturing lots in total and each lot individually? Why or why not?

## T-Tests on Suspension Coils

I then performed t-tests on the same data in order to determine whether or not the lots were statistically different from the population mean of 1500 pounds per square inch.  This was analyzed among all of the lots together as well as each lot individually. 
Below are the results of the t-test for all lots:

![All Lots](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lots_TTest.png)


Here are the results from lots 1-3, respectively:

![Lot1](https://github.com/heatherhutchinson211/MechaCar_Statistical_Analysis/blob/main/Lot1.png)
![Lot2]()
![Lot3]()
## Study Design: MechaCar vs Competition
