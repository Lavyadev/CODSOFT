# Credit Card Fraud Detection

This repository contains a project to detect fraudulent credit card transactions using machine learning algorithms. We will experiment with Logistic Regression, Decision Trees, and Random Forests to classify transactions as fraudulent or legitimate.

## Table of Contents

- [Introduction](#introduction)<br/>
- [Dataset](#dataset)<br/>
- [Installation](#installation)<br/>
- [Usage](#usage)<br/>
- [Models](#models)<br/>
- [Results](#results)<br/>
- [Contributing](#contributing)<br/>


## Introduction

Credit card fraud is a significant issue in the financial industry, causing substantial financial losses. This project aims to develop a machine learning model that can accurately classify credit card transactions as fraudulent or legitimate. We will explore various algorithms to achieve this goal and compare their performance.

## Dataset

The dataset used in this project contains information about credit card transactions. It includes features such as transaction amount, time, and various anonymized variables derived from the original features. The target variable indicates whether a transaction is fraudulent.<br/>
- **Source**: [Credit Card Transactions Fraud Detection Dataset](https://www.kaggle.com/datasets/kartik2112/fraud-detection)<br/>
- **Size**: 1,296,674 transactions<br/>
- **Features**: 21 anonymized features + target variable<br/>

## Installation

To run this project locally, you'll need to have Python installed. Follow these steps to set up the environment:<br/>
1. Clone this repository:
    ```bash
    git clone https://github.com/Lavyadev/CODSOFT.git
    cd CODSOFT
    ```

## Usage

1. **Train the models**:

   Run `python train_models.ipynb` script
    

2. **Evaluate the models**:

   Run `python evaluate_models.ipynb` script
   

## Models

We experiment with the following machine learning algorithms:<br/>
- **Logistic Regression**: A linear model used for binary classification.<br/>
- **Decision Trees**: A non-linear model that splits the data into subsets based on feature values.<br/>
- **Random Forests**: An ensemble method that combines multiple decision trees to improve performance and reduce overfitting.<br/>

## Results

The performance of each model is evaluated using metrics such as accuracy, precision, recall, and F1-score. Detailed results and comparisons are provided in the [results](results.md) file.

## Contributing

Contributions are welcome! Please fork this repository and submit a pull request with your improvements.

