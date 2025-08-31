# Data Cleaning Walkthrough (East African E-Commerce Dataset)

## Overview

This repository contains a Jupyter Notebook that demonstrates the process of cleaning and preparing a real-world dataset step by step. 

The dataset used in this walkthrough is a **synthetic East African E-Commerce dataset**. It has been generated to simulate real-world data while ensuring no sensitive or private information is included. The dataset contains customer information such as:
- Customer ID
- Name (First and Last)
- Email
- Registration and Last Login Dates
- Country and City
- Total Spent
- Currency
- Age
- Phone Number


## Features

The notebook walks through the following steps:

1. **Loading and Exploring the Dataset**  
   - Load the dataset and inspect its structure and contents.

2. **Renaming and Standardizing Columns**  
   - Ensure column names are consistent and standardized.

3. **Handling Missing Values**  
   - Identify and handle missing data using appropriate techniques (e.g., imputation, removal).

4. **Removing Duplicates**  
   - Detect and remove duplicate rows to ensure data integrity.

5. **Cleaning Text, Numbers, and Dates**  
   - Standardize text fields, clean numerical data, and ensure date fields are in a consistent format.

6. **Detecting and Handling Outliers**  
   - Identify outliers in numerical columns and handle them appropriately.

7. **Feature Engineering**  
   - Create new features to enhance the dataset's usability for analysis.

8. **Exporting the Cleaned Dataset**  
   - Save the cleaned dataset to a CSV file for further analysis.

## Dataset

The dataset used in this walkthrough is an East African E-Commerce dataset. It contains customer information such as:
- Customer ID
- Name (First and Last)
- Email
- Registration and Last Login Dates
- Country and City
- Total Spent
- Currency
- Age
- Phone Number

The dataset is located in the `datacleaning` directory.

## How to Use

1. Clone this repository to your local machine.
2. Open the `data_cleaning_walkthrough.ipynb` notebook in Jupyter Notebook or JupyterLab.
3. Follow the steps in the notebook to clean and prepare the dataset.
4. The cleaned dataset will be saved as `eastafrican-ecommerce-dataset.cleaned.csv` in the `datacleaning` directory.

## Prerequisites

Ensure you have the following Python libraries installed:
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`
- `fuzzywuzzy`
- `Pillow`

You can install the required libraries using the following command:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn fuzzywuzzy Pillow