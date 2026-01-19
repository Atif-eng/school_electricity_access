# ⚡ Lighting the Future: Global School Electricity Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue)
![Library](https://img.shields.io/badge/Library-Plotly-green)
![Algorithm](https://img.shields.io/badge/Algorithm-K--Means-orange)
![Status](https://img.shields.io/badge/Status-Completed-success)

## 📌 Project Overview
**"How can students learn in the dark?"**

This project analyzes the global disparity in electricity access for schools over the last two decades (2000-2020). By using **Time-Series Analysis** and **K-Means Clustering**, we identify which nations are successfully bridging the energy gap and which are being left behind.

**Author:** Muhammad Atif

## 📂 Dataset
The dataset tracks the percentage of schools with electricity access across different countries and years.
- **Key Metrics:** `% of schools with electricity`
- **Scope:** Global (covering multiple continents and economic zones).
- **Timeframe:** 2000 - 2020.

## 🛠 Tech Stack
- **Language:** Python
- **Data Manipulation:** `pandas`, `numpy`
- **Visualization:** - `plotly.express` & `plotly.graph_objects` (For interactive animated maps).
  - `seaborn` & `matplotlib` (For static trend analysis).
- **Machine Learning:** `scikit-learn` (K-Means Clustering, StandardScaler).

## 📊 Project Workflow

### 1. Exploratory Data Analysis (EDA) 
- **The Global Map:** Created an animated choropleth map to visualize how the "lights turned on" across the world over 20 years.
- **The Energy Gap:** Identified the stark contrast between developed nations (100% access) and Sub-Saharan Africa (often <20%).

### 2. Machine Learning: Clustering Nations
We didn't just plot lines; we grouped countries based on their *development trajectory* using **K-Means Clustering**:
- **Cluster 0 (The Leaders):** Countries that have maintained near 100% access.
- **Cluster 1 (The Developing):** Nations showing rapid improvement (the "Rising Stars").
- **Cluster 2 (The Energy Poor):** Countries consistently struggling with infrastructure.

### 3. Key Findings
- **The Digital Divide:** While Europe and North America are fully powered, nations like Niger and Chad still face critical shortages.
- **Investment Targets:** The "Developing" cluster represents the best opportunity for renewable energy impact investing.

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/your-username/global-school-electricity.git](https://github.com/your-username/global-school-electricity.git)
