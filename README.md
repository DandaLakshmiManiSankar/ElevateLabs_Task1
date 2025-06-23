# ElevateLabs_Task1_Data Cleaning & Preprocessing
This project focuses on exploring and preprocessing the Titanic dataset using Python in Google Colab. The goal is to prepare the data for further machine learning modeling by handling missing values, encoding categorical variables, and performing exploratory data analysis (EDA).The dataset used is the classic Titanic Dataset, which contains passenger information such as age, sex, ticket fare, and survival status.

# What This Project Covers
1.Library Setup
->Imported essential Python libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.

2.Dataset Loading & Exploration
->Loaded the dataset and used .info() and .head() to understand the structure and view initial entries.

3.Missing Value Handling
->Filled missing values in Age and Fare with the median.
->Filled missing Embarked values with the mode.
->Verified imputation with .isnull().sum().
->Encoding Categorical Variables
->Converted Sex to numerical using label encoding (male: 0, female: 1).
->Used one-hot encoding for Embarked, dropping the first category to avoid dummy variable trap.

# To run this project:

->Install the requirements.txt file using this command in Google Colab: " !pip install -r requirements.txt "
->Upload the Titanic dataset to your Colab environment.
->Open "Task1.ipynb" in Google Colab.
->Run all cells for a complete preprocessing pipeline.
