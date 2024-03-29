# Home-assignments
I will store here a bunch of home assignments that I got (without company names) and their solutions. 
I will not share any specific questions or company names, only my notebook and a general explanation of what I did.

# Data Science Project 1 - Invoice Relevance Prediction

## Project Overview

This project aims to address a common challenge in the data flow at an organization. The task involves determining the relevance of documents, specifically invoices, for tax purposes. The objective is to build a machine learning model that predicts the relevance of an invoice based on extracted features.

## Dataset

The dataset comprises two sets: a training dataset (`project_df`) with labeled data and a holdout dataset (`holdout_df`) for future predictions. Features are provided in two formats: a pandas DataFrame and a sparse matrix with tf-idf scores.

## Project Tasks

1. **Building a Model:**
    - Developed a machine learning model to predict the relevance of invoices.
    - Utilized the training dataset and tf-idf scores for feature representation.

2. **Predictions:**
    - Applied the trained model to make predictions on the holdout dataset.

3. **Performance Evaluation:**
    - Assessed the model's performance on the holdout data using appropriate metrics.
  

# Business Data Science Project 2 - Budget Allocation

## Project Overview

This project addresses the challenge of optimizing ad spend budget for a company's performance marketing team. The goal is to maximize the return on investment (ROI) by recommending the best allocation of spend among different advertising networks. The task involves analyzing historical data, extracting insights, and building a model to predict next month's revenue.

## Dataset

Two CSV files, "spend.csv" and "revenue.csv," contain mock data representing digital marketing spend and attributed revenues, respectively. The data includes information on the network, date, campaign, spend, purchase date, user ID, subscription details, and revenue.

## Project Tasks

1. **Data Examination and Visualization:**
    - Examined and visualized the data to gain insights that assist in further analysis.

2. **Relationship between Spend and Revenues:**
    - Explored and identified relationships between ad spend and revenues.

3. **Model Building:**
    - Constructed a model to predict next month's revenue.

4. **Answering Stakeholder Questions:**
    - Provided insights on how to allocate spend among different networks to maximize revenues.
    - Shared expectations for future revenues based on the proposed model and insights.

5. **Summary for Stakeholders:**
    - Composed a short summary for non-technical stakeholders, including key findings and visualizations.

## Addressing Specific Topics

- **Data Examination and Usage:**
    - Thoroughly examined and visualized data to make informed decisions.

- **Decision Explanation:**
    - Clearly explained decisions from both a data science and business perspective.

- **Coding Skills:**
    - Demonstrated efficient usage of Python packages for data analysis and modeling.

- **Avoided Processes/Methods Explanation:**
    - Explained reasons for avoiding certain processes or methods due to time constraints.

# Sales Forecasting Model - Assignment #3

## Overview

This project focuses on the development of a sales forecasting model for a range of products within the same category. The dataset comprises sales data, competitor sales, holiday dates, and business events, providing a comprehensive foundation for analysis and prediction.

## Project Scope

### Descriptive Statistics

A meticulous exploration of descriptive statistics for both sales and competitor data was conducted to extract essential insights. This initial phase set the stage for subsequent modeling decisions.

### Sales Forecasting Model

The development of a predictive model involved the selection of an algorithm tailored to the intricacies of the dataset. Standard procedures such as data cleaning and validation were rigorously applied to ensure the model's reliability.

### Model Validation

Validation was a critical step to verify the accuracy and consistency of the model's predictions. Rigorous testing against known data ensured the robustness of the forecasting model.

### Interpretation and Future Steps

Upon successful model implementation, sales predictions for the next 6 months were generated. The interpretation section provides an in-depth analysis of significant variables, assesses the model's strengths and weaknesses, and suggests avenues for improvement.

## Project Files

- **sales_forecasting.ipynb:** Access the Jupyter Notebook to review the code, analysis, and modeling details.
- **sales_forecast_predictions.xlsx:** Refer to the Excel file for a detailed breakdown of sales predictions.

