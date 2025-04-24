# 💊 Drug Prediction using Machine Learning

[![Made with Python](https://img.shields.io/badge/Python-3.8+-blue?logo=python)](https://www.python.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
[![Jupyter](https://img.shields.io/badge/Notebook-Jupyter-orange?logo=jupyter)](https://jupyter.org)

> A machine learning project to predict the most suitable drug for a patient based on their health attributes.

---

## 🧠 Project Overview

This notebook presents an end-to-end ML pipeline:
- 📥 Data loading & exploration
- 🔧 Feature encoding & preprocessing
- 📊 Model training & evaluation
- 📉 Accuracy comparison & visualization
- 🧾 Drug recommendation prediction

---

## 📂 Dataset Features

| Feature      | Description                                      |
|--------------|--------------------------------------------------|
| `Age`        | Age of the patient                               |
| `Sex`        | Gender of the patient (`M`/`F`)                  |
| `BP`         | Blood Pressure (`LOW`, `NORMAL`, `HIGH`)         |
| `Cholesterol`| Cholesterol level (`NORMAL`, `HIGH`)             |
| `Na_to_K`    | Sodium-to-potassium ratio                        |
| `Drug`       | Target class: `DrugY`, `DrugC`, `DrugX`, `DrugA`, `DrugB` |

---

## 🔍 Technologies Used

- 🐍 Python 3.8+
- 📘 Pandas, NumPy
- 🧪 Scikit-learn
- 📊 Matplotlib, Seaborn
- 📓 Jupyter Notebook

---

## 🤖 ML Models Used

| Model                  | Type            |
|------------------------|-----------------|
| Decision Tree          | Classification  |
| K-Nearest Neighbors    | Classification  |
| Support Vector Machine | Classification  |
| Logistic Regression    | Classification  |
| Naive Bayes            | Classification  |

---

## 📈 Model Evaluation

- Accuracy metrics were used to evaluate performance.
- Comparative visualization via bar plots to easily identify the best-performing model.

---
