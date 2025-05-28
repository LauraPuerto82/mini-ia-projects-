# 🧥 Mini-Project: Image Classification with CNNs

This project is part of my AI & Machine Learning specialization roadmap. It focuses on developing and evaluating a Convolutional Neural Network (CNN) to classify grayscale fashion images from the Fashion MNIST dataset.

## 🧪 Objective
To train a CNN model from scratch to accurately classify clothing items into 10 predefined categories using Fashion MNIST.

## 🧱 Model Architecture
- Input: 28×28 grayscale images
- 2× Convolutional layers (ReLU activation)
- 2× MaxPooling layers
- 1× Flatten layer
- 2× Dense layers
- Output layer with Softmax activation

## 📌 Key Tasks
- Data preprocessing and normalization
- CNN model design using Keras & TensorFlow
- Training and evaluation with validation set
- Visualization of performance metrics and prediction examples

## 🧠 Tools Used
- Python, NumPy, Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

## 📁 Files
- `image_classification_cnn.ipynb` – Full training pipeline, evaluation, and visualizations

## 📊 Results
- Final test accuracy: **88.84 %**
- Training accuracy: 92.19 %
- Validation accuracy: 89.03 %

## 🔍 Insights
- Most confusion occurred between similar categories such as *shirt* and *top*
- The model generalizes well with no major overfitting
- Architecture remains simple and effective for Fashion MNIST

## 🚀 Next Steps
- Add dropout layers to reduce overfitting
- Experiment with more filters or deeper CNNs
- Try data augmentation or transfer learning on more complex datasets
