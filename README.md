# Netflix Data Cleaning Project

## Overview

This project focuses on cleaning and preprocessing the Netflix Titles dataset using Python and Pandas. The goal is to transform raw data into a clean, structured, and analysis-ready dataset by handling common data quality issues.

## Objectives

* Load and explore the dataset
* Handle missing values
* Remove duplicate records
* Standardize column names
* Correct data types
* Detect and handle outliers using the IQR method
* Encode categorical variables
* Validate the cleaned dataset
* Export the cleaned dataset to a new CSV file

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

## Dataset

* Name:  Netflix Titles Dataset
* Format: CSV
* Source: Kaggle

## Project Structure

```text
Netflix-Data-Cleaning-Project/
│── Netflix_Data_Cleaning.ipynb
│── netflix_titles.csv
│── cleaned_netflix_dataset.csv
│── README.md
│── requirements.txt
```

## Data Cleaning Steps

1. Loaded the dataset using Pandas.
2. Explored the data with `head()`, `info()`, and `describe()`.
3. Identified missing values and visualized them using a heatmap.
4. Filled or removed missing values based on each column.
5. Removed duplicate rows.
6. Renamed columns to snake_case.
7. Converted columns to appropriate data types.
8. Detected and handled outliers using the IQR method.
9. Encoded categorical variables using One-Hot Encoding.
10. Validated the cleaned dataset with summary statistics.
11. Exported the cleaned dataset as `cleaned_netflix_dataset.csv`.

## Results

* Missing values handled successfully.
* Duplicate records removed.
* Column names standardized.
* Data types corrected.
* Outliers detected and handled.
* Categorical variables encoded.
* Clean dataset exported successfully.


## Output Files

* `cleaned_netflix_dataset.csv` – Cleaned dataset
* `Netflix_Data_Cleaning.ipynb` – Complete notebook with all cleaning steps

## Author

Rohan Mahajan
Internship: WeIntern
Project: Netflix Data Cleaning Project
