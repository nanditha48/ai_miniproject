# Breast Cancer Detection Neural Network

This repository contains code for a breast cancer detection neural network trained on the Breast Cancer Wisconsin (Diagnostic) Dataset. The model is implemented using TensorFlow and Keras.

## Overview

The neural network is designed to predict whether a tumor is malignant or benign based on various features extracted from breast cancer biopsies.

## Dependencies

- `numpy` for mathematical operations
- `pandas` for handling data in tabular form
- `matplotlib` for data visualization
- `scikit-learn` for dataset loading and preprocessing
- `tensorflow` and `keras` for building and training the neural network

 ## Dataset

The Breast Cancer Wisconsin (Diagnostic) Dataset is loaded from scikit-learn and converted into a Pandas DataFrame. It consists of features such as mean radius, mean texture, and mean smoothness, among others.

## Results
The neural network is trained for 10 epochs, and the training/validation accuracy and loss are visualized. The final accuracy on the test set is also printed.

## Publication
Link to the research paper published regarding the same topic: https://ymerdigital.com/archives/?cpage=6&issId=%202202 (Scroll up to 117 title)

Install the dependencies using:
```bash
pip install numpy pandas matplotlib scikit-learn tensorflow







