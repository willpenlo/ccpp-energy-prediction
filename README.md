# CCPP Energy Output Prediction

## Overview
Machine learning project predicting net hourly electrical energy output 
of a Combined Cycle Power Plant using ambient environmental readings.

## Dataset
- 9,568 hourly readings
- Features: Ambient Temperature, Exhaust Vacuum, Ambient Pressure, Relative Humidity
- Target: Net Energy Output (PE)

## Models & Results
| Model | R² | MAE | MSE |
|-------|-----|-----|-----|
| Linear Regression | 0.9275 | 3.65 | 21.24 |
| Random Forest | 0.9617 | 2.39 | 11.22 |

## Key Finding
Ambient Temperature showed strongest correlation with PE (-0.948)
