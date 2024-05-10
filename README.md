# MRI Tumor Detection with Deep Learning

## Overview
This project involves the application of advanced deep learning models to enhance tumor detection in MRI datasets. The MRI images were subjected to various preprocessing methods including flipping, random cropping, and adjustments in color, hue, and brightness to increase dataset diversity and robustness.

## Models Used
- **VGG16**
- **ResNet50**
- **Vision Transformer (ViT)**

## Key Findings
The research highlights the effectiveness of using the Vision Transformer (ViT) model, which outperformed other models with:
- **Accuracy**: 80.46%
- **Precision**: 0.85
- **Recall**: 0.80
- **F1 Score**: 0.80

ResNet50 showed strong recall capabilities:
- **Accuracy**: 76.65%
- **Precision**: 0.74
- **Recall**: 0.83
- **F1 Score**: 0.77

VGG16, while effective, showed:
- **Accuracy**: 62.44%
- **Precision**: 0.66
- **Recall**: 0.61
- **F1 Score**: 0.63

## Conclusion
The findings underscore the superior performance of the Vision Transformer (ViT) in terms of accuracy, precision, recall, and F1 score, demonstrating its robust feature extraction capabilities which are crucial for accurate tumor classification.

## Dataset and Preprocessing
The MRI dataset used in this project underwent extensive preprocessing to simulate real-world conditions that affect image quality and detail. Techniques used included:
- Flipping
- Random cropping
- Color, hue, and brightness adjustments

## Running the Code
To replicate our findings or to test the models with new MRI images, follow the setup instructions and use the scripts provided in this repository.

## Citation
If you find our work useful in your research, please consider citing:

