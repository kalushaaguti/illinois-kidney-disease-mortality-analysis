# Spatial-Temporal Analysis of Kidney Disease Mortality in Illinois (2008–2022)

## Overview
This project analyzes the spatial and temporal patterns of kidney disease mortality across Illinois counties from 2008 to 2022 using GIS, interactive mapping, and animated cartography.

The goal was to identify geographic disparities, track trends over time, and communicate patterns using static maps, animations, and web-based visualization.

---

## Study Area
Illinois, United States (County Level)

---

## Data Sources
- Illinois Department of Public Health (IDPH) – Kidney disease mortality data (2008–2022)
- IDPH – Population data
- Illinois County Boundary Shapefile

---

## Tools & Technologies
- ArcGIS Pro
- ArcGIS Online
- PowerPoint (for animation)
- CSV Data Processing

---

## Methodology

### Data Preparation
- Joined mortality and population data to county shapefile
- Calculated mortality rate per 100,000 population
- Standardized dataset across all years (2008–2022)

### Mapping
- Created choropleth maps using **Natural Breaks (Jenks) classification**
- Maintained consistent class breaks across all years
- Fixed map layout elements for animation consistency

### Animation
- Exported yearly maps as images
- Created time-series animation (2008–2022) using PowerPoint

### Interactive Map
- Published dataset to ArcGIS Online
- Configured popups to display county-level mortality rates

---

## Workflow
CSV Data → Join to Counties → Calculate Rates → Choropleth Mapping → Export Maps → Animation + Web Map


---

## Results

### Spatial Patterns
- **Southern Illinois**: consistently high mortality (Pulaski, Alexander, Perry, Wabash)
- **Northern Illinois**: consistently low mortality (Cook, McHenry, Boone)
- Clear **north–south disparity** across all years

### Temporal Trends
- Overall increase in mortality from **2008 to 2022**
- Peak values observed between **2018–2022**
- Some counties show slight improvements after 2020

---

## Key Findings
- Strong and persistent high-mortality cluster in southern Illinois
- Stable low-mortality pattern in northern Illinois
- Increasing statewide mortality trend over time
- Spatial inequality clearly visible across the entire period

---

## Outputs
- 15 Choropleth Maps (2008–2022)
- Time-series animation (MP4)
- Interactive ArcGIS Online map

---

## Skills Demonstrated
- Spatial-Temporal Analysis
- Choropleth Mapping
- Data Normalization (rates per 100,000)
- ArcGIS Pro
- ArcGIS Online
- Animated Cartography
- Public Health GIS Analysis

---

## Why This Project Matters
This project demonstrates how GIS can be used to analyze and communicate long-term public health trends, identify geographic disparities, and support data-driven decision-making.

---

## Map Samples
![Map 2008](maps/map_2008.png)
![Map 2015](maps/map_2015.png)
![Map 2022](maps/map_2022.png)

## Animation
[Watch Animation](animation/your-video-name.mp4)

## Author
Kalusha Aguti  
M.S. Geography (GIS & Data Analytics Application)  
Southern Illinois University Edwardsville
