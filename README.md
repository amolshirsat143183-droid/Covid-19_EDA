## 🦠 COVID-19 Global Data EDA

## 📌 Overview
This project performs **Exploratory Data Analysis (EDA)** on a COVID-19 dataset to analyze and visualize the global impact of the pandemic.  
The dataset contains country-level statistics including confirmed cases, deaths, recoveries, active cases, and weekly changes.

**Objectives:**
- Explore the COVID-19 spread across countries and regions.
- Identify countries with the highest number of cases and deaths.
- Analyze recovery and fatality rates.
- Study trends in weekly changes.

---

## 📂 Dataset Information
**Shape:** `187 rows × 15 columns`  
**Source:** *(Add source link here – e.g., WHO or Kaggle)*  

| Column Name                | Description |
|----------------------------|-------------|
| `Country/Region`           | Name of the country or region |
| `Confirmed`                | Total confirmed cases |
| `Deaths`                   | Total reported deaths |
| `Recovered`                | Total recovered cases |
| `Active`                   | Currently active cases |
| `New cases`                | New cases reported on the latest date |
| `New deaths`               | New deaths reported on the latest date |
| `New recovered`            | New recoveries reported on the latest date |
| `Deaths / 100 Cases`       | Death rate per 100 confirmed cases |
| `Recovered / 100 Cases`    | Recovery rate per 100 confirmed cases |
| `Deaths / 100 Recovered`   | Deaths per 100 recovered cases |
| `Confirmed last week`      | Total confirmed cases from the previous week |
| `1 week change`            | Change in confirmed cases over the last week |
| `1 week % increase`        | Percentage increase in confirmed cases |
| `WHO Region`               | WHO region classification |

---

## 🔍 Steps Performed

### 1. Data Loading & Inspection
- Loaded dataset using **Pandas**.
- Checked shape, column types, and missing values.
- Identified numerical and categorical features.

### 2. Data Cleaning
- Verified data consistency.
- Ensured correct data types.
- Checked for outliers and anomalies.

### 3. Exploratory Data Analysis
- **Top 10 countries** by confirmed cases.
- Countries with **highest fatality rates**.
- Countries with **highest recovery rates**.
- Weekly change trends across countries.
- Analysis by **WHO Region**.

### 4. Visualization
- Bar charts for top affected countries.
- Pie charts for case distribution.
- Heatmap for correlations.
- Trend analysis for weekly changes.

---

## 📈 Key Insights
- Countries like **[Example: USA, India, Brazil]** had the highest confirmed cases.
- **Death rate** varied significantly between countries, with some exceeding global averages.
- **Recovery rates** were highest in some regions, indicating effective healthcare management.
- Weekly percentage changes helped identify emerging hotspots.

---

## 🛠️ Tools & Libraries Used
- **Python** (v3.x)
- **Pandas** – Data manipulation
- **NumPy** – Numerical computations
- **Matplotlib** – Data visualization
- **Seaborn** – Advanced visualization
- **Jupyter Notebook** – Analysis environment

---
