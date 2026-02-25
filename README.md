# LeNet CNN for MNIST Digit Classification

## Overview
This project implements a Convolutional Neural Network (CNN) based on the LeNet architecture to classify handwritten digits from the MNIST dataset.  
The model learns image features using convolution layers and predicts digits from 0–9.

## Model Architecture
- Convolution Layer  
- Pooling Layer  
- Convolution Layer  
- Pooling Layer  
- Fully Connected Layers  
- Output Layer (10 classes)

## Dataset
MNIST Handwritten Digits  
- 28 × 28 grayscale images  
- 10 digit classes (0–9)

## Training
- Data preprocessing using PyTorch transforms  
- Model trained using cross-entropy loss  
- Optimization with backpropagation  

## Results
The model achieves approximately 98–99% accuracy on the test dataset.

## Technologies Used
- Python  
- PyTorch  
- Jupyter Notebook
