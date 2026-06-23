# 📊 Unemployment Analysis in India using Python

## 📌 Project Overview

Unemployment is one of the major economic indicators that reflects the health of an economy. This project focuses on analyzing unemployment trends in India using data analysis and visualization techniques.

The main objective of this project is to explore unemployment patterns, study the impact of COVID-19 on employment, compare unemployment rates across different regions, and understand the relationship between employment-related factors.

---

## 🎯 Objectives

- Analyze unemployment trends over time
- Study the impact of COVID-19 on unemployment rates
- Compare unemployment rates across Indian states
- Analyze Rural vs Urban unemployment patterns
- Understand the relationship between labour participation and unemployment
- Build a machine learning model to predict unemployment rate

---

## 🗂️ Dataset Description

The dataset contains monthly unemployment records with the following features:

| Column | Description |
|--------|-------------|
| Region | Indian state/region name |
| Date | Monthly record date |
| Frequency | Frequency of data collection |
| Estimated Unemployment Rate (%) | Percentage of unemployed population |
| Estimated Employed | Number of employed people |
| Estimated Labour Participation Rate (%) | Labour participation percentage |
| Area | Rural or Urban classification |

---

## 🛠️ Technologies Used

- Python
- Google Colab
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 🔍 Project Workflow

### 1. Data Loading
- Imported unemployment dataset
- Checked dataset structure and information

### 2. Data Cleaning
- Handled missing values
- Converted date column into proper format
- Created additional year and month features

### 3. Exploratory Data Analysis

Performed analysis on:

- Overall unemployment trend
- COVID-19 unemployment impact
- State-wise unemployment comparison
- Rural vs Urban unemployment analysis
- Correlation analysis between variables

### 4. Data Visualization

Created visualizations using:

- Line charts
- Bar charts
- Heatmaps

to identify patterns and trends.

---

## 🤖 Machine Learning Model

A Linear Regression model was implemented to predict unemployment rate.

### Features Used:

- Estimated Employed
- Labour Participation Rate
- Year
- Month

### Evaluation Metrics:

- Mean Absolute Error (MAE)
- R² Score

---

## 📈 Key Insights

- Unemployment rate increased significantly during the COVID-19 period.
- Different states showed different unemployment patterns.
- Labour participation rate had an impact on unemployment trends.
- Rural and urban areas showed variations in employment conditions.

