# Higgs Boson Event Classification Using Machine Learning

## Overview

This project investigates the application of machine learning techniques to particle-physics-inspired event classification.

A Random Forest classifier was developed to distinguish signal events from background events using a multivariate feature set.

The project demonstrates a complete machine learning workflow including:

- Data exploration
- Visualization
- Feature analysis
- Model training
- Performance evaluation
- Feature importance interpretation

---

## Objectives

- Explore event classification methodologies
- Develop a supervised machine learning model
- Evaluate classification performance
- Identify the most influential predictive variables

---

## Methodology

### Dataset

- 10,000 events
- 20 predictive features
- Binary classification labels

### Machine Learning Model

Random Forest Classifier

### Train-Test Split

- Training Set: 8,000 events
- Testing Set: 2,000 events

---

## Results

| Metric | Value |
|----------|----------|
| Accuracy | 95.9% |
| Precision | ~0.96 |
| Recall | ~0.96 |
| F1 Score | ~0.96 |

---

## Generated Figures

### Class Distribution

See:

`figures/class_distribution.png`

### Feature Distribution

See:

`figures/feature0_distribution.png`

### Confusion Matrix

See:

`figures/confusion_matrix.png`

### Feature Importance

See:

`figures/feature_importance.png`

---

## Project Structure

```text
CERN_Event_Classification
│
├── data
├── figures
├── notebooks
├── report
├── src
└── README.md
```

---

## Technologies Used

- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-Learn
- Jupyter Notebook

---
## Key Results

- Accuracy: 95.9%
- Precision: ~0.96
- Recall: ~0.96
- F1 Score: ~0.96

## Repository Contents

- Research notebook
- Data exploration notebook
- Project report
- Generated figures
- Machine learning workflow

## Author

Wasifa Jahan Chaudhry

## Full Project Report

The complete project report is available here:

[Project Report PDF](report/project_report.pdf)