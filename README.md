# MNIST Handwritten Digit Classification (PyTorch)

This project implements a neural network to classify handwritten digits (0–9) from the MNIST dataset using PyTorch.  
It was completed as part of a Udacity Deep Learning project.

## Project Overview

MNIST is a standard benchmark dataset in computer vision, containing:
- 60,000 training images
- 10,000 test images  
Each image is a 28×28 grayscale handwritten digit.

In this project, a convolutional neural network (CNN) was trained to recognize digits with high accuracy.

## Model Architecture

The model consists of:
- Two convolutional layers with ReLU activation and max pooling
- A dropout layer to reduce overfitting
- Two fully connected layers
- Output layer with 10 classes (digits 0–9)

This architecture allows the model to capture spatial features such as edges and strokes, which improves performance over a simple fully connected network.

## Training Details

- Framework: PyTorch
- Loss function: CrossEntropyLoss
- Optimizer: Adam
- Device: CPU
- Dataset: MNIST (torchvision)
- Test Accuracy: **~99.2%**

## Results

The trained model achieved approximately **99.2% accuracy** on the MNIST test set, which is comparable to other high-performing single CNN models on this dataset.
