# 🚴 London Bike Rides – Tableau Dashboard Project

This is a data analytics project where I explored bike rental trends in London using a public dataset from Kaggle.  
I started by cleaning and transforming the data using **Python** and **Jupyter Notebook**, and then built an interactive dashboard in **Tableau** to visualize key insights.

**My goal was to follow a complete data analytics workflow—from raw CSV data to a polished, interactive dashboard—and to highlight my ability to turn data into insights through storytelling.**

------------------------

## 📊 Project Summary

The dataset contains hourly bike rental data from **2015 to 2017**, along with weather attributes such as **temperature**, **humidity**, and **wind speed**. I used this data to explore how bike usage patterns change based on time, weather, and day of the week.

Some of the questions I focused on:
- When are people most likely to rent bikes in London?
- How does weather (like rain or cold) affect rental volumes?
- Are weekends different from weekdays in terms of bike activity?

---------------------

## 🧹 Data Cleaning & Preparation

I used **Jupyter Notebook** and **Pandas** to prepare the data for analysis in Tableau.  
Here’s what I did during the data preprocessing step:

- Renamed columns for better readability
- Converted timestamps into usable date/time fields
- Handled missing or null values
- Created new features such as `hour`, `weekday`, and `season`
- Filtered irrelevant rows for cleaner insights

All preprocessing steps can be found in the `london_bikes.ipynb` notebook.

---

## 📸 Dashboard Overview

I designed the dashboard in Tableau to be clean, intuitive, and interactive.  
Here’s what it includes:

- 📈 **Line charts** showing daily and monthly rental trends
- 🔥 **Heatmaps** to visualize peak hours across weekdays
- 🌡️ **Temperature vs Rentals** analysis
- 📅 **Weekday vs Weekend** comparisons

🔍 I also added **interactive tooltips**—when you hover over charts, they display extra info like:
- Mini-charts within tooltips (e.g., hourly breakdowns for specific days)
- Weather stats tied to each data point
- Dynamic filtering based on selections

These enhancements make the dashboard more engaging and help users explore the data on their own.

---

## 🛠 Tools Used

- **Python**: Jupyter Notebook, Pandas for data cleaning
- **Tableau Public**: for interactive visualizations and dashboard creation
- **Kaggle Dataset**: [London Bike Sharing Dataset](https://www.kaggle.com/datasets/hmavrodiev/london-bike-sharing-dataset)

---

