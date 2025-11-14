Fashion MNIST Image Classification (CNN)

This project builds a simple Convolutional Neural Network (CNN) to classify images from the Fashion MNIST dataset. The dataset contains 28×28 grayscale images of 10 types of clothing and accessories.

Overview:
The goal is to train a CNN that can correctly identify fashion items such as shirts, shoes, bags, and more.

Dataset Details:
Total images: 70,000
Training: 60,000
Testing: 10,000
Image size: 28×28 (grayscale)

Classes (10): T-shirt/top, Trouser, Pullover, Dress, Coat, Sandal, Shirt, Sneaker, Bag, Ankle boot

Model Summary

The CNN includes:

Convolutional layers (ReLU activation)

MaxPooling layers

Dense layers

Final softmax layer for 10-class prediction

Installation

Check Python version:

python --version



Install dependencies:

pip install -r requirements.txt
