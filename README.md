# MechaCar_Statistical_Analysis
## Linear Regression to Predict MPG
* Which variables/coefficients provided a non-random amount of variance to the mpg values in the dataset?
Vehicle_length and spoiler_angle
* Is the slope of the linear model considered to be zero? Why or why not?
No because the p-value of the intercept is less than 0.05.
* Does this linear model predict mpg of MechaCar prototypes effectively? Why or why not?
Yes, the R-squared value which is about 71% of a mpg prediction will be correct while using the linear model

## Summary Statistics on Suspension Coils

![Screen Shot 2022-07-02 at 10 38 20 AM](https://user-images.githubusercontent.com/98988407/177010779-7967aad4-25dd-4c79-9112-2b90a4567e94.png)

In total summary, the variance is less than the 100 pounds requirement.

![Screen Shot 2022-07-02 at 10 38 37 AM](https://user-images.githubusercontent.com/98988407/177010795-f57f7ba2-bc37-432f-b405-09f878a330cd.png)

In lot summary, lot 1 and 2 meet the requirement while lot 3 does not.

## T-Tests on Suspension Coils
For the t-test, the p-value is not less than the significance level of 0.05, therefore the sample mean is not statistically different from the population mean of 1500 PSI. We will not reject the null hypothesis. However, the p-value of Lot 3 is statistically different from the population mean so we will reject the null hypothesis.

## Study Design: MechaCar vs Competition
* What metric or metrics are you going to test?
Upfront cost of car, maintenance cost, and safety rating.
* What is the null hypothesis or alternative hypothesis?
Null Hypothesis: Based on cost and safety rating, MechaCar's outperform competitors.
Alternative Hypothesis: Based on cost and safety rating, MechaCar's underperform competitors.
* What statistical test would you use to test the hypothesis? And why?
I would perform Multiple Linear regression since there are more than two independent variables. We would also be able to determine if the independent variables are correlated with each other as well as the relationship between each other.
* What data is needed to run the statistical test?
In order to run the statistical test we would need the cost of cars, maintenance costs, and safety ratings of both MechaCars and competitors.
