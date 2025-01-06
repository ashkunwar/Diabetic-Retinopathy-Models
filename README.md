# Diabetic Retinopathy Detection Using Deep Learning

This repository contains the implementation of deep learning models for detecting diabetic retinopathy from medical retinal images. The project focuses on classifying retinal images into different severity levels of diabetic retinopathy using pre-trained models and advanced techniques.

## Table of Contents
- [Introduction](#introduction)
- [Preprocessing](#preprocessing)
- [Model Architecture](#model-architecture)
- [Training](#training)
- [Results](#results)
- [Usage](#usage)

## Introduction
Diabetic retinopathy is a severe eye condition that can lead to blindness if not detected early. This project aims to develop a robust deep learning pipeline to classify diabetic retinopathy images into different severity levels.

## Preprocessing
The following preprocessing steps were applied:
1. Resizing images to a fixed input size.
2. Normalization to standardize pixel values.
3. Splitting the dataset into training, validation, and testing sets.

## Model Architecture
The repository contains implementations for:

1. **Inception-ResNet-v2**:
   - Fine-tuned for diabetic retinopathy classification.

2. **DenseNet**:
   - Pre-trained on ImageNet and fine-tuned for the task.

## Training
- Training and validation loss were monitored to address overfitting.
- Optimization techniques like learning rate scheduling and dropout were utilized.

## Results
The results indicate the effectiveness of fine-tuning pre-trained models for diabetic retinopathy classification. However, further improvements can be made to boost accuracy and reduce overfitting.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ashkunwar/Diabetic-Retinopathy-Models.git
   cd Diabetic-Retinopathy-Models
   ```

