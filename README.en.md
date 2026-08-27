# Predictive Modeling: Contextual Factors in Pedagogical Vocation

[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-scikit--learn-orange.svg)](#)

[ 🇪🇸 Versión en Español ](README.md) · [ 🇬🇧 English version ](README.en.md)

End-to-end **Data Science & Machine Learning** pipeline designed to uncover socioeconomic, academic, and institutional drivers influencing high school graduates' inclination to pursue teacher education careers in the Metropolitan Region of Santiago, Chile.

Developed within the *Postgraduate Diploma in Artificial Intelligence* at Universidad Técnica Federico Santa María (USM).

---

## 🎯 Project Overview & Objectives

Addressing the national shortage of certified teachers requires evidence-based diagnostic tools. This project builds a transparent, reproducible predictive framework:

1. **Integrated Analysis:** Harmonizing student-level and school-level public educational records.
2. **Classification Models:** Training Decision Trees and Random Forest ensembles with hyperparameter optimization.
3. **Interpretability & Policy Impact:** Extracting feature importance scores to guide targeted retention and scholarship policies.

---

## 📁 Repository Pipeline

| Notebook / File | Stage & Scope | Stack |
| :--- | :--- | :--- |
| **`InformeFinalDIPLOIAUSMEVT.ipynb`** | Executive summary and synthesized findings. | Jupyter · Matplotlib |
| **`Proyecto/01database.csv.gz`** | Compressed and curated dataset. | CSV Gzip |
| **`Proyecto/02database.ipynb`** | Data ingestion, schema validation, and integrity checks. | Pandas · NumPy |
| **`Proyecto/03analisis.ipynb`** | Exploratory Data Analysis (EDA) and correlation patterns. | Seaborn · Matplotlib |
| **`Proyecto/04preprocesamiento.ipynb`** | Imputation, categorical encoding, and feature scaling. | Scikit-learn |
| **`Proyecto/05entrenamiento.ipynb`** | Model training (Decision Tree, Random Forest). | Scikit-learn |
| **`Proyecto/06validacion.ipynb`** | Performance metrics (Precision, Recall, F1, ROC-AUC). | Scikit-learn Metrics |
| **`Proyecto/07prueba.ipynb`** | Test set inference and interpretability evaluation. | Scikit-learn |

---

## 🚀 Quickstart

```bash
git clone https://github.com/evegat/modelo-predictivo-educacion.git
cd modelo-predictivo-educacion

python -m venv .venv
source .venv/bin/activate  # On Windows: .venv\Scripts\activate
pip install -r requirements.txt
jupyter notebook
```

---

## 👤 Author

**Eduardo Vega Toledo**  
*Public Administrator · Master in Government & Public Management · Computer Engineering Student*  
Former National Head of Technology Coordination (Ministry of Education, Chile) · Lecturer at FAGOB Universidad de Chile.
