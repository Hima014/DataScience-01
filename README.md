# Titanic Dataset - Data Cleaning & Exploratory Data Analysis (EDA)

## Overview

This project demonstrates a complete Data Cleaning and Exploratory Data Analysis (EDA) workflow using the Titanic dataset. The objective is to clean the data, analyze relationships between variables, identify patterns, and visualize key insights that influence passenger survival.

This project was completed as part of the Prodigy InfoTech Data Science Internship.

---

## Objectives

- Load and understand the dataset
- Handle missing values
- Remove unnecessary data
- Detect duplicate records
- Perform exploratory data analysis
- Identify relationships between variables
- Visualize important patterns
- Draw meaningful insights

---

## Dataset

**Dataset:** Titanic Passenger Dataset

The dataset contains demographic and travel information for passengers aboard the RMS Titanic, including:

- Passenger Class
- Name
- Sex
- Age
- Fare
- Embarkation Port
- Survival Status

---

## Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn

---

## Project Workflow

### 1. Data Loading

- Imported dataset using Pandas
- Explored dataset dimensions
- Inspected data types

### 2. Data Cleaning

- Checked missing values
- Filled missing Age values using the median
- Filled missing Embarked values using the mode
- Removed the Cabin column due to excessive missing values
- Removed duplicate records

### 3. Exploratory Data Analysis

Performed visual analysis of:

- Survival Distribution
- Gender Distribution
- Passenger Class Distribution
- Age Distribution
- Fare Distribution
- Survival by Gender
- Survival by Passenger Class
- Survival by Embarkation Port
- Fare Outliers
- Correlation Heatmap
- Pairwise Relationships

---

## Key Insights

- Female passengers had a significantly higher survival rate than males.
- First-class passengers were more likely to survive.
- Most passengers were between 20 and 40 years old.
- Fare values contained several outliers.
- Passenger class showed a strong relationship with survival.
- Age had a weaker correlation with survival compared to passenger class.

---

## Project Structure

```
PRODIGY_DS_02/
│
├── data/
├── images/
├── PRODIGY_DS_02.ipynb
├── README.md
├── requirements.txt
└── LICENSE
```

---

## Skills Demonstrated

- Data Cleaning
- Exploratory Data Analysis
- Data Visualization
- Statistical Analysis
- Correlation Analysis
- Python Programming
- Data Interpretation

---

## Future Improvements

- Interactive Dashboard using Plotly
- Feature Engineering
- Predictive Machine Learning Models
- Advanced Statistical Analysis

---

## Author
Hima M

Artificial Intelligence & Data Science Student

Passionate about Data Science, Artificial Intelligence, Machine Learning, and building impactful AI solutions.
