# Predicting Credit Risk

Supervised machine learning models to predict whether a loan from LendingClub will become high risk or not.

## Description

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API. Data from 2019 & 2020 is used in this repository to create machine learning models **(Logistic Regression model and Random Forest Classifier)** that predict the credit risk of loans from the first quarter of 2020.

The **Resources** directory contains two CSV files of data used to train and test the models. The GenerateData.ipynb file in the **Generate** directory is used to download data from LendingClub and output two CSV files that are undersampled, to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk. To get a truly accurate model, special techniques need to be used on imbalanced data. Undersampling is one of those techniques.

Models trained and tested in the Credit Risk Evaluator.ipynb Jupyter Notebook file

**Data preprocessing:** The pd.get_dummies() Pandas function is used to convert the categorical data to numeric columns in 

## Getting Started

### Technologies Used 

* Jupyter Notebook
* Pandas 
* sklearn 

### Installing

* Clone this repository to your desktop.
* Navigate to the home directory and open index.html in your browser.

### Data Sources

* LendingClub (2019-2020) Loan Stats. Retrieved from: https://resources.lendingclub.com/

## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
