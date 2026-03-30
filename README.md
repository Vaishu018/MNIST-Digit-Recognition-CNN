# MNIST-Digit-Recognition-CNN
# Handwritten Digit Recognition System using CNN

A deep learning-based project that recognizes handwritten digits (0–9) using a Convolutional Neural Network (CNN) trained on the MNIST dataset.  
The project includes data preprocessing, model training, evaluation, and digit classification with high accuracy.

## 🚀 Features
- Recognizes handwritten digits from 0 to 9
- Uses the MNIST dataset for training and testing
- Implements a Convolutional Neural Network (CNN)
- Includes data preprocessing and normalization
- Evaluates model performance using accuracy and loss metrics
- Achieves approximately 90–95% classification accuracy

##  Technologies Used
- Python
- Machine Learning
- Deep Learning
- Convolutional Neural Network (CNN)
- TensorFlow / Keras
- NumPy
- Matplotlib
- MNIST Dataset

##  Dataset
- **Dataset Used:** MNIST Handwritten Digits Dataset
- Contains 70,000 grayscale images of handwritten digits (0–9)
- Image size: 28x28 pixels

##  Model Workflow
1. Load the MNIST dataset
2. Preprocess and normalize image data
3. Reshape input for CNN model
4. Build the CNN architecture
5. Train the model on training data
6. Evaluate model performance on test data
7. Predict handwritten digits

##  Model Performance
- **Accuracy Achieved:** 90–95%
- Demonstrates strong performance compared to basic machine learning baseline models

##  Project Structure
handwritten-digit-recognition-cnn/
│── data/
│   └── mnist_sample/
│
│── models/
│   └── digit_model.h5
│
│── notebooks/
│   └── handwritten_digit_recognition.ipynb
│
│── screenshots/
│   ├── accuracy_graph.png
│   ├── loss_graph.png
│   └── prediction_output.png
│
│── src/
│   ├── train_model.py
│   ├── predict_digit.py
│   └── preprocess.py
│
│── app.py
│── requirements.txt
│── README.md
│── .gitignore
