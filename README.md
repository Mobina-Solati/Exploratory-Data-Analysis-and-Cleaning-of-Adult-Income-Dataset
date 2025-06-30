Exploratory Data Analysis and Cleaning of Adult Income Dataset

Overview

This project focuses on the initial exploration and cleaning of the Adult Income dataset, which contains demographic and employment-related information to predict income levels. The dataset is analyzed to identify missing values, duplicates, outliers, and inconsistencies, followed by data preprocessing steps to improve its quality for further analysis or modeling.

Project Details

Dataset: Adult Income Dataset
Source: Available via public repositories (e.g., UCI Machine Learning Repository)
Date: June 30, 2025
Tools: Python, Pandas, Matplotlib, Seaborn, NumPy, Scipy, Scikit-learn, RapidFuzz
Objective: Perform exploratory data analysis (EDA) and data cleaning to prepare the dataset for machine learning tasks.

Features

Columns: age, workclass, fnlwgt, education, education-num, marital-status, occupation, relationship, race, sex, capital-gain, capital-loss, hours-per-week, native-country, income
Rows: 50,064 entries
Data Types: Mix of object (categorical) and float64 (numeric)

Analysis and Cleaning Steps

Data Loading: Loaded the dataset into a Pandas DataFrame for analysis.
Initial Exploration: Reviewed column names, first row, shape, and data types.
Missing Values: Identified and quantified missing data in each column.
Duplicate Values: Detected and reported duplicate rows.
Outlier Detection: Visualized potential outliers using box plots for numeric columns.
Data Correction: Applied corrections to categorical data (e.g., education, occupation, workclass) to standardize values.
Visualization: Compared raw and cleaned data distributions for key columns using bar charts.

Results

Missing Values: Significant missing data in workclass (11,910), fnlwgt (12,681), and other columns.
Duplicates: 1,229 duplicate rows identified.
Outliers: Detected in numeric columns like fnlwgt, capital-loss, and hours-per-week.
Cleaning: Standardized categorical data and visualized improvements.

Usage

Clone the repository: git clone <repository-url>
Install dependencies: pip install -r requirements.txt
Run the Jupyter notebook: jupyter notebook DM_phase1.ipynb

Requirements

Python 3.x
pandas
matplotlib
seaborn
numpy
scipy
scikit-learn
rapidfuzz

