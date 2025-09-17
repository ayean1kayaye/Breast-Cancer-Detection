# Breast-Cancer-Detection
Breast Cancer Detection – Performance Optimization &amp; Comparative Analysis in Resource-Constrained Environments


Objectives

Optimize CNN models (baseline CNN, pruned CNN, transfer learning with MobileNet/EfficientNet).
Compare CNN vs ML (Logistic Regression, Random Forest, SVM) across multiple datasets.
Study impact of dataset size, augmentation, and preprocessing on performance.
Evaluate resource usage (training time, memory, compute) under constrained environments.
Discuss real-world applicability in rural/low-resource healthcare centers.

Datasets Used

Breast Histopathology Images (Kaggle)
IDC vs non-IDC image patches.
Used for CNN & transfer learning experiments.
Sklearn Breast Cancer Dataset
Tabular dataset (30 numeric features).
Used with traditional ML classifiers.
Breast Cancer Wisconsin Dataset (Kaggle – UCI)
Tabular dataset with diagnostic features.
Used for validating ML results and consistency with literature.

https://www.kaggle.com/datasets/paultimothymooney/breast-histopathology-images
made data set

https://scikit-learn.org/stable/modules/generated/sklearn.datasets.load_breast_cancer.html
numeric data. set

https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/code
Sam data set



Methodology

1. Preprocessing
Image normalization, resizing.
Data augmentation: flips, rotations, zooming.
Feature scaling for numeric datasets.
2. Models Implemented
Baseline CNN
Pruned/Simplified CNN (resource-optimized)
Transfer Learning Models: MobileNet, EfficientNet
Traditional ML Models: Logistic Regression, Random Forest, SVM
3. Resource-Constrained Setup
Experiments conducted on Google Colab (limited GPU/RAM).
Comparative measurement of:
Accuracy
Training time
Memory footprint


Results (Ongoing Comparative Analysis)

CNN (image-based) → Higher accuracy but more resource-intensive.
Lightweight CNNs (pruned/transfer learning) → Balanced accuracy + reduced compute cost.
ML (numeric datasets) → Very fast, low-resource, but limited accuracy compared to CNN on image data.


Real-World Impact

This project demonstrates how breast cancer detection models can be adapted for real-world feasibility, especially in low-resource medical setups. By combining performance optimization with comparative analysis, the project highlights practical trade-offs to make AI in healthcare more accessible.
