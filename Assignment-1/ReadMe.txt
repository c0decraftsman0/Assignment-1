Data Cleaning and Exploratory Data Analysis (EDA)

Overview

This project performs **data cleaning** and **exploratory data analysis (EDA)** on the `codeforces.tsv` dataset. The dataset contains various contest-related features, including numerical and categorical attributes. The goal is to preprocess the data by handling missing values, removing duplicates, detecting outliers, and performing statistical analyses.

Steps Performed

1. Data Cleaning
- Loading Data: The dataset is loaded from a `codeforces.tsv` file.
- Handling Missing Values:
  - Numerical columns are filled with their median values.
  - Categorical columns are filled with their mode values.
- Removing Duplicates: Duplicate rows are identified and removed.
- Outlier Detection & Treatment:
  - The Interquartile Range (IQR) method is used to detect outliers.
  - Outliers are replaced with `NaN` values for further handling.
- Standardizing Categorical Values:
  - String-based columns are converted to lowercase and stripped of extra spaces.

2. Exploratory Data Analysis (EDA)
- Summary Statistics: Computes mean, median, variance, skewness, etc.
- Univariate Analysis:
  - Histograms with KDE to visualize numerical feature distributions.
- Bivariate Analysis:
  - Correlation matrix heatmap to explore relationships between numerical variables.
- Multivariate Analysis:
  - Pair plots to analyze interactions between multiple features.
  - Box plots comparing categorical and numerical values.

Output
- A cleaned dataset ready for further analysis or modeling.
- Visual insights from histograms, box plots, and heatmaps.

