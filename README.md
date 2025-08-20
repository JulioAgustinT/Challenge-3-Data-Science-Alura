# Challenge-3-Data-Science-Alura

# TelecomX - Predicción de Cancelación de Clientes (Churn)

Este proyecto tiene como objetivo **predecir la cancelación de clientes (churn)** en una empresa de telecomunicaciones, utilizando técnicas de **Machine Learning**.  
Se implementa un pipeline completo: carga y limpieza de datos, análisis exploratorio, balanceo de clases, entrenamiento de modelos y evaluación comparativa.

---

## Características principales
- Preprocesamiento de datos:
  - Limpieza de valores nulos e inconsistentes.
  - Codificación de variables categóricas.
  - Balanceo de clases con **SMOTE**.
- Modelos probados:
  - **Regresión Logística**
  - **SVM (RBF)**
  - **KNN**
  - **Random Forest**
- Métricas evaluadas:
  - Accuracy, Precision, Recall, F1-score, AUC.
  - Matrices de confusión.
- Análisis de **variables más influyentes** en el churn.
- **Estrategias de retención** basadas en insights de negocio.

---

## Estructura del proyecto
📁 TelecomX_Churn_Pipeline/
 ├── data/                # Datos originales y preprocesados
 ├── notebooks/           # Notebooks Jupyter con el pipeline
 ├── results/             # Gráficos y reportes generados
 ├── README.md            # Documentación del proyecto
 └── requirements.txt     # Dependencias del entorno

---

## Requisitos
Instala las dependencias con:

```bash
pip install -r requirements.txt
```

Dependencias principales:
- Python 3.9+
- pandas, numpy
- scikit-learn
- imbalanced-learn
- matplotlib, seaborn

---

## Uso
1. Clona este repositorio:
   ```bash
   git clone https://github.com/tu_usuario/TelecomX_Churn_Pipeline.git
   cd TelecomX_Churn_Pipeline
   ```

2. Abre el notebook principal:
   ```bash
   jupyter notebook notebooks/TelecomX_Churn_Pipeline.ipynb
   ```

3. Sigue los pasos del pipeline:
   - Cargar y limpiar datos
   - Entrenar modelos
   - Evaluar métricas
   - Analizar factores de churn
   - Revisar estrategias de retención

---

## Resultados
- **Mejor modelo (según Recall/F1):** SVM (RBF).  
- **Modelo más interpretable:** Regresión Logística.  
- **Principales factores de churn:**
  - Tenure bajo.
  - Contrato mes a mes.
  - Pago electrónico.
  - Cargos mensuales altos.
- **Factores protectores:**
  - Pago automático.
  - Contratos de largo plazo.
  - Servicios de soporte (OnlineSecurity, TechSupport).

---

## Estrategias de retención sugeridas
- Incentivar contratos de mayor duración.
- Ofrecer beneficios a clientes nuevos (primeros meses críticos).
- Promocionar pagos automáticos con descuentos/recompensas.
- Fortalecer servicios de soporte y seguridad como valor agregado.

---


