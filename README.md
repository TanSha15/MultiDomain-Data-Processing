
# Multi-Domain Data Cleaning and Preprocessing

## Overview

This repository contains data cleaning and preprocessing projects using datasets from multiple real-world platforms, including Amazon, Netflix, and Airbnb.

The primary objective is to clean raw datasets, improve data quality, maintain consistency, handle missing values, and prepare the data for further analysis and machine learning applications using Python.

## Datasets

The original datasets can be downloaded from Kaggle using the links below.

| Dataset | Kaggle Source | Description |
|---|---|---|
| Amazon | [Amazon Prime Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/amazon-prime-movies-and-tv-shows) | Dataset containing information about movies and TV shows available on Amazon Prime Video. |
| Netflix | [Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows) | Dataset containing information about movies and TV shows available on Netflix. |
| Airbnb | [New York City Airbnb Open Data](https://www.kaggle.com/datasets/dgomonov/new-york-city-airbnb-open-data) | Dataset containing information about Airbnb listings, hosts, prices, locations, and reviews in New York City. |

**Note:** The links above are commonly used Kaggle datasets. Verify that they match the exact CSV files used in this project before publishing.

## Project Objectives

- Practice data cleaning on real-world datasets.
- Improve data quality and consistency.
- Identify and remove unnecessary information.
- Handle missing and duplicate values.
- Standardize column names and data formats.
- Prepare datasets for Exploratory Data Analysis (EDA).
- Develop practical data preprocessing skills using Python.

## Data Cleaning and Preprocessing

The following operations were performed on the datasets.

### 1. Removing Redundant Columns

Removed unnecessary or redundant columns that did not contribute to the intended analysis.

### 2. Renaming Columns

Renamed columns to improve readability, maintain consistency, and make the datasets easier to work with.

### 3. Removing Duplicate Records

Identified and removed duplicate records to reduce data redundancy and improve dataset quality.

### 4. Cleaning Individual Columns

Cleaned individual columns by addressing formatting inconsistencies, irregular values, and other data quality issues where applicable.

### 5. Handling Missing Values

Removed rows containing missing (`NaN`) values to prepare the datasets for further processing.

### 6. Additional Data Transformations

Applied additional transformations as required to improve data consistency, structure, and usability.

## Technologies and Libraries Used

- **Python:** Core programming language for data processing.
- **Pandas:** Data manipulation, cleaning, and transformation.
- **NumPy:** Numerical operations and data handling.
- **Jupyter Notebook:** Interactive environment for executing and documenting the cleaning workflow.

## Workflow

The general workflow followed in this project is:

1. Load the original CSV dataset.
2. Inspect the dataset structure, columns, and data types.
3. Identify redundant columns and duplicate records.
4. Rename columns for consistency and readability.
5. Clean individual columns and address data quality issues.
6. Handle missing values.
7. Apply additional data transformations.
8. Export the cleaned dataset for further use.

## Repository Structure

The following is a suggested directory structure for organizing the project.

```text
MultiDomain-Data-Cleaning/
|
|-- Amazon/
|   |-- original_data.csv
|   |-- processed_data.csv
|   |-- data_cleaning.ipynb
|
|-- Netflix/
|   |-- original_data.csv
|   |-- processed_data.csv
|   |-- data_cleaning.ipynb
|
|-- Airbnb/
|   |-- original_data.csv
|   |-- processed_data.csv
|   |-- data_cleaning.ipynb
|
|-- README.md
```

The folder and file names above are illustrative. Update them to match the actual files in your repository.

## Expected Outcomes

- Cleaner and more consistent datasets.
- Reduced data redundancy.
- Standardized column names and formats.
- Better handling of missing values.
- Datasets prepared for further analysis and visualization.
- Practical experience with data preprocessing using Python.

## Future Improvements

- Perform Exploratory Data Analysis (EDA) on each cleaned dataset.
- Investigate outliers and unusual data distributions.
- Apply feature engineering techniques where appropriate.
- Create visualizations to identify patterns and trends.
- Compare dataset quality before and after cleaning.
- Document the impact of each cleaning operation.

## Acknowledgements

The original datasets are credited to their respective creators on Kaggle. Please refer to the individual dataset pages for licensing, attribution, and usage conditions.

## Author

**Tanish Sharma**

