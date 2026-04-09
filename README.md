# Task1
 # Data Cleaning & Preprocessing - Titanic Dataset

## Project Overview

This project focuses on cleaning and preprocessing raw data to make it suitable for machine learning models. 

## Objective

* Handle missing values
* Convert categorical data into numerical form
* Normalize/standardize features
* Detect and remove outliers

## Dataset

* Dataset: Titanic Dataset
* Source: Public dataset (GitHub / Kaggle)

## Steps Performed

### 1. Data Exploration

* Checked dataset structure using `.info()`
* Identified missing values using `.isnull().sum()`

### 2. Handling Missing Values

* Filled Age with median
* Filled Embarked with mode
* Dropped Cabin column

### 3. Encoding Categorical Variables

* Converted Sex into numeric values
* Applied one-hot encoding on Embarked

### 4. Feature Scaling

* Used StandardScaler to normalize numerical features

### 5. Outlier Detection & Removal

* Visualized using boxplot
* Removed outliers using IQR method

## Technologies Used

* Python
* Pandas
* NumPy
* Seaborn
* Matplotlib
* Scikit-learn

## Output

* Cleaned dataset ready for machine learning
* File generated: `cleaned_titanic.csv`

## Key Learnings

* Importance of data cleaning
* Handling missing values effectively
* Encoding categorical variables
* Feature scaling techniques
* Outlier detection methods
