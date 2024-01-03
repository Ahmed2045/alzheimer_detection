# Alzheimer's Disease Classification with CNN

## Overview

This repository contains a Convolutional Neural Network (CNN) for the classification of Alzheimer's disease stages using brain MRI images. The model is implemented using TensorFlow and Keras.

## Dataset

The dataset used in this project includes MRI images of patients with different stages of Alzheimer's disease. The images are categorized into four classes: Mild Alzheimer's, Moderate Alzheimer's, Non-Alzheimer's, and Very Mild Alzheimer's.

##Data Preprocessing
The dataset is loaded and split into training, testing, and validation sets.
ImageDataGenerator is used for real-time data augmentation during training.
Model Architecture
The CNN model architecture consists of convolutional layers, max-pooling layers, batch normalization, and fully connected layers. The model is trained to classify MRI images into one of the four Alzheimer's disease stages.
##Training
The model is trained for 30 epochs with a learning rate of 0.0001. Training and validation accuracy and loss are monitored and visualized.

##Results
The accuracy of the model on the test set is approximately 95%

##Conclusion
This project demonstrates the application of a CNN for the classification of Alzheimer's disease stages based on MRI images. Further improvements and fine-tuning can be explored to enhance the model's performance

