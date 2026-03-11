# 🧠 Brain Tumor Detection System using CNN
## Dataset

The dataset used in this project can be downloaded from:

https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset

After downloading, extract the dataset and place it in the project folder.

## 📌 Project Overview

This project focuses on detecting and classifying brain tumors from MRI images using a Convolutional Neural Network (CNN). The model is trained to identify different types of brain tumors and predict the tumor category from an uploaded MRI image. A user-friendly interface is developed using Gradio, allowing users to upload MRI scans and receive predictions instantly.

## 🎯 Objective

The goal of this project is to assist in early detection of brain tumors by applying deep learning techniques to medical imaging data. The system classifies MRI images into different tumor categories with high accuracy.

## 🧠 Tumor Classes

The model predicts one of the following classes:

* Glioma Tumor
* Meningioma Tumor
* Pituitary Tumor
* No Tumor

## 🛠 Technologies Used

* Python
* TensorFlow / Keras
* NumPy
* Matplotlib
* Scikit-learn
* Gradio (for frontend interface)

## ⚙ Model Architecture

The model uses a Convolutional Neural Network (CNN) consisting of:

* Multiple Conv2D layers for feature extraction
* MaxPooling layers for dimensionality reduction
* Dense layers for classification
* Dropout layer to reduce overfitting
* Softmax activation for multi-class classification

## 📊 Model Evaluation

Model performance was evaluated using:

* Accuracy
* Confusion Matrix
* Classification Report
* Validation Loss and Accuracy

## 💻 User Interface

A simple and interactive web interface is built using Gradio where users can:

1. Upload an MRI image
2. Click the predict button
3. View the predicted tumor type and confidence score

## 📷 Example Output

Prediction: Pituitary Tumor
Confidence: 97.66%

## 🚀 Future Improvements

* Use larger datasets for better generalization
* Apply transfer learning models like ResNet or VGG
* Deploy the application using cloud platforms

## 📌 Conclusion

This project demonstrates how deep learning and medical imaging can be combined to build intelligent healthcare tools for tumor detection and classification.
