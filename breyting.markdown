Gun violence continues to impact communities across New York City, with thousands of shooting incidents reported over the past two decades. But beyond the raw numbers lies a deeper question: **Who is shooting whom and under what circumstances?**

Are young men the primary perpetrators and victims? Do these incidents follow daily or seasonal rhythms? Are certain neighborhoods consistently more affected?

Gun violence has long been a central issue in the United States, debated politically, studied socially, and felt personally. And in NYC, efforts to reduce shootings are ongoing. Programs like the [Office to Prevent Gun Violence](https://criminaljustice.cityofnewyork.us/programs/office-to-prevent-gun-violence/) work to address these issues on the ground. However, to prevent violence effectively, we also need to understand the patterns behind it.

In this project, we dive into public [NYPD shooting incident data](https://catalog.data.gov/dataset/nypd-shooting-incident-data-historic), containing information about shootings in NYC from 2006-2024, to examine how gender, age, time, and location intersect in shaping the landscape of urban gun violence.

Our guiding question is:
#### **“Who shoots whom in New York City, and how do patterns of age, gender, place, and time influence that dynamic?”**

Through all sorts of visualizations, we aim to go beyond headlines and uncover the underlying structure of these events, not to sensationalize, but to support clearer understanding, smarter prevention, and stronger public awareness.


Navigating through the website
We have structured this page in a simple “click-through” format to guide you through it. When you have read through the introduction, simply click on each navigation button at the top of this webpage in correct order and you will follow our data story.
Overview
Who: First, we will look into the demographics of the shooters and victims
When: Next, we take a look at the shootings by time
Where: The last category that we will look into is the location of the shootings
Finally, the page will take you to the conclusion section, where we will cover what we learned through this project. For those who are too curious to navigate each chapter, the conclusion can also be found below.
Tinna Sól


reword - Age Patterns in Gun Violence

Beyond gender, age plays a major role in shaping who gets involved in shootings. 
The chart below breaks down the relationship between perpetrators and victims across age groups, showing whether violence tends to happen within or across generations.

What stands out is a clear age mirroring effect: younger individuals, especially those aged 18–24 and 25–44, are both the most common perpetrators and the most frequent victims. This suggests that gun violence in NYC often occurs between individuals of similar age, rather than across generational lines.

The heatmap in **Figure 3** below lets you explore how each age group is involved on both sides of the incident.



Each row in the chart represents a group of perpetrators, and each column shows their victims. This allows us to see not just who is involved, but who is shooting whom across different age groups.

One pattern is immediately clear: Men between the ages of 18 and 44 are the most frequent perpetrators and also the most common victims. By contrast, women appear far less often in the data, whether as perpetrators or victims.

This chart brings the central pattern of NYC gun violence into sharp focus: It is concentrated within a small and specific demographic.


Where Does Gun Violence Happen?
When discussing gun violence, where it occurs is just as important as who is involved, and when it happens. In a city as large and diverse as New York, some areas experience far more incidents than others, and understanding these geographic patterns is essential for meaningful insights.

Gun violence is not spread evenly across the five boroughs. Instead, it clusters in specific neighborhoods, reflecting deeper social, economic, and structural conditions.


Hour-by-Hour: Mapping Shooting Density Over Time
Now let’s take a closer look at how time and location come together.

The animated heatmap below shows where shootings happen across NYC during different hours of the day. As the timeline moves, a clear pattern shows up, late evenings and early mornings tend to be the most active - especially in areas like Brooklyn and the Bronx.

This view helps us see that gun violence is not random. It often follows daily routines, social patterns, and the rhythms of city life as day turns into night.

Where and when shootings happen go together and both are key to prevention.

### Where Age Meets Place: Borough-Level Shooting Patterns

While total shootings per borough reveal where gun violence is most concentrated, they don't show **who** is most involved. To explore this, the boxplots below visualize the **distribution of yearly shootings by perpetrator age group within each borough** of NYC.

This set of plots offers several important insights:

- In **Brooklyn** and the **Bronx**, perpetrators aged **18–24** and **25–44** are the most frequently involved in shootings year after year. The taller boxes and longer whiskers reflect both **higher typical counts** and **greater variability**, suggesting more frequent spikes in gun violence among these age groups.
- **Minors (<18)** appear in every borough, but are particularly prominent in the Bronx and Brooklyn, where their median and range of involvement are notably higher than elsewhere.
- **Older age groups (45–64 and 65+)** consistently show **low and stable** involvement, with compressed boxplots indicating few incidents and little fluctuation across years.
- **Manhattan** and **Queens** exhibit lower yearly shooting counts across all age groups, though young adults (18–44) still stand out compared to other groups.
- **Staten Island** shows the **lowest overall involvement** in shootings, regardless of age, with especially compact boxplots and limited outliers—reinforcing its status as the least affected borough.

---

### Understanding the Chart: How to Read These Boxplots

Each subplot represents one borough, breaking down yearly shootings by perpetrator age group. These are **boxplots**, which summarize:

- **The median** (center line),
- **Interquartile range (IQR)** (the box itself),
- **Whiskers** (which indicate variability outside the IQR), and
- **Outliers** (individual dots above or below the whiskers).

This design captures both **typical patterns** and **extremes**. For instance:

- A **tall box** with long whiskers (as seen in Brooklyn’s 18–24 group) suggests years of both **high volume and volatility**.
- A **short, compressed box** (as seen in most 65+ groups) points to **consistent, low-level activity**.

By combining demographic (age) and spatial (borough) data, this visualization offers a nuanced view of how gun violence patterns shift across NYC communities. It helps identify **which age groups** are most active in which boroughs - and how that changes from year to year - informing more focused and effective interventions.

![Map of locations](/assets/agemeetplace.png)

**Figure 11:** *This set of boxplots shows the yearly distribution of shootings for different age groups in each borough. Each box summarizes the range and spread of shootings within a group. Compare across boroughs to spot differences in patterns.*

**Figure 10: Yearly Shooting Distribution by Perpetrator, Age Group, and Borough**  
_A series of boxplots showing the distribution of yearly shootings by age group across NYC boroughs._  
Boxplots are used to visualize both **central tendencies** and **variability**, including the **median, interquartile range, and outliers**. This design helps compare the consistency and intensity of age-related gun violence across boroughs. The longer “whiskers” in boroughs like Brooklyn and the Bronx reflect years of **heightened volatility**, while shorter boxes in groups like **65+** suggest relative stability and infrequency. The figure supports a nuanced spatial-demographic understanding of how age intersects with geographic gun violence trends.


### Where Age Meets Place: Borough-Level Shooting Patterns

While total shootings per borough reveal where gun violence is most concentrated, they don't show **who** is most involved. To explore this, the boxplots below visualize the **distribution of yearly shootings by perpetrator age group within each borough** of NYC.

Each subplot represents one borough and uses **boxplots** to show the yearly distribution of shootings for each age group. These plots summarize both **central tendencies**—like the median—and **variability**, including the interquartile range (IQR), the spread of data (whiskers), and any outliers. This format reveals not just how often certain age groups are involved, but how consistently or erratically their involvement changes from year to year.

Several important patterns emerge:

- In **Brooklyn** and the **Bronx**, perpetrators aged **18–24** and **25–44** are the most frequently involved in shootings year after year. The taller boxes and longer whiskers reflect both **higher typical counts** and **greater volatility**, suggesting more frequent spikes in gun violence among these age groups.
- **Minors (<18)** appear in every borough, but are especially prominent in the Bronx and Brooklyn, where their median and spread are higher than elsewhere.
- **Older age groups (45–64 and 65+)** consistently show **low and stable** involvement, with compressed boxplots indicating few incidents and little fluctuation across years.
- **Manhattan** and **Queens** exhibit lower yearly shooting counts across all age groups, though young adults (18–44) still stand out compared to others.
- **Staten Island** shows the **lowest overall involvement**, regardless of age, with particularly compact plots and few outliers—reinforcing its status as the least affected borough.

By combining demographic and geographic perspectives, this visualization offers a nuanced understanding of how gun violence patterns vary across NYC communities—helping inform targeted interventions where they are needed most.

![Map of locations](/assets/agemeetplace.png)

**Figure 11:** *Boxplots show the yearly distribution of shootings by perpetrator age group in each borough. Each box captures the typical range and variability within a group. Taller boxes and longer whiskers reflect greater volatility, while short, compressed boxes indicate stable, low-frequency trends. Compare across boroughs to identify local differences in patterns.*
