# Energy Data

Two data analysis projects built to explore electricity demand patterns 
using real grid and weather data.

## Projects

### 1. PJM Electricity Demand Analysis (2002–2018)
Analysis of 145,000+ hours of PJM East grid data. Explores daily and 
seasonal demand patterns and uses rolling z-score anomaly detection to 
flag unusual grid events including the 2014 Polar Vortex.

**Tools:** Python, pandas, matplotlib, seaborn

### 2. California Weather + Demand Correlation (2023)
Correlates Los Angeles temperature data from NOAA with California 
electricity demand from the EIA API. Identifies a non-linear cooling 
threshold effect and compares linear vs polynomial regression models.

**Tools:** Python, pandas, requests, scikit-learn, matplotlib
