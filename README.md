🌿 Plant Disease Classification using CNN (TensorFlow/Keras)
----------------------------------------------------------------------------------------------------------------------------------------------------------------
This repository contains a complete deep learning pipeline for classifying plant leaf diseases using a custom Convolutional Neural Network (CNN) built with TensorFlow and Keras. The model is trained on the New Plant Diseases Dataset (Augmented) and supports prediction on individual images after training.

🚀 Features
-----------------------------------------------------------------------------------------------------------------------------------------------------------------
Custom-built CNN architecture with multiple convolutional blocks
Data loading via image_dataset_from_directory
Mixed-precision training for faster GPU performance
Regularization using dropout and early stopping
Automatic learning rate reduction
Final model exported in .keras format
Inference-ready code for predicting disease from a new leaf image

📁 Contents
------------------------------------------------------------------------------------------------------------------------------------------------------------------
index.py — full training, preprocessing, and prediction script
README.md — repository overview and instructions
Dataset Link - https://www.kaggle.com/datasets/vipoooool/new-plant-diseases-dataset
grey-leaf-spot-of-maize-maize-1.jpg - image being used to predict the model's output

🧪 Model Summary
------------------------------------------------------------------------------------------------------------------------------------------------------------------
Input size: 128 × 128 × 3
Layers: Multiple Conv2D, MaxPool2D, dense layers, and dropout
Output: Softmax across 38 plant disease categories
Optimizer: Adam (lr=0.0001)
Loss: Categorical Crossentropy

🔧 How to Use
-------------------------------------------------------------------------------------------------------------------------------------------------------------------
Add the dataset in the required folder structure.
Install dependencies and run the training script.
Use any leaf image to test the trained model.
