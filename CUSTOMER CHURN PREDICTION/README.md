# CUSTOMER CHURN PREDICTION

This repository contains a project for predicting customer churn for a subscription-based service or business using historical customer data, including features like usage behavior and customer demographics. The project utilizes machine learning algorithms such as Logistic Regression, Random Forest, and Gradient Boosting to predict churn.

## Table of Contents

-[Project Overview](#project-overview)<br/>
-[Data Set](#data-set)<br/>
-[Installation](#installation)<br/>
-[Usage](#usage)<br/>
-[Results](#results)<br/>
-[Contributing](#contributing)<br/>

## Project Overview

Customer churn prediction is crucial for subscription-based businesses to retain customers and improve services. This project aims to develop a predictive model using machine learning techniques to identify customers likely to churn. The steps involved include data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Dataset

The dataset used for this project includes historical customer data with the following features:<br/>
__1. CustomerID:__ A unique identifier for each customer.<br/>
__2. Surname:__ The last name of the customer.<br/>
__3. CreditScore:__ The credit score of the customer, which is a numerical expression based on the analysis of their credit files to represent their creditworthiness.<br/>
__4. Geography:__ The country or region where the customer is located.<br/>
__5. Gender:__ The gender of the customer (e.g., Male, Female).<br/>
__6. Age:__ The age of the customer.<br/>
__7. Tenure:__ The number of years the customer has been with the bank.<br/>
__8. Balance:__ The balance amount in the customer's bank account.<br/>
__9. NumOfProducts:__ The number of products the customer has purchased through the bank (e.g., credit cards, loans, savings accounts).<br/>
__10. HasCrCard:__ Indicates whether the customer has a credit card (1 for yes, 0 for no).<br/>
__11. IsActiveMember:__ Indicates whether the customer is an active member (1 for active, 0 for inactive).<br/>
__12. EstimatedSalary:__ The estimated annual salary of the customer.<br/>
__13. Exited:__ Indicates whether the customer has exited (churned) the bank (1 for yes, 0 for no).

## Installaion

To run this project locally, follow these steps:<br/>
1. Clone the repository:
```
bash
git clone https://github.com/Lavyadev/CODSOFT.git
```
2. Navigate to the project directory:
```
bash
cd CODSOFT
```

## Usage 

To run churn prediction model, follow these steps:<br/>
1. Ensure you have the dataset in CSV format named customer_churn.csv in the project directory.<br/>
2. Run the ```customer_churn_prediction.ipynb``` script.

## Results

The evaluation metrics for each model (Logistic Regression, Random Forest, and Gradient Boosting) will be printed in the console. Additionally, the script will plot the feature importances for the Random Forest and Gradient Boosting models.

## Contributing






