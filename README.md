<div align="center">
  
# 🌫️ India Air Quality Analytics & Visualization
**A deep-dive data science project analyzing the air pollution crisis across India.** 

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557c?style=for-the-badge&logo=python&logoColor=white)
![Seaborn](https://img.shields.io/badge/Seaborn-4C4C4C?style=for-the-badge&logo=python&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-3F4F75?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white)

[![Data Source](https://img.shields.io/badge/Data-CPCB_India-brightgreen?style=flat-square)](#)
[![Status](https://img.shields.io/badge/Status-Completed-blue?style=flat-square)](#)
[![Academic](https://img.shields.io/badge/Project-Academic-orange?style=flat-square)](#)

</div>

---

## 📖 Table of Contents
- [About the Project](#-about-the-project)
- [Dataset Highlights](#-dataset-highlights)
- [Key Features & Visualizations](#-key-features--visualizations)
- [Technologies Used](#-technologies-used)
- [Project Structure](#-project-structure)
- [Installation & Usage](#-installation--usage)
- [The Team](#-the-team)

---

## 🌍 About the Project

India faces a significant environmental challenge with fluctuating air quality levels across its diverse geography. This project is a comprehensive Python-based data analysis and visualization endeavor designed to uncover actionable insights into the scale of this crisis. 

By processing real-time monitoring data from the Central Pollution Control Board (CPCB), this analysis identifies severe pollution hotspots, tracks regional disparities, and correlates different pollutant levels to understand the broader environmental impact. 

> **Academic Context:** This project was developed as an academic submission for the **Data Modelling & Visualization** course under the guidance of Faculty Joe Arun Raja.

---

## 📊 Dataset Highlights

The analysis is built on a robust dataset sourced from `DATA.GOV.IN` (CPCB India, April 2026), featuring:

- **🏙️ Cities Monitored:** 267 distinct urban centers.
- **🗺️ States Covered:** 30 states across all regions of India.
- **📈 Data Points:** 3,447 recorded readings.
- **☠️ Pollutants Tracked:** 7 critical metrics[cite: 1]:
  - `PM2.5` & `PM10` (Particulate Matter)
  - `NO₂` (Nitrogen Dioxide)
  - `CO` (Carbon Monoxide)
  - `OZONE` (O₃)
  - `SO₂` (Sulfur Dioxide)
  - `NH₃` (Ammonia)

---

## ✨ Key Features & Visualizations

We utilized advanced Python charting libraries to transform raw data into a compelling visual narrative:

*   **National Pollution Summary:** High-level statistical summaries calculating national pollutant averages and comparing them directly against WHO safe limits[cite: 1].
*   **State-wise Ranking & Comparisons:** Bar charts comparing specific pollutants across all monitored states to identify the most and least polluted regions[cite: 1].
*   **Multi-Dimensional Analysis:** Radar charts profiling multiple pollutants simultaneously for top-tier states (e.g., Delhi, Haryana, Madhya Pradesh)[cite: 1].
*   **Statistical Distributions:** Histograms and stacked bar charts visualizing pollution severity tiers (Good, Moderate, Poor, Very Poor, Hazardous)[cite: 1].
*   **Correlation & Heatmaps:** Scatter plots mapping PM2.5 against PM10, alongside concentration heatmaps showing top states crossed with all 7 distinct pollutants[cite: 1].

---

## 💻 Technologies Used

*   **Core Language:** Python 3.x
*   **Data Manipulation:** `pandas`, `numpy`
*   **Data Visualization:** 
    *   `matplotlib` (Base plotting)
    *   `seaborn` (Statistical data visualization & heatmaps)
    *   `plotly` (Interactive graphs and radar charts)
*   **Environment:** Jupyter Notebooks (`.ipynb`) / Python Scripts (`.py`)

---

## 📁 Project Structure

```text
india-air-quality-analysis/
│
├── data/
│   └── india_air_pollution_2026.csv   # The raw CPCB dataset
│
├── notebooks/
│   └── Air_Quality_Analysis.ipynb     # Main Jupyter Notebook with code & graphs
│
├── images/
│   └── (Saved charts and visualizations for the README)
│
├── requirements.txt                   # List of Python dependencies
└── README.md                          # Project documentation

