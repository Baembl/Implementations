# SMS Spam Detection using Naive Bayes

This project implements an SMS spam detection system using Naive Bayes classifiers in Python. The workflow includes data loading, preprocessing, feature extraction using TF-IDF, model training, evaluation, and visualization of results.

## Features

- Loads and preprocesses SMS spam data.
- Extracts features using TF-IDF vectorization.
- Trains a Multinomial Naive Bayes classifier.
- Evaluates model performance with accuracy, classification report, and confusion matrix.
- Visualizes confusion matrix using Seaborn.

## Requirements

- Python 3.x
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Usage

1. Place your dataset (e.g., `spam.csv`) in the specified path.
2. Run the notebook cells in order.
3. The main function will:
    - Load and preprocess the data.
    - Extract features.
    - Split the data into training and test sets.
    - Train and evaluate the model.
    - Display results and plots.

## File Structure

- `load_data(filepath)`: Loads and formats the dataset.
- `preprocess_data(data)`: Cleans and encodes the data.
- `extract_features(data)`: Extracts TF-IDF features.
- `train_and_evaluate(X_train, X_test, y_train, y_test)`: Trains and evaluates the model.
- `main()`: Orchestrates the workflow.