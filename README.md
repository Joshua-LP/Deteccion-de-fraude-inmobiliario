# 🧠 Detección de Fraude con Autoencoder

Proyecto académico enfocado en la detección de posibles fraudes financieros utilizando un modelo **Autoencoder** aplicado al dataset público **Home Credit Default Risk** (Kaggle).

---

## 📊 Descripción
El objetivo principal del proyecto es entrenar un **autoencoder** capaz de identificar patrones anómalos en solicitudes de crédito, basándose en características socioeconómicas, demográficas y financieras.  
El modelo se entrena con datos de clientes que **no presentan incumplimientos** y detecta posibles fraudes o comportamientos atípicos en nuevas observaciones.

---

## 🚀 Flujo del Proyecto
1. **Carga y exploración de datos**  
   - Análisis inicial y cálculo de tasa de incumplimiento.
2. **Selección de variables y feature engineering**  
   - Creación de ratios financieros, variables sociales y detección de inconsistencias.
3. **Preparación de datos y escalado**  
   - Limpieza, imputación y estandarización con `RobustScaler`.
4. **Entrenamiento del modelo Autoencoder**  
   - Reconstrucción no supervisada con `Keras` y `TensorFlow`.
5. **Cálculo de umbral y detección de anomalías**  
   - Definición de un límite óptimo de error para clasificar observaciones.
6. **Visualización PCA y t-SNE**  
   - Representación de normalidad vs anomalía en espacios reducidos.
