# Telecom-Customer-Churn-Analysis
This repository contains my project on a End to end data science project on a Telecom Dataset. The project includes the EDA notebook and a Tableau Story for a Stakeholder Report. Project highlights:

## Tableau Story - Stakeholder Report
EDA notebook
custom-elt-project
Tableau Story - Stakeholder Report
Available at link - 
https://public.tableau.com/views/Teleco-Churn-Analysis_17399136377210/TelecomChurnAnalysis?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

The 7 page story details:

Dataset Intro Statistics
Correlation Map for feature trimming
General Linear Model for feature selection
Customer Demographics vs Churn
Account Features vs Churn
Opt-In Services vs Churn
Q4 Revenue vs Churn

![image](https://github.com/user-attachments/assets/3cdcda42-44e6-4201-8e19-e18f26a8630e)


## EDA Notebook
The EDA consists of the following sections:

Data Preprocessing
Data type conversion
Missing Value Handling
Class Imbalance and Distribution
Analyzing Dataset Feature
Customer Demographics
Location Data
Opt-In Services
Payment Features
Distribution of Continous Features
Feature Selection
Correlation Mapping
General Linear Modelling
Recursive Feature Elimination
Modelling (Logistic Regression, SVM, Random Forests, Decision Trees, Naive Bayes)
Model Optimization
Hyper-parameter Tuning - Randomized Search Cross Validation
Dataset Used
IBM Fictional Telecom Dataset (Link: https://accelerator.ca.analytics.ibm.com/bi/?perspective=authoring&pathRef=.public_folders%2FIBM%2BAccelerator%2BCatalog%2FContent%2FDAT00148&id=i9710CF25EF75468D95FFFC7D57D45204&objRef=i9710CF25EF75468D95FFFC7D57D45204&action=run&format=HTML&cmPropStr=%7B%22id%22%3A%22i9710CF25EF75468D95FFFC7D57D45204%22%2C%22type%22%3A%22reportView%22%2C%22defaultName%22%3A%22DAT00148%22%2C%22permissions%22%3A%5B%22execute%22%2C%22read%22%2C%22traverse%22%5D%7D)

## Overview of the Custom ELT Project
Docker based ETL pipeline managing data transfer from src to dest. PostgreSQL RDB, with an integrated Flask UI for data entry. The Airflow/CRON job orchestrated pipeline periodically uploads to Amazon S3 / Redshift, for further EDA and Tableau visualization. Proceed in to the custom-elt-project folder for more details
