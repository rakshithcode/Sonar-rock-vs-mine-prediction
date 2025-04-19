# Sonar Rock vs Mine Prediction

This project implements a **Logistic Regression** model using **supervised machine learning** to classify whether an object detected by sonar is a **rock** or a **mine**.

## 📌 Project Overview

Sonar is used to detect objects under water by sending out sound waves and analyzing their reflections. The goal of this project is to predict the type of object (Rock or Mine) based on the sonar return signal data.

The dataset contains 60 features representing sonar signals and a target label (`R` for Rock and `M` for Mine).

## 🧠 Machine Learning Approach

- **Algorithm Used**: Logistic Regression
- **Type**: Supervised Learning - Binary Classification
- **Evaluation Metrics**: Accuracy Score, Confusion Matrix

## 🗂️ Dataset

- **Source**: UCI Machine Learning Repository
- **Features**: 60 numeric attributes (energy in frequency bands)
- **Target**: Binary label (`R` for rock, `M` for mine)

You can download the dataset [here](https://drive.google.com/file/d/1pQxtljlNVh0DHYg-Ye7dtpDTlFceHVfa/view).

## 🔧 Tech Stack

- Python
- NumPy
- Pandas
- scikit-learn
