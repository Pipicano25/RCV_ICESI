# RCV_ICESI

Reto de predicción del riesgo cardiovascular desarrollado en el marco de la Maestría en Inteligencia Artificial Aplicada (ICESI). Analiza datos clínicos y sociodemográficos de pacientes de la ESE Oriente (comunas 13, 14, 15 y 21 de Cali) entre 2019 y 2023 para estimar el riesgo cardiovascular mediante modelos de machine learning, siguiendo la metodología CRISP-DM.

## Objetivo

Predecir el riesgo de hospitalización por complicaciones cardiacas usando datos históricos clínicos y demográficos, con métricas de evaluación como precisión, sensibilidad, especificidad y área bajo la curva ROC.

## Tecnologías

- Python
- pandas, NumPy, Matplotlib, scikit-learn
- Jupyter Notebook

## Estructura

- `scripts/1_1_parquet_converter.ipynb` y `1_2_unify_parquet.ipynb` — conversión y unificación de los datos a formato Parquet.
- `scripts/2_1_set_column_formats.ipynb` — definición de formatos de columnas.
- `scripts/3_1_exploratory_analysis.ipynb` — análisis exploratorio de datos.
- `scripts/4_1_model.ipynb` y `4_2_model.ipynb` — construcción y evaluación del modelo predictivo.
- `context.txt` — contexto y objetivos del reto (correo del encargado del proyecto).
- `main.py` y `requirements.txt` — archivos auxiliares (actualmente vacíos).

## Uso

Ejecutar los notebooks en orden (del 1 al 4) para replicar el flujo CRISP-DM: preparación de datos, análisis exploratorio, modelado y evaluación del modelo.

## Licencia

MIT
