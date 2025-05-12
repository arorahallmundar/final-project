---
layout: default
title: Trends Over Time
permalink: /where
---

##  Where Does Gun Violence Happen?

When discussing gun violence, where it occurs is just as important as *who* is involved, and *when* it happens. In a city as large and diverse as New York, some areas experience far more incidents than others, and understanding these geographic patterns is essential for meaningful insights.

Gun violence is not spread evenly across the five boroughs. Instead, it clusters in specific neighborhoods, reflecting deeper social, economic, and structural conditions.

###  Borough Breakdown

The choropleth map below shows the total number of shootings recorded in each borough.

Two boroughs stand out: **Brooklyn and the Bronx** consistently experience significantly more shootings than Manhattan, Queens, or Staten Island. Looking at NYC’s most recent population data ([NYC Planning, 2023](https://www.nyc.gov/assets/planning/download/pdf/planning-level/nyc-population/population-estimates/current-population-estimates-2023-June2024-release.pdf)), shootings don’t appear to follow borough population size in a straightforward way.

This disparity likely reflects deeper, long-standing structural differences between boroughs. While we do not analyze the root causes directly in this project, factors such as economic inequality, housing conditions, and policing patterns are commonly discussed in broader research on urban violence.

<iframe src="/final-project/assets/boroughmap.html" width="100%" height="600" frameborder="0"></iframe>


**Figure 9:** *This animated heatmap visualizes the density of shootings by hour and location across NYC. Darker red areas indicate higher concentrations. Hover over each borough to see the total number of shooting incidents recorded there.*

## Hour-by-Hour: Mapping Shooting Density Over Time

Now let’s take a closer look at how time and location come together.

The animated heatmap in **Figure 10** below shows where shootings happen across NYC during different hours of the day. As the timeline moves, a clear pattern shows up, late evenings and early mornings tend to be the most active - especially in areas like Brooklyn and the Bronx.

This view helps us see that gun violence is not random. It often follows daily routines, social patterns, and the rhythms of city life as day turns into night.

Where and when shootings happen go together and both are key to prevention.

<iframe src="/final-project/assets/hourlydensity.html" width="100%" height="600" frameborder="0"></iframe>

**Figure 10:** *This animated heatmap shows how shooting density changes throughout a 24-hour cycle across NYC. Darker red areas indicate higher concentrations. Watch how intensity shifts by hour, and use the timeline to pause or scrub through different times of day*


### Where Age Meets Place: Borough level Shooting Patterns

While total shootings per borough reveal where gun violence is most concentrated, they don't show *who* is most involved. To explore this, the boxplots in **Figure 11** below visualize the **distribution of yearly shootings by perpetrator age group within each borough** of the city.

Each subplot represents one borough and uses boxplots to show the yearly distribution of shootings for each age group. These plots summarize the median (center line) and variability, including the interquartile range (IQR), the spread of data (whiskers), and any outliers (dots). This format reveals not just how often certain age groups are involved, but how consistently or irregularly their involvement changes from year to year.

This visualization offers several key insights:

- In **Brooklyn** and the **Bronx**, the **18–24** and **25–44** age groups are the most frequently involved in shootings year after year. The taller boxes and longer whiskers reflect both **higher typical counts** and **greater variability**, suggesting more frequent spikes in gun violence among these age groups.
- **Younger perpetrators (<18)** are present in every borough, but particularly more visible in in the Bronx and Brooklyn, where their median and range of involvement are notably higher than elsewhere.
- **Older age groups (45–64 and 65+)** consistently show **low and stable** involvement, with compressed boxplots indicating few incidents and little fluctuation across years.
- **Manhattan** and **Queens** show lower, more stable counts across all age groups, suggesting fewer high-risk incidents, though young adults (18–44) still stand out compared to other groups.
- **Staten Island** consistently reports the fewest shootings across all groups, with especially compact boxplots and limited outliers, reinforcing its position as the least affected borough. 

By combining geography and age group, we gain a richer understanding of how gun violence patterns shift across NYC communities - helping to inform more targeted interventions where they are needed most.

![Map of locations](/assets/agemeetplace.png)

**Figure 11:** *This set of boxplots shows the yearly distribution of shootings for different age groups in each borough. Each box captures the typical range and spread within a group. Taller boxes and longer whiskers reflect greater volatility, while short, compressed boxes indicate stable, low-frequency trends. Compare across boroughs to identify local differences in patterns.*


<p style="text-align: center;">
  <a href="{{ '/#conclusions' | relative_url }}" style="padding: 10px 20px; background-color: #d9534f; color: white; text-decoration: none; border-radius: 5px;">→ Continue to Conclusions</a>
</p>

