# MIS505_Module_8
This repository is for Module 8 Portfolio Part 2.
# Zimbabwe Primary Enrollment and GDP Analysis (2001–2020)

## Overview

This repository contains the files developed for the **MIS 505 – Data Wrangling Module 8 Portfolio Project**. The objective of the project was to investigate whether primary school enrollment in Zimbabwe increased as gross domestic product (GDP) per capita improved between 2001 and 2020.

Data from the United Nations education dataset and the World Bank World Development Indicators (WDI) dataset were cleaned, transformed, merged, and analyzed using Python in a Jupyter Notebook environment through Anaconda. The final dataset was exported to a CSV file, stored in a SQLite database, and documented with a JSON metadata file.

## Repository Contents

* **`zimbabwe_education_gdp.csv`** – Cleaned dataset containing annual primary school enrollment and GDP per capita for Zimbabwe from 2001–2020.
* **`zimbabwe_education_gdp.db`** – SQLite database containing the cleaned dataset.
* **`zimbabwe_education_gdp_metadata.json`** – Metadata file describing the dataset attributes, including column names, data types, and descriptions.
* **`Module8Portfolio.ipynb`** – Jupyter Notebook containing the complete data wrangling workflow and analysis.
* **`Module8Portfolio.html`** – HTML export of the completed Jupyter Notebook (if included).

## Tools and Technologies

* Python
* Jupyter Notebook (Anaconda)
* pandas
* NumPy
* Matplotlib
* SQLite

## Data Sources

* United Nations education dataset (Primary School Enrollment)
* World Bank World Development Indicators (WDI) dataset (GDP per Capita)

## Project Summary

The project demonstrates key data wrangling techniques, including:

* Loading and validating datasets
* Filtering data by country
* Selecting relevant variables
* Handling missing values using mean imputation
* Merging multiple datasets
* Exporting a cleaned dataset to CSV
* Creating and verifying a SQLite database
* Visualizing trends using line and scatter plots
* Evaluating the relationship between variables using the Pearson correlation coefficient

## Author

Shelene Taylor

Colorado State University Global
MIS 505 – Data Wrangling
