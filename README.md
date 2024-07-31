# Building a linear regression model for the prediction of demand for shared bikes.
## Problem Statement:
> A US bike-sharing provider BoomBikes a Mobility Services firm has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

Essentially the company wants :

* To understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19, by creating a linear model.
* To identify the variables affecting their revenues i.e. Which variables are significant in predicting the demand for shared bikes.
* To know the accuracy of the model, i.e. How well those variables describe the bike demands
* They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Business Goal:
> You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.

## Insights
![image](https://github.com/user-attachments/assets/c7e53c76-60f6-4f09-9882-d9e46a24912e)
Detailed attribute info here.
1. The graph effectively illustrates the qualitative distribution of the data. When combined with the model's identified key predictors, these graphs enhance our confidence in the model's predictions. For the variable "season," it is evident that Category 3 (Fall) has the highest median, indicating increased demand during this season, while Category 1 (Spring) shows the lowest demand.

2. In comparison, 2019 saw a higher user count than 2018. Rental counts are fairly consistent throughout the week. There is a noticeable drop in rentals during heavy rain or snow, suggesting these weather conditions are particularly adverse. The highest rental counts occur during Clear and Partly Cloudy weather conditions.

3. Rentals peaked in September, while December saw a decrease, likely due to typical substantial snowfall during that month. Additionally, user counts are lower during holidays.

4. The "Workingday" boxplot shows that most bookings occur between 4000 and 6000, with the median user count remaining relatively stable throughout the week. There is little difference in bookings whether it is a working day or not.

## Conclusions:
1. All the positive coefficients like temp,season_Summer indicate that an increase in these values will lead to an increase in the value of cnt.
2. All the negative coefficients indicate that an increase in these values will lead to a decrease in the value of cnt.
3. From R-Sqaured and adj R-Sqaured value of both train and test dataset we could conclude that the above variables can well explain more than 79% of bike demand.
4. Coeffiencients of the variables explains the factors effecting the bike demand
5. Based on final model top three features contributing significantly towards explaining the demand are:
6. Temperature (0.493719)
7. weathersit : Pleasant (0.097303)
8. year (0.237519)

> As a result, it is clear that the variables of month, season, and weather have a big impact on predicting the demand for shared bikes.

## Recommendations
* The months - Jan , Jul , Sep , Nov , Dec should be considered by the company as they have a higher demand as compared to other months.
* With an increase in temperature the demand also increases, hence it should keep track of the weather conditions.
* During the Winter season the demand rises, hence it should be well prepared to meet the high demand
* 
## Contact
Created by [@githubusername] - feel free to contact me!
