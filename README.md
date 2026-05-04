# DSSS Assessment – CASA0006

## Overview

This project investigates which crime type best represents urban crime risk in London using spatial features and machine learning models.

## Repository Structure
- `submission/` - data folder
  - `lsoa_crime_rates.csv` - crime rates per LSOA
  - `population.csv` - population data
  - `final_dataset.csv` - processed dataset with urban features
  - `imd_lsoa.csv` - LSOA-level Index of Multiple Deprivation (IMD 2019)
  - `dataset_fe.csv` - feature-engineered dataset for modelling
  - `London_boundaries/` - spatial boundary data
- `Template_submission_CASA0006.ipynb` - main analysis notebook (EDA, modelling, SHAP)


## How to Run

Open and run `Template_submission_CASA0006.ipynb`. Data is loaded automatically from GitHub raw URLs — no local setup needed.

## Data Sources

- London crime data
- ONS datasets (population, IMD)
- Urban features: population exposure, road network, POI density

## Notes

All results in the report are reproducible from the provided datasets.
EOF