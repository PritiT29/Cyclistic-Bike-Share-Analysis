# Cyclistic-Bike-Share-Analysis

Cyclistic Bike-Share Analysis: Subscriber vs. Casual Behavior


📋 Project Overview
This project is part of the Google Data Analytics Professional Certificate. The goal is to analyze historical trip data from "Cyclistic," a fictional bike-share company in New York City, to understand how Annual Subscribers and Casual Riders use the service differently.

Business Task
Design marketing strategies aimed at converting casual riders into annual members by identifying trends in usage patterns, location preferences, and weather impacts.

🛠️ Data Stack
Data Source:
The raw data used for this analysis is provided by **Citi Bike New York** and is made available under the [Citi Bike Data License Agreement](https://www.citibikenyc.com/data-license-agreement). 

Dataset: [Citi Bike Trip Histories](https://citibikenyc.com/system-data)
Scope: This analysis focuses on trip data within the Manhattan borough, specifically targeting the Chelsea and Clinton neighborhoods.

Processing: SQL (BigQuery/PostgreSQL) for data cleaning and aggregation:[https://github.com/PritiT29/Cyclistic-Bike-Share-Analysis/blob/a0d07e23ab3c273734c275bb8c8702a060047015/Data%20Cleaning%20and%20Transformation]
Data Analysis:[https://github.com/PritiT29/Cyclistic-Bike-Share-Analysis/blob/c46a8159c60e03395902587623c0b173da9de141/Data%20Analysis%20SQL]

Visualization: Tableau Public [https://public.tableau.com/views/CyclisticStationDashboard/Dashboard1?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link]

Visualizations Included
Users by Neighbourhood: A bar hierarchy showing the most popular start/end locations.

Trip vs. Minute Distribution: Pie charts comparing total volume against total time spent.

Station Matrix: A breakdown of Borough-to-Borough movement.

Climate Trend Analysis: A dual-line chart showing how temperature impacts daily trip counts.

Documentation: Markdown

📊 Key Insights from Analysis
1. The "Commuter vs. Tourist" Gap
Subscribers account for the vast majority of total trips (~439k) but maintain shorter average ride times, suggesting a focus on utility and commuting.

Casual Customers spend significantly more time per ride (~16 mins average), indicating leisure use, even though their total trip count is lower.

2. Geographic Dominance
Manhattan is the primary hub of activity, specifically the Chelsea and Clinton neighborhoods.

Trips are highly localized; most rides start and end within the same borough, reinforcing the "last-mile" transit use case for subscribers.

3. The "Sweet Spot" for Weather
Usage is highly seasonal and temperature-dependent.

Peak activity occurs between 60°F and 80°F. Conversion marketing should be maximized during these "Goldilocks" months (May–September).

Recommendations:
1. Digital Out-of-Home (DOOH) Ads: Place ads near top casual start stations in Chelsea and the Lower East Side.

2. Summer Membership Pass: Introduce a "Summer-Only" membership to bridge the gap for casual riders active during high-temperature months.

3. App Gamification: Offer "Commuter Rewards" for trips taken during weekday rush hours to appeal to the subscriber demographic.
