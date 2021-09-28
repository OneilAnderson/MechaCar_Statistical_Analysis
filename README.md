# MechaCar_Statistical_Analysis

## Linear Regression to Predict MPG

In this part of the analysis, we are using our knowledge of R to design a linear model that will predict the miles per gallon for the MechaCar prototypes. As we can see from the data that we analyzed, we noticed that the intercept, the vehicle length and the ground clearance all have p-values that are less than .05. This means that these categories have a significant impact on the mpg values and they provide a non-random amount of variance.Since there is a significant relationship between the mpg values and the ground clearance/ vehicle length , it's not possible for our slope to be zero. When we look at our coefficient of determination, we see that 71% of the varation of the MechaCar prototypes' mpg can be determined by the data given.

## Summary Statistics on Suspension Coils

In this part of the analysis, we are using R to create a summary statistics table. In this table, we are analyzing the suspension coli's PSI and the metrics for each lot. In total, the manufacturing lots do meet the design specification, with the PSI variance being 62. However, the individual Lot3 does not meet the requirements, with the PSI variance being at 170. 

## T-Tests on Suspension Coils

In this part of the analysis, we performed t-tests to see if there was a statistical difference between the population mean and the individual manufacturing lots plus all the lots. For the manufacturing lots grouped together, we see that the p-value is more than .05, so we fail to reject the null hypothesis. For Lot1 and Lot2, we notice that their p-values are greater than .05, so we fail to reject the null hypothesis. However, we notice that Lot3 has a p-value less than .05, so we reject the null hypothesis.

## Study Design: MechaCar vs Competition

For our Study Design ,we can use horsepower, torque, and top speed to compare the performance of the MechaCar. The alternative hypothesis for our experiment would be that there is a significant difference between the MechaCar and its competition. To perform this, we would need to collect the metrics for the MechaCar(Horsepower,Torque,Top Speed) to the competition's metrics. We would then perform t-tests on both the MechaCar and the competition. We would then analyze the p-value and if the values are more than .05, then we agree with our alternative hypothesis. If not, we would reject our null hypothesis.
