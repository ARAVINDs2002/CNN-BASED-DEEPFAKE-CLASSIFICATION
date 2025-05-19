# CNN-BASED-DEEPFAKE-CLASSIFICATION
A CNN-based model for classifying images as real or deepfake. It uses extracted video frames to train a neural network that detects visual inconsistencies caused by manipulation, enabling accurate and automated deepfake detection.
# CNN-Based Deepfake Classification

A deep learning project using Convolutional Neural Networks (CNNs) to classify images as real or deepfake based on extracted video frames.

## 📂 Dataset

- Structured into two classes: `real` and `fake`
- Images are extracted frames from video clips

## 🧠 Model

- CNN architecture with 3 convolutional layers
- PReLU activations and max-pooling
- Fully connected layer with sigmoid output

## ⚙️ Training Details

- Image size: 128x128
- Batch size: 32
- Loss function: L1Loss
- Optimizer: Adam
- Epochs: 10

## 📊 Evaluation

- Metrics: Accuracy, Confusion Matrix, Classification Report
- Visualization with matplotlib


