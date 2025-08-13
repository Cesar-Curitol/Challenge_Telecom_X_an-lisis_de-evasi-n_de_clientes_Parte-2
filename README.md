# 📡 Telecom X — Predicción de Cancelación (Churn)

## 📖 Descripción del Proyecto
Este proyecto corresponde a la **Parte 2** del desafío **Telecom X**, cuyo objetivo es desarrollar modelos predictivos para identificar clientes con alta probabilidad de cancelar sus servicios (*Churn*).  
El trabajo parte desde un **dataset limpio** generado en la Parte 1 y avanza hacia la construcción, evaluación e interpretación de modelos de Machine Learning.

---

## 🎯 Objetivos
- Preprocesar y preparar los datos para modelado.
- Aplicar técnicas de **codificación, normalización** y **balanceo de clases** (si es necesario).
- Entrenar **al menos dos modelos** de clasificación.
- Evaluar el rendimiento con métricas relevantes.
- Analizar la **importancia de las variables** en la predicción.
- Proponer **estrategias de retención** basadas en los hallazgos.

---

## 🛠️ Tecnologías Utilizadas
- **Python 3.x**
- **Pandas**, **NumPy**, **Matplotlib**, **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook / Google Colab**

---

## 📊 Modelos Probados
1. **Regresión Logística** (con estandarización)
2. **Random Forest** (sin estandarización)

---

## 🔍 Hallazgos Clave
- **Contrato “Month-to-month”**: principal driver de cancelación; contratos **One/Two year** protegen contra churn.
- **Tenure corto**: mayor probabilidad de cancelar.
- **Cargo mensual alto + cargo total bajo**: clientes recientes con alto riesgo si no perciben valor rápidamente.
- **Falta de servicios de soporte/seguridad**: (TechSupport/OnlineSecurity) asociada a mayor churn.

---

## 🚀 Recomendaciones Accionables
- **Migración de contrato**: campañas para pasar clientes *month-to-month* a *One/Two year* con incentivos.
- **Onboarding (0–6 meses)**
