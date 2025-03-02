# Predicción de Manchas Solares usando Redes Neuronales

## Descripción

Este proyecto tiene como objetivo predecir el número de manchas solares utilizando redes neuronales. El modelo está diseñado para predecir la actividad solar a partir de datos históricos, un factor importante para entender fenómenos como las tormentas solares que afectan las tecnologías modernas (comunicaciones satelitales, redes eléctricas, etc.).

## Enfoque

Se utilizan **Redes Neuronales Recurrentes (RNN)**, en particular **LSTM (Long Short-Term Memory)**, para abordar el problema de la predicción de series temporales. El modelo fue entrenado utilizando datos históricos sobre el número de manchas solares y ahora se puede utilizar para hacer predicciones de futuros valores.

## Objetivos

1. Predecir el número de manchas solares para los próximos días o meses.
2. Evaluar el rendimiento del modelo en la predicción de series temporales.
3. Establecer una base de comparación entre diferentes arquitecturas de redes neuronales para predicciones futuras.

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **TensorFlow/Keras**: Framework para el desarrollo de redes neuronales.
- **NumPy** y **Pandas**: Para manipulación de datos.
- **Matplotlib** y **Seaborn**: Para visualización de datos.

## Temas Involucrados

- **Astrofísica**
- **Ciencia de Datos**
- **Redes Neuronales**

## Estructura del Repositorio

```bash
Prediccion_de_Manchas_Solares_usando_redes_neuronales/
├── Link_de_descarga_de_los_modelos.txt  # Enlace para descargar los modelos entrenados
├── Manchas_Solares.ipynb               # Jupyter Notebook con el análisis y predicción
├── Manchas_Solares.pdf                 # Versión PDF del notebook
├── README.md                           # Este archivo
