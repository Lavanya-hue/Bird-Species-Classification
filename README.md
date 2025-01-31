# Bird Species Classification with Explainable AI (XAI)

This project employs state-of-the-art deep learning models to classify bird species, coupled with Explainable AI (XAI) techniques to ensure transparency and trustworthiness in predictions.

## Overview

Birds are vital indicators of biodiversity and ecosystem health, but traditional methods of identifying bird species are often manual and time-intensive. This project integrates deep learning and XAI techniques to automate bird species classification while highlighting the decision-making process for improved transparency and reliability.

## Features

- **Deep Learning Models**: Utilizes VGG16, InceptionResNet V2, EfficientNetB2, and Inception V3 for classification.
- **Explainable AI**: Implements LIME and Grad-CAM to visualize the features influencing model predictions.
- **User-Friendly Interface**: Streamlit-based web tool and a mobile app built using Flutter for intuitive interaction.
- **Data Augmentation**: Enhances model robustness using techniques like rotation, flipping, and zoom.
- **Performance Metrics**: Evaluates models with accuracy, precision, recall, and F1 score.

## Methodology

1. **Data Preprocessing**: 
   - Images from the CUB-200-2011 dataset are resized, normalized, and split into training, validation, and test sets.
   - Augmentation includes rotation, width shift, zoom, and flip.

2. **Model Training**: 
   - Transfer learning with pretrained models fine-tuned on the dataset.
   - Regularization techniques like dropout and batch normalization are applied.
   - Early stopping prevents overfitting.

3. **Explainable AI**:
   - **LIME**: Generates local explanations highlighting influential features for specific predictions.
   - **Grad-CAM**: Produces heatmaps identifying key regions contributing to the model's predictions.

4. **Deployment**: 
   - A Streamlit web application allows users to upload bird images and analyze predictions.
   - A Flutter-based mobile app provides bird species identification on the go.

## Results

- **EfficientNetB2** achieved a validation accuracy of 90.84% with strong generalization.
- XAI techniques provided meaningful insights into the models' predictions, enhancing transparency.

## Contributors
Aditi Nadiger,
Bhoomika K,
Buddula Vanshika

## Acknowledgments
Dr. Sandeep Varma N, 
Associate Professor, 
Department of Machine Learning, 
BMS College of Engineering
