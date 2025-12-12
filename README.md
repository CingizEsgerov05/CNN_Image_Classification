# CNN Image Classification (CIFAR-10)

This project demonstrates a simple Convolutional Neural Network (CNN) for classifying images from the CIFAR-10 dataset.  
The goal is to show the fundamentals of deep learning and image classification using TensorFlow/Keras.

## 📌 Project Overview
- Dataset: CIFAR-10 (60,000 images, 10 classes)
- Model Type: CNN (2 convolutional layers)
- Framework: TensorFlow / Keras
- Evaluation Metric: Accuracy

## 🧠 Model Architecture
- Conv2D + ReLU
- MaxPooling
- Conv2D + ReLU
- MaxPooling
- Flatten
- Dense (64 units, ReLU)
- Dense (10 units, Softmax)

## 🚀 Results
The model achieves around **60–70% accuracy** depending on training.

## 📂 Files
- `cnn_image_classification.ipynb` — full training notebook  
- `requirements.txt` — dependencies  

## 🖼️ Example Prediction
The notebook visualizes:
- Training accuracy  
- Random image prediction  
