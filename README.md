# Multi-Domain Data Processing

## Overview

This repository contains data cleaning and preprocessing projects using datasets from Amazon, Netflix, and Airbnb.

The objective is to improve data quality, maintain consistency, remove unnecessary information, and prepare datasets for further analysis and machine learning applications using Python.

## Datasets

The original datasets can be downloaded from Kaggle using the links below.

| Dataset | Kaggle Source | Description |
|---|---|---|
| Amazon | [Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) | Movies and TV shows available on Amazon Prime Video. |
| Netflix | [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) | Information about movies and TV shows available on Netflix. |
| Airbnb | [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) | Airbnb listings, hosts, prices, locations, and reviews in New York City. |

**Note:** Verify that these links match the exact datasets used in your project.

## Data Cleaning and Preprocessing

The following operations were performed on the datasets:

- Removed redundant and unnecessary columns.
- Renamed columns for better readability and consistency.
- Identified and removed duplicate records.
- Cleaned individual columns to address formatting and consistency issues.
- Removed rows containing missing (`NaN`) values.
- Applied additional data transformations to improve data quality and consistency.

## Technologies Used

- Python
- Pandas
- NumPy
- Jupyter Notebook

## Repository Structure

```text
MultiDomain-Data-Cleaning/
├── Amazon/
│   ├── original_data.csv
│   ├── processed_data.csv
│   └── data_cleaning.ipynb
├── Netflix/
│   ├── original_data.csv
│   ├── processed_data.csv
│   └── data_cleaning.ipynb
├── Airbnb/
│   ├── original_data.csv
│   ├── processed_data.csv
│   └── data_cleaning.ipynb
└── README.md
