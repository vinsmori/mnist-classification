# MNIST Classification Analysis

This project explores classification tasks using the MNIST dataset, a classic benchmark for handwritten digit recognition.

The main goal is to study how different classification approaches behave on image data, starting with a binary classification task and then expanding to multiclass evaluation.

## Objectives

- Load and inspect the MNIST dataset
- Visualize sample digit images
- Build a binary classifier to detect one target digit
- Evaluate the model using cross-validation
- Analyze performance beyond accuracy
- Study confusion matrix, precision, recall, and F1-score
- Explore the precision-recall tradeoff
- Plot ROC curve and compute ROC AUC
- Extend the problem to multiclass classification
- Perform basic error analysis on misclassified digits

## Dataset

MNIST contains 70,000 grayscale images of handwritten digits from 0 to 9.
Each image has 28 × 28 pixels, represented as 784 input features.

## Project Structure

```text
.
├── notebooks/
├── src/
├── data/
├── figures/
├── requirements.txt
└── README.md
