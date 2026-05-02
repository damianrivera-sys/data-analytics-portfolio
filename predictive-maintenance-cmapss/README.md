# Predictive Maintenance for Aircraft Engines - NASA CMAPSS

## Problem
Predict remaining useful life (RUL) of turbofan engines to optimize maintenance schedules.

## Dataset
- **Source:** NASA CMAPSS (Turbofan Engine Degradation Simulation)
- **Train:** 100 engines, 26 sensors, 3 operational settings
- **Goal:** Predict RUL at each cycle

## Approach
1. Exploratory Data Analysis (EDA)
2. Feature engineering (rolling statistics, sensor trends)
3. Model: Random Forest / XGBoost
4. Evaluation: RMSE

## Results
- RMSE: XX (to be updated after running)
- RUL predictions within ±XX cycles

## How to run
1. Clone this repo
2. Install dependencies: `pip install -r requirements.txt`
3. Open `notebooks/1.0_eda_modelling.ipynb` and run all cells

## Visuals
![Sensor degradation](images/sensor_degradation.png)

## Contact
Julio Damián Rivera – Aerospace & Data Analytics
