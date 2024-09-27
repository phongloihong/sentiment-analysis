# IMDB Movie Review Sentiment Analysis

This project performs sentiment analysis on IMDB movie reviews using machine learning techniques. It includes data preprocessing, exploratory data analysis, and classification using Decision Trees and Random Forests.

## Features

1. Data loading and preprocessing
2. Text cleaning and normalization
3. Exploratory Data Analysis (EDA) with visualizations
4. TF-IDF vectorization for feature extraction
5. Sentiment classification using Decision Trees and Random Forests

## Usage

1. Ensure you have the 'IMDB_Dataset.csv' file in the same directory as the notebook.
2. Run the Jupyter notebook 'train.ipynb' cell by cell to:
   - Load and preprocess the data
   - Perform EDA with visualizations
   - Train and evaluate the classifiers

## Data Preprocessing

The text preprocessing pipeline includes:
- HTML tag removal
- Contraction expansion
- Emoji removal
- URL removal
- Punctuation removal
- Lowercasing
- Lemmatization
- Stopword removal

## Models

Two classifiers are implemented:
1. Decision Tree Classifier
2. Random Forest Classifier

## Results

The accuracy scores for both models are printed at the end of the notebook.
