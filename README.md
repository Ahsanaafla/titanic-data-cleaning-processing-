Titanic Data Cleaning & Preprocessing
Objective
Learn how to clean and prepare raw data for machine learning models using basic Python and data science libraries.

Dataset
File Used: Titanic-Dataset.csv

Contains passenger data like age, class, gender, fare, and survival status.

Tools & Libraries
Python

Pandas – for data handling

NumPy – for numerical operations

Matplotlib/Seaborn – for visualization

Preprocessing Steps
Import & Explore Dataset

Load dataset using pandas.read_csv()

View columns, data types, shape, null values, and unique counts

Handle Missing Values

Numeric columns → Fill missing values with mean

Categorical columns → Fill missing values with mode

Drop Duplicates

Remove repeated rows for cleaner data

Encode Categorical Features

Convert object columns to category codes using .astype('category').cat.codes

Standardize Numerical Features

Visualize & Remove Outliers

Use boxplots to visualize outliers

Apply IQR method to remove them:

Outliers<Q1−1.5×IQRor>Q3+1.5×IQR

Outcome
A cleaned, standardized dataset ready for machine learning or analysis — no missing values, no outliers, and all features numeric.

Run This Project
Open in Google Colab or Jupyter and run the full script in one cell. Replace 'Titanic-Dataset.csv' with your file name if needed.
