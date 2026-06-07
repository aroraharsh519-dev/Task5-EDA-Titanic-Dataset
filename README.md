# Titanic Dataset - Exploratory Data Analysis (EDA)

## Project Overview

This project performs Exploratory Data Analysis (EDA) on the Titanic dataset using Python. The goal is to identify patterns, trends, and factors that influenced passenger survival.

## Objective

- Explore and understand the dataset
- Analyze missing values
- Visualize distributions and relationships
- Identify factors affecting survival
- Summarize insights using statistical and visual analysis

## Tools & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Colab

## Dataset

Titanic Passenger Dataset

Dataset Features:
- PassengerId
- Survived
- Pclass
- Name
- Sex
- Age
- SibSp
- Parch
- Ticket
- Fare
- Cabin
- Embarked

## Data Exploration

### Dataset Information
- Total Records: 891
- Total Features: 12
- Numerical and Categorical variables analyzed

### Missing Values Found
| Column | Missing Values |
|----------|----------|
| Age | 177 |
| Cabin | 687 |
| Embarked | 2 |

## Visualizations Performed

### 1. Age Distribution
Histogram showing the distribution of passenger ages.

### 2. Survival by Gender
Comparison of survival rates between male and female passengers.

### 3. Survival by Passenger Class
Analysis of survival rates across different passenger classes.

### 4. Correlation Heatmap
Visualization of relationships between numerical variables.

### 5. Pairplot Analysis
Comparison of important numerical features and survival.

## Key Findings

### Gender Impact
- Female passengers had significantly higher survival rates.
- Most male passengers did not survive.

### Passenger Class Impact
- First-class passengers had the highest survival rate.
- Third-class passengers had the lowest survival rate.

### Age Distribution
- Most passengers were between 20 and 40 years old.
- Very few passengers were above 60 years of age.

### Correlation Insights
- Fare showed a positive relationship with survival.
- Passenger class showed a negative relationship with survival.
- Higher-class passengers generally paid higher fares.

## Conclusion

The Exploratory Data Analysis revealed that gender, passenger class, and fare were important factors influencing survival on the Titanic. Female passengers and first-class passengers had a much higher chance of survival compared to others. The dataset also contains missing values that should be handled before building machine learning models.

## Repository Contents

```text
Titanic_EDA.ipynb
EDA_Report.pdf
train.csv
README.md
screenshots/
```

