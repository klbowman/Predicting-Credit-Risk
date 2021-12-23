# Predicting Credit Risk

Supervised machine learning models to predict whether a loan from LendingClub will become high risk or not.

## Description

LendingClub is a peer-to-peer lending services company that allows individual investors to partially fund personal loans as well as buy and sell notes backing the loans on a secondary market. LendingClub offers their previous data through an API. Data from 2019 & 2020 is used in this repository to create machine learning models (Logistic Regression model and Random Forest Classifier) that predict the credit risk of loans from the first quarter of 2020.

The **Resources** directory contains two CSV files of data used to train and test the models. The GenerateData.ipynb file in the **Generate** directory is used to download data from LendingClub 



You will be using an entire year's worth of data (2019) to predict the credit risk of loans from the first quarter of the next year (2020).
Note: these two CSVs have been undersampled to give an even number of high risk and low risk loans. In the original dataset, only 2.2% of loans are categorized as high risk. To get a truly accurate model, special techniques need to be used on imbalanced data. Undersampling is one of those techniques. Oversampling and SMOTE (Synthetic Minority Over-sampling Technique) are other techniques that are also used.

The dashboard includes a drop-down menu that displays the numerical code for each individual sample. When a sample is selected, the “Demographic Info” panel is populated with metadata and the following three charts are populated with data:
* Bar graph displaying the top 10 OTUs by count
* Gauge plot showing the belly button scrubs per week
* Bubble plot displaying OTU counts for the entire sample

<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/145615550-98e49162-44c9-4e39-9050-ba837dc42863.png" alt="Dashboard Image"/>
</p>
<p align="center">
  <img src="https://user-images.githubusercontent.com/74067302/145615561-5fc19f35-646b-47aa-9f63-4a93a495efe5.png" alt="Dashboard Image"/>
</p>

## Getting Started

### Technologies Used 

* JavaScript
* HTML
* CSS

### Installing

* Clone this repository to your desktop.
* Navigate to the home directory and open index.html in your browser.

### Data Sources

* LendingClub (2019-2020) Loan Stats. Retrieved from: https://resources.lendingclub.com/

## Author

Katlin Bowman, PhD

E: klbowman@ucsc.edu

[LinkedIn](https://www.linkedin.com/in/katlin-bowman/)
