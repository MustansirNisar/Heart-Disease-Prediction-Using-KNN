# Heart Disease Prediction Using K-Nearest Neighbors (KNN)

A comprehensive guide and implementation for predicting heart disease using the K-Nearest Neighbors (KNN) algorithm in Python. This project covers the theory behind KNN, data preprocessing, model building, evaluation, and best practices, making it a valuable resource for both beginners and intermediate practitioners in machine learning and healthcare analytics.

---

## Table of Contents

- [Overview](#overview)
- [What is KNN?](#what-is-knn)
- [Dataset](#dataset)
- [Project Structure](#project-structure)
- [Requirements](#requirements)
- [How to Run](#how-to-run)
- [Notebook Features](#notebook-features)
- [Results](#results)
- [References](#references)

---

## Overview

Heart disease is among the leading causes of death worldwide. Early prediction can save lives by enabling timely intervention. This project demonstrates how to use the K-Nearest Neighbors (KNN) machine learning algorithm to classify whether a patient is likely to have heart disease based on various clinical features.

---

## What is KNN?

K-Nearest Neighbors (KNN) is a simple, intuitive, and widely used supervised machine learning algorithm. It can be used for both classification and regression tasks, but in this project, it is used for classification. The algorithm is also called as Lazy Learning Algorithm. The algorithm predicts the class of a new data point by looking at the majority class among its 'K' closest neighbors in the feature space.

**Key characteristics:**
- Non-parametric and instance-based
- No explicit learning phase (lazy learner)
- Sensitive to feature scaling and irrelevant features

---

## Dataset

The dataset used (`heart.csv`) contains 918 samples with the following features:

- Age
- Sex
- ChestPainType
- RestingBP
- Cholesterol
- FastingBS
- RestingECG
- MaxHR
- ExerciseAngina
- Oldpeak
- ST_Slope
- HeartDisease (target: 0 = No, 1 = Yes)

**Note:** The dataset is assumed to be available in the project directory.

---

## Project Structure

```
.
├── Untitled.ipynb       # Main Jupyter Notebook with code and explanations
├── heart.csv            # Dataset file 
├── README.md            # This file
```

---

## Requirements

- Python 3.7+
- pandas
- numpy
- scikit-learn
- matplotlib (for plotting, optional)
- Jupyter Notebook

You can install the required packages using:

```bash
pip install pandas numpy scikit-learn matplotlib
```

---

## How to Run

1. Clone this repository or download the files.
2. Open `Untitled.ipynb` in Jupyter Notebook.
3. Run all cells sequentially to:
    - Load and explore the dataset
    - Preprocess data (encoding, scaling)
    - Build and evaluate the KNN classifier
    - View results and performance metrics

---

## Notebook Features

- **Comprehensive Theory:** Introduction to AI, ML, and KNN with detailed markdown explanations and diagrams.
- **Data Exploration:** Loading, inspecting, and understanding the heart disease dataset.
- **Preprocessing:** Handling categorical variables, feature scaling, and dealing with missing values.
- **Model Building:** Training a KNN classifier using scikit-learn.
- **Evaluation:** Model performance measured using accuracy, confusion matrix, and cross-validation.
- **Best Practices:** Tips on choosing K, feature selection, and handling real-world data.

---

## Results

The notebook demonstrates the entire workflow, from theory to practical implementation, including:

- Data inspection: class distribution, missing values
- Data encoding: One-hot encoding of categorical variables
- Model training: Optimal K selection using cross-validation
- Performance metrics: Accuracy, precision, recall, F1-score (as appropriate)

**Note:** Actual results and plots can be viewed by running the notebook.

---

## References

- [K-Nearest Neighbors (Wikipedia)](https://en.wikipedia.org/wiki/K-nearest_neighbors_algorithm)
- [Scikit-learn KNeighborsClassifier Documentation](https://scikit-learn.org/stable/modules/generated/sklearn.neighbors.KNeighborsClassifier.html)
- [Machine Learning with Python – GeeksforGeeks](https://www.geeksforgeeks.org/machine-learning/)

---

## License

This project is for educational purposes only.
