# Formula 1 Race Outcome Analysis (2020–2025) and Weather analysis (2022-2025)
Data repository and R code for analysis of 2020-2025 F1 races and how drivers performed

## Project Overview

This project analyzes Formula 1 race performance and race outcomes from the 2020–2025 seasons. The goal of this analysis is to determine how factors such as weather conditions, fastest laps, penalties, and driver reliability influence race success and fantasy Formula 1 scoring.

The project was completed using R and ArcGIS StoryMaps for visualization and presentation.
--
## Research Questions

1. Does obtaining the fastest lap increase the likelihood of winning a race?
2. How do weather conditions affect driver performance?
3. Which drivers demonstrate the highest reliability across seasons?
4. How do penalties influence race outcomes?
5. Which drivers perform best under specific weather conditions?

--
## Data information

Race data and telemetry:
- Tracing Insights GitHub repositories
  - Formula 1 race result datasets (2020–2025)
 
Weather data:
- MeteoMotorsports
- Race weather condition datasets categorized as:
  - No Wind
  - Low Wind
  - High Wind
--
## Methods

Analyses performed include:
- Data cleaning and preprocessing
- Correlation analysis
- Reliability metric calculations
- Visualization using ggplot2
- Comparative driver analysis
- Weather category comparisons

--
## Required Packages

```r
install.packages(c(
  "readxl",
  "lme4",
  "lmerTest",
  "broom",
  "scales"
))
```
--
## Key Findings

- Weather conditions influenced both reliability and race outcomes.
- Certain drivers consistently outperformed others under adverse weather conditions.
- Reliability varied substantially across teams and seasons.

---

## Figures

Example visualizations include:
- Driver wins per season
- Reliability index plots
- Fastest lap comparisons
- Weather condition performance graphs

