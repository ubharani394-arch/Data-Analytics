# Task 1: Data Immersion & Wrangling

## Project Overview

This project demonstrates the process of Data Immersion and Data Wrangling using a sample sales dataset. The goal is to understand the dataset, identify data quality issues, clean the data, perform basic feature engineering, and prepare the data for analysis.

## Objectives

* Understand the structure of the dataset.
* Identify missing values and duplicate records.
* Clean and transform the data.
* Create new features for analysis.
* Perform basic data analysis.
* Export a cleaned dataset for future use.

## Technologies Used

* Python
* Pandas
* NumPy

## Dataset Description

The dataset contains the following information:

| Column Name | Description             |
| ----------- | ----------------------- |
| Order_ID    | Unique order identifier |
| Customer    | Customer name           |
| Age         | Customer age            |
| City        | Customer city           |
| Sales       | Sales amount            |

## Data Wrangling Steps

### 1. Dataset Creation

A sample sales dataset was created using Python dictionaries and converted into a Pandas DataFrame.

### 2. Data Exploration

* Displayed the original dataset.
* Examined dataset structure using `info()`.
* Checked column data types.

### 3. Missing Value Analysis

Identified missing values in:

* Age column
* City column

### 4. Data Cleaning

* Filled missing Age values using the mean age.
* Filled missing City values with "Unknown".
* Removed duplicate records.

### 5. Feature Engineering

Created a new column named `Age_Group`:

* Young (Age < 30)
* Adult (30 ≤ Age < 50)
* Senior (Age ≥ 50)

### 6. Basic Data Analysis

Performed:

* Summary statistics
* Total sales calculation
* Average sales calculation
* Sales analysis by city

### 7. Export Cleaned Data

The cleaned dataset was saved as:

`cleaned_sales_data.csv`

## Project Files

```text
Task1_Data_Wrangling/
│
├── data_wrangling.py
├── cleaned_sales_data.csv
└── README.md
```

## Output

The project produces:

* A cleaned dataset with no missing values.
* Duplicate records removed.
* A new Age_Group feature.
* Basic sales insights and summary statistics.

## Learning Outcomes

Through this project, I learned:

* Data exploration techniques.
* Handling missing values.
* Removing duplicates.
* Feature engineering.
* Data analysis using Pandas.
* Exporting cleaned datasets for further analysis.



