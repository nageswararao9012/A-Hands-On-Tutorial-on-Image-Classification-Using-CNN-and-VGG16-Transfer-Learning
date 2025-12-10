# A-Hands-On-Tutorial-on-Image-Classification-Using-CNN-and-VGG16-Transfer-Learning
Individual Assignment: Machine Learning Tutorial
Author: Nageswararao Konidhela
Student ID: 24098979
Project Overview

This repository contains a complete, tutorial-style implementation of flower image classification using:

✅ A baseline Convolutional Neural Network (CNN)
✅ Transfer learning with VGG16
✅ Fine-tuning for performance improvement
✅ Performance evaluation with confusion matrices
✅ Prediction visualisations
✅ Training metrics and figures

Flowers Recognition Dataset from Kaggle: https://www.kaggle.com/datasets/apollo2506/flowers-recognition-dataset

How To Run
 Download the dataset ZIP
 Run the notebook end-to-end
 Dataset is automatically extracted
 Data is cleaned and prepared
 CNN is trained
 VGG16 is applied
 Fine-tuning is performed
 Plots and results are generated

 Models Implemented
1️⃣ Baseline CNN (Trained from Scratch)
3 convolution layers
Dense classifier
Data augmentation
Suffers from overfitting
Final accuracy: 70%

2️⃣ VGG16 Transfer Learning (Frozen Base)
Uses pretrained ImageNet features
Only trains classifier
Major improvement in performance
Final accuracy: 79%

3️⃣ VGG16 Fine-Tuned
Upper layers unfrozen
Low learning rate
Specialisation to flower features
Final accuracy: 88.5%
