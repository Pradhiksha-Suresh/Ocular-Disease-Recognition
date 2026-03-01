Project Overview

This project focuses on building a deep learning model to automatically classify retinal fundus images into multiple ocular disease categories: glaucoma, cataract, age-related degeneration, myopia, and normal. The goal is to assist in early disease detection using computer vision and transfer learning techniques.

What Was Done
1. Data Preparation

Organized retinal images by disease category.

Removed unrelated classes (hypertension, diabetes, others).

Identified and addressed significant class imbalance.

2. Image Preprocessing

Converted images to grayscale.

Applied CLAHE (Contrast Limited Adaptive Histogram Equalization) to enhance retinal features.

Rescaled pixel values for model compatibility.

3. Data Balancing & Augmentation

Used augmentation techniques such as brightness adjustments and horizontal flipping.

Balanced dataset to ensure fair learning across all disease categories.

4. Train–Validation–Test Split

Split dataset into:

80% Training

10% Validation

10% Testing

5. Model Development (Transfer Learning)

Tested multiple pretrained CNN architectures:

InceptionV3

VGG16

ResNet50

Custom classification layers were added on top of pretrained ImageNet weights.

6. Model Evaluation

Evaluated using Accuracy, Precision, Recall, and AUC.

InceptionV3 achieved the best overall performance (~88% accuracy).

VGG16 performed competitively (~83% accuracy).

Key Outcome

The project demonstrates how transfer learning combined with proper preprocessing and class balancing can significantly improve multi-class medical image classification performance.
