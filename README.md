# Crop Recommendation Using Machine Learning Model (Gaussian Naive Bayes ) with 99.55% Accuracy
This repository provides a Crop Recommendation System using the Gaussian Naive Bayes algorithm, achieving an accuracy of 99.55%. The system uses agricultural and environmental data, including soil nutrients, temperature, humidity, pH, and rainfall, to recommend the most suitable crop for farming. Key features of this project include:

- Implementation of Gaussian Naive Bayes for multi-class classification.
- Data preprocessing with label encoding and train-test splitting.
- Detailed evaluation using confusion matrix, classification report, and accuracy metrics.
- Visualization of model performance.
- Real-time predictions for crop recommendations based on input parameters.
- Model persistence using Python's pickle library for reuse.
- This project demonstrates how machine learning techniques can be applied to precision agriculture, aiding in improving crop yield and optimizing farming practices.
---

## Features

- **High Accuracy:** Implements the Gaussian Naive Bayes algorithm, achieving a 99.55% accuracy on the test dataset.
- **Preprocessing:** Encodes categorical labels and splits data into training and testing sets.
- **Model Evaluation:**
  - Generates a confusion matrix for visualizing model performance.
  - Provides a classification report with precision, recall, and F1-score.
- **Visualization Tools:** Uses Matplotlib and Seaborn for performance analysis.
- **Real-Time Prediction:** Accepts user input for environmental and soil parameters to recommend crops.
- **Model Persistence:** Saves the trained model using pickle for future use.

---

## Dataset

The dataset used for this project includes the following parameters:

- **Soil Nutrients:** Nitrogen (N), Phosphorus (P), Potassium (K)
- **Environmental Conditions:** Temperature, Humidity, pH, Rainfall
- **Label:** Crop name (target variable)

Ensure the dataset `Crop_recommendation.csv` is available in the specified path for the project.

---
