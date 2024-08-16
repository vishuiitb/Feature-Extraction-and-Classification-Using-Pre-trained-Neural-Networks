# Feature Extraction and Classification Using Pre-trained Neural Networks

## Project Overview

This repository contains the code and resources for the project titled **Feature Extraction and Classification Using Pre-trained Neural Networks**. The main objective of this project is to leverage a pre-trained ResNet18 model as a fixed feature extractor for image data, followed by optimizing machine learning models like SVM and Random Forest for classification tasks.

## Features

- **Pre-trained ResNet18 Feature Extraction**:
  - A function was created to utilize the ResNet18 model pre-trained on ImageNet as a fixed feature extractor.
  - Extracted features from training images produce an Nx512 dimensional array, where N is the number of images.

- **Model Optimization**:
  - Support Vector Machine (SVM) and Random Forest models were optimized for the classification task.
  - Performance metrics such as accuracy and F1 score were used to evaluate model performance on test data.
