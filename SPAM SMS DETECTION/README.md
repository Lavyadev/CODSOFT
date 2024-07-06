# SPAM SMS DETECTION

This projects aims ot classify SMS messages as spam or legitimate(ham) using various machine learning techniques. The dataset used is the SMS Spam Collection Dataset from UCI Machine Learning Repository.

## Table of Contents

[Introduction](#introdcution)<br/>
[Dataset](#dataset)<br/>
[Installation](#installation)<br/>
[Usage](#usage)<br/>
[Project Structure](#project-structure)<br/>
[Feature Extraction](#feature-extarction)<br/>
[Model Training](#model-training)<br/>
[Model Evaluation](#model-evaluation)<br/>
[Results](#results)<br/>
[Contributing](#contributing)<br/>
[License](#license)

## Introduction

SMS spam detection is a common problem in natural language processing. The goal of this project is to build a machine learning model that can classify SMS messages as either spam or legitimate (ham). We will use techniques like TF-IDF for feature extraction and classifiers like Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) to build the model.

## Dataset

The dataset used in this project is the SMS Spam Collection Dataset. It contains 5,574 SMS messages, each labeled as either "ham" (legitimate) or "spam". You can download the dataset from 
[here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## Installation

To run this project, you need to have Python installed on your system. You can install the required libraries using the following command:
```
bash<br/>
pip install pandas scikit-learn
```

## Usage

1. Clone the repository:
```
bash<br/>
git clone https://github.com/yourusername/sms-spam-classification.git<br/>
cd sms-spam-classification
```
2. Download the dataset and place it in the project directory.<br/>
3. Run the script to train and evaluate the model:
```
bash<br/>
python sms_spam_classification.py
```

## Project Structure

```
kotlin<br/>
sms-spam-classification/
│
├── data/
│   └── SMSSpamCollection.zip
│
├── sms_spam_classification.py
├── README.md
└── requirements.txt



