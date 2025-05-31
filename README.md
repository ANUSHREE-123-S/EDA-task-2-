Task 2: Exploratory Data Analysis (EDA) – Titanic Dataset

This task involves performing initial data exploration and basic cleaning on the Titanic dataset as part of my internship project.

Dataset->

Source: Titanic Dataset (CSV format)

File used: Titanic-Dataset.csv


EDA Steps Performed->

1. Loaded the dataset using pandas.

2. Cleaned column names by stripping unwanted whitespaces.

3. Checked for column validity to ensure "Age" column exists.

4. Handled missing values:

If "Age" exists, missing values are filled with the median.

If not, a default "Age" column is added with value 0.

5. Displayed dataset information using .info() to inspect column types and null values.

 Libraries Used->

pandas

 Notes->

A debugging print was included to list all column names, ensuring "Age" is handled correctly.

This script ensures data consistency before further analysis or visualization.
