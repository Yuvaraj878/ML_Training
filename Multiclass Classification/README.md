# Multiclass classification
# CIFAR-10: Dog, Cat, and Deer Classifier

This repository contains code and instructions to train a simple Convolutional Neural Network (CNN) using TensorFlow and Keras to classify images of **dogs**, **cats**, and **deer** from the CIFAR-10 dataset. The project demonstrates how to filter selected classes, train & save a model, reload it, and make predictions on your own images.

## Dataset

- **Source:** CIFAR-10 (https://www.cs.toronto.edu/~kriz/cifar.html)
- **Classes used:** Dog, Cat, Deer

## Requirements

- Python 3.x
- TensorFlow (>=2.x)
- NumPy

## Code Overview

1. **Dataset Loading & Filtering**
   - Load CIFAR-10 and filter for only dogs, cats, and deer images.
2. **Model Building**
   - Simple CNN model with three output classes.
3. **Training**
   - Trains for 20 epochs with validation split.
4. **Evaluation**
   - Evaluates and displays test set accuracy.
5. **Model Save & Load**
   - Demonstrates saving and restoring the trained model.
6. **Prediction**
   - Shows how to predict the class of a custom image.
 7. **Predicting on Your Own Images**

Replace `cat1.jpeg` in the script with your image file (ensure it is in the repo folder). The image will be preprocessed and classified as either dog, cat, or deer.

