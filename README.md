# CNN Computer Vision Project

## Project Overview

This project focuses on building a Convolutional Neural Network (CNN) model for image classification using TensorFlow/Keras.

The objective of the project was to classify images into four categories:

- dent
- scratch
- stain
- normal

The project demonstrates the complete deep learning workflow including:
- dataset exploration
- image preprocessing
- CNN model creation
- model training
- evaluation
- confusion matrix analysis
- sample predictions

# Problem Type

This dataset represents an Image Classification problem because each image belongs to one specific category.

The CNN model learns visual patterns from images and predicts the correct defect class.

# Dataset Exploration

## Classes in Dataset

- dent
- scratch
- stain
- normal

## Images Per Class

Each class contains approximately 120 images.

## Image Dimensions

- 96 x 96 pixels

The dataset is balanced across all categories.


# Image Preprocessing

The following preprocessing steps were performed:

- Resizing images to 128x128

- Normalizing pixel values

- Splitting into training and validation datasets

- Creating image generators using TensorFlow/Keras



# CNN Architecture

The CNN model includes:

- Convolution layers

- MaxPooling layers

- Flatten layer

- Dense layer

- Dropout layer

- Output layer with Softmax activation



# Model Performance

## Final Validation Accuracy

- Approximately 83%

## Observations

The model performed very well on the normal and stain classes.

Some confusion occurred between dent and scratch images due to similar visual patterns.

Overall, the CNN successfully learned meaningful image features from the dataset.



# CNN Concepts

## What is Convolution?

Convolution helps the CNN detect important image features such as edges, textures, scratches, and shapes using filters.

## Why is Pooling Used?

Pooling reduces image size while preserving important features. It also helps reduce computation and overfitting.

## Why is ReLU Commonly Used in CNNs?

ReLU introduces non-linearity into the network and helps the model learn complex image patterns efficiently.

## Why are CNNs Better for Images?

CNNs are specifically designed for image data because they automatically learn spatial and visual features directly from pixels.



# Business Use Case

This type of CNN solution can be used in manufacturing industries for automated quality inspection.

The model can help identify product defects such as dents, scratches, or stains automatically, reducing manual inspection effort and improving quality control.
