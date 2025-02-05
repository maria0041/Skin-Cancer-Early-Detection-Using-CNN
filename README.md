# Skin-Cancer-Detection
Overview
This project demonstrates the effectiveness of Convolutional Neural Networks (CNNs) in detecting skin cancer from dermoscopic images. The proposed model, trained on the ISIC 2024 Skin Cancer Detection with 3D-TBP dataset, achieved an 88.55% accuracy in classifying skin lesions as benign or malignant.

The results indicate that the model can learn complex features from images and generalize well to unseen data. This study highlights the potential of deep learning techniques in improving the accuracy and efficiency of skin cancer diagnosis.

Key Findings

✅ High Accuracy: The CNN-based model achieved 88.55% accuracy in classifying skin lesions.

✅ Deep Learning for Diagnosis: CNNs help reduce the subjectivity and variability in human diagnosis, improving patient outcomes.

✅ Large-Scale Dataset: Training on ISIC 2024 dataset improved model generalization and performance.

✅ Overfitting Challenges: Some overfitting was observed, requiring further regularization and data augmentation strategies.

Dataset
Source:
ISIC 2024 Skin Cancer Detection Challenge
Description: The dataset contains dermoscopic images of skin lesions with corresponding labels (benign/malignant).
Preprocessing: Images were resized to 224×224, normalized, and augmented for better generalization.


Model Architecture

Base Model: Custom CNN trained from scratch 

Layers:
Conv2D layers with ReLU activation; 
MaxPooling for feature extraction; 
Fully Connected (Dense) layers for classification

Loss Function: Binary Cross-Entropy  
Optimizer: Adam  
Metrics: Accuracy, Precision, Recall

Installation & Setup
1. Clone the Repository
   
git clone https://github.com/maria0041/skin-cancer-detection.git

cd skin-cancer-detection

References
ISIC Archive – Large-scale dermatology dataset
Related Research:
CNNs for Skin Cancer Classification
Deep Learning for Dermatology Diagnosis 
Regularization Techniques for CNNs 

License
This project is licensed under the MIT License.
