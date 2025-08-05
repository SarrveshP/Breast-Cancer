# 🧠 Breast Cancer Classification using Decision Tree

A supervised machine learning project that classifies breast tumors as **Benign** or **Malignant** using the **Decision Tree Classifier** on the Breast Cancer Wisconsin (Diagnostic) dataset.

---

## 📌 Project Overview

Breast cancer is one of the most common and deadly diseases affecting women worldwide. Early detection and accurate classification of tumors significantly increase survival rates.

This project leverages the power of a **Decision Tree Classifier** for binary classification of breast cancer tumors. The model is trained and evaluated using industry-standard metrics and visualized for interpretability.

---

## 🎯 Objectives

- Load and preprocess the Breast Cancer dataset.
- Train a Decision Tree Classifier using the Gini index.
- Evaluate performance using:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix
  - ROC Curve & AUC
- Visualize the decision tree and feature importances.

---

## 📂 Dataset

- **Source**: [UCI ML Repository – Breast Cancer Wisconsin (Diagnostic)](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- **Attributes**: 32 columns (ID, Diagnosis, 30 features)
- **Target**: `diagnosis` (M = Malignant, B = Benign)

---

## ⚙️ Technologies & Libraries

- Python 3
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

---

## 📊 Model Training & Evaluation

- **Algorithm**: DecisionTreeClassifier (`criterion='gini'`, `max_depth=4`)
- **Train-Test Split**: 80% training, 20% testing
- **Accuracy**: **94.74%**

### 🔍 Classification Report

| Metric     | Benign | Malignant |
|------------|--------|-----------|
| Precision  | 0.96   | 0.93      |
| Recall     | 0.96   | 0.93      |
| F1-Score   | 0.96   | 0.93      |

### 🧮 Confusion Matrix

```
                  Predicted
               | Benign | Malignant
--------------|--------|----------
Actual Benign |   68   |     3
Actual Malign |   3    |    40
```

---

## 📈 Visualizations

- ✅ Decision Tree Structure
- 📌 Top 15 Feature Importances
- 📊 Confusion Matrix (Heatmap)
- 📉 ROC Curve (AUC = 0.97)

---

## 💡 Key Insights

- **Interpretability**: Decision Trees provide clear and transparent logic.
- **Balanced Metrics**: Excellent class-wise performance.
- **Non-linear Modeling**: Captures complex feature relationships.
- **Improvements**: Potential overfitting — can be mitigated using Random Forests, Gradient Boosting, or pruning.

---

## ✅ Conclusion

The Decision Tree Classifier proved highly effective for binary tumor classification with an accuracy of **94.74%**, demonstrating strong performance across all key metrics.

This interpretable model is well-suited for healthcare applications and sets a solid baseline for further enhancements using ensemble techniques and hyperparameter tuning.

---

## 📧 Author

**Sarvesh Jayant Patil**  
📫 Email: [sarrveshpatil@gmail.com](mailto:sarrveshpatil@gmail.com)  
📍 Connect on [LinkedIn](https://www.linkedin.com/in/sarrvesh-patil-/) 

---

## 📜 License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.
