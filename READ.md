# MNIST Digit Classification

This project is focused on classifying handwritten digits from the MNIST dataset using a deep learning model built with Keras and TensorFlow.

## Overview

The MNIST dataset consists of 60,000 training images and 10,000 testing images, each 28x28 pixels and labeled with a digit from 0-9. This project implements a neural network model to classify these digits.

## Table of Contents

- [Setup](#setup)
- [Data Preprocessing](#data-preprocessing)
- [Model Architecture](#model-architecture)
- [Performance Evaluation](#performance-evaluation)
- [Challenges](#challenges)
- [Results](#results)
- [Links](#links)

## Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/ML-Projects.git
   cd MNIST-Classification


2. Install the requirementts
pip install -r requirements.txt


## Data Preprocessing
Data Preprocessing
The dataset is loaded directly from Keras, where it is split into training and test sets. The images are reshaped and normalized before being fed into the model.

Preprocessing Steps:
Reshaping the data to 28x28x1.
Normalization of pixel values (scaling to the range [0, 1]).


## Model Architecture
Model Architecture
A simple feed-forward neural network (fully connected layers) was used for digit classification. The architecture consists of:

Input Layer: Flatten the 28x28 pixel data.
Hidden Layer 1: Dense layer with 128 units and ReLU activation.
Hidden Layer 2: Dense layer with 64 units and ReLU activation.
Output Layer: Dense layer with 10 units (one per digit) and softmax activation.
Performance Evaluation
The model's performance was evaluated using the following metrics:

Accuracy: The percentage of correctly predicted digits.
Precision: The proportion of positive predictions that were actually correct.
Recall: The proportion of actual positives that were correctly predicted.

Evaluation Results:
Accuracy: 97.56%
Precision: 97.57%
Recall: 97.54%


## Challenges
Challenges
Initially struggled with input shape mismatch, but resolved by reshaping the data properly.
Fine-tuned the model's architecture and hyperparameters for better performance.


## Results
Results
The final model achieved approximately 98% accuracy on the test set, making it highly efficient for digit classification.