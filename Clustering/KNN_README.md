# Breast Cancer Diagnosis using k-Nearest Neighbors (kNN)

This Jupyter Notebook demonstrates a complete workflow for classifying breast cancer tumors as malignant or benign using the k-Nearest Neighbors (kNN) algorithm. The dataset used is a CSV file containing various features computed from digitized images of breast mass cell nuclei.

## Workflow Overview

1. **Import Libraries**  
    Essential libraries for data manipulation, visualization, and machine learning are imported, including `numpy`, `pandas`, `matplotlib`, `seaborn`, and scikit-learn modules.

2. **Load Dataset**  
    The dataset is loaded from a CSV file using pandas.

3. **Data Exploration & Visualization**  
    - Display dataset shape and preview the first few rows.
    - Check for missing values and data types.
    - Visualize the distribution of the target variable (`diagnosis`) and numerical features using bar plots and histograms.
    - Generate a correlation heatmap to understand feature relationships.

4. **Data Preprocessing**  
    - Remove unnecessary columns (`id`, `Unnamed: 32`).
    - Encode the target variable (`diagnosis`) as numerical values (Malignant: 1, Benign: 0).
    - Split the data into training and test sets.
    - Standardize features using `StandardScaler`.

5. **Model Training & Evaluation**  
    - Train a kNN classifier (default k=5) on the scaled training data.
    - Predict on the test set and evaluate performance using accuracy, confusion matrix, and classification report.
    - Compare train and test accuracy to check for overfitting.
    - Calculate additional metrics: precision, recall, specificity, and classification error.
    - Experiment with different values of k to observe changes in accuracy.

6. **Results Visualization**  
    - Visualize the confusion matrix using a heatmap.

## How to Run

1. **Requirements**
    - Python 3.x
    - Jupyter Notebook
    - Required libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `scikit-learn`

2. **Setup**
    - Place the dataset CSV file at the specified path in the notebook or update the `data_path` variable accordingly.

3. **Execution**
    - Run each cell sequentially in the Jupyter Notebook to reproduce the analysis and results.

## Key Results

- The kNN classifier achieves high accuracy on the test set (e.g., ~95.6% with k=5).
- The confusion matrix and classification report provide detailed insights into model performance.
- Experimenting with different k values helps in tuning the model for optimal results.

## Notes

- The notebook includes comprehensive data exploration and visualization steps to understand the dataset before modeling.
- Feature scaling is crucial for kNN performance due to its reliance on distance metrics.
- The workflow can be adapted for similar classification problems with minimal changes.

---
**Author:**  
This notebook was created as a demonstration of machine learning workflow for breast cancer diagnosis using kNN.