# 🔢 Mini-Project: Handwritten Digit Classification with CNN

This project is part of my AI & Machine Learning specialization roadmap. It focuses on training a Convolutional Neural Network (CNN) to classify grayscale images of handwritten digits from the MNIST dataset.

## 🧪 Objective
To build and evaluate a CNN capable of classifying handwritten digits (0–9) from the MNIST dataset with high accuracy.

## 🧱 Model Architecture
- Input: 28×28 grayscale images
- 2× Convolutional layers (ReLU activation)
- 2× MaxPooling layers
- 1× Flatten layer
- 2× Dense layers
- Output layer with 10 neurons and Softmax activation

## 📌 Key Tasks
- Data normalization and preprocessing
- CNN model design using TensorFlow and Keras
- Model training and evaluation
- Visualization of accuracy and loss curves
- Display of prediction results on sample images

## 🧠 Tools Used
- Python, NumPy, Matplotlib
- TensorFlow / Keras
- Jupyter Notebook

## 📁 Files
- `image_classification_cnn.ipynb` – Complete notebook with model code, evaluation, and visualizations

## 📊 Results
- Final test accuracy: **98.74 %**
- Training accuracy: **99.41 %**
- Validation accuracy: **98.49 %**

## 🔍 Insights
- Excellent performance on clean, centered digits
- Occasional confusion between similar digits (e.g., 4 vs 9, 3 vs 5)
- Simple architecture achieves high performance without overfitting

## 🚀 Next Steps
- Explore dropout or batch normalization for regularization
- Try deeper architectures or convolutional blocks
- Evaluate performance on noisy or shifted digit images
