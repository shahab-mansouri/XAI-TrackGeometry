# XAI for Track Geometry Predictive Maintenance  
## **Trade-Off Between Model Accuracy and Interpretability in Railway Infrastructure Management**

**Authors**: Shahab Aldin Mansouri, Rebecca Dziedzic, Riccardo Licciardello, Sepehr Abdi Goudarzi, Vito Renò, Angelo Cardellicchio, Massimiliano Nitti  

**Contact**: [shahabaldin.mansouri@uniroma1.it](mailto:shahabaldin.mansouri@uniroma1.it)

---

## 📌 Overview  
This repository contains the Python implementation accompanying our paper:

> **"Trade-Off Between Interpretability and Accuracy: How Can XAI Build Trust in Track Geometry Predictive Maintenance?"**  
*Presented at RSSRail 2025.*

This study explores the balance between accuracy and interpretability of Machine Learning models predicting railway track geometry defects. We apply Explainable AI (XAI) methods (**SHAP** and **LIME**) to enhance transparency, trust, and informed decision-making in predictive maintenance.

---

## 🛠️ Methodology & Workflow
The complete workflow is documented in the primary **Jupyter Notebook** (`XAI_TGD_LAST.ipynb`):

- **Data Preparation**
  - Loading and preprocessing
  - Feature engineering and selection
  
- **Machine Learning Models**
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
  - XGBoost
  - Support Vector Machine (SVM)
  - Neural Networks (NN)

- **Model Evaluation**
  - Accuracy, Precision, Recall, F1-Score, ROC
  - 5-fold cross-validation
  
- **Explainable AI (XAI)**
  - SHAP (global interpretability)
  - LIME (local interpretability)
  - Analysis of feature importance, redundancy, and model transparency
  
- **Visualization**
  - Results and XAI explanations (SHAP beeswarm, heatmaps, LIME plots)

---

## ⚙️ Dependencies  

This project requires **Python 3.10**. You can install all necessary packages using the following command:

```bash
pip install -r requirements.txt
```

Required packages include:
pandas

numpy

matplotlib

joblib

scikit-learn

imbalanced-learn

lime

shap

---

## 📞 Contact
Questions or collaboration inquiries:
shahabaldin.mansouri@uniroma1.it ,
rebecca.dziedzic@concordia.ca ,
riccardo.licciardello@uniroma1.it ,
vito.reno@cnr.it  

---

## 📄 Copyright
Copyright © 2025 Shahab A. Mansouri
All rights reserved.
Please contact the author for permission before reusing or distributing any part of this repository.
