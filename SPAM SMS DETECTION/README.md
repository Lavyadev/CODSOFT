# SPAM SMS DETECTION

This projects aims to classify SMS messages as spam or legitimate(ham) using various machine learning techniques. The dataset used is the SMS Spam Collection Dataset from UCI Machine Learning Repository.

## Table of Contents

-[Introduction](#introdcution)

-[Dataset](#dataset)

-[Installation](#installation)

-[Usage](#usage)

-[Project Structure](#project-structure)

-[Feature Extraction](#feature-extarction)

-[Model Training](#model-training)

-[Model Evaluation](#model-evaluation)

-[Results](#results)

-[Contributing](#contributing)

## Introduction

SMS spam detection is a common problem in natural language processing. The goal of this project is to build a machine learning model that can classify SMS messages as either spam or legitimate (ham). We will use techniques like TF-IDF for feature extraction and classifiers like Naive Bayes, Logistic Regression, and Support Vector Machines (SVM) to build the model.

## Dataset

The dataset used in this project is the SMS Spam Collection Dataset. It contains 5,574 SMS messages, each labeled as either "ham" (legitimate) or "spam". You can download the dataset from 
[here](https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset).

## Installation

To run this project, you need to have Python installed on your system. You can install the required libraries using the following command:
```
pip install pandas scikit-learn
```

## Usage

1. Clone the repository:
```
bash
git clone https://github.com/Lavyadev/CODSOFT.git
cd CODSOFT
```
2. Download the dataset and place it in the project directory.<br/>
3. Run the script `sms_spam_detection.ipynb` to train and evaluate the model:

## Project Structure

```
sms_spam_detection/
│
├── data/
│   └── spam.csv
│
├── sms_spam_detection.ipynb
├── README.md
```

## Feature Extraction

We use TF-IDF (Term Frequency-Inverse Document Frequency) to convert the text data into numerical features. This helps in transforming the text data into a format suitable for machine learning algorithms.

## Model Training

We train multiple classifiers to compare their performance:<br/>
1.Naive Bayes<br/>
2.Logistic Regression<br/>
3.Support Vector Machines (SVM)<br/>

## Model Evaluation

We evaluate the model using various matrices:<br/>
-Accuracy

-Precision

-Recall

-F1-Score

-Confusion Matrix

## Results

The performance of the model is as follows:<br/>
|MODEL                              |Accuracy   |
|-----------------------------------|-----------|
|Naive Bayes                        |0.96       |
|Logistic Regression                |0.96       |
|Support Vector Machine(SVM)        |0.98       |

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.





