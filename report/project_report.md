# Higgs Boson Event Classification Using Machine Learning

## Author

Wasifa Jahan Chaudhry

---

## Abstract

This project investigates the application of machine learning techniques to particle-physics-inspired event classification. A Random Forest classifier was trained to distinguish signal events from background events using a multivariate feature set. Model performance was evaluated using accuracy, precision, recall, F1-score, confusion matrix analysis, and feature importance ranking.

The model achieved an accuracy of 95.9%, demonstrating strong classification performance.

---

## Introduction

Particle physics experiments generate large volumes of collision-event data that must be analyzed to identify rare signal events among extensive background processes.

Machine learning techniques provide powerful tools for event classification by exploiting relationships among multiple measured variables.

The objective of this project was to develop and evaluate a machine learning workflow for binary event classification.

---

## Dataset

The dataset contained:

* 10,000 events
* 20 predictive features
* Binary class labels

Classes represented:

* Signal events
* Background events

The dataset was approximately balanced.

---

## Methodology

The following workflow was implemented:

1. Data exploration
2. Visualization
3. Train-test splitting
4. Random Forest classification
5. Performance evaluation
6. Feature importance analysis

An 80/20 train-test split was used.

---

## Results

### Model Accuracy

95.9%

### Classification Performance

* Precision ≈ 0.96
* Recall ≈ 0.96
* F1-score ≈ 0.96

### Feature Importance

Several features contributed strongly to classification performance, demonstrating the effectiveness of multivariate approaches.

---

## Generated Outputs

* Class distribution visualization
* Feature distribution visualization
* Confusion matrix
* Feature importance ranking

---

## Conclusion

The machine learning workflow successfully classified signal and background events with high predictive accuracy.

The results demonstrate the usefulness of machine learning techniques for binary event classification problems and provide a foundation for future application to real high-energy physics datasets.

---

## Limitations

The dataset used in this study was synthetically generated for workflow development purposes.

Future work will apply the same methodology to real Higgs boson event datasets.
