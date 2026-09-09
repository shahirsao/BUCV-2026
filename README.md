# Computer Vision 2026 Coursework - Spinal X-Ray Multimodal Sex Classification and BMI Regression
## Overview
The objective of this project was to create a multi-task deep learning pipeline for regression of BMI and classification of sex from X-ray images of spines. 1000 labelled training images were given alongside 195 unlabelled test images, some having added noise. In addition, the project asked for xAI analysis using tools such as Grad-CAM to explain the reasoning of the deep-learning models that was used for prediction. Deep-learning architectures that were implemented included DenseNet121, ResNet18 and EfficientNet (all pre-trained on ImageNet), with an untrained CNN used as a benchmark. The best predictive model established in this project was an ensemble of one ResNet18 and one DenseNet121.

## Running Instructions
The code in the notebook is written with the intention that the bucv26 file is placed in Google Drive.
