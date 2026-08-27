# Experiment 3 – Implementation of CNNs for Image Classification

## Overview
This experiment implements a Convolutional Neural Network (CNN) from scratch using TensorFlow/Keras to classify images from the CIFAR-10 dataset. It covers the building blocks of CNNs (convolution, pooling, activation, flattening, dense layers), the effect of hyperparameters like kernel size, stride, and padding, feature map visualization, and model evaluation.

## Dataset
- **Dataset:** CIFAR-10
- **Classes:** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- **Image size:** 32×32×3

## Model
- **Architecture:** Conv2D → ReLU → MaxPooling → Conv2D → ReLU → MaxPooling → Flatten → Dense → Softmax
- **Optimizer:** Adam
- **Loss function:** Sparse Categorical Crossentropy
- **Batch size:** 32–64
- **Epochs:** ~12–20

## What's Covered
- Loading and exploring the dataset (sample images, class distribution)
- Comparing kernel sizes (3×3, 5×5, 7×7)
- Comparing stride and padding settings
- Visualizing feature maps from the convolutional layers
- Comparing Max Pooling vs Average Pooling
- Training and evaluating the final CNN
- Accuracy, precision, recall, F1-score, confusion matrix, classification report

## How to Run
1. Open the notebook in Google Colab or Jupyter.
2. Set the runtime to GPU (Colab: Runtime → Change runtime type → GPU).
3. Run all cells in order.
4. Plots and evaluation metrics will be generated automatically in the notebook.

## Files
- `Experiment_3.ipynb` — main notebook with all code cells
- `README.md` — this file

## Results
Performance metrics (accuracy, precision, recall, F1-score) and plots are recorded in the lab report after running the notebook.

## Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn
- scikit-learn

## Author
Saraswathi Nalamothu
B.Tech AI & Data Science, Shiv Nadar University Chennai
