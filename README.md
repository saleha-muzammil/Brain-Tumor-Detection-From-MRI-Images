# Image Classification of Brain Tumors with Deep Learning

## Project Overview

This project aims to develop a deep learning model to classify brain images for tumor detection, using the dataset from [Kaggle](https://www.kaggle.com/datasets/navoneel/brain-mri-images-for-brain-tumor-detection/data). Brain tumors can be cancerous or benign, with varying symptoms based on the affected brain area. Timely and accurate detection is crucial for effective treatment planning.

## Project Goals

- Develop a model that accurately identifies brain tumors from MRI and CT scans.
- Improve diagnostic accuracy with high sensitivity and specificity to minimize false diagnoses.
- Enhance clinical decision-making through automated, reliable image analysis.

## Methodology

### Data Preprocessing

- Visualization, handling duplicates and corrupt images.
- Normalization, shuffling, and splitting of data for training and testing.

### Model Development

- Using convolutional neural networks (CNNs) to extract and classify image features.
- Architecture includes layers for convolution, pooling, dropout, and dense connections for classification.

### Training and Evaluation

- Training with stochastic gradient descent (SGD) or Adam optimizer.
- Evaluation using accuracy, precision, recall, and F1 score metrics.

### Custom CNN Model

- Achieved a high training accuracy, with detailed evaluation metrics available.
- Model loss, confusion matrix, and other statistics indicate robust performance.

### Transfer Learning with VGG-16

- Adapted VGG-16 architecture to classify brain tumors effectively.
- Utilized model augmentation and fine-tuning techniques for enhanced performance.
