# Smart Moves: Decoding Hand Gestures through Machine Learning Techniques

## Overview

This project investigates the use of smartphone sensors and machine learning models for hand gesture recognition. The primary aim is to develop a robust and accurate gesture recognition system leveraging accelerometer data collected through the Phyphox application. The project explores multiple classification models to classify various gestures like circular motions, waving, beckoning, and dismissing.

This paper and project were written and submitted as part of the module **Data Science with Machine Learning** at the **University of Nottingham**.

## Features

- **Data Collection**: Captured accelerometer data using the Phyphox app for multiple gestures across diverse scenarios.
- **Data Preprocessing**: Applied filtering, trimming, segmentation, and feature extraction techniques to enhance data quality.
- **Machine Learning Models**: Trained and evaluated models like Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier, AdaBoost Classifier, and Support Vector Classifier (SVC).
- **Feature Engineering**: Extracted statistical and signal-based features, including wavelet decompositions and spectral features.
- **Results**: Gradient Boosting Classifier achieved the highest accuracy (92.8%) among all models.

## Dataset

The dataset comprises accelerometer readings for the following gestures:
- Circular motions
- Waving
- Beckoning ("Come here")
- Dismissing ("Go away")

Collected data includes variations due to user diversity, motion style, and context (e.g., standing, walking).

## Data Collection

- Use the [Phyphox app](https://phyphox.org/) to record accelerometer data.
- Follow the preprocessing scripts for cleaning and feature extraction.

## Train Models

- Use provided scripts to train models on your dataset.
- Hyperparameter tuning and evaluation are integrated.

## Results

### Model Performance Table

| **Model**                   | **Test Accuracy** | **Training Accuracy** | **F1-Score** |
|-----------------------------|-------------------|-----------------------|--------------|
| Gradient Boosting Classifier | 92.8%            | 96.7%                | 0.93         |
| Random Forest Classifier     | 90.6%            | 92.8%                | 0.90         |
| Support Vector Classifier    | 86.0%            | 88.2%                | 0.87         |
| Logistic Regression          | 86.0%            | 87.5%                | 0.85         |
| AdaBoost Classifier          | 71.4%            | 75.6%                | 0.73         |

## Future Work

- **Advanced Feature Engineering**: Implement sophisticated time-frequency analysis methods.
- **Deep Learning Models**: Incorporate CNNs or LSTMs for capturing complex temporal dependencies.
- **Real-Time Applications**: Develop low-latency models for on-device gesture recognition.
- **Multimodal Data**: Integrate gyroscope and magnetometer data for richer insights.
- **Expanding Gesture Vocabulary**: Include additional gestures for broader applicability.

## Contributors

- **Arun Veeriampalayam Soundararajan**: MSc. Computer Science with AI  
  Email: psxav7@nottingham.ac.uk  
- **Nidhi Saini**: MSc. Data Science  
  Email: nidhi.r.saini@gmail.com  
- **Girija Suresh Dahibhate**: MSc. Data Science  
  Email: psxgd2@nottingham.ac.uk  

## References

Key references include research on gesture recognition via accelerometer data, machine learning advancements, and real-world applications of human-computer interaction.

1. Siddiqui, N., & Chan, R. H. M. "Multimodal hand gesture recognition using single IMU and acoustic measurements at wrist," PLOS ONE, 2020.
2. Zhao, S., et al. "Hand gesture recognition on a resource-limited interactive wristband," MDPI, 2021.
3. Oudah, M., et al. "Hand gesture recognition based on Computer Vision: A review of techniques," MDPI, 2020.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
