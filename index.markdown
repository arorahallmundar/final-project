---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
title: "Who Shoots Whom?"
permalink: /
---

# Introduction

Gun violence continues to impact communities across New York City, with thousands of shooting incidents reported over the past two decades. But beyond the raw numbers lies a deeper question: **Who is shooting whom and under what circumstances?**

Are young men the primary perpetrators and victims? Do these incidents follow daily or seasonal rhythms? Are certain neighborhoods consistently more affected?

Gun violence has long been a central issue in the United States, debated politically, studied socially, and felt personally. And in NYC, efforts to reduce shootings are ongoing. Programs like the [Office to Prevent Gun Violence](https://criminaljustice.cityofnewyork.us/programs/office-to-prevent-gun-violence/) work to address these issues on the ground. However, to prevent violence effectively, we also need to understand the patterns behind it.

In this project, we dive into public [NYPD shooting incident data](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8), containing information about shootings in NYC from 2006-2024, to examine how gender, age, time, and location intersect in shaping the landscape of urban gun violence.

Our guiding question is:
#### **“Who shoots whom in New York City, and how do patterns of age, gender, place, and time influence that dynamic?”**

Through all sorts of visualizations, we aim to go beyond headlines and uncover the underlying structure of these events, not to sensationalize, but to support clearer understanding, smarter prevention, and stronger public awareness. For more behind the scenes of the development of this data story, please see our [explainer Jupyter Notebook]()

---
## Navigating through the website
We have structured this page in a simple "click-through" format to guide you through it. When you have read through the introduction, simply click on each navigation button at the top of this webpage in correct order and you will follow our data story.

**Overview**
1. **Who:** First, we will look into the demographics of the shooters and victims 
2. **When:** Next, we take a look at the shootings by time
3. **Where:** Last category that we will look into is the location of the shootings 

- Finally, the page will take you to the conclusion section, where we will cover what we learned through this project. For those who are too curious to navigate each chapter, the conclusion can also be found below.

You can click the **"Start exploring"** button below to jump straight to the first section:

<p style="text-align: center;">
  <a href="{{ '/who' | relative_url }}" style="padding: 10px 20px; background-color: #d9534f; color: white; text-decoration: none; border-radius: 5px;">Start exploring</a>
</p>

---

## <a id="conclusions"></a> Conclusion: Who Shoots Whom in NYC?

Throughout this project, we’ve taken a closer look at gun violence in New York City not just in terms of numbers, but the people, places, and patterns behind those numbers.

Our main question was simple but important:  
**Who shoots whom in New York City, and how do patterns of age, gender, place, and time influence that dynamic?**
### What We Found

- **Men are at the center of gun violence in NYC**, making up over **97% of identified shooters** and over **90% of victims** in the data. This means that when a shooting occurs, it is almost always a man pulling the trigger, and usually, a man on the receiving end.
- The most frequent dynamic is **male-on-male violence**, highlighting that the issue is largely concentrated within a specific demographic group.
- The two largest age groups are **18–24** and **25–44**. These groups are nearly equal in size and together they account for approximately **64% of all perpetrators** and around **81% of victims**. This reinforces the pattern of peer-to-peer gun violence among young adult men in NYC.
- **Shootings happen mostly at night**, especially between 10 PM and 2 AM and this is especially true for younger age groups.
- **Place matters**: the Bronx and Brooklyn see more incidents than other boroughs.
- **There’s a seasonal rhythm**, with shootings peaking in the summer particularly among younger males.
- **The COVID-19 pandemic disrupted previous trends** - shootings spiked in 2020 after years of decline.  
  [Source: NYT, 2021](https://www.nytimes.com/2021/05/14/nyregion/shootings-nyc-covid.html)

These patterns show us that gun violence isn’t random. It follows rhythms, shaped by age, gender, time of day, the seasons, and where people live and move around. Understanding those patterns helps us ask better questions, and maybe even find better solutions.

We used data, maps, and interactive charts to make the story more accessible, not just for researchers or policymakers, but for anyone who wants to understand what’s happening in their city. Because behind every data point is a person — and behind every pattern, a chance to change it.

To tie these findings together, we zoomed in on the group driving most of the incidents: males under 45, **Figure 12** below illustrates this comparison. This includes both young perpetrators (<25) and adults aged 25–44, who together make up the bulk of gun-related activity in NYC.

<iframe src="/final-project/assets/youngmalelocate.html" width="100%" height="600" frameborder="0"></iframe>

**Figure 12:** *This interactive heatmap shows the density of shootings involving young male perpetrators under 45, across both time of day and borough. Use the color scale to interpret intensity, darker areas indicate more incidents. Hovering over the chart reveals the exact number of incidents and the corresponding hour. This view combines age, time, and location into one visualization, helping uncover where and when violence is most concentrated in the relevant age group.*

A closer look at when and where these incidents happen shows clear patterns, Brooklyn and the Bronx remain the key hotspots, and evenings through early mornings are when activity surges. The heatmap below illustrates how time and place combine to reveal where violence is most concentrated for these groups.

This kind of insight goes beyond surface-level stats, it helps pinpoint where resources, outreach, and prevention efforts might be most effective.

---

## Credits & Sources

### References

1. New York City Police Department. (n.d.). *NYPD Shooting Incident Data (Historic)*. Retrieved from [https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8](https://data.cityofnewyork.us/Public-Safety/NYPD-Shooting-Incident-Data-Historic-/833y-fsy8)
2. New York Times (2021). *Shootings in NYC Doubled in 2020*. Retrieved from [https://www.nytimes.com/2021/05/14/nyregion/shootings-nyc-covid.html](https://www.nytimes.com/2021/05/14/nyregion/shootings-nyc-covid.html)
3. Everytown for Gun Safety (2021). *Guns and Violence Against Women*. Retrieved from [https://everytownresearch.org/report/guns-and-violence-against-women/](https://everytownresearch.org/report/guns-and-violence-against-women/)
4. NYC Planning (2023). *Current Population Estimates: June 2024 Release*. Retrieved from [https://www.nyc.gov/assets/planning/download/pdf/planning-level/nyc-population/population-estimates/current-population-estimates-2023-June2024-release.pdf](https://www.nyc.gov/assets/planning/download/pdf/planning-level/nyc-population/population-estimates/current-population-estimates-2023-June2024-release.pdf)


### Team members
- Áróra Hallmundardóttir - s242693
- Nanna Kristín Bjarnadóttir - s243949
- Tinna Sól Björvinsdóttir -s242744

**Notebook:** [Link to Jupyter Notebook coming soon]

---

