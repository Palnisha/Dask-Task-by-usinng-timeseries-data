# Dask Task

*COMPANAY* : CODTECH IT SOLUTION 

*NAME* : NISHA PAL

*INTERN ID* : CT6WKRM

*DOMAIN* : DATA ANALYST

*DURATION* : 8 WEEKS

*MENTOR* : NEELA SANTOSH

# Dataset : Created a Dataset 

# Project Overview: Dask-Based Time Series Data Processing

This project demonstrates how to handle time series data with Dask, including creating a sample dataset, preprocessing, resampling, filtering, and visualizing results. By using Dask's parallel computation features, we can efficiently process and analyze large time series datasets.

# 🛠️ Key Components of the Project

## Dataset Creation & Loading

Generates 1 million rows of synthetic time-series data.
Uses pandas to create a DataFrame and then converts it into a Dask DataFrame for parallel processing.
Loads data from CSV and Parquet formats using Dask.

## Preprocessing & Cleaning

Converts the timestamp column into a datetime format.
Drops missing values using dropna().
Adds a new ‘date’ column for grouping.

## Computation Using Dask

Resamples the dataset by day and calculates the mean value for each category.
Filters data for January 2025.
Performs delayed computations using dask.delayed for efficient processing.
Computes sum, difference, and product of numerical columns.

## Visualization

 Plots daily averages for a specific category (Category A).
Uses Matplotlib to generate line charts.

![Image](https://github.com/user-attachments/assets/e67c1776-a380-4714-b990-5c671729f089)

## Performance Optimization

Compares Dask vs. Pandas computation time for efficiency.
Uses Dask’s distributed computing for large datasets.

## Summary of this project

![Image](https://github.com/user-attachments/assets/bdaea53c-d44e-4545-9bd9-bb33c7c207df)

