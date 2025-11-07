🛳 Titanic Data Analysis
📘 Project Overview

This project explores the Titanic dataset to understand what kinds of people were more likely to survive the sinking of the Titanic.
Using Python libraries like Pandas, Matplotlib, and Seaborn, this notebook performs data cleaning, visualization, and feature creation to analyze passenger characteristics.

🎯 Objectives

Explore the Titanic dataset to find patterns and relationships.

Understand how gender, age, class, and family affected survival chances.

Practice data analysis and visualization skills in Python.

📂 Dataset

The dataset is loaded from:

https://raw.githubusercontent.com/datasciencedojo/datasets/master/titanic.csv


It includes details such as:

PassengerId, Name, Sex, Age

Pclass (Passenger class)

SibSp, Parch (Family onboard)

Cabin, Embarked, Fare, and Survived status

🧩 Steps Involved

Data Loading & Inspection

Importing dataset using Pandas

Checking missing values

Exploratory Data Analysis (EDA)

Visualizing passenger distribution by gender and class

Creating a new column Person to classify children

Checking age distribution and deck (cabin) levels

Feature Engineering

Created an Alone column to identify passengers traveling solo vs. with family

Visualizations

Count plots using Seaborn (sns.catplot)

Age distribution with KDE plots

Cabin deck analysis

🧠 What You’ll Learn

How to use Pandas for handling real-world datasets

How to perform EDA using Matplotlib and Seaborn

How to create new features to better understand data

How to interpret graphs to draw meaningful insights

🛠️ Tools & Libraries

Python 3

Pandas

NumPy

Matplotlib

Seaborn

📈 Sample Visuals

Count of passengers by gender

Distribution of passengers by class

Age distribution by gender

Cabin deck frequency


🙌 Acknowledgments

Dataset from Data Science Dojo on GitHub
