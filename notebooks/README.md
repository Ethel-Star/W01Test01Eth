# Notebooks Directory

## Overview

The `notebooks/` directory contains Jupyter Notebooks used for exploratory data analysis, data visualization, and modeling. These notebooks provide interactive and visual insights into the dataset, and are intended to assist in understanding data patterns, trends, and relationships.

## Purpose

The notebooks in this directory aim to:

- Explore and analyze the dataset through various statistical and visual techniques.
- Provide interactive analysis to uncover insights and trends.
- Serve as a reference for data exploration and preliminary modeling.

## Notebooks

### 1. data_exploration.

**Purpose:** Perform initial data exploration, including statistical summaries, data quality checks, and basic visualizations.

**Key Sections:**
- Data loading and initial inspection
- Descriptive statistics for numeric columns
- Missing values and outliers detection
- Basic plots and distributions

### 2. time_series_analysis.

**Purpose:** Analyze time series data for patterns and trends, focusing on variables like GHI, DNI, DHI, and temperature.

**Key Sections:**
- Time series plots for solar irradiance and temperature
- Monthly and daily trends
- Anomaly detection in time series data

### 3. correlation_analysis.

**Purpose:** Investigate the correlations between different variables and visualize relationships using heatmaps and scatter matrices.

**Key Sections:**
- Correlation heatmaps
- Pair plots for solar radiation and temperature measures
- Scatter matrices for wind conditions and solar irradiance

### 4wind_and_temperature_analysis

**Purpose:** Examine wind data and temperature relationships, including polar plots for wind speed and direction, and temperature influences.

**Key Sections:**
- Polar plots for wind speed and direction
- Temperature analysis in relation to relative humidity
- Visualizations of wind patterns and temperature effects

### 5.advanced_visualizations

**Purpose:** Create advanced visualizations such as bubble charts and histograms to explore complex relationships and data distributions.

**Key Sections:**
- Bubble charts for multi-variable relationships
- Histograms for frequency distribution of key variables
- Z-score analysis to identify anomalies

## Instructions

To run the notebooks:

1. Ensure you have Jupyter Notebook or JupyterLab installed. You can install it via Anaconda or pip:
   ```bash
   pip install jupyterlab
