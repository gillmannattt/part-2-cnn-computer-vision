# part-2-cnn-computer-vision
# Computer Vision Problem Formulation and CNN Prototype

## Objective
Build a CNN-based image classification model to detect manufacturing product defects.

## Problem Type
Image Classification

## Classes
- normal
- scratch
- dent
- stain

## Dataset
The dataset contains image samples of product surfaces. Each image belongs to one of four classes.

## Preprocessing
- Resized images to 128 × 128
- Normalized pixel values
- Split data into training and testing sets
- Applied augmentation

## Model
A CNN model was built using:
- Conv2D layers
- ReLU activation
- MaxPooling layers
- Flatten layer
- Dense layer
- Softmax output layer

## Evaluation
The model was evaluated using:
- Accuracy
- Loss
- Confusion matrix
- Sample predictions

## CNN Concepts
Convolution detects visual patterns. Pooling reduces image size while keeping important features. ReLU helps the model learn complex patterns. CNNs are better than regular feed-forward networks for images because they preserve spatial relationships.

## Business Use Case
This model can be used in manufacturing quality inspection to automatically detect defects such as scratches, dents, and stains.

## Conclusion
The CNN model demonstrates how computer vision can support automated defect detection and improve manufacturing quality control.
