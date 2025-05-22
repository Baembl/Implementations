# SMS Spam Detection using Recurrent Neural Networks (PyTorch)

This Jupyter Notebook demonstrates how to build a simple SMS spam detection model using a Recurrent Neural Network (RNN) implemented in PyTorch. The dataset used is a collection of SMS messages labeled as "spam" or "ham" (not spam).

## Features

- **Data Loading & Preprocessing:**  
    Loads SMS data from a public URL, tokenizes and encodes the text, and pads sequences for uniform input length.
- **Label Encoding:**  
    Converts categorical labels ("spam", "ham") to numerical values using `LabelEncoder`.
- **Custom Dataset & DataLoader:**  
    Wraps the data in a PyTorch `Dataset` and uses `DataLoader` for batching.
- **RNN Model:**  
    Defines a simple RNN-based classifier using PyTorch's `nn.Module`.
- **Training & Evaluation:**  
    Trains the model and evaluates its accuracy on a held-out test set.
- **Loss Visualization:**  
    Plots the training loss over epochs.

## Usage

1. **Install Dependencies:**
        - PyTorch
        - pandas
        - numpy
        - scikit-learn
        - matplotlib

2. **Run the Notebook:**
        - Execute each cell in order to preprocess the data, train the model, and evaluate its performance.

3. **Results:**
        - The notebook prints the training loss per epoch and the final test accuracy.
        - A plot of the training loss over epochs is displayed.

## Reference

The implementation in this notebook is referenced from the following article:  
[Implementing Recurrent Neural Networks in PyTorch - GeeksforGeeks](https://www.geeksforgeeks.org/implementing-recurrent-neural-networks-in-pytorch/)