# Data Mining — Predicción de Calidad del Vino (KDD)

> **Autor:** Pablo Sáez Gil

---

## ¿Qué problema resuelve?

Predecir la calidad del vino (escala 0-10) a partir de propiedades físico-químicas, aplicando el proceso completo **KDD** (Knowledge Discovery in Databases) sobre el dataset Wine Quality de la UCI (6.497 registros de vinos tintos y blancos combinados).

## Proceso KDD aplicado

1. **Selección** — carga y comprensión del dataset (variables, tipos, distribuciones)
2. **Preprocesado** — limpieza, detección y tratamiento de outliers con IQR
3. **Transformación** — encoding, escalado, reducción de dimensionalidad con PCA
4. **Minería de datos** — entrenamiento y comparación de modelos
5. **Evaluación** — métricas, curvas ROC/Precision-Recall, interpretación

## Modelos aplicados

`Random Forest` · `Logistic Regression` · `Decision Tree` · `KNN` · `SVM`

## Stack

`Python` · `pandas` · `numpy` · `scikit-learn` · `matplotlib` · `seaborn`

## Estructura

```
data-mining-kdd-portfolio/
├── notebooks/
│   └── wine_quality_kdd.ipynb
├── data/
│   └── bank-full.csv
└── README.md
```

## Cómo reproducir

```bash
git clone https://github.com/pablosaezmath/data-mining-kdd-portfolio.git
cd data-mining-kdd-portfolio
pip install pandas numpy scikit-learn matplotlib seaborn jupyter
jupyter notebook notebooks/wine_quality_kdd.ipynb
```

## Autor

**Pablo Sáez Gil** — Graduado en Matemáticas · Máster en Big Data y Ciencia de Datos (VIU) · saeznovelda@gmail.com
