# Effectiveness of Neural Network Architectures on MNIST Dataset

# Overview
This study investigates the effectiveness of different neural network architectures in identifying handwritten digits from the MNIST dataset. Handwritten digit recognition poses a fundamental perceptual challenge, and neural networks have demonstrated remarkable capability in addressing this task. The study compares the performance of two regularized neural network architectures: a Dense Neural Network (DNN) and a Convolutional Neural Network (CNN).

While it's widely assumed that Convolutional Neural Networks, due to their translational invariance and hierarchical pattern discovery capabilities, would outperform other architectures in this task, this study serves as a comparative analysis and a challenging experiment.

# Methodology
The study proceeds with the following steps:

### Dataset Preparation:
The MNIST dataset, comprising 60,000 training images and 10,000 testing images of handwritten digits, is used for training and evaluation.

### Neural Network Architectures:

* Dense Neural Network (DNN): A traditional fully connected neural network architecture.
* Convolutional Neural Network (CNN): A specialized neural network architecture for image processing tasks, leveraging convolutional layers.

### Model Training: 
Both neural network architectures are trained on the MNIST dataset using appropriate regularization techniques to prevent overfitting. Also a custom implementation of a K-Fold Cross Validation algorithm were used.

### Evaluation: 
The trained models are evaluated on a separate test set to measure their performance in digit recognition accuracy.

Through this study, we aim to gain insights into the comparative effectiveness of different neural network architectures on the MNIST dataset. While the Convolutional Neural Network architecture is expected to excel due to its inherent properties, the results may reveal nuanced performance differences and provide valuable insights.
