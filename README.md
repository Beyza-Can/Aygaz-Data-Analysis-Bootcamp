# Aygaz-Data-Analysis-Bootcamp
This repository contains my data analysis project . 


# Aygaz Data Analysis Bootcamp Project
# Overview
This project was developed as part of the Aygaz Data Analysis Bootcamp. It demonstrates data analysis techniques applied to a adult-income dataset. The goal is to extract meaningful insights and present findings using various data preprocessing, visualization, and modeling methods.

# Features
# Data Cleaning: 
Identifying and handling missing values, duplicates, and outliers.
# Exploratory Data Analysis (EDA): 
Summarizing and visualizing the dataset to uncover patterns and trends.
# Feature Engineering: 
Creating new features to improve model performance.
# Modeling: 
Applying machine learning algorithms to solve specific business problems.
# Evaluation: 
Assessing the performance of models using appropriate metrics.
# Dataset
The dataset used in this project is related to a real life scenario where a company tries to find who is earning enough oney to live . Key features include:

# Categorical Feature :
race,gender,occuptaion,workclass,marital-status,relationship,education
# Numerical Feature : 
age,working-per-hours,educational-num 

# Tools and Libraries
This project utilizes the following tools and libraries:

# Programming Language: Python
# Libraries:
Data Manipulation: Pandas, NumPy
Visualization: Matplotlib, Seaborn
Machine Learning: Scikit-learn
# Project Structure
The repository contains the following files:
notebook.ipynb: The main Jupyter Notebook with all code and analysis.
README.md: Project description and documentation (this file).
# Results

Accuracy of predictive model: 87%
And EDA conclusion :
* this dataset can be used to predict if a person earning <50k or not
* working hours mostly 40 hours that doesnt affect much
* after the age of 65+ your income is significantly dropping
* 30-50 and 50-65 earns the most as age
* if you are male you are earning more
* if you are asian you earn more >50k
* managers and profs are earning more than the other occupations
* as marital stats married person earns more
* as educational level doctorate and prof schools earns more
* if your working class is self employed inc you are earning more than others
* so if you are male,asian,married,50 year old ,self emplyed prof you are earning the best money for this dataset!!!
* for the machine learning model gradient boosting and xgboost works fine for this dataset.
