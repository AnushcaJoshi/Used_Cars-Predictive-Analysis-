# Used Car Price Analysis and Visualization

Welcome to the Used Car Price Analysis Project! This project explores a dataset of used cars to gain insights into manufacturer trends, price patterns, and feature correlations. Using Python and its powerful data visualization libraries, this project includes data preprocessing, feature engineering, correlation analysis, and detailed visualizations to understand the resale value of cars based on various attributes.

You can explore the analysis notebook [here](Car%20Price%20Prediction.ipynb).

## Table of Contents

1. [Introduction](#introduction)  
2. [Dataset Overview](#dataset-overview)  
3. [Data Cleaning and Preparation](#data-cleaning-and-preparation)  
4. [Exploratory Data Analysis (EDA)](#exploratory-data-analysis-eda)  
5. [Visualizations](#visualizations)  
6. [Conclusion](#conclusion)

---

## Introduction

The goal of this project is to analyze a dataset of used cars and extract meaningful insights regarding pricing, car features, and trends in the resale market. The analysis focuses on:

- Understanding which manufacturers dominate the used car market.
- Exploring how features like mileage, engine capacity, and power affect car prices.
- Identifying correlations between numerical attributes.

Technologies used:  
- **Python** (Pandas, NumPy, Matplotlib, Seaborn)  
- **Jupyter Notebook** for exploratory analysis

---

## Dataset Overview

The dataset consists of listings of used cars with the following key columns:

- **Name**: Complete name of the car  
- **Kilometers_Driven**: Total distance driven  
- **Fuel_Type**: Fuel variant – Petrol, Diesel, CNG, etc.  
- **Transmission**: Manual or Automatic  
- **Owner_Type**: First-hand, second-hand, etc.  
- **Mileage**, **Engine**, **Power**: Core performance attributes  
- **Seats**: Seating capacity  
- **Price**: Selling price of the used car  
- **Year**: Year of manufacture  

---

## Data Cleaning and Preparation

To ensure the data was ready for analysis, several preprocessing steps were performed:

- **Handled Missing Values**: Replaced nulls in `Mileage`, `Engine`, `Power`, and `Seats` with column-wise means.
- **Parsed Columns**: Extracted numerical values from string fields such as `Mileage`, `Engine`, and `Power`.
- **Standardized Values**: Cleaned inconsistent string formats and ensured numerical consistency.
- **Feature Engineering**:
  - Extracted `Manufacturer` from the `Name` column for better group analysis.
  - Created a `Year_Used` column to calculate how old the car is.

---

## Exploratory Data Analysis (EDA)

A detailed EDA was conducted to understand the data better:

- **Manufacturer Distribution**:
  - Top manufacturers by number of used cars in the market were identified.
  - Most frequent brands include **Maruti**, **Hyundai**, and **Honda**.

- **Correlation Heatmap**:
  - Studied how features like engine size, power, mileage, and number of years used correlate with price.
  - Observed a strong positive correlation between **Power and Price**, and **Engine and Price**.

---

## Visualizations

The following visualizations were created as part of the analysis:

### 1. **Count of Cars by Manufacturer**
https://github.com/AnushcaJoshi/Used_Cars-Predictive-Analysis-/issues/1#issue-2999815109


This chart shows that **Maruti**, **Hyundai**, and **Honda** dominate the used car listings.

---

### 2. **Car Sales by Manufacturer**
https://github.com/AnushcaJoshi/Used_Cars-Predictive-Analysis-/issues/2#issue-2999818518

Sales distribution by manufacturer helps assess market presence and popularity of brands.

---

### 3. **Correlation Heatmap**
https://github.com/AnushcaJoshi/Used_Cars-Predictive-Analysis-/issues/3#issue-2999820904

A heatmap reveals the strength of relationships between numerical features and car price.

---

## Conclusion

This project highlights the power of data-driven insights in the automotive resale industry. By identifying the key drivers of used car prices—such as power, engine size, and brand—stakeholders can make informed decisions about buying and selling strategies.

Future work can include:
- **Modeling**: Building predictive models like XGBoost or Random Forest to estimate car prices.
- **Dashboarding**: Creating interactive dashboards in Power BI or Streamlit.
- **Time Trends**: Analyzing how price trends change with time for each brand.

---

Thank you for reviewing the Used Car Price Analysis Project! Feel free to connect or contribute with feedback.
