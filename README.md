# Worlds Getting Warmer

Analysis of Atlantic hurricane and US tornado trends against global 
temperature data from 1980 to 2023.

## Data Sources
- Temperature: NASA GISS Surface Temperature Analysis (GISTEMP v4)
- Hurricanes: NOAA National Hurricane Center, HURDAT2
- Tornadoes: NOAA Storm Prediction Center

## Methods
Pearson correlation between annual global temperature anomaly and storm 
activity measures across 44 years of data. Analysis done in R using 
tidyverse and ggplot2.

## Key Findings
- Named Atlantic storms: r = 0.61 with temperature
- Major hurricanes (Cat 3+): r = 0.39 with temperature
- US tornado count: r = 0.38 with temperature

## Live Report
https://dataworkslabs.github.io/climate-storm-analysis
