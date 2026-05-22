# Student Academic Performance Analysis

## Introduction
Educational institutions generate large volumes of student data covering academic scores, attendance, behavioral patterns, and socioeconomic indicators. Raw educational datasets often contain missing values, inconsistent formats, and redundant features that reduce the quality of analysis and modeling. Proper data cleaning and preprocessing techniques are therefore essential to transform raw student data into a structured and analysis-ready format.

This project focuses on performing comprehensive data cleaning, preprocessing, exploratory data analysis, and feature engineering using the Students Grading Dataset. Techniques such as handling missing values, outlier detection, encoding categorical variables, feature scaling, and feature engineering were applied to improve data quality and prepare the dataset for predictive modeling.

## Problem Statement
Student performance datasets often contain missing entries, categorical inconsistencies, and redundant features that make them unsuitable for direct use in machine learning pipelines. The Students Grading Dataset contains issues such as missing values in attendance and assignment scores, mixed categorical and numerical variables, and overlapping features that reduce data quality and reliability. Without proper preprocessing, these issues can negatively impact model performance and analytical outcomes.

The objective of this project is to preprocess and analyze the student dataset by applying systematic data cleaning, transformation, visualization, and feature engineering techniques. The project aims to convert the raw dataset into a clean, encoded, scaled, and machine-learning-ready format while extracting meaningful insights related to student performance and academic outcomes.

## Methodology
The project followed a structured data preprocessing and analysis workflow across five sections. Initially, the dataset was loaded into a Pandas DataFrame and irrelevant PII columns were removed. Basic data understanding techniques such as checking dataset dimensions, column types, and summary statistics were performed.

Missing values in categorical and numerical columns were handled using mode and mean imputation respectively. Outlier detection using the IQR method and box plot visualization confirmed no significant outliers were present, and all records were retained.

Exploratory Data Analysis (EDA) was conducted through univariate histograms, categorical count plots, a correlation heatmap, and group-level box plots. Feature engineering was applied to create a composite Performance_Index from the three major exam scores. Categorical variables were converted into numerical format using Ordinal Encoding and One-Hot Encoding. StandardScaler was applied to normalize continuous numerical features.

## Dataset Description
The dataset used in this project is the Students Grading Dataset containing academic performance records of undergraduate students.

| Attribute | Details |
|-----------|---------|
| Dataset Name | Students Grading Dataset (Biased) |
| Source | Kaggle |
| Number of Records | 5,000 |
| Number of Features | 23 (after preprocessing) |
| Data Type | Structured Educational Data |

The dataset includes student demographics, academic scores, behavioral metrics, and socioeconomic indicators. It contains both numerical and categorical variables and includes missing values, making it appropriate for demonstrating real-world data preprocessing tasks.

## Data Acquisition
The dataset was obtained from Kaggle in CSV format and imported into the Python environment using the Pandas library. The dataset was loaded into a Pandas DataFrame using the `read_csv()` function. Four PII columns (Student_ID, First_Name, Last_Name, Email) were dropped immediately, leaving 19 analysis-ready columns for preprocessing.

## Analysis
Please refer to the notebook (.ipynb) file for full analysis.

## Conclusion
Please refer to the notebook (.ipynb) file for conclusion.

## Files

| File | Description |
|------|-------------|
| `student_performance_analysis.ipynb` | Full preprocessing and EDA notebook |
| `cleaned_student_dataset.csv` | Final cleaned, encoded, and scaled dataset |

## Tools & Libraries
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## References
- Kaggle — Students Grading Dataset  
  https://www.kaggle.com/datasets/mahmoudelhemaly/students-grading-dataset

- Pandas Documentation  
  https://pandas.pydata.org/docs/

- Scikit-learn Documentation  
  https://scikit-learn.org/stable/

- Matplotlib Documentation  
  https://matplotlib.org/stable/

- Seaborn Documentation  
  https://seaborn.pydata.org/

- NumPy Documentation  
  https://numpy.org/doc/
