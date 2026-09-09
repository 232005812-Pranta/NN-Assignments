Problem Set 01: Pediatric Chest X-Ray Classification using CNN

Overview
This directory contains the solution for Problem Set 01, which focuses on classifying pediatric chest X-ray images into two classes: **Normal** and **Pneumonia** using a Deep Learning approach.

Methodology
- Preprocessing & Augmentation: Input images were resized to 150x150 pixels and normalized. Data augmentation techniques (random rotations, zoom, horizontal flip) were applied to the training set to minimize overfitting.
- Model Architecture: Built a Sequential Convolutional Neural Network (CNN) consisting of 3 Conv2D + MaxPooling layers, followed by Flatten, Dropout (0.5), and Dense layers with Sigmoid output.
- Training Parameters: Compiled using the Adam optimizer and Binary Crossentropy loss function over 10 training epochs.

## Model Findings & Results
- Test Accuracy: ~88.46%
- Pneumonia Recall: High sensitivity (~0.98), effectively identifying positive pneumonia cases.
- Evaluation: Evaluated using Precision, Recall, F1-Score, Loss-Accuracy curves, and Confusion Matrix.
