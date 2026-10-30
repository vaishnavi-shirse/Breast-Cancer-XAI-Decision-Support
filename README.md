# Breast Cancer XAI Decision Support System

An interactive machine learning project that predicts breast cancer diagnosis risk (Benign vs. Malignant) using fine-needle aspiration biopsy features and provides **Explainable AI (SHAP)** breakdowns in plain, human-friendly language to assist clinical decision-making.

## 🚀 Features
- **Predictive Modeling:** Trains a robust Random Forest classifier on the Wisconsin Breast Cancer Dataset.
- **Explainable AI (SHAP):** Translates complex model calculations into visual waterfall charts showing exact feature impacts.
- **Plain-Language Summary:** Automatically converts technical risk scores into easy-to-understand explanations for patients and doctors.
- **Interactive Patient Intake:** Allows users to input custom cell measurements (radius, texture, perimeter) dynamically.

## 🛠️ Tech Stack
- **Python**
- **Scikit-Learn** (Machine Learning & Dataset)
- **SHAP** (Explainable AI / Model Interpretation)
- **Pandas / NumPy** (Data Manipulation)
- **Google Colab** (Cloud-Based Execution Environment)

## 📌 How to Run
1. Open the `.ipynb` notebook file in [Google Colab](https://colab.research.google.com/).
2. Run the all-in-one interactive cell.
3. Enter custom cell measurements when prompted to view the AI prediction, plain-language summary report, and visual SHAP waterfall plot.
