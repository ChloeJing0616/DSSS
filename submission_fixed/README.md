# DSSS Coursework – Crime Risk Modelling

## Overview
This project investigates which crime type best represents urban crime risk in London using spatial features and machine learning models.

## Files
- `notebook.ipynb` – main analysis (EDA, modelling, SHAP)
- `dataset_fe.csv` – processed dataset used for modelling
- `crime_rates.csv` – crime rates per LSOA
- `London_boundaries/` – spatial boundary data

## Data
Raw data were obtained from:
- London crime data
- ONS datasets (population, IMD)

Preprocessing steps (aggregation, cleaning, merging) were conducted prior to modelling.  
Due to file size constraints, only the final dataset is included.

## How to run
Open and run `notebook.ipynb` to reproduce results.

## Notes
All results in the report are reproducible from the provided dataset.