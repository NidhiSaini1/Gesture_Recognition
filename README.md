# Gesture Recognition System

## 📖 Overview

This repository implements a gesture recognition system using machine learning and smartphone accelerometer data. It classifies various hand gestures, enabling intuitive human-computer interaction. The project evaluates several machine learning models and employs robust data preprocessing and feature engineering techniques to achieve high accuracy.

## ✨ Features

- **Gesture Dataset**: Includes gestures such as:
  - Circular motion
  - Waving
  - "Come here"
  - "Go away"
- **Machine Learning Models**:
  - Gradient Boosting Classifier
  - Random Forest Classifier
  - Logistic Regression
  - Support Vector Classifier (SVC)
  - AdaBoost Classifier
- **Advanced Feature Engineering**:
  - Statistical features
  - Wavelet decomposition
  - Signal processing
- **Comprehensive Evaluation**:
  - Cross-validation and hyperparameter tuning
  - Test accuracy up to 92.8%

## 📊 Results

| Model                  | Test Accuracy | Training Accuracy |
|------------------------|---------------|-------------------|
| Gradient Boosting      | 92.8%         | 96.7%            |
| Random Forest          | 90.6%         | 92.8%            |
| Logistic Regression    | ~86.0%        | ~88.0%           |
| SVC                    | ~86.0%        | ~88.0%           |
| AdaBoost Classifier    | 71.4%         | ~75.0%           |

## 🛠️ Methodology

1. **Data Collection**:
   - Recorded gestures using the [Phyphox app](https://phyphox.org).
   - Diverse scenarios for robust dataset creation (sitting, walking, standing).

2. **Data Preprocessing**:
   - Applied Butterworth low-pass filtering to reduce noise.
   - Used sliding window segmentation for meaningful data chunks.
   - Normalized and standardized data.

3. **Feature Extraction**:
   - Time-domain and frequency-domain features.
   - Wavelet-based feature decomposition for temporal insights.

4. **Model Training**:
   - Trained models with hyperparameter tuning.
   - Balanced dataset using SMOTE.

5. **Model Evaluation**:
   - Gradient Boosting Classifier achieved the highest accuracy.
   - Random Forest and SVC performed competitively.

## 🚀 Getting Started

### Prerequisites

- Python 3.7+
- Required libraries are listed in `requirements.txt`.

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/gesture-recognition
   cd gesture-recognition
