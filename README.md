# 🚗 U.S. Traffic Accidents – Exploratory Data Analysis (EDA)

A complete exploratory analysis of the U.S. Traffic Accidents Dataset, focusing on accident patterns across cities, time, regions, and environmental conditions.
This project performs data cleaning, visualization, pattern discovery, and hotspot identification using Python’s core data analytics libraries.

## 1.📌 Project Overview

The goal of this project is to analyze U.S. accident records to understand how weather, road conditions, time, day of week, and location influence accident severity and casualty counts.

The analysis includes:

Data preprocessing and type corrections

Univariate & bivariate exploration

Geospatial visualization of accident hotspots

Insights into patterns that impact road safety

## 2.🎯 Objectives

• Understand dataset structure and accident attributes

• Explore trends across day, time, region, and city

• Analyze the effect of weather, light, and road conditions

• Identify high-risk regions using geospatial mapping

• Discover patterns influencing severity and casualty rates

• Visualize accident density using heatmaps and statistical charts

## 3.🧰 Tech Stack

Python Ecosystem

• Pandas – Data preparation & cleaning

• NumPy – Numerical processing

• Matplotlib & Seaborn – EDA & visual insights

• Plotly (Mapbox) – Interactive accident hotspot maps

• Folium – Geospatial visualization (optional)

## 4.🗂️ Dataset

Custom U.S. Accident Dataset containing key fields:

| Column             | Description                                      |
|--------------------|--------------------------------------------------|
| Accident_ID        | Unique accident identifier                       |
| Date               | Accident date                                    |
| Time               | Accident time                                    |
| Day_of_Week        | Weekday of incident                              |
| Weather            | Weather during accident                          |
| Road_Condition     | Dry/Wet/Icy etc.                                 |
| Light_Condition    | Daylight, Dusk, Night                            |
| Severity           | Minor / Major                                    |
| Vehicles_Involved  | Count of vehicles                                |
| Casualties         | Injuries/Fatalities                              |
| Region             | U.S. region (West, Midwest, Northeast, etc.)     |
| City               | City of occurrence                               |
| Latitude / Longitude | Coordinates for mapping hotspots               |


## 5.📊 Analysis Workflow
✅ Data Loading & Cleaning

• Converted date/time formats

• Verified latitude/longitude ranges

• Checked distributions & missing values

🔍 Exploratory Data Analysis (EDA)

• Accidents by weekday, time of day

• Weather & road condition effects

• Severity distribution

• Casualty vs vehicle involvement patterns

🌍 Geospatial Insights

• City-wise accident clusters

• Regional accident density

• Mapbox-based accident heatmaps

📈 Visualizations

• Bar charts, count plots

• Heatmaps (severity vs. conditions)

• Interactive density maps

## 6.💡 Key Insights

1️⃣Major hotspots observed in high-density areas like Los Angeles, New York City, Houston, and Chicago.

2️⃣ Casualty-heavy clusters appear along key highways and interstates.

3️⃣ Fatal accidents tend to concentrate in suburban/rural stretches with poor lighting.

4️⃣ Clear weather still dominates accident counts — suggesting speed and distraction as major causes.

5️⃣ Wet or icy conditions show higher severity zones, especially in northern U.S. states.

## 7.📈 Safety & Analytical Impact

This project demonstrates the ability to:

• Perform extensive EDA on real-world traffic data

• Analyze environmental & temporal risk factors

• Create hotspot visualizations for safety planning

• Reveal patterns useful for transportation departments

• Build a foundation for future predictive modeling (severity prediction, risk scoring)

## 8.📸 Screenshots / Visuals

![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(1).png)
![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(2).png)
![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(3).png)
![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(4).png)
![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(5).png)
![Dashboard Preview](https://github.com/ravisaini007/SCT_DS_4/blob/main/ss-1%20(6).png)
          
