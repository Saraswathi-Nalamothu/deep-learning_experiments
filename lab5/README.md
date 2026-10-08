# Experiment 5 – CNN Training, Regularization, Optimization, Hyperparameter Tuning, Transfer Learning and Cross-Validation

## Overview
This experiment studies how different design choices affect image classification performance using MobileNetV2 (pretrained on ImageNet) on the Oxford-IIIT Pet dataset (37 breeds, images resized to 224×224).

## What's Covered
- Weight initialization (zero, random, Xavier, He)
- Regularization (L2, Dropout, Batch Normalization)
- Optimizers (SGD, Momentum, RMSProp, Adam)
- Hyperparameter tuning (learning rate, batch size, dropout rate)
- Feature extraction vs fine-tuning
- 5-fold cross-validation
- Final model evaluation (accuracy, precision, recall, F1-score, confusion matrix)

## Results
| Metric | Value |
|---|---|
| 5-Fold CV Accuracy | 87.57 ± 1.15 % |
| Test Accuracy | 87.87 % |
| Precision | 88.91 % |
| Recall | 87.87 % |
| F1-score | 87.61 % |
| Parameters | 2,305,381 |

## How to Run
1. Open `Untitled7.ipynb` in Google Colab.
2. Set the runtime to GPU.
3. Run all cells in order.

## Requirements
- Python 3.x
- TensorFlow / Keras
- TensorFlow Datasets
- NumPy, Pandas, Matplotlib
- scikit-learn

## Author
Saraswathi Nalamothu
B.Tech AI & Data Science, Shiv Nadar University Chennai
