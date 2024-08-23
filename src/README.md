# Source Code

This directory contains the main source code for the project. It includes modules for data processing, analysis, and visualization.

## Contents
 statistical measures:

- **Mean:** The average value of the column.
- **Median:** The middle value when the column is sorted.
- **Mode:** The most frequently occurring value.
- **Standard Deviation:** A measure of the amount of variation or dispersion.
- **Variance:** The squared standard deviation.
- **Skewness:** The measure of asymmetry in the distribution.
- **Kurtosis:** The measure of the "tailedness" of the distribution.
- **Min and Max:** The minimum and maximum values.
- **Quartiles (25th, 50th, 75th):** Values that divide the data into four equal parts.

## Data Quality Check

### Missing Values

Check for missing values in all columns, with particular focus on:

- **GHI (Global Horizontal Irradiance)**
- **DNI (Direct Normal Irradiance)**
- **DHI (Diffuse Horizontal Irradiance)**
- **ModA (Sensor A)**
- **ModB (Sensor B)**
- **WS (Wind Speed)**
- **WSgust (Wind Gust Speed)**

### Outliers and Incorrect Entries

Identify outliers and incorrect entries, particularly:

- **GHI, DNI, DHI:** Look for values that deviate significantly from expected ranges.
- **ModA, ModB:** Inspect sensor readings for anomalies.
- **WS, WSgust:** Check for unrealistic wind speed values (e.g., extreme highs or lows).
- **Negative Values:** Ensure no negative values where only positives should exist.

## Time Series Analysis

- **Plot Line Graphs or Area Plots:** For GHI, DNI, DHI, and Tamb (ambient temperature) to observe patterns:
  - **By Month:** Identify seasonal trends.
  - **Throughout the Day:** Detect daily patterns or anomalies.
  - **Anomalies:** Look for peaks in solar irradiance or temperature fluctuations.

## Evaluate Impact of Data Cleaning

Assess the effect of the 'Cleaning' column on sensor readings (ModA, ModB) over time to understand how cleaning procedures influence data quality.

## Correlation Analysis

- **Heatmaps or Pair Plots:** Visualize correlations between:
  - **GHI, DNI, DHI (solar radiation components)**
  - **TModA, TModB (temperature measures)**
- **Scatter Matrices:** Investigate the relationship between wind conditions (WS, WSgust, WD) and solar irradiance.

## Wind Analysis

- **Polar Plots:** Identify trends and significant wind events by showing:
  - **Wind Speed Distribution**
  - **Wind Direction Distribution**
  - **Wind Direction Variability**

## Temperature Analysis

- **Examine Relative Humidity (RH):** Explore its influence on temperature readings and solar radiation.

## Histograms

- **Create Histograms:** For variables such as GHI, DNI, DHI, WS, and temperatures to visualize the frequency distribution.

## Z-Score Analysis

- **Calculate Z-Scores:** To identify data points significantly different from the mean, flagging potential anomalies.

## Bubble Charts

- **Explore Relationships:** Between variables such as GHI vs. Tamb vs. WS, with bubble size representing an additional variable like RH (Relative Humidity) or BP (Barometric Pressure).

## Data Cleaning

- **Handle Anomalies and Missing Values:** Based on the initial analysis, clean the dataset:
  - **Comments Column:** Address any columns with entirely null values.