# Air Quality Impact Analysis

---

## Project Overview

Jagriti is a data-driven air pollution impact analysis project that studies air quality trends across major Indian cities. The project uses historical AQI data to identify pollution hotspots, seasonal pollution patterns, and key emission drivers.

The objective is to convert environmental data into actionable insights for policymakers and urban planners.

---

## Dataset Overview

The analysis uses large-scale historical air quality data.

Key statistics:

- 5+ years of AQI historical data
- 26+ cities across India
- 120+ monitoring stations
- 1M+ hourly and daily records
- Major pollutants analyzed: PM2.5 and PM10

---

## Key Insights

### 1. Pollution Concentration
Air pollution is highly clustered in specific cities rather than evenly distributed.

- NCR and Indo-Gangetic cities dominate pollution rankings.
- Top 10 cities contribute disproportionately to PM2.5 levels.

### 2. Station-Level Hotspots
City averages often hide extreme pollution zones.

- Station-level PM2.5 peaks exceed city averages by **20–30%**.
- Highest recorded station-level PM2.5: **153 µg/m³**.

### 3. Seasonal Pollution Patterns

**Winter (Nov–Jan)**
- Strong PM2.5 spikes
- Temperature inversion traps pollutants

**Summer (Apr–Jun)**
- Ozone peaks due to sunlight-driven reactions

**Monsoon (Jul–Sep)**
- Cleanest air period due to rainfall removing particulates

### 4. Event-Based Pollution

**Diwali Effect**

- October: ~70 µg/m³
- November: ~108 µg/m³  
- Nearly **50% increase in PM2.5**

### 5. Pollution Drivers

Correlation analysis revealed major pollution sources:

| Pollutant Relationship | Interpretation |
|---|---|
| PM2.5 ↔ PM10 | Road dust & combustion |
| NO₂ ↔ CO | Vehicular emissions |
| SO₂ | Industrial sources |
| O₃ | Sunlight-driven chemical reactions |

---

## High-Risk Cities

Cities with the highest pollution exposure:

- Lucknow
- Delhi
- Patna
- Gurugram

Exposure duration: **1600–1950 high-pollution days**

Peak winter PM2.5: **~200 µg/m³**

---

## Impact on Public Health

High pollution exposure affects vulnerable populations:

- Children → lung development risk
- Elderly → cardio-respiratory stress
- Outdoor workers → chronic exposure

---

## Action Framework

Recommended interventions based on pollution drivers.

| Problem | Action |
|---|---|
| Winter PM spikes | Dust suppression & construction control |
| Vehicular emissions | Traffic restrictions & cleaner fuel |
| Crop burning | Regional policy coordination |
| Summer ozone | Emission precursor control |

---

## Power BI Dashboard

The interactive dashboard was built using **Microsoft Power BI** to visualize pollution trends, seasonal patterns, and high-risk regions.

Due to GitHub file size limits, the `.pbix` file is hosted externally.

Power BI File:  
(https://drive.google.com/file/d/1sZ5_PLT6jdEHxCmXq2mH1NTgr2XForNg/view?usp=sharing)

---

## Project Files

Jagriti/

│

├── Jagriti.pdf → Project presentation

├── jagriti.pbix → Power BI dashboard

├── README.md → Project documentation


---

## Tools Used

- Power BI
- Python
- Pandas
- Data Visualization
- Environmental Data Analysis

---

## Conclusion

Air pollution in India shows strong spatial clustering and seasonal patterns. By identifying key drivers and high-risk zones, targeted interventions can significantly reduce exposure and improve public health outcomes.

## Author

Prachi Mittal  
