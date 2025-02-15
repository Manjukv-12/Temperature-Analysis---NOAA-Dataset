# Temperature-Analysis---NOAA-Dataset
Overview

This project analyzes temperature data from the NOAA dataset to visualize temperature trends and station locations near Ann Arbor, Michigan, USA. The dataset includes temperature recordings from 2005 to 2015.

Dataset

temperature.csv: Contains station ID, date, temperature elements (TMAX, TMIN), and recorded values.

BinSize.csv: Includes metadata for weather stations, such as ID, latitude, longitude, elevation, and state.

Objectives

Visualize record high and low temperatures (2005-2014) using a line graph with shaded areas.

Identify and overlay 2015 temperature data that broke previous records.

Exclude February 29 (leap year) from the dataset.

Display station locations on an interactive map.

Provide a temperature summary for Ann Arbor in 2015.

Implementation

Data Preprocessing:

Load datasets and handle missing values.

Convert date columns and extract relevant features.

Separate historical (2005-2014) and 2015 data.

Temperature Visualization:

Compute record high and low temperatures per day.

Overlay 2015 data points that broke previous records.

Geospatial Mapping:

Plot station locations using latitude and longitude.

Statistical Summary:

Generate boxplots summarizing 2015 temperature trends.

Dependencies

Python (Pandas, NumPy, Matplotlib, Seaborn, Folium, Datetime)

Usage

Load and run the Jupyter Notebook.

Ensure datasets are in the same directory as the script.

View generated plots and interactive maps.

Output

Line graph of record high/low temperatures.

Scatter plot overlay for 2015 record-breaking temperatures.

Interactive station map (saved as station_map.html).

Boxplot summarizing temperature trends in 2015.
