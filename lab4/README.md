# Experiment 4 – Comparative Study of Deep CNN Architectures Using Transfer Learning

## Overview
This experiment implements transfer learning on the CIFAR-10 dataset using a pretrained MobileNetV2 model. It covers loading and preprocessing the dataset, building a transfer learning model, training with a frozen base, fine-tuning the last few layers, and evaluating performance using standard classification metrics.

## Dataset
- **Dataset:** CIFAR-10
- **Classes:** airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck
- **Image size:** 32×32×3 (resized to 96×96 for the pretrained model)

## Model
- **Base model:** MobileNetV2 (pretrained on ImageNet)
- **Added layers:** Global Average Pooling → Dense (ReLU) → Dense (Softmax, 10 classes)
- **Training stages:**
  1. Frozen base — only the new top layers are trained
  2. Fine-tuning — last block of the base model is unfrozen and trained with a lower learning rate

## How to Run
1. Open the notebook in Google Colab or Jupyter.
2. Set the runtime to GPU (Colab: Runtime → Change runtime type → GPU).
3. Run all cells in order — dataset loading, model building, training, fine-tuning, and evaluation.
4. Plots and metrics will be generated automatically in the notebook.

## Files
- `Experiment_4.ipynb` — main notebook with all code cells
- `README.md` — this file

## Results
Performance metrics (accuracy, precision, recall, F1-score) and comparison tables are recorded in the lab report after running the notebook.

## Requirements
- Python 3.x
- TensorFlow / Keras
- NumPy, Matplotlib, Seaborn
- scikit-learn

## Author
Saraswathi Nalamothu
B.Tech AI & Data Science, Shiv Nadar University Chennai
