---
layout: default
title: Trends Over Time
permalink: /where
---

##  Where Does Gun Violence Happen?

When discussing gun violence, *where* it occurs is just as important as *who* is involved. In a city as large and diverse as New York, some areas experience far more incidents than others and understanding these geographic patterns is essential for meaningful insights.

Gun violence is not spread evenly across the five boroughs. Instead, it clusters in specific neighborhoods, reflecting deeper social, economic, and structural conditions.

###  Borough Breakdown

The choropleth map below shows the total number of shootings recorded in each borough.

Two boroughs stand out: **Brooklyn and the Bronx** consistently experience significantly more shootings than Manhattan, Queens, or Staten Island.

This disparity goes beyond population differences. It reflects long-standing inequalities in areas like income, housing stability, policing, and access to community resources. These underlying conditions contribute to a higher risk of violence - and a higher burden placed on certain communities.

<iframe src="/final-project/assets/boroughmap.html" width="100%" height="600" frameborder="0"></iframe>


*Figure 3: Showing how shootings happen between boroughs*

## Hour-by-Hour: Mapping Shooting Density Over Time

Now let’s take a closer look at how time and location come together.

The animated heatmap below shows where shootings happen across NYC during different hours of the day. As the timeline moves, a clear pattern shows up, late evenings and early mornings tend to be the most active - especially in areas like Brooklyn and the Bronx.

This kind of view helps us understand how gun violence shifts throughout the day. It’s not random follows people’s routines, social activities, and the way life changes as day turns into night.

Where and when shootings happen go together and both are key to prevention.

<iframe src="/final-project/assets/hourlydensity.html" width="100%" height="600" frameborder="0"></iframe>

*Figure 3: LAGA TEXTANN*

### Where Age Meets Place: Borough level Shooting Patterns

While total shootings per borough highlight where violence is concentrated, they don’t reveal who
is most involved in each area. To uncover deeper spatial patterns, the boxplot below breaks down the **yearly distribution of shootings by age group within each borough**.

This visualization offers several key insights:

- In **Brooklyn** and the **Bronx**, the **18–24** and **25–44** age groups consistently account for the most shootings each year, with wider spreads indicating frequent spikes.
- **Younger perpetrators (<18)** are present in every borough, but particularly more visible in Brooklyn.
- **Manhattan** and **Queens** show lower, more stable counts across all age groups, suggesting fewer high-risk incidents.
- **Staten Island** consistently reports the fewest shootings across all groups, reinforcing its position as the least affected borough.

By combining geography and age group, we gain a richer understanding of the *spatial dimensions* of gun violence—helping to inform more targeted interventions where they are needed most.

![Map of locations](/assets/agemeetplace.png)

*Figure 3: LAGA TEXTANN OG NY MYND!!!*

## Forecasting NYC Shootings with Machine Learning
To go beyond visual analysis, we used a Ridge Regression model with 12 months of historical lag features to predict future shooting trends. We trained on historical monthly data and tested on the last 12 months. The model achieved a root mean squared error (RMSE) of 18.33 shootings.

As shown in the plot:

The black line shows actual data used for training.

The blue line represents actual shootings during the test period.

The red line represents the model's predicted values.

While not perfect, this method captures key trends and could serve as a basis for early-warning systems or resource planning.


## Forecasting NYC Shootings with Machine Learning
To go beyond visual trends, we applied a Ridge Regression model to forecast future shooting incidents in New York City. Ridge Regression is a linear model that includes regularization, which helps prevent overfitting, especially useful when dealing with highly correlated features like time lags.

*How the Model Works*
We transformed the raw data into a monthly time series and engineered 12 lag features, meaning the model uses the number of shootings in the previous 12 months to predict the next one. This method enables the model to learn temporal patterns such as seasonality or year-over-year trends.

We trained the model on historical monthly data and reserved the most recent 12 months as a test set. The model was implemented using a pipeline that includes feature scaling and Ridge Regression.

*Performance and Insights*
The model achieved a Root Mean Squared Error (RMSE) of 18.33 shootings, meaning that on average, its monthly prediction was off by about 18 incidents. While not perfect, the model captures major fluctuations and overall directional trends.

This approach could be a foundation for early warning systems, resource allocation, or policy planning in high-risk periods.

*Visualization*
In the plot:

The black line shows actual historical data used for training, the blue line shows actual values from the test period and the red line shows the model’s predictions for the same period.

This predictive modeling serves as a proof-of-concept that machine learning can contribute to understanding and potentially mitigating urban violence patterns over time.

![Map of locations](/assets/machinelearn.png)

*Figure 3: LAGA TEXTANN*

