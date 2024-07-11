# MOVIE GENRE CLASSIFICATION

This project uses machine learning techniques to predict the genre of a movie based on its description. The model is trained on a dataset of movie descriptions and their respective genres, and evaluated using test data with known genre labels.

## Project Overview

The main goal of this project is to classify movies into different genres based on textual descriptions using Natural Language Processing (NLP) techniques. We use TF-IDF (Term Frequency-Inverse Document Frequency) for feature extraction and Logistic Regression for classification.

## Project Structure

The project directory structure is as follows:
```
- README.md                             (This file)
- train_data.txt                        (Training data)
- test_data.txt                         (Test data)
- test_data_solution.txt                (Test data with genre labels)
- movie_genre_classifier.ipynb          (Main script for training and evaluating the model)
- genre_classifier_model.pkl            (Saved trained model)
- tfidf_vectorizer.pkl                  (Saved TF-IDF vectorizer)
```

## Setup Instructions 

### Installation

Clone the repository and install dependencies:
```
git clone https://github.com/Lavyadev/CODSOFT.git
cd CODSOFT
pip install pandas scikit-learn joblib
```
### Running the Code

To train the model and evaluate it, run: `movie_genre_classifier.ipynb` script<br/>
Make sure the required data files `(train_data.txt, test_data.txt, test_data_solution.txt)` are in the project directory.

## Data Format

train_data.txt: Contains training data with columns ID, TITLE, GENRE, and DESCRIPTION.<br/>
test_data.txt: Contains test data with columns ID, TITLE, and DESCRIPTION.<br/>
test_data_solution.txt: Contains test data with columns ID and GENRE (actual genre labels for evaluation).<br/>

## Model Details

The model uses Logistic Regression with TF-IDF vectorization for feature extraction from movie descriptions.

## Results

After training and evaluating the model, the following results were obtained:

__Accuracy__ Mention the accuracy achieved on the test set.
__Classification Report:__ Provide details like precision, recall, and F1-score for each genre.

## Future Improvements

Potential enhancements for future iterations of the project:

Experimenting with different machine learning models (e.g., SVM, Random Forests) for better performance.<br/>
Tuning hyperparameters to improve accuracy.<br/>
Handling larger datasets and optimizing memory usage.<br/>







