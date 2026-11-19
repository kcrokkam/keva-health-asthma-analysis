# Keva Health — Air Quality and Asthma Emergency Visits

**Integrated Experiential Learning · ALY6080 · Spring 2021**  
**Presentation:** June 24, 2021  
**Group 7:** Krishna Chaitanya Rokkam and Li-Ying Wang

## Research objective

Examine associations between air quality and asthma-related emergency department visits in California, and explore how findings might inform Keva Health's patient education and alert design.

## Data

- California Health & Human Services: asthma emergency department visit measures
- U.S. Environmental Protection Agency: daily county-level Air Quality Index (AQI)
- Analytical period: 2011–2019

The project compared county-level asthma ER visits with the number of days AQI exceeded 50, average AQI, and days when ozone or PM2.5 were recorded as the primary pollutant under elevated AQI conditions.

## Analytical methods

- Exploratory data analysis and data merging in Tableau/Excel
- Six simple and multiple linear regression analyses in R
- Statistical significance tests and assessment of model R²
- Model selection by AIC for a multiple-regression specification

## Results presented

| Analysis | Reported result |
| --- | --- |
| Days with AQI above 50 vs. asthma ER visits | Positive association; R² approximately 0.26; p < 0.05 |
| Average AQI vs. asthma ER visits | Positive association; R² approximately 0.226; p < 0.05 |
| Ten counties with most elevated-AQI days | Positive association; R² approximately 0.45; p < 0.05 |
| Ozone-linked elevated-AQI days | Positive association; R² approximately 0.122; p < 0.05 |
| PM2.5-linked elevated-AQI days | Positive association; R² approximately 0.25; p < 0.05 |
| Multivariable AQI analysis | 2016 and 2019 average AQI selected by stepwise AIC in the presentation |

## Healthcare application

Proposed using air-quality information and observed associations to support physician education and **potential** AQI-based patient alerts in Keva Health's application.

## Interpretation and limitations

These are **observational associations**, not estimates of the number of ER visits caused by pollution. R² describes explained variation in the model and must not be interpreted as a causal percentage. County-level aggregates can be influenced by population size, access to healthcare, weather, demographic patterns, and other confounders. The presentation outlines an implementation proposal; it does not document a deployed alert feature.

## Primary sources

- [California Health & Human Services Open Data](https://data.chhs.ca.gov/)
- [EPA Air Quality System data](https://aqs.epa.gov/aqsweb/airdata/download_files.html)

*Prepared from the original 20-slide ALY6080 Group 7 presentation. This Markdown document is a readable presentation overview, not the original PDF.*
