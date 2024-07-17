# Potato Plant Disease Image Classification with Fast.ai and Ensemble Learning

This project demonstrates an advanced image classification pipeline using Fast.ai. By fine-tuning multiple pretrained models and employing ensemble bagging, we achieved an impressive accuracy of 98%.

# Overview
In this project, I fine-tuned several state-of-the-art pretrained models using the Fast.ai library to classify images into various categories. To enhance the robustness and accuracy of the predictions, I used ensemble bagging to combine the predictions from these models, selecting the most frequent prediction as the final output.

# Key Features
Pretrained Models: Utilized multiple pretrained models such as ResNet, EfficientNet, and others.
Fine-Tuning: Applied transfer learning techniques to fine-tune the models on our specific dataset.
Ensemble Bagging: Implemented an ensemble bagging method to aggregate predictions from all models, ensuring high accuracy and reliability.
High Accuracy: Achieved an overall accuracy of 98%, demonstrating the effectiveness of the ensemble approach.

# Methodology
1. Data Preparation:
Loaded and preprocessed the dataset.
Applied data augmentation techniques to enhance the diversity of the training data.

2. Model Fine-Tuning:
Leveraged the Fast.ai library to fine-tune several pretrained models.
Employed learning rate finder and one-cycle policy for optimal training.

3. Bagging:
Collected predictions from all fine-tuned models.
Used majority voting to determine the final prediction for each input.

# Dataset
The dataset used for this project is available on Kaggle. You can find it https://www.kaggle.com/datasets/hafiznouman786/potato-plant-diseases-data.

# Results
The ensemble bagging approach significantly improved the model's performance, resulting in a robust classifier with an accuracy of 98%.
