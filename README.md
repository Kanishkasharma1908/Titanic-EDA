# Titanic-EDA
Titanic Survival Analysis – Exploratory Data Analysis (EDA)
Overview

This project performs an in-depth Exploratory Data Analysis (EDA) on the famous Titanic dataset to uncover insights about passenger demographics, travel classes, and survival factors.
It demonstrates data preprocessing, visualization, and analytical storytelling using Python and key data science libraries.

The main goal is to understand:

What factors influenced passenger survival rates?

How do age, gender, and class relate to survival probability?

What patterns can we identify through visual exploration?

Dataset

The dataset used is the Titanic dataset from Kaggle
, which contains information about passengers such as:

Column	Description
PassengerId -	Unique identifier for each passenger
Survived -	Survival status (0 = No, 1 = Yes)
Pclass -	Ticket class (1 = Upper, 2 = Middle, 3 = Lower)
Name -	Passenger’s name
Sex -	Gender
Age -	Age in years
SibSp -	Number of siblings/spouses aboard
Parch -	Number of parents/children aboard
Ticket -	Ticket number
Fare -	Passenger fare
Cabin -	Cabin number
Embarked -	Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

Data Cleaning & Preprocessing

Key steps included:

Handling missing values (Age, Cabin, Embarked)

Imputing missing ages using the median of corresponding passenger classes

Dropping irrelevant or redundant columns (Ticket, Cabin)

Encoding categorical variables using one-hot encoding (pd.get_dummies)

Converting True/False dummy values into numeric (0/1)

Exploratory Data Analysis

Performed thorough EDA to identify trends and relationships:

Univariate Analysis: Distribution of Age, Fare, and Survival.

Bivariate Analysis: Survival rate vs. Gender, Pclass, and Embarkation point.

Multivariate Analysis: Combined effects of multiple variables on survival.

Visual Insights: Created insightful plots such as boxplots, heatmaps, and countplots using Seaborn and Matplotlib.

Key Findings

Females had a significantly higher survival rate.

First-class passengers were more likely to survive.

Younger passengers (especially children) had higher chances of survival.

Most passengers embarked from Southampton.

Age and fare distributions varied notably by passenger class.

Tools & Libraries Used

Python 3.9+

NumPy

Pandas

Matplotlib

Seaborn

Jupyter Notebook
