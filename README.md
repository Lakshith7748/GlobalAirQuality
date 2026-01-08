# 🌍 Global Air Quality and Pollution Trends  

## ⌅Project Overview  
Air pollution is one of the most critical global public health challenges.  
This project explores how air quality varies across regions, time, climate, and socioeconomic conditions.  
Using multiple datasets, we perform extensive data mining and exploratory analysis to uncover hidden patterns, correlations, and insights.

The primary goal is to understand pollution behavior, identify high-risk regions, and analyze factors influencing air quality worldwide. This includes answering key exploratory questions through data cleaning, visualization, statistical analysis, and machine learning.

---

## 📂 Datasets Used  

1. Global Air Pollution Data
2. World Bank – Air Quality & Socioeconomic Indicators
3. US EPA PM2.5 Monitoring Data
4. PM2.5 Exposure – World Bank Dataset
=
We merged datasets that where necessary to explore relationships between pollution, geography, health, and economic development.

---


# Air Quality Analysis Report

## 1. Which countries/cities have the highest and lowest average pollution levels?

### Why it matters
Geographical disparities highlight regions requiring urgent policy intervention, improved monitoring, or targeted emission control strategies.

### Analysis
→ Computed average AQI for each country (and city where available)  
→ Ranked countries from highest to lowest pollution levels

### Insights
* Republic of Korea recorded the highest average AQI (421)
* Palau recorded the lowest average AQI (16.3)
* India ranked 9th among all countries.

---

## 2. How do major pollutants (PM2.5, PM10, NO₂, CO, O₃) correlate with each other?

### Why it matters
Pollutant correlations help identify common emission sources and determine which pollutants most strongly influence overall AQI.

### Analysis
→ Computed correlation matrix for all pollutants  
→ Visualized correlations using a heatmap  
→ Used regression plots (e.g., PM2.5 vs AQI) to assess pollutant influence

### Insights
* PM2.5 shows strong positive correlation with overall AQI
* PM10 and NO₂ exhibit moderate correlation, suggesting shared sources
* O₃ shows weaker correlation, indicating different formation dynamics

---

## 3. What is the relationship between GDP per capita and air pollution?

### Why it matters
Understanding this relationship helps evaluate whether economic growth enables cleaner technologies and stricter environmental regulations.

### Analysis
→ Merged GDP per capita data with country-level PM2.5 values  
→ Applied linear regression to quantify the relationship  
→ Visualized results using a scatter plot with a regression line

### Insights
* Higher GDP per capita generally correlates with lower PM2.5 levels
* Several high-income countries deviate from this trend, indicating policy impact
* The countries with cleaner air , had seen significant growth in their economy , since the past few years.

---

## 4. Are there seasonal variations in air pollution levels?

### Why it matters
Seasonal pollution spikes are critical for public health planning and early warning systems.

### Analysis
→ Computed monthly averages of PM2.5  
→ Visualized seasonal trends using line charts

### Insights
* Winter months show significantly higher pollution levels.
* Seasonal spikes are likely due to temperature inversions and increased fuel usage.
* PM2.5 levels drop significantly during the summer months.

---

## 5. How has air quality changed globally and regionally over the last 20 years?

### Why it matters
Long-term trends help assess the effectiveness of air-quality policies and identify regions with improving or worsening conditions.

### Analysis
→ Calculated annual mean PM2.5 levels (2000–2020).
→ Analysed Global Air Quality.

### Insights
*  2000–2011: Global pollution rose sharply, driven by rapid industrial growth in developing regions.
*  Post-2015: Pollution levels gradually declined due to strong clean-air policies in China and sustained improvements in Europe and North America.

---

## 6. How volatile is air quality across regions?

### Why it matters
Average AQI masks pollution spikes, which pose serious health risks and require emergency preparedness.

### Analysis
→ Calculated standard deviation (SD) of AQI to measure absolute variability.
→ Calculated coefficient of variation (CV) to measure relative volatility.

### Insights
*  Papua New Guinea has the highest AQI volatility (CV ≈ 0.97).
*  Australia, Namibia, Paraguay, and Chile also show large fluctuations despite moderate averages.
* Volatility provides additional risk insight beyond average AQI values.
---

## 🛠️ Tech Stack & Dependencies  

### **Programming Language**
- Python

### **Libraries & Tools**
- `pandas` – data cleaning and manipulation  
- `numpy` – numerical operations  
- `matplotlib` / `seaborn` – visualizations  
- `scikit-learn` – clustering & regression  
- `requests` – API data fetching  


## 👥 Team Members  

| Name | GitHub |
|---|---|
| Achuta Lakshith | https://github.com/Lakshith7748 |
| Sai Praneeth Sharma | https://github.com/SHARMA1525 |
| Geethika | https://github.com/heidi04aldidi |

---

Thank you for exploring our project!  
If you find it helpful, please consider starring the repository.
