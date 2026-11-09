# Week 2 – Data Preprocessing and Feature Engineering

## Project Title
AI-Based Bike Rental Demand Prediction Using Machine Learning

## Overview
This folder contains the Week 2 implementation of the bike rental demand prediction project. The main objective of this phase is to clean, analyze, and transform the Capital Bikeshare trip-history dataset into a structured hourly demand dataset suitable for machine learning.

## Dataset
- **Source:** Capital Bikeshare System Data
- **Data period:** October 2025
- **Original file:** `202510-capitalbikeshare-tripdata.csv`
- **Original records:** 624,869
- **Original features:** 13

Official dataset source: https://capitalbikeshare.com/system-data

The original trip-history CSV is not included in this folder. It can be downloaded from the official source.

## Files Included

| File | Description |
|---|---|
| `Week2_Bike_Rental_Preprocessing.ipynb` | Jupyter Notebook containing data inspection, cleaning, exploratory analysis, feature engineering, visualizations, and preprocessing. |
| `processed_bike_rental_demand_october_2025.csv` | Processed hourly bike rental demand dataset for October 2025. |

## Tools and Libraries
- Python
- Google Colab / Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Preprocessing Activities
1. Dataset loading and inspection.
2. Duplicate and invalid timestamp checks.
3. Missing-value handling.
4. Ride duration calculation.
5. Outlier detection using the IQR method.
6. Exploratory data analysis and visualization.
7. Aggregation of individual rides into hourly rental demand.
8. Feature engineering, including hour, day of week, month, weekend, rush hour, and cyclic time features.
9. Categorical encoding demonstration.
10. Numerical feature scaling using StandardScaler.
11. Final validation and CSV export.

## How to Run the Notebook

1. Download `Week2_Bike_Rental_Preprocessing.ipynb`.
2. Download the October 2025 Capital Bikeshare trip-history CSV from the official source.
3. Open https://colab.research.google.com/.
4. Upload and open the notebook.
5. Run the notebook cells in order.
6. When prompted, upload the original CSV file.
7. After successful execution, the notebook generates the processed hourly dataset.

## Output
The main output is:

`processed_bike_rental_demand_october_2025.csv`

It contains hourly rental counts and engineered time-based features. The `rental_count` column represents the number of rides starting during each hour.

## Project Progress
- Week 1: Project research and planning.
- Week 2: Data preprocessing and feature engineering.

## Next Phase
The processed dataset will be used in the upcoming machine learning model development phase to build and evaluate bike rental demand prediction models.
