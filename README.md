# 🌫️ VINHAR — India Air Quality Analytics Dashboard

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Chart.js](https://img.shields.io/badge/Chart.js-FF6384?style=for-the-badge&logo=chartdotjs&logoColor=white)
![D3.js](https://img.shields.io/badge/D3.js-F9A03C?style=for-the-badge&logo=d3.js&logoColor=white)

> A comprehensive, interactive data visualization and modelling dashboard analyzing India's air pollution crisis. 

## 📊 Project Overview

This project visualizes real-time monitoring data from the Central Pollution Control Board (CPCB) India. Designed to help users understand the scale of the air quality challenge across the nation, the dashboard identifies pollution hotspots and tracks regional disparities. 

This project was developed as an Academic Submission for the Data Modelling & Visualization course (Faculty: Joe Arun Raja).

### Key Statistics
* **Cities Monitored:** 267
* **States Covered:** 30[cite: 1]
* **Data Points:** 3,447 readings[cite: 1]
* **Pollutants Tracked:** 7 distinct metrics (PM2.5, PM10, NO₂, CO, OZONE, SO₂, NH₃)[cite: 1]

## ✨ Features & Visualizations

The dashboard employs over 10 distinct interactive chart types to break down complex environmental data[cite: 1]:

* **National Pollution Summary:** High-level KPIs comparing national pollutant averages against WHO safe limits[cite: 1].
* **State-wise Pollution Ranking:** Interactive horizontal bar charts to compare specific pollutants across all 30 monitored states[cite: 1].
* **Regional Radar Comparison:** Multi-dimensional pollution profile comparisons analyzing the North, South, East, and West regions[cite: 1].
* **Statistical Distribution:** Frequency histograms and stacked bar charts visualizing pollution severity and state counts within different Air Quality Index (AQI) tiers[cite: 1].
* **Pollutant Deep Dive:** Scatter plots (PM2.5 vs PM10) and comprehensive heatmaps showing top states crossed with 7 pollutants[cite: 1].

## 🛠️ Technical Stack

* **Frontend Structure:** HTML5 & CSS3 (Custom responsive UI with CSS Grid and Flexbox)
* **Logic & Data Handling:** Vanilla JavaScript
* **Data Visualization Libraries:** 
  * `Chart.js` (Bar, Doughnut, Scatter, Radar, and Histogram charts)[cite: 1]
  * `D3.js` & `TopoJSON` (Geospatial mapping and rendering)[cite: 1]

## 🚀 Getting Started

To run this dashboard locally, no build steps or package managers are required.

1. Clone the repository:
```bash
   git clone [https://github.com/yourusername/india-air-quality-dashboard.git](https://github.com/yourusername/india-air-quality-dashboard.git)
