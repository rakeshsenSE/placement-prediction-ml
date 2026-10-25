<div align="center">

  # 🎓 Student Placement Prediction System

  **A Machine Learning project that predicts student placement status based on CGPA and IQ.**

  [![Python](https://img.shields.io/badge/Python-3.11+-blue.svg?style=for-the-badge&logo=python&logoColor=white)](https://www.python.org/)
  [![Scikit-Learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)
  [![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)](https://pandas.pydata.org/)
  [![Jupyter](https://img.shields.io/badge/Jupyter-Lab-orange.svg?style=for-the-badge&logo=jupyter)](https://jupyter.org/)

</div>

---

## 📌 Overview

This repository contains my **first Machine Learning project**, built following the **CampusX (100 Days of ML)** curriculum. 

The goal of this project is to build an end-to-end classification pipeline that takes a student's **CGPA** and **IQ** as inputs and predicts whether they will land a job placement (`1` = Placed, `0` = Not Placed).

---

## 🛠️ Tech Stack & Tools

| Category | Tools / Libraries Used |
| :--- | :--- |
| **Language** | Python 3.11+ |
| **Data Processing** | Pandas, NumPy |
| **Visualization** | Matplotlib, Seaborn |
| **Machine Learning** | Scikit-Learn (`LogisticRegression`, `StandardScaler`) |
| **Model Serialization** | Pickle |
| **Environment** | VS Code & Jupyter Notebook |

---

## 🔄 Machine Learning Pipeline

```mermaid
flowchart LR
    A[Raw Data] --> B[Data Cleaning & EDA]
    B --> C[Train-Test Split]
    C --> D[StandardScaler Scaling]
    D --> E[Logistic Regression Model]
    E --> F[Model Evaluation]
    F --> G[Export model.pkl]
