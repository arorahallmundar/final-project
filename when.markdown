---
layout: default
title: "Shootings by Time"
permalink: /when
---

## When Do Shootings Happen?

So far, we've looked at who is most involved in gun violence in NYC and who they target. But timing matters too.

Understanding who is involved in gun violence is only part of the story, when these incidents occur adds another important dimension. By looking at time-based patterns, we begin to uncover how social rhythms, daily routines, seasons, and even major societal events influence the likelihood of violence.

In this section, we explore three different time scales: 
- **Hour of Day** - When are shootings most likely to occur during a 24-hour period?
- **Yearly Trends** - How has the overall volume of gun violence changed over time?
- **Seasonal Patterns** - Are some months consistently more violent than others?

Together, these views help reveal the deeper structure of time in New York City’s gun violence.

### Time of day

We begin with a breakdown of shootings by hour of day, separated by gender and age group of the perpetrator. This chart helps us understand how the city’s daily rhythm intersects with violent incidents.

<iframe src="/final-project/assets/shootings_by_hour.html" width="100%" height="600" frameborder="0"></iframe>

**Figure 5:** *This interactive chart shows the number of shootings by hour of the day, filtered by the perpetrator’s gender and age group. Use the legend in the upper-right corner to click on specific age groups to select/deselect them.*

One group dominates the late-night activity: young men aged 18–24. Their involvement in shootings peaks during the evening and early morning hours, aligning with times of increased social activity, reduced visibility, and greater exposure to risky environments.

In contrast, shootings involving women or older individuals are relatively rare and show a much flatter distribution across the day. Their trends are not as tightly tied to nighttime hours, suggesting different social contexts and circumstances.

These timing patterns reflect deeper social dynamics, offering potential clues for more informed prevention efforts and community-based interventions

### Yearly trends

Zooming out, we examine how gun violence has evolved over the last two decades. The chart below aggregates incidents per year and reveals a few striking patterns.

![Bar chart gender](/assets/yearlytrends.png)

**Figure 6:** *This bar chart displays the total number of shooting incidents each year, with a dotted line capturing the overall trend. You can also see a vertical line marking the beginning of COVID-19 in 2020*

Throughout much of the 2010s, shootings steadily declined - but then came an abrupt reversal in 2020, with a sharp spike during the first year of the COVID-19 pandemic.

This jump wasn’t isolated to NYC. Cities across the U.S. experienced a similar trend, likely tied to pandemic-related stress, economic insecurity, and strained public institutions. In NYC, shootings surged by nearly 100% in 2020 compared to the year before, a rise widely documented in local and national media (New York Times, 2021).

Even as other forms of crime remained low, gun violence soared - showing how external shocks can dramatically alter urban safety dynamics.

### Seasonal trends

Lastly, we take a closer look at seasonality by examining the average number of shootings per month, again segmented by gender and age group.
A clear pattern emerges: the summer months especially June, July, and August consistently experience the highest levels of gun violence. This spike is particularly pronounced among young male perpetrators.

The reasons likely include a combination of social and environmental factors: warmer weather means more people are outside, schools are out, structured programs may be on pause, and tensions can escalate during longer, unstructured days.

This cyclical pattern reinforces a broader point: gun violence in NYC isn’t just about who or where, but also about when. Timing shapes risk, and understanding these rhythms can support more effective and targeted responses.

<iframe src="/final-project/assets/seasonal.html" width="100%" height="600" frameborder="0"></iframe>

**Figure 7:** *This interactive visualization highlights average monthly shootings, broken down by age and gender of the perpetrator. Use the dropdown and/or legend to filter and explore patterns for different groups.*

## Forecasting NYC Shootings with Machine Learning
To go beyond visual trends, we applied a Ridge Regression model to forecast future shooting incidents in New York City. Ridge Regression is a linear model that includes regularization, which helps prevent overfitting, especially useful when dealing with highly correlated features like time lags.

*How the Model Works*

We transformed the raw data into a monthly time series and engineered 12 lag features, meaning the model uses the number of shootings in the previous 12 months to predict the next one. This method enables the model to learn temporal patterns such as seasonality or year-over-year trends.

We trained the model on historical monthly data and reserved the most recent 12 months as a test set. The model was implemented using a pipeline that includes feature scaling and Ridge Regression.

*Performance and Insights*

The model achieved a Root Mean Squared Error (RMSE) of 10.94 shootings, meaning that on average, its monthly prediction was off by about 11 incidents. While not perfect, the model captures major fluctuations and overall directional trends.

This approach could be a foundation for early warning systems, resource allocation, or policy planning in high-risk periods.

![Map of locations](/assets/machinelearn.png)

**Figure 8:** *A machine learning forecast of monthly shootings in NYC using Ridge Regression. The black line shows the training data (actual historical data), blue indicates actual shootings from the test period, and red shows the model's predictions for the same period.*

This predictive modeling serves as a proof-of-concept that machine learning can contribute to understanding and potentially mitigating urban violence patterns over time.

<p style="text-align: center;">
  <a href="{{ '/where' | relative_url }}" style="padding: 10px 20px; background-color: #d9534f; color: white; text-decoration: none; border-radius: 5px;">→ 3. Where?</a>
</p>
