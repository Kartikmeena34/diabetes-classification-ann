# Diabetes Classifier — ANN Classification

Predicts whether a patient has diabetes or not using an ANN built with PyTorch.

## Features
Pregnancies, Glucose, BloodPressure, SkinThickness,
Insulin, BMI, DiabetesPedigreeFunction, Age

## Results
| Experiment | Train | Test |
|------------|-------|------|
| Baseline (128 neurons) | 99.67% | 70.13% |
| Reduced network + Dropout | 89.58% | 71.43% |
| 200 epochs | 88.44% | 73.38% |
| Class imbalance fix | 85.50% | 75.97% |

## Key Concepts Applied
- Dropout for regularization
- Train vs Test accuracy monitoring

## Tech Stack
Python, PyTorch, Scikit-learn, Pandas