##Gesture Recognition System Using Machine Learning and Smartphone Sensors
###Overview
This repository contains the implementation details and methodologies for a gesture recognition system that leverages smartphone accelerometer data and machine learning techniques. The project explores various hand gestures and their classification using models such as Logistic Regression, Random Forest, Gradient Boosting, AdaBoost, and Support Vector Classifier (SVC).

The study demonstrates the use of rigorous data preprocessing and feature extraction methods to achieve high accuracy in gesture recognition, with a focus on human-computer interaction.

###Features
Data Collection: Utilizes the Phyphox application to collect accelerometer data for gestures.
Machine Learning Models: Implements various classifiers including Gradient Boosting, Random Forest, Logistic Regression, and SVC.
Feature Engineering: Employs techniques such as wavelet decomposition, signal processing, and statistical analysis.
Performance Evaluation: Includes hyperparameter tuning and model evaluation to achieve robust results.
Dataset
The dataset includes accelerometer readings for the following gestures:

Circular motion
Waving
"Come here"
"Go away"
Each gesture was performed under diverse conditions to enhance variability and robustness.

###Methodology
Data Preprocessing:

Filtering and trimming to remove noise.
Window segmentation for pattern isolation.
Normalization and standardization for consistent scaling.
Feature Extraction:

Time-domain and frequency-domain features.
Signal features like zero-crossing rate and spectral energy.
Wavelet-based feature extraction.
Model Training:

Applied classifiers with optimized hyperparameters.
Evaluated models using cross-validation for accuracy and robustness.
Results:

Gradient Boosting achieved the highest test accuracy of 92.8%.
Random Forest and SVC also performed competitively.
Installation and Usage
Clone this repository:

bash
Copy code
git clone https://github.com/your-username/gesture-recognition
cd gesture-recognition
Install dependencies:

bash
Copy code
pip install -r requirements.txt
Collect gesture data using the Phyphox app or use the provided dataset.

Train the models:

bash
Copy code
python train.py
Evaluate the models:

bash
Copy code
python evaluate.py
Visualize results:

bash
Copy code
python visualize.py
Future Enhancements
Integration of deep learning models such as CNNs or LSTMs for dynamic gesture recognition.
Real-time gesture recognition on mobile devices.
Addition of multimodal sensor data (e.g., gyroscope).
Expanding the gesture vocabulary for broader application scenarios.
Contributing
Contributions are welcome! Please submit a pull request or open an issue for suggestions.

Authors
Arun Veeriampalayam Soundararajan
Nidhi Saini
Girija Suresh Dahibhate
License
This project is licensed under the MIT License - see the LICENSE file for details.

References
Refer to the References section in the documentation for the complete list of sources and inspiration.


