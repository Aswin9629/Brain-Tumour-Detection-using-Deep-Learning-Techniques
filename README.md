# Brain Tumor Detection using Deep Learning Techniques

## Overview
This project focuses on detecting brain tumors from MRI and CT scan images using deep learning techniques. CNN, VGG19, and ResNet models were implemented and compared to identify the most accurate model for tumor detection.

## Problem Statement
Manual brain tumor detection from medical images can be time-consuming and may vary between radiologists. This project aims to build an automated deep learning-based system to improve detection accuracy and support faster diagnosis.

## Dataset
The dataset contains MRI and CT scan images categorized into tumor and no-tumor classes. Images were resized to 224x224 pixels and augmented using rotation, flipping, and scaling.

## Technologies Used
- Python
- TensorFlow
- Keras
- OpenCV
- NumPy
- Matplotlib
- Scikit-learn
- CNN
- VGG19
- ResNet50

## Models Implemented
- Custom CNN
- VGG19 using transfer learning
- ResNet50 using transfer learning

## Methodology
The images were preprocessed, resized, normalized, and augmented to improve model performance. Three deep learning models were trained and evaluated using accuracy, precision, recall, and F1-score.

## Results

| Model | Training Accuracy | Testing Accuracy |
|---|---:|---:|
| CNN | 98% | 97% |
| VGG19 | 99% | 97% |
| ResNet | 99% | 99% |

ResNet achieved the best testing accuracy of 99%, making it the most effective model in this project.

## Future Improvements
- Use a larger and more diverse medical image dataset
- Add Grad-CAM for explainable AI visualization
- Deploy the model using Streamlit or Flask
- Add image upload and real-time prediction
- Compare with transformer-based models

## Author
Aswin S
