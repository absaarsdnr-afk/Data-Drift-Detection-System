# Data Drift Detection & Model Monitoring System

## Overview
This project detects feature distribution shifts between training and production datasets and measures the impact of drift on machine learning model performance.

## Features
- KS-Test based drift detection
- Drift severity scoring
- Distribution visualization
- Random Forest model monitoring
- Automated retraining recommendation

## Tech Stack
- Python
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn

## Workflow

Training Data
→ Train Random Forest Model
→ Production Data
→ Drift Detection
→ Performance Monitoring
→ Accuracy Drop Analysis
→ Retraining Recommendation

## Results

- Drifted Features Detected: 3
- Training Accuracy: 100%
- Production Accuracy: 87.43%
- Accuracy Drop: 12.57%
- Recommendation: Retrain Model