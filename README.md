# Telecom X - Predicción de Cancelación de Clientes (Parte 2)

## Introducción

En esta segunda etapa del proyecto se utilizan los datos previamente limpiados para desarrollar modelos de machine learning capaces de predecir la cancelación de clientes (Churn).

El objetivo es identificar patrones asociados a la evasión de clientes y construir modelos predictivos que permitan anticipar este comportamiento.

## Dataset

Se utiliza el dataset limpio generado en la Parte 1 del proyecto, almacenado en el archivo:

telecom_data_clean.csv

Este dataset contiene únicamente las variables relevantes y los datos ya estandarizados.

## Preparación de datos

Antes de entrenar los modelos se realizaron los siguientes pasos:

- Eliminación de columnas irrelevantes
- Codificación de variables categóricas (One-Hot Encoding)
- Análisis de balance de clases
- Análisis de correlación entre variables
- Separación de datos en entrenamiento y prueba (70/30)

## Modelos utilizados

Se entrenaron dos modelos de clasificación:

- Árbol de Decisión
- Random Forest

Estos modelos permiten identificar patrones en los datos para predecir la probabilidad de cancelación de los clientes.

## Resultados

Los modelos fueron evaluados mediante métricas de clasificación como accuracy y matriz de confusión.

El modelo **Random Forest** mostró un mejor desempeño general para la predicción de churn.

## Conclusiones

El análisis permitió identificar algunos factores asociados a la cancelación de clientes:

- Los clientes con contratos mensuales presentan mayor probabilidad de cancelar el servicio.
- Los clientes con menor antigüedad tienen mayor riesgo de churn.
- Los cargos mensuales más altos muestran una mayor tasa de cancelación.

Estos hallazgos pueden ayudar a desarrollar estrategias de retención de clientes más efectivas.

## Autor

Proyecto desarrollado por **Rómulo García**.
