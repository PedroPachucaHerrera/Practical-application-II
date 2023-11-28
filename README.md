###### Practical application assignment customer report 

This report provides recommendations to our customer on what features are more important to consider in maximizing used car sales. 
for this analysis, we used a dataset from Kaggle that contained information on more than 400K used cars and used machine learning techniques we provide the below recommendations:
Analysis shows that the features that are more relevant to used car prices are:

 -  Number of cylinders: The price of the vehicle is higher when the number of cylinders is higher, and this feature is the one with a major impact on the price of the car.
 -  Transmission:  our analysis shows that this feature has the second-largest impact on the price of the car.
 -  Model, condition, and paint color also show a positive impact on the price of the car.

In contrast, our analysis shows the following features have a negative impact on the price of the car 

 - Fuel: this feature has the most negative impact on the price of the car
 - Age: this feature is the second largest feature with a negative impact on the car price 
 - Odometer: the feature also has a significant negative impact on the price of the car

This analysis was conducted using the CRISP-DM Framework and we applied 3 regression models: linear regression, Ridge, and Lasso regression.
Our models showed similar performance as shown below.

![image](https://github.com/PedroPachucaHerrera/Practical-application-II/assets/39275405/bd8968db-13a8-40e5-94ed-810ad9e7fdc2)

 
Linear regression and Ridge models show almost identical performance and Lasso regression shows slightly worse MSE, RMSE, and MAE.
Although any of those models can be used to predict car prices. We recommend using liner regression that shows the best metrics

 
