# 🌦️ Weather Dashboard (Power BI)

## 📌 Project Overview
This project is an interactive **Weather Analytics Dashboard** built using **Microsoft Power BI**.  
The dashboard analyzes weather data to provide insights on temperature trends, humidity levels, wind speed, and other atmospheric conditions.

It helps users understand **weather patterns, climate trends, and regional conditions** through interactive visualizations and KPI indicators.

---

# 🛠 Tools & Technologies
- Microsoft Power BI
- Power Query (ETL)
- DAX (Data Analysis Expressions)
- Data Modeling
- Data Visualization

---

# 📂 Dataset
The dataset includes weather observations such as:

- Temperature
- Humidity
- Wind Speed
- Atmospheric Pressure
- Weather Condition
- Date / Time
- Location

---

# 📊 Key Performance Indicators (KPIs)

| KPI | Description |
|----|-------------|
| Avg Temperature | Average temperature across selected time period |
| Max Temperature | Highest recorded temperature |
| Min Temperature | Lowest recorded temperature |
| Avg Humidity | Average humidity level |
| Avg Wind Speed | Average wind speed |
| Weather Condition Count | Frequency of weather types |

---

# 📈 Metrics Used

- Temperature Trend
- Humidity Distribution
- Wind Speed Analysis
- Weather Condition Frequency
- Daily Weather Comparison
- Location-based Weather Insights

---

# 📏 Measures (DAX)

### Average Temperature
```DAX
Avg Temperature = AVERAGE(Weather[Temperature])
