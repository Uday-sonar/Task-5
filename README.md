# Task-5
# Titanic Dataset - Exploratory Data Analysis (EDA)

## Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset to understand passenger characteristics, survival patterns, and relationships between different variables using statistical summaries and visualizations.

---

## Dataset Information

The dataset contains information about Titanic passengers, including:

* PassengerId – Unique passenger ID
* Survived – Survival status (0 = No, 1 = Yes)
* Pclass – Passenger class (1, 2, 3)
* Name – Passenger name
* Sex – Gender
* Age – Age of passenger
* SibSp – Number of siblings/spouses aboard
* Parch – Number of parents/children aboard
* Ticket – Ticket number
* Fare – Ticket fare
* Cabin – Cabin number
* Embarked – Port of embarkation

---

## Tools and Libraries Used

* Python
* Pandas – Data analysis
* Matplotlib – Data visualization
* Seaborn – Statistical visualization
* Jupyter Notebook / Anaconda

---

## Steps Performed

### 1. Data Loading

* Loaded dataset using pandas
* Checked structure using `.info()`

### 2. Statistical Summary

* Used `.describe()` to view mean, median, min, max, and standard deviation
* Used `.value_counts()` for categorical variables

### 3. Data Visualization

The following plots were created:

* Histogram – Age distribution
* Histogram – Fare distribution
* Boxplot – Fare vs Passenger class
* Scatterplot – Age vs Fare
* Pairplot – Relationship between numerical variables
* Heatmap – Correlation between features
* Countplot – Survival distribution

---

## Key Findings / Observations

1. Most passengers were aged between 20–40 years.
2. Majority of passengers were male.
3. Most passengers traveled in 3rd class.
4. Fare distribution was highly skewed with few high-value fares.
5. First-class passengers paid significantly higher fares.
6. Fare and passenger class showed strong negative correlation.
7. Survival rate was lower than non-survival rate.
8. Most passengers embarked from port 'S'.

---

## Conclusion

EDA helped identify important patterns and relationships in the dataset. Passenger class, fare, and age were key factors influencing survival trends. Visualization made it easier to understand data distribution and correlations.

---

## Files Included

* Titanic Dataset (tested.csv)
* EDA Python Script / Notebook
* README.md (this file)


Course: Data Science / Machine Learning
Project: Titanic EDA
