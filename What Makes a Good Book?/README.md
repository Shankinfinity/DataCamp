# Predicting Book Popularity with Machine Learning

## Overview

In this project, I developed a machine learning model to predict whether a book is likely to be popular based on its metadata and customer reviews. After preprocessing the dataset, I engineered features from review helpfulness, book categories, and review text, then trained a Random Forest Classifier to distinguish between popular and non-popular books.

## Key Insights

* Extracted helpfulness metrics from customer reviews by calculating the proportion of helpful reviews.
* Engineered text-based features by counting positive words in book descriptions, review summaries, and review text.
* Converted book categories into numerical features using one-hot encoding.
* Trained a Random Forest Classifier using both structured and engineered features.
* Evaluated the model by measuring its prediction accuracy on a separate test dataset.

## Skills Demonstrated

* Data preprocessing with Pandas
* Feature engineering
* Text processing with CountVectorizer
* Random Forest classification
* Model evaluation using accuracy


