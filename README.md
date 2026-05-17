# Child Welfare ML — Telangana, India

Machine learning analysis of child welfare indicators across Telangana, India. Uses government nutrition surveillance data to model and predict malnutrition indicators (wasting, stunting, underweight) across districts.

## Overview
This project analyzes multi-year data from Telangana's ICDS (Integrated Child Development Services) program:
- **Wasting, Stunting & Underweight** trend analysis (2020–2021)
- **Literacy Rate** correlations with child welfare outcomes
- **Rainfall & Temperature** impact on nutrition indicators
- **Road infrastructure & Godown availability** vs malnutrition rates
- **Crop yield** analysis as a socio-economic predictor

## Notebooks
| Notebook | Description |
|---|---|
| `Childfinal_1.ipynb` | Main ML pipeline — feature engineering, model training |
| `Childfinal_UW.ipynb` | Underweight-specific analysis and prediction |
| `LiteracyRate.ipynb` | Literacy rate EDA and correlation analysis |
| `RainfallAndTemp.ipynb` | Climate factors vs child welfare indicators |
| `RoadAndGodowns.ipynb` | Infrastructure impact analysis |
| `Crops.ipynb` | Agricultural output and food security analysis |

## Data
Monthly government reports across 33 Telangana districts (April 2020 – March 2021).

## Tech Stack
Python · pandas · scikit-learn · matplotlib · seaborn · numpy

## Author
Yogeshvar Reddy Kallam · UG Capstone Project
