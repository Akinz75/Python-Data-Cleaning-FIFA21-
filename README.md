# Python-Data-Cleaning-FIFA21

## Overview
This repository houses the code and documentation for the data cleaning of the FIFA21 dataset. The aim is to improve the dataset, which features information about players from the FIFA21 video game.

## Dataset Source and Summary
The FIFA 21 dataset used here originated from a data cleaning challenge on X (Twitter) in which I participated. It includes player attributes, statistics, and related data.

The original dataset contains over 18,000 player records. Each entry represents a player and includes attributes such as name, age, nationality, club, overall rating, and more.

## Data Issues Identified
Data Issues Identified
During the initial review, several problems were found, including:

- Missing values: The Hits and Loan Date End columns had gaps that needed attention.
- consistent formatting: Variations across columns, like the differing units in the Height and Weight fields, required standardization.

## Tools Utilized
Key tools used in the data cleaning process included:

- Python: For the data cleaning tasks.
- Pandas: For manipulating, cleaning, and managing missing data.
- NumPy: For mathematical operations during the cleaning.
- Jupyter Notebooks: For interactive coding and documentation.

## Data Cleaning Approach
The cleaning process involved the following:

1. **Data Familiarization:** Examining the dataset to understand its structure and meaning. Since there was no accompanying data dictionary, I created one using online sources.
2. **Data Exploration:** Performing Exploratory Data Analysis (EDA) to identify trends and issues.
3. **Handling Missing Data:** It was clear from EDA that the missing values in Hits and Loan Date End were legitimate. Hits tracked how often a player was searched, so some records were naturally blank. Similarly, Loan Date End was blank for players not under loan contracts.
4. **Formatting Standardization:** Addressed issues like inconsistent units in Height and Weight using transformations and normalization.
5. **Validation and Quality Assurance:** The cleaned data underwent checks to ensure its accuracy and consistency.

























