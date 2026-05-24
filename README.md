**Handwritten Digit Classification using CNN**

This repository presents an academic project focused on building a Convolutional Neural Network (CNN) to classify handwritten digits (0–9) using the MNIST dataset. The project explores the complete deep learning pipeline, from data preprocessing and model design to evaluation and practical usage.

The objective was to gain hands-on experience with image classification and understand how CNNs learn spatial patterns from visual data.

**Project Overview**

Handwritten digit recognition is a foundational computer vision task with applications in document digitization and automated data entry systems. In this project, a CNN model was trained on 28×28 grayscale digit images to accurately predict digit classes while maintaining good generalization on unseen data.

Beyond model training, the project also demonstrates how a trained model can be reused in a simple real-time application.

**Dataset**

**MNIST handwritten digit dataset**

70,000 grayscale images

60,000 training samples

10,000 test samples

Image size: 28 × 28

10 output classes (digits 0–9)

The dataset was normalized and reshaped to meet CNN input requirements.

**Model Architecture**

The CNN architecture was designed to balance simplicity and performance:

Convolutional layers with ReLU activation

Max pooling layers to reduce spatial dimensions

Fully connected layers for classification

Softmax output for multi-class prediction

This design allowed the model to effectively learn spatial features from handwritten digits.

**Training & Evaluation**

Optimizer: Adam

Loss Function: Categorical Cross-Entropy

Evaluation included:

Accuracy and loss curves

Confusion matrix

Precision, recall, and F1-score

The model achieved strong performance on the test dataset with minimal misclassification.

**Repository Contents**

MNIST-Handwritten-Digit-Classification.ipynb – Model implementation, training, and evaluation

MNIST-Handwritten-Digit-Classification.html – Exported notebook for easy viewing
