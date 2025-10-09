# Engineering Air Quality Analysis

## Project Overview
This data visualization project investigates air quality measurements across three distinct environments at NUS Engineering. The study compares pollutant levels and temperature readings from **indoor, hybrid, and outdoor** settings to understand spatial variations in air quality. Built using **R** and the **Tidyverse** package.

### Course: ESE3201 Air Quality in Changing Environments

---

## Measured Parameters

- **Temperature (°C)** - Ambient temperature
- **CO (ppm)** - Carbon monoxide concentration
- **NO₂ (ppm)** - Nitrogen dioxide concentration  
- **O₃ (ppm)** - Ozone concentration
- **SO₂ (ppm)** - Sulfur dioxide concentration

**Data Collection:** 60 timestep measurements per location using air quality sensors

---

## Visualizations

1. **Time Series Analysis**  
   Tracks pollutant concentrations over 60 timesteps across all three locations
   * File: `time_series_grid.png`

2. **Normalized Pollutant Levels**  
   Compares average pollutant levels using min-max normalization (0-1 scale)
   * File: `barchart_normalised.png`

3. **Distribution Analysis**  
   Box plots showing the statistical distribution of measurements
   * File: `boxplot_distribution.png`

4. **Correlation Heatmap**  
   Explores relationships between different air quality variables
   * File: `heatmap_correlation.png`

---
