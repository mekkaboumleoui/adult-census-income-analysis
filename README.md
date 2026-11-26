# Adult Census Income Analysis

## Project Overview

This project explores the Adult Census Income dataset to study demographic, educational and professional characteristics associated with income levels.

The main objective is to analyze the factors associated with earning more than $50K per year and to develop machine learning classification models to predict income categories.

## Dataset

- **Source:** [Adult Census Income – Kaggle](https://www.kaggle.com/datasets/uciml/adult-census-income)
- **Initial observations:** 32,561
- **Number of variables:** 15
- **Target variable:** `income`
- **Target categories:** `<=50K` and `>50K`

## Project Workflow

### 1. Data Exploration
- Dataset overview and structure
- Variable types
- Descriptive statistics
- Initial data quality assessment

### 2. Data Cleaning
- Missing-value diagnosis
- Duplicate detection and removal
- Data preparation

### 3. Exploratory Data Analysis (EDA)
- Analysis of numerical and categorical variables
- Data visualization
- Study of relationships between individual characteristics and income
- Outlier detection using the IQR method

### 4. Machine Learning
- Logistic Regression
- Decision Tree
- Random Forest
- Model comparison
- Hyperparameter optimization using RandomizedSearchCV
- Model evaluation

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Repository Structure

```text
adult-census-income-analysis/
│
├── README.md
└── adult_census_income_analysis.ipynb
```

## Current Status

The exploratory analysis, data preparation and initial classification experiments have been carried out.

Further improvements are planned, including feature engineering, deeper model interpretation and additional evaluation.

## Author

Master's student in MADA  
Interested in Data Science, Statistical Analysis and Machine Learning.
