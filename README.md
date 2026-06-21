# Data Drift Detection & Model Monitoring System

## Overview

This project detects feature distribution shifts between training and production datasets using statistical testing and evaluates their impact on machine learning model performance.

## Features

- KS-Test based drift detection
- Drift severity scoring
- Distribution visualization
- Random Forest performance monitoring
- Automated retraining recommendation

## Tech Stack

- Python
- Pandas
- NumPy
- SciPy
- Scikit-learn
- Matplotlib
- Seaborn
- Jupyter Notebook

## Workflow

Training Data  
↓  
Train Random Forest Model  
↓  
Production Data  
↓  
Drift Detection (KS Test)  
↓  
Performance Monitoring  
↓  
Accuracy Drop Analysis  
↓  
Retraining Recommendation

## Results

| Metric | Value |
|----------|----------|
| Drifted Features | 3 |
| Training Accuracy | 100% |
| Production Accuracy | 87.43% |
| Accuracy Drop | 12.57% |
| Recommendation | Retrain Model |

## Project Structure

```text
Data-Drift-Detection-System/
│
├── README.md
├── requirements.txt
│
├── data/
│   ├── train.csv
│   └── production.csv
│
├── reports/
│   └── drift_report.csv
│
└── notebooks/
    └── drift_detection.ipynb
```

## Key Insight

The project demonstrates how distributional drift in production data can lead to measurable degradation in machine learning model performance and provides automated recommendations for retraining.
