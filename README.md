#Proyecto: Predicción de abandono de clientes de banco
# 🏦 Predicción de Churn en Clientes Bancarios

Este proyecto tiene como objetivo predecir la probabilidad de abandono (`churn`) de clientes en una entidad bancaria, utilizando técnicas de Machine Learning.  

Fue desarrollado como práctica para dominar herramientas de análisis, visualización, preprocesamiento, modelado y control de versiones con Git.

---

## 📁 Estructura del proyecto

- `clientes_banco_churn.csv`: Dataset simulado
- `churn_model.ipynb`: Notebook principal con análisis y modelado
- `README.md`: Este archivo
- Carpeta del proyecto versionada con Git desde terminal

---

## 🔍 Objetivo

Identificar clientes propensos a abandonar el banco, utilizando variables como:
- Edad
- Saldo
- Ingresos
- Tipo de cuenta
- Número de productos contratados

---

## ⚙️ Proceso realizado

1. Análisis exploratorio (EDA)
2. Limpieza de datos:
   - Tratamiento de valores nulos
   - Detección y corrección de outliers
3. Codificación de variables categóricas
4. División del dataset en entrenamiento y prueba
5. Entrenamiento con:
   - Regresión logística (baseline)
   - Random Forest con `class_weight='balanced'`
   - Random Forest + **SMOTE** para mejorar detección de churn
6. Evaluación con:
   - Accuracy, precision, recall, F1-score
   - Matriz de confusión

---

## 📊 Resultados

- Accuracy: **90%**
- Recall para `churn`: **75%**
- El modelo final logra detectar clientes en riesgo con buen equilibrio entre precisión y sensibilidad.

---

## 🔧 Tecnologías usadas

- Python
- Pandas, NumPy, Seaborn, Matplotlib
- Scikit-learn
- imbalanced-learn (SMOTE)
- Git y GitHub

---

## 💬 Reflexiones

Este proyecto me permitió practicar un flujo completo de ciencia de datos, comprender la importancia del balanceo de clases y aplicar técnicas reales para problemas de negocio relacionados con retención de clientes.

---

## ✨ Autora

Julieta Rivera Zamora  