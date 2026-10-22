# Insurance Portfolio Data Analysis

**Tools:** Microsoft Excel | PivotTables | PivotCharts | Interactive Dashboard

<img width="1241" height="631" alt="image" src="https://github.com/user-attachments/assets/e042ac97-d9ae-477f-8025-bf9b4d7831ae" />

## Project Overview

This project is an initial exploration of a simulated insurance dataset containing 10,000 policyholders.

Rather than starting with a specific hypothesis, I wanted to get a better understanding of the data, identify any interesting patterns, and find potential areas worth investigating further.

<img width="1056" height="463" alt="image" src="https://github.com/user-attachments/assets/4b8bac5a-f64f-4705-8847-eaf77dda67da" />

Using Excel, I explored how insurance policies and claims were distributed across different policy types, age groups and genders.

I then created an interactive dashboard to bring the information together and make it easier to explore.

The aim wasn't to draw definitive conclusions, but to see what the data could tell me and what questions might be worth asking next.



## 1. Exploring Policy Distribution

After cleaning the dataset, I decided to create an AgeGroup column. Grouping policyholders into age brackets would make it easier to compare demographics and identify potential patterns.

I then created a PivotTable showing the total number of policies, broken down by age group and gender. I also added a PolicyType slicer, allowing me to switch between insurance categories without rebuilding the table.

This gave me an initial overview of how policies were distributed across different demographic groups.

<img width="473" height="419" alt="image" src="https://github.com/user-attachments/assets/d54a6a78-c1b1-4471-8375-8f42f32f19c5" />

One thing that stood out was the difference in Health insurance policy counts between males and females. This could be an interesting area to investigate further, particularly to understand whether the differences remain when accounting for the size of each demographic group.

## 2. Exploring Average Claim Amounts

Next, I looked at average settled claim amounts across different age groups and genders, using slicers to explore each insurance type.

<img width="686" height="485" alt="image" src="https://github.com/user-attachments/assets/ef2b629d-3910-4e4c-911a-ee1db3773040" />

One interesting pattern appeared in Life insurance:

Ages 30–39: Males had a higher average settled claim amount ($3,078) than females ($2,952).

Ages 40–49: The pattern reversed, with females averaging $3,406 compared with $2,981 for males.

This caught my attention because the difference between genders changes noticeably across these age groups.

I'd be interested in examining the individual claims to see whether this reflects a consistent pattern or whether a small number of particularly large claims are influencing the averages.
