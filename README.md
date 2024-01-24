# Data Imputation and Exploratory Data Analysis (EDA) Project
![Data Science](https://img.shields.io/badge/Data%20Science-Exploration%20%7C%20Cleaning-blue)
![Python](https://img.shields.io/badge/Language-Python%203.8-yellow)

## Overview

This GitHub repository houses a comprehensive data cleaning and exploratory data analysis (EDA) project, showcasing the process of preparing and analyzing a dataset using Python. The project leverages popular libraries such as Pandas, NumPy, Seaborn, and Matplotlib, and it encompasses various essential steps in the data science pipeline.

## Project Highlights

### 1. **Data Loading and Initial Exploration:**

- **Libraries Used:** Pandas, NumPy, Seaborn, Matplotlib.
- **Data Source:** A CSV file ("online.csv").
- **Initial Exploration:** Displaying the top rows of the dataset and dropping unnecessary columns ("Unnamed: 0", "Unnamed: 13", '9', '#@%').

### 2. **Exploratory Data Analysis (EDA):**

- **Visualization Tools:** Seaborn, Matplotlib.
- **Insights Gained:**
  - Analyzing "Marital Status" and "Gender" distributions using count plots.
  - Employing boxplots to understand the relationship between "Gender," "Marital Status," and "Age."
  - Exploring demographic trends and outliers.

### 3. **Data Cleaning:**

- **Handling Missing Values:**
  - Imputing missing values in the "Age" column using mean, median, and mode methodologies.
- **Outlier Detection and Treatment:**
  - Identifying outliers in the "Age" column using Z-Score, IQR, and boxplots.
  - Treating outliers through trimming and capping methodologies.
- **Handling Categorical Values:**
  - Converting nominal and ordinal categorical variables into numerical format through one-hot encoding and label encoding.
- **Data Export:**
  - Saving the cleaned dataset to a new CSV file ("onlineclean.csv") for potential machine learning applications.

### 4. **Insights and Visualizations:**

- **Statistical Analysis:**
  - Utilizing descriptive statistics to understand the distribution of variables.
- **Visualizing Outliers:**
  - Comparing boxplots before and after outlier treatment for the "Age" column.

### 5. **How to Use:**

- Clone the repository to your local machine.
- Open the Jupyter Notebook or Python script in your preferred development environment.
- Run the script sequentially to execute the data cleaning and EDA steps.
- Explore the generated visualizations and cleaned dataset.

-----
## Conclusion

This project serves as a comprehensive guide for data cleaning and EDA, providing insights into handling missing values, outliers, and categorical variables. Feel free to use and modify this project script for your own datasets or as a reference for similar projects. Contributions and feedback are welcomed to enhance the project further.
-----
