# Proyección Financiera con Series Temporales

## Descripción
Este proyecto desarrolla un modelo de proyección financiera utilizando técnicas de series temporales y modelamiento contable. Se toma como referencia a OppFi Inc., a partir de información financiera histórica obtenida de **Yahoo Finance** y **Macrotrends**, con el objetivo de analizar tendencias y construir escenarios de proyección de ventas, estado de resultados y balance general.

---

## Enfoque del proyecto
El trabajo se centra en:
- Análisis de tendencias macro de ventas.
- Entrenamiento de modelos de series temporales.
- Construcción de proyecciones financieras consistentes.

---

## Metodología

### Ventas
- Conversión de datos trimestrales a frecuencia mensual.
- Interpolación lineal.
- Normalización Min-Max.
- Modelo LSTM con ventana de 6 meses.
- Proyección hasta 2030.

### Estado de resultados
- Estimación de ingresos mediante Prophet.
- Cálculo de ratios financieros históricos.
- Proyección de cuentas operativas y financieras.

### Balance general
- Proyección basada en drivers vinculados a ventas.
- Aplicación de ratios históricos.
- Cierre contable mediante identidad Activo = Pasivo + Patrimonio.
---

## Modelos y técnicas
- LSTM (TensorFlow / Keras)
- Prophet.
- Modelamiento financiero por ratios.
- Validación mediante métricas de error.

---

## Métricas
- MAE.
- RMSE.
- MAPE.
- R².

---

## Datos
Los datos utilizados provienen de estados financieros públicos obtenidos de:
- Yahoo Finance.
- Macrotrends.

Archivos de apoyo y hojas de cálculo utilizadas en el análisis:
https://docs.google.com/spreadsheets/d/1NzObQ1YSy3iLTcgUsPirLmNwAzKmcbeb6mEXAezkzgo/edit?usp=sharing

---

## Tecnologías
Python, Pandas, NumPy, Matplotlib, TensorFlow, Prophet, Scikit-learn
