# Credit Card Fraud Detection

## Overview
This project aims to predict fraudulent credit card transactions using various machine learning models. 

## Setup
1. Install required dependencies:
    ```bash
    pip install -r requirements.txt
    ```

2. Train the model:
    ```bash
    python train.py
    ```

3. Model save:
    ```bash
    random_forest_model.pkl
    scaler.pkl
    ```

## Directory Structure
- `train.py`: Script for data processing, model training, and evaluation.
- `requirements.txt`: Dependencies for the project.
- `random_forest_model.pkl`: Trained model saved as a Pickle file.
- `scaler.pkl`: Scaler used during data processing.

## Future Work
- Explore additional data augmentation methods
- Further hyperparameter tuning
- Trying different algorithms or ensemble methods

## Conclusion
This project provides a comprehensive solution for detecting credit card fraud, demonstrating the importance of effective handling of imbalanced data and robust model evaluation.
