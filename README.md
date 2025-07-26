# Supervised_learning
# 🧠 Handwritten Digit Classification using SVM

This project demonstrates how to classify handwritten digits using a **Support Vector Machine (SVM)** model from the `scikit-learn` library. It uses the built-in `load_digits` dataset, trains a classifier, and evaluates the model's performance.

---

## 📊 Dataset

- **Source**: `sklearn.datasets.load_digits()`
- **Description**: 8x8 pixel grayscale images of handwritten digits (0–9)
- **Samples**: 1797 total images
- **Classes**: 10 (digits 0 through 9)

---

## 🚀 What This Project Does

- Loads and visualizes digit image samples
- Splits data into training and testing sets
- Trains an SVM classifier using a **linear kernel**
- Predicts test data labels
- Evaluates performance using **accuracy** and **classification report**

---

## 🧠 Machine Learning Model

- **Algorithm**: Support Vector Machine (SVM)
- **Library**: `sklearn.svm.SVC`
- **Kernel**: `'linear'` (can be changed to `'rbf'`, `'poly'`, etc.)

---

## 🖥️ Requirements

Make sure the following libraries are installed:

```bash
pip install scikit-learn matplotlib

 How to Run
Clone or download this repository

Make sure required libraries are installed

Run the script:

bash
Copy
Edit
python main.py
You will see:

A digit image visualized with its label

Model accuracy

Classification report

