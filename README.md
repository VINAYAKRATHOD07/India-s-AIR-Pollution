# 🌫️ VINHAR — India Air Quality Analytics & Modeling

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black)
![Plotly](https://img.shields.io/badge/Plotly-239120?style=for-the-badge&logo=plotly&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white)

> An exploratory data analysis (EDA) and multi-pollutant visualization project tracking India's atmospheric health using Python.

## 📊 Project Overview

This project ingests, cleans, and visualizes real-time environmental monitoring data from the **Central Pollution Control Board (CPCB) India**. By leveraging Python's data science stack, the project transforms raw station readouts into a high-level diagnostic of regional air pollution.

Developed as an Academic Submission for the *Data Modelling & Visualization* course (Faculty: Joe Arun Raja).

### Dataset Overview
* **Scope:** 267 Cities across 30 Indian States
* **Volume:** 3,447 individual monitoring station readouts
* **Target Pollutants (7):** $\text{PM}_{2.5}$, $\text{PM}_{10}$, $\text{NO}_2$, $\text{CO}$, $\text{SO}_2$, $\text{O}_3$ (Ozone), and $\text{NH}_3$ (Ammonia).

---

## 🔬 Key Analytical Features

1. **Automated Data Wrangling:** Handled missing sensor inputs, standardized timestamp formats, and aggregated station-level data into state-wide means using `Pandas`.
2. **Distribution & Outlier Analysis:** Box-plots and histograms isolating extreme pollution events (e.g., severe $\text{PM}_{10}$ spikes in Northern industrial zones).
3. **Multi-Pollutant Correlation:** Seaborn correlation matrices identifying the symbiotic rise of specific compound pairs (e.g., Carbon Monoxide and Nitrogen Dioxide).
4. **Geospatial & Tiered AQI Mapping:** Exported interactive HTML dashboards allowing users to filter pollution severity by specific CPCB monitoring stations.

---

## 📂 Repository Structure

```text
├── data/
│   └── 3b01bcb8-0b14-4abf-b6f2-c1bfd384ba69.csv  # Raw CPCB dataset
├── outputs/
│   └── india_air_pollution.html                  # Generated interactive dashboard 
├── [your-main-code-file.ipynb / .py]             # Primary analysis notebook/script
├── requirements.txt                              # Python dependencies
└── README.md
