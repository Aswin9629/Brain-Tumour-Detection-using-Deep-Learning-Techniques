# Brain-Tumour-Detection-using-Deep-Learning-Techniques
Brain Tumor Detection using Deep Learning Techniques is a medical imaging project focused on identifying brain tumors from MRI and CT scan images using advanced deep learning models. The project compares the performance of CNN, VGG19, and ResNet architectures to evaluate which model provides the most accurate and reliable tumor detection.

The image dataset was preprocessed by resizing all images to 224×224 pixels, followed by data augmentation techniques such as rotation, flipping, and scaling to improve model generalization. CNN was built as a custom baseline model, while VGG19 and ResNet were fine-tuned using transfer learning with pre-trained ImageNet weights.

The models were evaluated using accuracy, precision, recall, and F1-score. CNN and VGG19 achieved 97% test accuracy, while ResNet achieved the best performance with 99% test accuracy. These results show that deep learning can support faster, more accurate, and more efficient medical image diagnosis by reducing manual workload and improving early tumor detection.

This project demonstrates the practical use of computer vision and deep learning in healthcare, with future improvements including larger datasets, explainable AI, and multimodal integration for more trustworthy clinical decision support.
