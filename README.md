# 🗽 NYC Yellow Taxi Profitability Analysis

This project was developed as part of a **Data Analytics for Business and Society** master’s program under the course Marketing Intelligence and Analytics and aims to analyze, clean, and model taxi trip data from New York City in 2023 using data science techniques. The work was completed for the **NYC Yellow Taxi Hackathon**, and focuses on profitability analysis and predictive modeling.

## 📊 Project Overview

This project tackles real-world transportation data through the following stages:

1. **ETL (Extract, Transform, Load)**

   * Merged all 2023 monthly taxi trip datasets from the [NYC TLC website](https://www.nyc.gov/site/tlc/about/tlc-trip-record-data.page)
   * Cleaned and consolidated into a unified structure for analysis

2. **Data Quality & Exploratory Analysis**

   * Addressed missing values, duplicates, outliers, and inconsistencies
   * Performed exploratory data analysis (EDA) to uncover patterns related to:

     * Peak hours & trip durations
     * Most common pickup zones
     * Payment method distribution

3. **Profitability Analysis**

   * Estimated trip-level **Revenue**, **Costs** (fuel, maintenance, driver), and **Operating Margin**
   * Investigated how variables such as time, distance, and tips affect profitability

4. **Predictive Modeling**

   * Developed machine learning models (linear regression, Stochastic Gradient Descent using sdg, and Xgboost)  to predict **trip profitability** based on:

     * Pickup datetime
     * Pickup & dropoff locations
     * Number of passengers
     * Rate code
     * Payment method
   * Models' performance evaluated and compared on the Test set and on data from 2024 using **Root Mean Squared Error (RMSE)**

## 🛠️ Tools & Technologies

* **R Studio** (.Rmd) for data processing and modeling
* **dplyr**, **lubridate**, **ggplot2** for EDA and visualization
* **biglm**, **sdg**, **xgboost**

## 📁 Repository Structure

```
├── Project_final_final.Rmd      # Full project code with explanations
└── README.md                    # This file
```

## 🔗 Live GitHub Project

You can explore the full project code and visuals in the `.Rmd` file here: [Project\_final\_final.Rmd](./Project_final_final.Rmd)
