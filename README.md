🚗 Crash Analytics
Data Cleaning → Python EDA → Power BI Modeling → 6 Dashboard Pages
📌 Overview
Crash Analytics is a comprehensive data analysis project focused on understanding accident patterns, severity, and contributing factors. The workflow includes data cleaning, exploratory data analysis (EDA) using Python, and interactive dashboards built in Power BI.

✅ Project Workflow


Data Cleaning

Standardized three datasets: Accidents, Casualties, and Weather.
Removed invalid characters, trimmed spaces, and replaced missing values with logical defaults or medians.
Created new derived fields (e.g., combined date column).



Python EDA

Merged datasets on Accident ID.
Checked for missing values, duplicates, and data types.
Visualizations:

Accidents by region and time of day.
Severity vs visibility.
Correlation heatmaps.


Key Insights:

Evening/night → highest accident frequency.
Poor visibility and bad weather increase severity.
Rural areas show more severe accidents.





Modeling & Dashboards (Power BI)

Pages:

Overview: KPIs, trends, geographic breakdown.
Casualties & Driver Analysis: Gender, causes, severity.
Weather & Road Conditions: Impact indices, visibility.
Geographic Analysis: Heatmaps, country-level data.
Severity & Type Analysis: Correlation with time and response time.


KPIs:

Total Accidents: 132K
Injuries: 1M
Fatalities: 263K
Avg Response Time: 32.51 min






📂 Project Structure
├── data/
│   ├── accidents.csv
│   ├── casualties.csv
│   ├── weather.csv
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
├── dashboards/
│   ├── crash_analytics.pbix
└── README.md


🔍 Key Insights

Distracted and drunk driving are leading causes.
Bad weather and poor road conditions significantly increase accident severity.
Asia and North America have the highest accident counts.


🛠 Tech Stack

Python: Pandas, Matplotlib, Seaborn
Power BI: Interactive dashboards
Data Sources: Accidents, Casualties, Weather datasets


📊 Dashboard Preview
(Add screenshots of your Power BI dashboards here)
