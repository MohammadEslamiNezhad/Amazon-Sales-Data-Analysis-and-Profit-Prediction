# Amazon Sales Data Analysis and Profit Prediction

## Project Overview

This project focuses on analyzing a dataset of Amazon sales to understand key sales metrics, identify factors influencing profitability, and build a machine learning model to predict total profit.

The goal is to demonstrate data analysis, visualization, and machine learning skills using a real-world dataset.

## Dataset

The dataset used in this project is the `AmazonSalesData.csv` file. It contains information about various sales transactions, including:

- Region and Country of sale
- Item Type and Sales Channel
- Order Priority, Order Date, and Ship Date
- Units Sold, Unit Price, and Unit Cost
- Total Revenue, Total Cost, and Total Profit

## Methodology

The project follows these main steps:

1.  **Data Loading and Initial Exploration**: Loading the dataset and examining its structure, data types, and summary statistics.
2.  **Data Wrangling**: Converting date columns to datetime objects and extracting relevant temporal features (Day, Weekday, Month, Year).
3.  **Exploratory Data Analysis (EDA)**: Analyzing and visualizing key sales metrics aggregated by different categorical dimensions (Region, Country, Item Type, Sales Channel, Order Priority) and over time to identify trends and patterns. This includes:
    *   Calculating descriptive statistics.
    *   Generating correlation matrices and heatmaps.
    *   Visualizing distributions and relationships using pie charts, bar plots, and time series plots.
4.  **Feature Engineering and Preprocessing**: Preparing the data for the machine learning model. This involves:
    *   Identifying relevant features for profit prediction.
    *   Applying data transformations (e.g., log transformation) and outlier handling techniques (e.g., winsorizing) on numerical features to improve model performance.
    *   Handling categorical features using One-Hot Encoding.
    *   Scaling numerical features.
    *   Splitting the data into training and testing sets.
5.  **Machine Learning Model**: Building and evaluating a regression model to predict 'Total Profit'.
    *   Using a **RandomForestRegressor** model.
    *   Evaluating the model's performance using metrics like Mean Absolute Error (MAE), Mean Squared Error (MSE), and R-squared.
6.  **Model Interpretation**: Analyzing feature importances from the trained model to understand which factors contribute most significantly to profit prediction.

## Key Findings

*(Replace this section with your key findings from the analysis and model interpretation. For example, mention which regions, item types, or sales channels are most profitable, and which features the model found most important for predicting profit.)*

## How to Run the Notebook

1.  Clone this repository to your local machine or open it directly in Google Colab.
2.  Ensure you have the required libraries installed (see Prerequisites).
3.  Run the cells in the Jupyter Notebook (`amazon_sales_data_analysis.ipynb`) sequentially.

## Prerequisites

The following Python libraries are required to run this notebook:

-   pandas
-   numpy
-   matplotlib
-   seaborn
-   scikit-learn

You can install these using pip:
