# YouTube Ad Recommender

## Overview

This project focuses on building a YouTube Ad Recommender system using machine learning techniques. The goal is to enhance the targeting of advertisements by analyzing video titles and descriptions, predicting suitable categories, and recommending ads accordingly.

## Contents

- [Data Preprocessing](#data-preprocessing)
- [Text Vectorization and Feature Engineering](#text-vectorization-and-feature-engineering)
- [Modeling and Training](#modeling-and-training)
- [Performance Evaluation and Analysis](#performance-evaluation-and-analysis)

## Data Preprocessing

- Addressed missing values and standardized text data.
- Converted text to lowercase, removed numbers, punctuation, and white spaces.
- Utilized lemmatization and removed stop words for improved textual data quality.
- Applied label encoding to the target variable for model training.

## Text Vectorization and Feature Engineering

- Employed TF-IDF vectorization to convert textual features into numerical representations.
- Utilized unigram and bigram features for both title and description texts.
- Conducted a detailed analysis of the features, extracting valuable insights for each class.

## Modeling and Training

- Split the data into training and testing sets for model evaluation.
- Trained Naive Bayes and SVM models on combined features derived from both title and description texts.

## Performance Evaluation and Analysis

- Evaluated model performance using precision, recall, and a confusion matrix.
- Visualized precision-recall curves for Naive Bayes and SVM, providing a comprehensive understanding of model performance.
- Communicated results effectively through clear and concise visualizations.

## Usage

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/youtube-ad-recommender.git
   cd youtube-ad-recommender

## Contributing 
  - Feel free to contribute to the project by opening issues or submitting pull requests. Any feedback or improvements are highly appreciated.
