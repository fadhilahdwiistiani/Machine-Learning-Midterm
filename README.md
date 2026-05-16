# Machine-Learning-Midterm
This assignment focuses on implementing an end-to-end machine learning workflow, including data preprocessing, model development, evaluation, and result analysis to solve machine learning problems using real datasets.

# 🚀 End-to-End Machine Learning Midterm Project

<div align="center">

![Python](https://img.shields.io/badge/Python-3.x-blue?style=for-the-badge&logo=python)
![Machine Learning](https://img.shields.io/badge/Machine-Learning-orange?style=for-the-badge)
![Scikit Learn](https://img.shields.io/badge/Scikit--Learn-ML-red?style=for-the-badge&logo=scikitlearn)
![MLflow](https://img.shields.io/badge/MLflow-Experiment%20Tracking-blue?style=for-the-badge)
![Optuna](https://img.shields.io/badge/Optuna-Hyperparameter%20Tuning-green?style=for-the-badge)

### Individual Midterm Assignment — Machine Learning

**Hands-on End-to-End Machine Learning Models**

</div>

---

# 👩‍🎓 Student Information

| Information | Details |
|------------|---------|
| **Name** | Fadhilah Dwi Istiani |
| **NIM** | 1103223141 |
| **Class** | Machine Learning |

---

# 📌 Project Overview

This repository contains the implementation of an **individual midterm assignment** for the Machine Learning course.

The objective of this project is to develop **end-to-end machine learning pipelines** across multiple tasks, including:

- Fraud Detection (**Classification**)
- Customer Segmentation (**Clustering**)
- Continuous Value Prediction (**Regression**)

Each project includes the complete machine learning workflow, from preprocessing to evaluation and experiment tracking.

---

# 🎯 Main Objectives

This assignment aims to enhance practical understanding of machine learning by implementing comprehensive end-to-end projects that include:

✅ Data cleaning and preprocessing  
✅ Missing value handling  
✅ Outlier treatment  
✅ Feature engineering  
✅ Model development  
✅ Hyperparameter tuning using **Optuna**  
✅ Experiment tracking with **MLflow**  
✅ Model evaluation using appropriate metrics  
✅ Interpretation of results  

---

# 🧠 Project Tasks

## 💳 1. Transaction Dataset — Fraud Detection (Classification)

### Objective
Build an end-to-end machine learning pipeline to predict the probability of an online transaction being fraudulent.

### Dataset
**train_transaction.csv**

### Description
This dataset contains labeled online transaction records used for fraud detection.

Features include:
- Transaction amount
- Transaction time
- Product code
- Card information
- Address details
- Additional transaction-related features

Target variable:
- **isFraud**
  - `1` → Fraudulent transaction
  - `0` → Legitimate transaction

### Workflow
- Data cleaning
- Handle missing values
- Handle class imbalance
- Feature engineering
- Model training
- Hyperparameter tuning (Optuna)
- Evaluation
- Experiment tracking (MLflow)

### Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

---

## 👥 2. Clustering Dataset — Customer Segmentation

### Objective
Design and implement an end-to-end clustering pipeline to segment customers based on spending and payment behavior.

### Dataset
**clusteringmidterm.csv**

### Description
This dataset contains customer credit card usage and payment behavior.

Key features:
- BALANCE
- BALANCE_FREQUENCY
- PURCHASES
- ONEOFF_PURCHASES
- INSTALLMENTS_PURCHASES
- CASH_ADVANCE
- PURCHASES_FREQUENCY
- CASH_ADVANCE_FREQUENCY
- CREDIT_LIMIT
- PAYMENTS
- MINIMUM_PAYMENTS
- PRC_FULL_PAYMENT
- TENURE

### Workflow
- Data preprocessing
- Missing value handling
- Outlier detection
- Feature scaling
- Clustering model development
- Cluster number selection
- Cluster evaluation
- Cluster interpretation

### Algorithms
Possible clustering methods:
- K-Means
- Hierarchical Clustering
- DBSCAN

### Evaluation Metrics
- Silhouette Score
- Elbow Method
- Cluster Interpretation Analysis

---

## 📈 3. Regression Dataset — Continuous Value Prediction

### Objective
Develop an end-to-end regression pipeline to predict continuous target values.

### Dataset
**midterm-regresi-dataset.csv**

### Description
This dataset contains audio-related numerical features.

Target:
- Release year of a song

Features:
- Numeric audio signal characteristics
- Feature_1, Feature_2, Feature_3, etc.

### Workflow
- Data preprocessing
- Missing value handling
- Outlier handling
- Feature engineering
- Model training
- Hyperparameter tuning (Optuna)
- Evaluation
- MLflow tracking

### Evaluation Metrics
- Mean Absolute Error (MAE)
- Mean Squared Error (MSE)
- Root Mean Squared Error (RMSE)
- R² Score

---

# ⚙️ Tech Stack

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Optuna
- MLflow

---

# 📁 Repository Structure

```bash
📦 machine-learning-midterm
│
├── datasets/
│   ├── train_transaction.csv
│   ├── clusteringmidterm.csv
│   └── midterm-regresi-dataset.csv
│
├── notebooks/
│   ├── fraud_detection.ipynb
│   ├── customer_clustering.ipynb
│   └── regression_prediction.ipynb
└── README.md
```

---

# ▶️ How to Run

### Clone repository
```bash
git clone https://github.com/your-username/machine-learning-midterm.git
```

### Install dependencies
```bash
pip install -r requirements.txt
```

### Run Jupyter Notebook
```bash
jupyter notebook
```

### Start MLflow UI
```bash
mlflow ui
```

---

# 📊 Expected Outputs

- Cleaned datasets
- Trained machine learning models
- Hyperparameter optimization results
- MLflow experiment logs
- Evaluation metrics
- Cluster analysis
- Fraud detection performance
- Regression prediction results

---

# 📝 Submission Notes

This repository includes:

✔ Source code implementation  
✔ Jupyter notebooks with explanations  
✔ Model evaluation results  
✔ Experiment tracking logs  
✔ README documentation  

---

<div align="center">

# 🌟 Author

### Fadhilah Dwi Istiani
**1103223141 — Machine Learning**

Made with ❤️ for Midterm Assignment

</div>
