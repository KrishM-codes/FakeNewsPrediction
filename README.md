# Fake News Prediction using Machine Learning

## Overview
This project aims to detect fake news based on text data using machine learning techniques. The model focuses on author names and news titles to classify news articles as either real or fake. The dataset used contains 20,800 entries with 5 attributes.

## Features
- **Data Preprocessing:** Cleaning and preparing text data, including removing stopwords and stemming using NLTK.
- **Feature Extraction:** Utilizes TF-IDF vectorization to convert text into numerical features.
- **Model Training:** Logistic Regression model trained on preprocessed data.
- **Model Evaluation:** Evaluates model accuracy and performance on test data.

## Dataset
- **Rows:** 20,800
- **Attributes:** 5 (Author, Title, Text, Label, etc.)
- **Focus:** Author name and title for prediction.

## Technologies Used
- Python (3.x)
- NumPy
- pandas
- re (Regular Expressions)
- NLTK (Natural Language Toolkit)
- Scikit-learn (TfidfVectorizer, Logistic Regression, train_test_split, accuracy_score)

## Usage
1. Open the Jupyter Notebook `fake_news_prediction.ipynb`.
2. Follow the steps in the notebook to understand data preprocessing, feature extraction, and model training.
3. Modify the notebook if needed for experimentation or use it as a base for similar projects.

## Model Performance
- Achieved an accuracy of **97.91%** on the test data.

## How It Works
1. **Data Preprocessing:** Cleans the text data by removing punctuation, stopwords, and performing stemming to reduce words to their root forms.
2. **Feature Extraction:** Converts the cleaned text data into numerical format using TF-IDF vectorization, which measures the importance of words.
3. **Model Training:** Uses a Logistic Regression classifier to train on the extracted features and labels.
4. **Prediction:** Predicts the label (real or fake) for new news titles and author names.

## Results
![image](https://github.com/user-attachments/assets/408642cc-6c07-4e5f-be46-72d7725dce23)


## Contributing
Feel free to fork this repository, create a new branch, and submit a pull request for any improvements.

## Acknowledgments
- The dataset used in this project was sourced from https://kaggle.com/competitions/fake-news.
- Special thanks to the open-source community for providing useful tools and libraries.
