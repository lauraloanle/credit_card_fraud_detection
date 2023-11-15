# Overview

This project is part of the DS4A 2023 - Data Skills For All initiative, focusing on building a comprehensive credit card fraud detection system. The system aims to leverage historical transaction data, customer profiles, and advanced analytics to predict and prevent fraudulent credit card activity.

# Background

With nearly $8.8 billion lost to fraud in 2022 and credit card fraud being one of the leading financial fraud types in the US, there's an urgent need for sophisticated fraud detection mechanisms. Financial institutions are now turning to data science and machine learning to address this challenge.

# Project Structure

The project is structured into five main components:
* Data Cleaning: Ensure the quality and integrity of the analysis.
* Exploratory data analysis (EDA): Conduct a thorough analysis to discern patterns and gather invaluable insights.
* Feature selection and Data Preprocessing: Conduct feature engineering to select relevant features for the model. Preparation and transformation of raw data into a structured format
* Machine Learning Models: Test different algorithms to identify the most effective at uncovering fraudulent activities. Made fine-tuning adjustments for better performance.
* Insight and recommendations: Present the best model for predicting fraudulent transactions and key insights from the analysis.

# Data Description

We have three main datasets containing information about 2000 customers, their credit card transactions, and card details spanning from January 2016 to December 2019.
* credit_card_transaction_data_de.parquet: Transactional data.
* credit_card_users_de.parquet: User profile data.
* sd254_cards_de.parquet: Credit card details.

# Objectives

The goals is to: Build a predictive model to determine the likelihood of a new transaction being fraudulent or not using the historical credit card transactions data. 

# Deliverables

This repository contains:
* Code: All relevant scripts and notebooks used for analysis and model building.
* Presentation: A slide deck summarizing our approach, findings, and recommendations.

# Results

Through the analysis, pinpointed top six crucial variables influencing fraudulent activities: merchant location, transaction year, 
the type of merchant (MCC), transaction hour, transaction amount, and the nature of the transaction (online vs. physical). Recognizing these factors can guide financial institutions in refining their fraud prevention strategies.

# Conclusions

The project brought forward both the complexities and opportunities within fraud detection. The next steps would include deploying the model in a live environment, continuous monitoring, and further refinement to adapt to evolving fraud tactics.
