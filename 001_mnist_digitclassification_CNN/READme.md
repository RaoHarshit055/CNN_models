🧠 MNIST Digit Classification with CNN

This repository contains a Convolutional Neural Network (CNN) implementation for handwritten digit recognition using the MNIST dataset. The model is built with TensorFlow/Keras and achieves high accuracy on classifying digits (0–9).

📌 Project Overview

1.Dataset: MNIST Handwritten Digits
 (60,000 training & 10,000 testing images).


2.Task: Classify grayscale digit images (28×28 pixels) into 10 classes.

3.Approach: Build and train a CNN to automatically learn spatial patterns in images.

🏗️ Model Architecture
The CNN is designed with the following layers:

1.Conv2D + ReLU – Feature extraction 

2.MaxPooling2D – Dimensionality reduction

3.Dropout – Prevents overfitting

4.Flatten – Converts 2D maps to 1D

5.Dense Layers – Fully connected layers for classification

6.Softmax Output Layer – Predicts digit class (0–9)

