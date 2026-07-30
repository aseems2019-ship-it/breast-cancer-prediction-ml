# 🩺 Predictive Analytics for Breast Cancer Diagnosis Using Machine Learning

![Python](https://img.shields.io/badge/Python-3.x-blue?logo=python)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-Machine%20Learning-orange?logo=scikitlearn)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-blue?logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-blue?logo=numpy)
![License](https://img.shields.io/badge/License-MIT-green)

## 📌 Project Overview

Breast cancer is one of the leading causes of cancer-related deaths worldwide. Early diagnosis significantly improves treatment outcomes and survival rates.

This project develops a **Machine Learning classification model** to predict whether a breast tumor is **Benign** or **Malignant** using the **Wisconsin Breast Cancer Dataset**. The project demonstrates a complete machine learning workflow, including data preprocessing, exploratory data analysis, model training, evaluation, and visualization.

---

## 🎯 Objectives

* Develop a predictive machine learning model for breast cancer diagnosis.
* Perform exploratory data analysis (EDA) to understand the dataset.
* Evaluate model performance using multiple classification metrics.
* Visualize important insights from the dataset.
* Demonstrate the application of predictive analytics in healthcare.

---

## 📊 Dataset

**Dataset:** Wisconsin Breast Cancer Dataset

**Source:** Kaggle

### Dataset Characteristics

* Total Records: **569**
* Total Features: **30**
* Target Variable: **Diagnosis**
* Classes:

  * Benign (B)
  * Malignant (M)

---

## 🛠 Technologies Used

* Python
* Google Colab / Jupyter Notebook
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn

---

## 🔄 Machine Learning Workflow

```text
Dataset
   │
   ▼
Data Preprocessing
   │
   ▼
Exploratory Data Analysis
   │
   ▼
Feature Selection
   │
   ▼
Train-Test Split (80:20)
   │
   ▼
Model Training
   │
   ▼
Prediction
   │
   ▼
Performance Evaluation
```

---

## 📈 Exploratory Data Analysis

The project includes:

* Distribution of Benign vs Malignant tumors
* Pie Chart of diagnosis distribution
* Correlation Heatmap
* Confusion Matrix
* Feature Importance Analysis

---

## 📊 Model Evaluation

The model was evaluated using:

* Accuracy
* Confusion Matrix
* Precision
* Recall
* F1-Score

### ✅ Results

| Metric   |     Value |
| -------- | --------: |
| Accuracy | **95.6%** |

The developed model successfully classified approximately **96 out of every 100 breast cancer cases**, demonstrating strong predictive performance.

---

## 📁 Repository Structure

```text
breast-cancer-prediction-ml/
│
├── data/
│   └── breast-cancer-wisconsin-data.csv
│
├── notebook/
│   └── project_cancer.ipynb
│
├── report/
│   └── Predictive_Analytics_for_Breast_Cancer_Diagnosis.pdf
│
├── images/
│
├── requirements.txt
├── README.md
└── LICENSE
```

---

## 🚀 Getting Started

### Clone the repository

```bash
git clone https://github.com/YOUR_USERNAME/breast-cancer-prediction-ml.git
```

### Install dependencies

```bash
pip install -r requirements.txt
```

### Run the notebook

```bash
jupyter notebook
```

Open:

```
project_cancer.ipynb
```

Run all cells.

---

## 📌 Future Improvements

* Compare multiple machine learning algorithms.
* Perform hyperparameter tuning.
* Deploy the model as a web application using Streamlit.
* Integrate explainable AI techniques (SHAP/LIME).
* Evaluate additional healthcare datasets.

---

## 👨‍💻 Author

**Aseem S**

M.Sc. Statistics
University of Kerala

* LinkedIn: *(linkedin.com/in/aseem-s-613781403)*
* GitHub: *(aseems2019-ship-it/breast-cancer-prediction-ml.git)*

---

## 📄 License

This project is licensed under the **MIT License**.

---

## ⭐ If you found this project useful, consider giving it a star!
