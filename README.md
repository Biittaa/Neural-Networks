# Neural Networks Project

This project demonstrates the implementation of different neural network architectures using PyTorch on popular datasets.

## Files and Descriptions

- **iris_mlp.py**  
  Implements a Multilayer Perceptron (MLP) to classify Iris flower species based on four features.  
  Dataset: Iris (150 samples, 3 classes).  
  Expected accuracy: at least 70% on training and test sets.

- **fashion_mlp.py**  
  Implements an MLP model to classify images from the MNIST-Fashion dataset.  
  Dataset: MNIST-Fashion (70,000 grayscale images, 10 classes).  
  Expected accuracy: at least 80% on training and test sets.

- **fashion_cnn.py**  
  Implements a Convolutional Neural Network (CNN) to classify MNIST-Fashion images, leveraging convolutional and pooling layers for feature extraction.  
  Expected accuracy: at least 90% on training and test sets.

## Requirements

- Python 3.x  
- PyTorch  
- torchvision (for loading datasets)  
- numpy

## Usage

Run each script independently. Make sure the required libraries are installed. Example:

```bash
python iris_mlp.py
python fashion_mlp.py
python fashion_cnn.py
