![](https://github.com/Sarthakkk16/Air-Quality-Index-Analysis/blob/main/air-quality-index-aqi-measurement-600nw-2418628893.webp)

# Air-Quality-Index-Analysis
This repository contains a complete workflow for Air Quality Index (AQI) forecasting using Python.The project demonstrates advanced data preprocessing, exploratory analysis, and time-series modeling using Facebook Prophet.

# Dataset - ![](https://archive.ics.uci.edu/dataset/360/air+quality)

# Project Highlights
**1. Data Preprocessing**

Loaded raw AQI dataset using pandas

Identified hidden missing values (-200)

Converted them to NaN and imputed using column-wise mean

Verified dataset integrity with EDA

**2. Exploratory Data Analysis (EDA)**

Trend inspection

AQI distribution analysis

Missing data visualization

Relationship checks between variables

**3. Time Series Forecasting**

Implemented Facebook Prophet to forecast AQI:

Handled date-time conversions

Created time-series structure compatible with Prophet

Visualized future predictions

Trend & seasonality components shown using Prophet plots

**4. Additional Workflows**

Regression task setup for AQI prediction

Feature selection & model-ready cleaned dataset
