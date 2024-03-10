# Digit_Recognition_Web_App

## Structure of App

### Technologies Used
- Keras
- TensorFlow.js
- HTML
- CSS
- JavaScript
- GitHub Pages

## Introduction
This project aims to create a convolutional neural network (CNN) for recognizing handwritten digits. The model is trained on the MNIST dataset available in Keras.

## MNIST Dataset
The MNIST dataset consists of 60,000 training images and 10,000 testing images. Each image is 28x28 pixels and grayscale.

## CNN Model Overview
- The model consists of 17 layers, including Conv2D, MaxPooling2D, BatchNormalization, Dense, Flatten, and Dropout layers.
- The input layer has 32 neurons, and the output layer has 10 neurons representing the 10 different classes.
- The model is trained for 30 epochs.
- Categorical cross-entropy is used as the loss function, and Adam is used for optimization.
- The model achieves an accuracy of 99.15%.

## Deployment
To deploy the model:
1. Save the model using TensorFlow.js converters as a JSON file and the weights as an .h5 file.
2. Use TensorFlow.js to load the model and make predictions in a JavaScript file.
