# Project Overview: Predicting Personal Loan Acceptance for Thera Bank Customers

## Introduction:

This project aims to assist Thera Bank in devising targeted marketing strategies to convert liability customers into personal loan customers while retaining them as depositors. Leveraging machine learning techniques, we analyze customer demographic and banking relationship data to predict the likelihood of a customer accepting a personal loan offer. By understanding the key factors influencing loan acceptance, Thera Bank can optimize its marketing campaigns to increase success rates while minimizing budget expenditure.

### Data Loading and Inspection:
The dataset 'Bank_Personal_Loan_Modelling.xlsx' containing customer data was loaded into a DataFrame.
Basic checks such as displaying the first few rows, checking shape, and checking for missing values were performed.

### Handling Missing Values:
No missing values were found in the dataset, so imputation or removal was not necessary.

### Feature Selection:
The columns 'ID' and 'ZIP Code' were dropped as they were not relevant for analysis.
Exploratory Data Analysis (EDA):
Numerical summaries including mean, standard deviation, and skewness were calculated.

Histograms and boxplots were plotted to visualize the distribution and spread of numerical features.

A distribution plot was created to visualize the distribution of the 'Experience' column.

Negative values in the 'Experience' column were replaced with the mean value.

Correlation analysis was performed to identify relationships between features and the target variable ('Personal Loan').

Heatmap was plotted to visualize correlations between numerical features.

Feature engineering was performed on the 'Education' column to categorize education levels.

Pie charts were created to visualize the distribution of education levels and account holder categories.

Box plots were created to visualize the relationship between education levels and income, and the distribution of income and credit card average with respect to personal loan acceptance.

Count plots were created to visualize the distribution of binary categorical variables with respect to personal loan acceptance.

### Outlier Detection and Treatment:
The Interquartile Range (IQR) method was used to detect outliers.

No specific treatment was performed for outliers in this summary.

### Feature Transformation:

Log-normal transformation was applied to the 'Income' and 'CCAvg' columns to make their distributions more symmetrical.
