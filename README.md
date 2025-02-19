# Skin-Cancer-Detection [![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

**CNN-Based Skin Cancer Detection from Dermoscopic Images**

Achieved 88.55% accuracy on the ISIC 2024 dataset, demonstrating the potential of deep learning for improving skin cancer diagnosis.

**[Repository](https://github.com/maria0041/skin-cancer-detection.git)**

## Overview

This project utilizes Convolutional Neural Networks (CNNs) to detect skin cancer from dermoscopic images.  Trained on the ISIC 2024 Skin Cancer Detection Challenge dataset, the model classifies skin lesions as benign or malignant. The results show that CNNs can learn complex image features and generalize well, highlighting their potential for improving diagnostic accuracy and efficiency.

## Key Findings

*   **High Accuracy:** 88.55% accuracy in classifying skin lesions.
*   **Deep Learning for Diagnosis:** Reduces subjectivity and variability in human diagnosis, potentially improving patient outcomes.
*   **Large-Scale Dataset:** Training on the ISIC 2024 dataset improved model generalization.
*   **Overfitting Challenges:**  Identified overfitting, suggesting a need for further regularization and data augmentation.

## Dataset

*   **Source:** ISIC 2024 Skin Cancer Detection Challenge
*   **Description:** Dermoscopic images of skin lesions with benign/malignant labels.
*   **Preprocessing:**
    *   Resized to 224x224.
    *   Normalized.
    *   Augmented for better generalization.

## Model Architecture

*   **Base Model:** Custom CNN trained from scratch.
*   **Layers:**
    *   Conv2D layers with ReLU activation.
    *   MaxPooling for feature extraction.
    *   Fully Connected (Dense) layers for classification.
*   **Loss Function:** Binary Cross-Entropy.
*   **Optimizer:** Adam.
*   **Metrics:** Accuracy, Precision, Recall.

## Installation & Setup

```bash
      git clone https://github.com/maria0041/skin-cancer-detection.git
      cd skin-cancer-detection
      pip install -r requirements.txt
```
## References
* ISIC Archive – Large-scale dermatology dataset
* Related Research:
   * CNNs for Skin Cancer Classification
   * Deep Learning for Dermatology Diagnosis
   * Regularization Techniques for CNNs
## License
MIT License. See LICENSE.
