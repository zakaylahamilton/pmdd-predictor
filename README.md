# PMDD Prediction using Deep Learning

This project uses a neural network to predict whether a woman has PMDD (Premenstrual Dysphoric Disorder) based on health data. It is part of a deep learning course project focused on women's health.

## 📁 Dataset

- The dataset contains features related to mood, lifestyle, and menstrual cycle data.
- Target variable: `PMDD_Diagnosis` (binary: Yes/No)
- NOTE: The dataset is not shared publicly because it is synthetic data.

## 🧠 Model Architecture

- Input layer: number of features (after encoding)
- Dense (64 units, ReLU) + L2 regularization + Dropout
- Dense (32 units, ReLU) + L2 regularization + Dropout
- Output: 1 sigmoid unit for binary classification

## 📊 Training

- Optimizer: Adam
- Loss: Binary Crossentropy
- Metrics: Accuracy
- Regularization: L2 and Dropout
- Epochs: 30
- Validation Split: 20%

## 📈 Results

- Training and validation loss are visualized
- Final validation accuracy printed in notebook

## ▶️ Run in Google Colab

1. Open the notebook in Google Colab
2. Upload your dataset
3. Run all cells

## 🙏 Acknowledgments

- Course: Deep Learning 
