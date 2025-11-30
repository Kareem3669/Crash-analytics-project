# 🚗 Crash Analytics  
**Data Cleaning → Python EDA → Power BI Modeling → 6 Dashboard Pages**

---

## 📌 Overview  
Crash Analytics is a data-driven project designed to analyze global traffic accidents, identify patterns, and visualize insights through interactive dashboards. The project combines **data cleaning**, **Python-based exploratory analysis**, and **Power BI dashboards** to deliver actionable insights.

---

## ✅ Project Workflow  
### **1. Data Cleaning**
- Cleaned and standardized three datasets:
  - **Accidents**: Date, location, severity, cause, vehicles involved.
  - **Casualties**: Injuries, fatalities, pedestrian/cyclist involvement.
  - **Weather**: Conditions, visibility, road condition.
- Steps:
  - Removed invalid characters and trimmed spaces.
  - Replaced missing values with logical defaults or medians.
  - Created derived fields (e.g., combined date column).

### **2. Python EDA**
- Merged datasets on `Accident ID`.
- Checked for missing values, duplicates, and data types.
- Visualizations:
  - Accidents by region and time of day.
  - Severity vs visibility.
  - Correlation heatmaps.
- **Key Insights**:
  - Evening/night → highest accident frequency.
  - Poor visibility and bad weather increase severity.
  - Rural areas show more severe accidents.

### **3. Power BI Dashboards**
Six interactive pages provide deep insights into accident trends:

---

## 📊 Dashboard Pages (Detailed)

### **Page 1: Overview**
- **KPIs**:
  - Total Accidents: **132K**
  - Total Injuries: **1M**
  - Total Fatalities: **263K**
  - Injury Rate: **9.51**
  - Fatality Rate: **2.00**
  - Avg Response Time: **32.51 min**
- **Visuals**:
  - Accidents by **time of day** (Morning, Afternoon, Evening, Night).
  - Accidents by **year** (1995–2020).
  - Geographic breakdown by **region and country**.
  - Urban vs rural distribution (54.28% rural vs 45.72% urban).
  - Road type analysis (Highway, Main Road, Street).

### **Page 2: Casualties & Driver Analysis**
- Accidents by **driver gender** (Male vs Female).
- Injuries by gender.
- Accident causes:
  - Distracted Driving
  - Drunk Driving
  - Mechanical Failure
  - Weather
  - Speeding
- Pedestrian involvement and vehicles involved.
- Severity breakdown:
  - Minor, Moderate, Severe accidents with fatalities and injuries.

### **Page 3: Weather & Road Conditions**
- **Weather Impact Index** by region.
- **Road Condition Risk Index** by region.
- Accidents by weather type (Rainy, Snowy, Foggy, Clear).
- Fatalities by road condition (Icy, Wet, Snow-covered, Dry).
- Visibility and poor road condition percentages.

### **Page 4: Geographic Analysis**
- Total accidents and fatalities by region.
- Country-level accident and injury data.
- Heatmaps for accident density.

### **Page 5: Accident Severity & Type**
- Severity breakdown: Minor, Moderate, Severe.
- Fatalities and injuries by severity.
- Correlation with time of day and emergency response time.

### **Page 6: Predictive Indicators**
- Emergency response time correlation with severity.
- Risk indices for weather and road conditions.

---

## 🔍 Key Insights
- Evening and night show higher accident frequencies.
- Asia and North America have the highest accident counts.
- Distracted and drunk driving are leading causes.
- Bad weather and poor road conditions significantly increase accident severity.

---

## 📂 Project Structure
```
├── data/
│   ├── accidents.csv
│   ├── casualties.csv
│   ├── weather.csv
├── notebooks/
│   ├── eda.ipynb
├── dashboards/
│   ├── crash_analytics.pbix
└── README.md
```

---

## 🛠 Tech Stack
- **Python**: Pandas, Matplotlib, Seaborn
- **Power BI**: Interactive dashboards
- **Data Sources**: Accidents, Casualties, Weather datasets

---

## 📊 Dashboard Preview

[Home Page]<img width="1324" height="653" alt="image 1" src="https://github.com/user-attachments/assets/49d57501-9852-4600-bcaf-19cf2984b38e" />

[Overview Dashboard]<img width="1326" height="650" alt="image 2" src="https://github.com/user-attachments/assets/3a220f28-086b-4d36-abf0-a73cc200d233" />

[Geographic Analysis]<img width="1323" height="653" alt="image 3" src="https://github.com/user-attachments/assets/946d2466-7499-40ac-9289-d2020866d7ef" />

[Casualties & Driver Analysis]<img width="1329" height="652" alt="image 4" src="https://github.com/user-attachments/assets/38d1ebfc-fb56-469b-afbf-ad5faa22b1c2" />

[Accident Severity & Type]<img width="1333" height="652" alt="image 5" src="https://github.com/user-attachments/assets/3f74fbfa-e2af-4fd6-8ab8-a878e0200d57" />

[Weather & Road Conditions Analysis]<img width="1328" height="654" alt="image 6" src="https://github.com/user-attachments/assets/90db6796-9119-4333-bc35-0f13227be912" />



---

