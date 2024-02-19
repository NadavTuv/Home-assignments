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
