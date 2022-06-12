# MechaCar_Statistical_Analysis

## Initial summary answers

The most significant variables in the dataset that showed a non-random effect on the MPG of the MechaCar were the Vehicle Lenth and the Ground Clearance. The p-values of these were 2.6X10-12 and 5-21-8, respectively. The intercept was also statistically significant, which would indicate that there were other factors not included in the current dataset that had an impact on the MPG of the MechCar. 
![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_1.png)

The slope of the linear model has a p-value of 5.35x10-11, which means the null hypothesis should be rejected. The relationship between the variables mentioned above and the MPG of the MechaCar are statistically signficant, as the linear model is not 0.

The model does predeict the MPG Of the MechaCar effectively as the r-squared value is 0.7149, or 71% accurate. While not as high as the client would want, it is still higher than the p-value. 

## Summary Statistics on Suspension Coills

![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_2.1.png)
![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_2.2.png)

When considering the variance of the suspension coils must not exceed 100 lbs./sq. inch, the manufacture is meeting them when the PSI is summarized (62 psi). However, when looking at the individual lots, lot 3 exceed the specification significantly (170.29 psi). 


## T-Tests on Suspension Coils
![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_3.1.png)

A review of the T-Test for the suspension coils show they are not statistically different from the population mean (.06 vs .05). 

![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_3.2.png)

The p-value for Lot 1 T-Test against the mean of 1500 is 1, again above the .05 minimum, significance level, the data is statistically similar. 

![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_3.3.png)

The p-value for Lot 2 T-Test is .06, which means the data is statistically similar. 

![This is an image](https://github.com/cwilkis/MechaCar_Statistical_Analysis/blob/main/images/Mecha_car_Deliverable_3.4.png)

The p-value for Lot 3 T-Test is .04, which is below the .05 significance level, showing this data is NOT statistically similar to 1500.

## Study Desion: MechaCar vs Competition

There are many factors consumers take into consideration when deciding which car to buy. Each buyer can have different factors being the most important, but there are usually similar "must haves". Consumers look at safety factors, gas mileage, and reliability as must haves before moving on to "wants" like heated sets, leather, and other aesthetic factors in their purchase. 

### Metrics to Test

- Highyway miles per gallon
- City miles per gallon
- Safety ratings from at least two neutral testing agencies
- Car Safety features

### Null/Alternative Hypothesis

- There is no statistical difference between MechaCar and the competition on the metrics outlined above.

### Statitical Test Used

- Sample T-Test on each metric to compare MechaCar against the competition

### Data Needed

- mileage for city and highway for MechaCar and competition model to be compared to
- list of car safety features for both
- safety ratings from independent agencies for both cars