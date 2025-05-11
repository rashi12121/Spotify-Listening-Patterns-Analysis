# 🎧 Spotify Listening Patterns Analysis Dashboard

## 📌 Project Title  
**Analyzing Spotify Music Listening Patterns Using Power BI Dashboards**

---

## 🧾 Overview / Introduction

This project dives deep into Spotify listening data to uncover user behavior trends around albums, artists, and tracks. By building dynamic dashboards in Power BI, the goal is to visualize how music consumption varies over time, across days, and among various content types. These insights can be highly valuable for streaming platforms, marketers, and artists to personalize experiences, optimize release strategies, and enhance user retention.

---

## 🎯 Problem Statement / Objective

The objective of this project is to transform raw Spotify listening data into actionable insights using intuitive visualizations. Key aims include:

- Analyzing how music engagement evolves across years and days of the week.
- Identifying the most popular albums, artists, and tracks.
- Understanding peak listening hours and content engagement levels.
- Providing an interactive grid for detailed data exploration and export.

---

## 📂 Dataset Description

The dataset includes several months/years of Spotify user listening data with the following fields:

- `Album Name`
- `Artist Name`
- `Track Name`
- `Listening Date & Time`
- `Listening Duration (minutes)`
- `Day of Week`, `Month`, `Year`
- `Listening Frequency`

This dataset enables multi-level analysis — from high-level trends to micro-level behaviors.
- [Dataset](https://github.com/rashi12121/Spotify-Listening-Patterns-Analysis/blob/main/spotify_history.xlsx)
---

## 🛠️ Tools & Technologies Used

- **Power BI**: Primary tool for dashboard creation and data visualization  
- **Power Query**: For data transformation and shaping  
- **DAX**: For calculated columns, measures, and KPIs  
- **Microsoft Excel / CSV**: Initial data cleaning and formatting  
- **Scatter Plots, Heat Maps, Matrix Visuals, and Cards**: For insight-rich representation

---

## 🧹 Data Preprocessing

- Removed missing or inconsistent data
- Converted timestamps to date, hour, weekday, month, and year
- Created flags for weekday vs weekend
- Generated summary statistics for listening frequency and duration
- Applied normalization for visualization consistency

---

## 📊 Exploratory Data Analysis (EDA)

- Frequency analysis by track, album, artist  
- Identified trends in monthly and yearly engagement  
- Analyzed variation between weekdays and weekends  
- Segmented tracks based on average listening time and repetition  
- Determined peak usage hours from listening timestamps

---

## 📈 Visualizations

The project features **three interactive dashboards**, each focusing on a distinct analytical perspective:

---

### 📌 Dashboard 1: Albums, Artists, Tracks Overview

This dashboard offers a holistic view of content performance and engagement.

#### 🎵 Albums, Artists, Tracks Insights:
- Total Played Over Time  
- Played by Year (Min & Max)  
- Weekday vs Weekend Listening Behavior  
- Top 5 by Frequency  
- LY (Latest Year) vs PY (Previous Year) Comparison  
- YoY Growth in Plays



🔗 ![Overview Dashboard](https://github.com/rashi12121/Spotify-Listening-Patterns-Analysis/blob/main/_Dashboard-1_Overview.png)


---

### 📌 Dashboard 2: Listening Patterns Analysis

This dashboard focuses on **when** and **how** users listen to music.

#### 🕒 Listening Hour Trends:
- Heat Map showing Listening Frequency by Hour and Day  
- Peak and low listening hours identified through color intensity  

#### 📊 Listening Time vs Frequency (Quadrant Scatter Plot):
Categorizes tracks into:
- 🎯 High Frequency & High Listening Time – Highly engaging
- 🎵 Low Frequency & High Listening Time – Deep, niche favorites
- 🔁 High Frequency & Low Listening Time – Trendy, quick tracks
- ❌ Low Frequency & Low Listening Time – Least popular

🔗 ![Listening Patterns Dashboard](https://github.com/rashi12121/Spotify-Listening-Patterns-Analysis/blob/main/_Dashboard-2_Listening%20Pattern.png)

---

### 📌 Dashboard 3: Detailed Grid View

This dashboard presents detailed tabular data with rich interaction capabilities.

#### 📄 Grid Features:
- Displays Album, Artist, and Track names alongside other key metrics  
- Supports drill-through functionality to detailed views  
- Exportable to CSV for reporting or offline analysis  
- Enables Drill Up/Drill Down using hierarchies (e.g., Year → Month → Day)

🔗 ![Details Dashboard1](https://github.com/rashi12121/Spotify-Listening-Patterns-Analysis/blob/main/_Dashboard-3_Details.png)
![Details Dashboard2](https://github.com/rashi12121/Spotify-Listening-Patterns-Analysis/blob/main/_Dashboard-3_Details-2.png)

---

## 🔍 Key Findings / Insights

- Music listening peaks during evening hours and weekends.
- Listeners show increased diversity in artist and track selection over the years.
- A few top artists and albums dominate engagement across time periods.
- Certain tracks have niche but strong engagement, indicating deep listener connection.
- Scatter analysis reveals opportunities for promoting underplayed high-duration tracks.

---

## ✅ Conclusion & Recommendations

This Spotify listening pattern project demonstrates the power of visual analytics in understanding user behavior. The dashboards offer clear, actionable insights that can help music platforms:

- Curate more personalized playlists based on listening hours and frequency  
- Promote underrepresented yet high-engagement tracks  
- Identify seasonal or day-specific engagement peaks for targeted campaigns  
- Monitor year-over-year trends to evaluate content performance  

---



