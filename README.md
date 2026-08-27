# Modelamiento Predictivo: Factores Contextuales y Vocación Pedagógica

[![Licencia](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://www.python.org/)
[![Machine Learning](https://img.shields.io/badge/Machine%20Learning-scikit--learn-orange.svg)](#)

[ 🇪🇸 Español ](README.md) · [ 🇬🇧 English version ](README.en.md)

Pipeline integral de **Ciencia de Datos y Machine Learning** para identificar las dimensiones contextuales, socioeducativas y territoriales que inciden en el interés por estudiar carreras de pedagogía en egresados de Educación Media de la Región Metropolitana (Chile).

Proyecto desarrollado en el marco del *Diplomado en Inteligencia Artificial* (Universidad Técnica Federico Santa María - USM).

---

## 🎯 Objetivo y Enfoque

El déficit proyectado de docentes en el sistema educativo chileno requiere herramientas analíticas basadas en datos para focalizar políticas de atracción temprana. Este proyecto implementa un flujo reproducible de clasificación y modelamiento predictivo para:

1. **Analizar variables socioeconómicas, académicas e institucionales** de estudiantes y establecimientos.
2. **Entrenar y comparar modelos de clasificación** basados en árboles de decisión y ensambles (*Random Forest*).
3. **Identificar factores críticos de decisión** (Feature Importance) que orienten intervenciones de política pública educativa.

---

## 📁 Estructura del Repositorio y Pipeline

El flujo de trabajo está modularizado en notebooks secuenciales y reproducibles dentro de la carpeta `Proyecto/`:

| Etapa / Archivo | Descripción | Stack / Herramientas |
| :--- | :--- | :--- |
| **`InformeFinalDIPLOIAUSMEVT.ipynb`** | Informe ejecutivo y consolidación de resultados finales. | Jupyter · Matplotlib |
| **`Proyecto/01database.csv.gz`** | Dataset procesado y comprimido con registros educativos. | CSV Gzip |
| **`Proyecto/02database.ipynb`** | Carga, estructuración y control de integridad de bases de datos. | Pandas · NumPy |
| **`Proyecto/03analisis.ipynb`** | Análisis Exploratorio de Datos (EDA), distribuciones y correlaciones. | Seaborn · Matplotlib |
| **`Proyecto/04preprocesamiento.ipynb`** | Limpieza, imputación, codificación de variables y normalización. | Scikit-learn |
| **`Proyecto/05entrenamiento.ipynb`** | Entrenamiento de modelos de clasificación y ajuste de hiperparámetros. | Decision Trees · Random Forest |
| **`Proyecto/06validacion.ipynb`** | Evaluación de métricas de desempeño (Accuracy, Precision, Recall, F1-Score, ROC-AUC). | Scikit-learn Metrics |
| **`Proyecto/07prueba.ipynb`** | Pruebas de inferencia sobre conjunto de test y análisis de interpretabilidad. | Scikit-learn |

---

## 🛠️ Stack Tecnológico

- **Lenguaje:** Python 3.10+
- **Bibliotecas:** `pandas`, `numpy`, `scipy`, `scikit-learn`, `matplotlib`, `seaborn`
- **Entorno:** Jupyter Notebooks / Google Colab

---

## 🚀 Reproducción del Proyecto

```bash
# 1. Clonar el repositorio
git clone https://github.com/evegat/modelo-predictivo-educacion.git
cd modelo-predictivo-educacion

# 2. Crear y activar entorno virtual
python -m venv .venv
source .venv/bin/activate  # En Windows: .venv\Scripts\activate

# 3. Instalar dependencias
pip install -r requirements.txt

# 4. Iniciar Jupyter Lab o Notebook
jupyter notebook
```

---

## 👤 Autor

**Eduardo Vega Toledo**  
*Administrador Público · Magíster en Gobierno y Gerencia Pública · Est. Ing. Civil Informática*  
Ex Jefe de Coordinación Nacional de Tecnologías (Ministerio de Educación de Chile) · Docente en FAGOB Universidad de Chile.
