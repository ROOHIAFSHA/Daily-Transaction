# Daily-Transaction
Daily Transaction Data Analysis and Machine Learning
## Project Overview

This project involves data analysis and predictive modeling using a dataset of daily household transactions. The objective is to analyze spending behavior, visualize transaction patterns, and build a machine learning model to predict transaction categories.

## Dataset

The dataset contains daily transaction records with the following columns:

Date: The date and time of the transaction

Mode: Payment mode used for the transaction

Category: Category of the transaction (e.g., Food, Entertainment)

Subcategory: Further breakdown of the category

Note: A brief description of the transaction

Amount: The transaction amount

Income/Expense: Indicates whether the transaction is an income or expense

Currency: All transactions are recorded in Indian Rupees (INR)

## Project Structure

Data Preprocessing: 

Data cleaning, handling missing values, feature engineering, and label encoding.

## Exploratory Data Analysis (EDA):

Income vs Expense distribution

Category and Subcategory analysis

Payment Mode analysis

Time-series analysis of monthly expenses and income

## Machine Learning:

Random Forest model for transaction category prediction

ROC-AUC calculation for model evaluation

Multi-class ROC curve plotting

## How to Run the Project

### Install the required dependencies using:

pip install -r requirements.txt

### Run the analysis and model training script:

python transaction_analysis.py

Dependencies

Python 3.8+

pandas

numpy

matplotlib

seaborn

scikit-learn

## Output

Classification report and confusion matrix

ROC-AUC score

Multi-class ROC curve plot
