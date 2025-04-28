# PRODIGY_DS_02
Perform data cleaning and exploratory data analysis (EDA) on a dataset of your choice, such as the Titanic dataset from Kaggle. Explore the relationships between variables and identify patterns and trends in the data.

# Titanic Dataset Survival Analysis

This project aims to explore and analyze the Titanic dataset to predict survival outcomes based on various factors such as gender, age, and passenger class. The dataset is cleaned and preprocessed, followed by various visualizations and statistical analysis to uncover insights.

## Project Overview

This project demonstrates the process of data exploration, cleaning, and visualization using Python and its libraries, including `Pandas`, `Seaborn`, and `Matplotlib`. We aim to understand the relationship between passenger features and survival rates. The steps involve:
- Loading and inspecting the dataset
- Handling missing data
- Data preprocessing (dropping irrelevant columns, imputing missing values)
- Visualizing relationships using plots
- Exploring correlations between numerical features
- Performing group-by operations and heatmaps

## Dataset

The dataset used in this project is the Titanic dataset, which contains information about the passengers aboard the RMS Titanic, including whether they survived or not (`Survived`).
https://www.kaggle.com/c/titanic/data

### Key Columns:
- **Survived**: Whether the passenger survived (1) or not (0)
- **Pclass**: Passenger class (1 = First class, 2 = Second class, 3 = Third class)
- **Name**: Name of the passenger
- **Sex**: Gender of the passenger (male, female)
- **Age**: Age of the passenger
- **SibSp**: Number of siblings/spouses aboard
- **Parch**: Number of parents/children aboard
- **Ticket**: Ticket number
- **Fare**: Fare paid for the ticket
- **Cabin**: Cabin number
- **Embarked**: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

### Requirements:
- Pandas
- Matplotlib
- Seaborn

## Visualizations
### Key visualizations:
- **Count plot** showing the survival rate based on gender (`Sex`)
- **Heatmap** visualizing survival rates by passenger class (`Pclass`)
- **Violin plot** showing age distribution split by survival and gender
- **Correlation heatmap** showing the relationship between numeric features
