# CIFAR-10 Image Classification with Keras

This project demonstrates how to build and train a Convolutional Neural Network (CNN) using Keras to classify images from the CIFAR-10 dataset.

## Overview

- Loads the CIFAR-10 dataset, which consists of 60,000 32x32 color images in 10 classes.
- Preprocesses the data by normalizing pixel values and one-hot encoding the labels.
- Defines a CNN architecture using Keras' Sequential API.
- Compiles and trains the model on the training data.
- Evaluates the model on the test data.

## Requirements

- Python 3.x
- Keras
- NumPy

## Usage

1. **Import Libraries and Load Data**
    - The code imports necessary libraries and loads the CIFAR-10 dataset.

2. **Preprocess Data**
    - Reshapes and normalizes the image data.
    - Converts class labels to one-hot encoded vectors.

3. **Build the Model**
    - Constructs a CNN with multiple convolutional, pooling, dropout, and dense layers.

4. **Compile and Train**
    - Compiles the model with categorical crossentropy loss and Adam optimizer.
    - Trains the model for 10 epochs.

## Files

- `notebook.ipynb`: Jupyter Notebook containing the code for data loading, preprocessing, model building, training, and evaluation.

## Notes

- The model achieves reasonable accuracy on CIFAR-10, but further tuning and data augmentation can improve results.
- You can modify the architecture, batch size, or number of epochs as needed.

## References

- [Keras Documentation](https://keras.io/)
- [CIFAR-10 Dataset](https://www.cs.toronto.edu/~kriz/cifar.html)