# Development of Machine Learning Model for Underwater Object Detection
This project focuses on the development of a machine learning-based solution for underwater object detection, addressing challenges like light scattering and absorption that hinder visibility and object classification in underwater environments. The project uses cutting-edge deep learning techniques to enhance detection accuracy for various marine objects.

# Introduction
Underwater object detection is a critical task in image processing and computer vision with applications in marine science, sub-aquatic structure maintenance, and conservation. Traditional computer vision-based approaches struggle to address challenges such as:

 - Light Scattering: Causes blurriness and distortion in images.
 - Light Absorption: Leads to color loss and low contrast, making object detection more difficult.
# Objectives
 - Detection using CNN: Develop a deep learning model for efficient underwater object detection and classification.
 - Object Detection using YOLO: Implement a YOLO-based detection system for robust performance on underwater image datasets.
# Proposed System
The system architecture integrates:

 - Backbone: ResNet-50 for residual learning and effective feature extraction.
 - Neck: ASPP and RFB modules for capturing multiscale context and strengthening feature representation.
 - Path Aggregation: FPN and PAN for enhancing feature propagation across layers.
 - Head: YOLOv8 for real-time and accurate object detection.
# Dataset
We used a brackish underwater image dataset containing 14,674 images across six classes:

 - Crab
 - Fish
 - Small Fish
 - Jellyfish
 - Starfish
 - Shrimp
# Data Split:
Training: 11,739 images
Validation: 1,467 images
Testing: 1,468 images
# Key Highlights
 - Tech Stack: Utilized CUDA 12.7 for GPU acceleration.
 - Performance Metrics: Measured accuracy, precision, recall, and F1-score for model evaluation.
# Challenges Addressed:
 - Improved detection in low-light conditions.
 - Enhanced model generalization for diverse underwater environments.
# Conclusion
This project provides a comprehensive analysis of underwater object detection techniques and proposes a robust system using state-of-the-art deep learning methods. Future research will focus on optimizing hyperparameters and extending the model's capabilities to more complex underwater scenarios.
