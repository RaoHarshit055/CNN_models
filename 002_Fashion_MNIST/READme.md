🧥👟 Fashion MNIST Classification with CNN
📌 Project Overview

This project implements a Convolutional Neural Network (CNN) using TensorFlow/Keras to classify images from the Fashion MNIST dataset into 10 categories such as shoes, shirts, bags, and coats.

The goal is to demonstrate how CNNs can effectively recognize fashion items compared to traditional fully connected networks.

📂 Dataset

1.Source: Fashion MNIST (60,000 training + 10,000 testing images)

2.Image size: 28x28 grayscale

3.Classes: 10 categories (e.g., T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot).

🏗️ Model Architecture
1.Conv2D + ReLU

2.MaxPooling2D

3.Conv2D + ReLU

4.MaxPooling2D

5.Flatten Layer

6.Dense (Hidden layers)

7.Dense (Output with Softmax)

⚙️ Training
Optimizer: Adam,Loss: Sparse Categorical Crossentropy,Epochs: 20
