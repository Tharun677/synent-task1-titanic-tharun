# Titanic Data Cleaning & Preprocessing

## 📌 Project Overview
This project focuses on cleaning and preprocessing the Titanic dataset to make it ready for analysis and machine learning applications. Data cleaning is an essential step in the Data Science workflow, as raw datasets often contain missing values, duplicate records, and inconsistent formats.

## 🎯 Objective
The objective of this project is to:
- Handle missing values
- Remove duplicate records
- Rename columns for better readability
- Convert data types where necessary
- Prepare a clean dataset for further analysis

## 📂 Dataset
Dataset Used: Titanic Dataset

Source:
https://www.kaggle.com/datasets/yasserh/titanic-dataset

## 🛠️ Tools & Technologies
- Python
- Pandas
- NumPy
- Google Colab
- GitHub

## 📋 Steps Performed

### 1. Data Loading
- Imported the dataset into Google Colab using Pandas.

### 2. Data Inspection
- Examined dataset shape
- Viewed column names
- Checked data types and missing values

### 3. Missing Value Handling
- Filled missing values in the `Age` column using the median value.
- Filled missing values in the `Embarked` column using the mode value.
- Removed the `Cabin` column due to a large number of missing values.

### 4. Duplicate Removal
- Checked for duplicate rows.
- Removed duplicate records if present.

### 5. Column Renaming
- Renamed columns to improve readability:
  - PassengerId → Passenger_ID
  - Pclass → Passenger_Class
  - Sex → Gender

### 6. Data Type Conversion
- Converted categorical columns into category data type:
  - Survived
  - Gender
  - Embarked

### 7. Dataset Export
- Saved the cleaned dataset as `Titanic_Cleaned.csv`.

## 📊 Output
The final output is a cleaned and structured Titanic dataset that is ready for:
- Exploratory Data Analysis (EDA)
- Data Visualization
- Machine Learning

## 📁 Repository Structure

```text
synent-task1-titanic-tharun
│
├── Titanic_Data_Cleaning.ipynb
├── Titanic_Cleaned.csv
└── README.md
```

## 🚀 Learning Outcomes
Through this project, I learned:
- Data cleaning techniques
- Handling missing values
- Removing duplicates
- Working with Pandas DataFrames
- Data preprocessing fundamentals
- Using Google Colab for Data Science projects
- Managing projects using GitHub

## 👨‍💻 Author
Tharun

Data Science Intern – Synent Technologies
