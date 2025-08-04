

---

# Breast Cancer Prediction using Machine Learning 🧬

![Python](https://img.shields.io/badge/Python-3.8+-blue.svg) ![Machine Learning](https://img.shields.io/badge/Machine%20Learning-ScikitLearn-orange) ![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📌 Overview

This project predicts whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** using the **Breast Cancer Wisconsin (Diagnostic) Dataset**. It demonstrates the **end-to-end pipeline** of data preprocessing, feature selection, model building, and evaluation.

---

## 🚀 Key Highlights

* **Data Cleaning & Preprocessing**

  * Removal of irrelevant columns
  * Encoding target variable (`M` → 1, `B` → 0)
  * Feature scaling for uniformity

* **Feature Selection**

  * Correlation analysis to identify multicollinearity
  * Dropping features with correlation > 0.92

* **Model Development**

  * Logistic Regression, Random Forest, SVM, KNN
  * Train-Test split (70-30) and scaling

* **Evaluation**

  * Accuracy, Precision, Recall, F1-score
  * Confusion Matrix visualization

---

## 🧠 Workflow

```mermaid
graph TD
A[Load Dataset] --> B[Data Preprocessing]
B --> C[Feature Encoding & Scaling]
C --> D[Correlation Analysis]
D --> E[Feature Reduction]
E --> F[Train-Test Split]
F --> G[Model Training]
G --> H[Model Evaluation]
H --> I[Prediction on New Data]
```

---

## 📊 Visualizations

### Correlation Heatmap

![Correlation Heatmap](correlation_heatmap.png)

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)

---

## 📂 Dataset

* **Source:** [Breast Cancer Wisconsin Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
* **Features:** 30 (after correlation reduction fewer)
* **Target:** `diagnosis` (Malignant = 1, Benign = 0)

---

## 🏆 Results

* Achieved **95–98% accuracy**
* Logistic Regression and Random Forest performed best
* Robust predictions with minimal false positives/negatives

---

## ⚙️ Installation

```bash
git clone https://github.com/<your-username>/breast-cancer-prediction.git
cd breast-cancer-prediction
pip install -r requirements.txt
jupyter notebook Breast_Cancer_Classification.ipynb
```

---

## 🔮 Future Scope

* Hyperparameter tuning for better accuracy
* Deployment as a Flask/Streamlit web app
* Integrate SHAP/LIME for explainability

---
Diagram 
Correlation Heatmap
<img width="1606" height="1123" alt="image" src="https://github.com/user-attachments/assets/966bd214-b269-4027-9adc-8cce2983f423" />

Confusion Matrix (Model Evaluation)
<img width="1540" height="1419" alt="confusion_matrix" src="https://github.com/user-attachments/assets/816180f7-5ef6-469f-a1c9-85e03952bf5f" />

---

## 👨‍💻 Author

**Jaawad Tashick**
*Computer Science Graduate | AI & ML Enthusiast*



---


