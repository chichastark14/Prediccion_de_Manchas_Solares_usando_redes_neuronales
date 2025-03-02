# Predicción de Manchas Solares usando Redes Neuronales

## Descripción

Este proyecto tiene como objetivo predecir la actividad solar, específicamente el número de manchas solares, utilizando redes neuronales. La predicción se basa en el análisis de datos históricos de manchas solares para ayudar a anticipar eventos solares que puedan afectar a las tecnologías modernas como las comunicaciones satelitales y las redes eléctricas.

### Enfoque

El modelo está basado en redes neuronales recurrentes (RNN) para capturar las dependencias temporales en los datos de series de tiempo. Se entrenó una **Red Neuronal LSTM (Long Short-Term Memory)** con el propósito de prever el comportamiento de las manchas solares a lo largo del tiempo.

### Objetivos

1. **Predecir el número de manchas solares** para los próximos días o meses.
2. Evaluar el rendimiento del modelo y su capacidad para realizar predicciones precisas sobre datos históricos de manchas solares.
3. Establecer una base de comparación entre diferentes arquitecturas de redes neuronales para la predicción de series temporales.

---

## Tecnologías Utilizadas

- **Python**: Lenguaje de programación principal.
- **TensorFlow/Keras**: Framework para el desarrollo de redes neuronales.
- **NumPy** y **Pandas**: Para manipulación de datos.
- **Matplotlib** y **Seaborn**: Para visualización de datos.

---

## Estructura del Repositorio

```bash
Prediccion_de_Manchas_Solares_usando_redes_neuronales/
├── data/                    # Datos de entrada (archivos CSV)
├── models/                  # Modelos entrenados y configuraciones
├── src/                     # Código fuente
│   ├── preprocessing.py     # Preprocesamiento de datos
│   ├── train.py             # Código de entrenamiento del modelo
│   ├── predict.py           # Predicciones con el modelo entrenado
├── README.md                # Este archivo
└── requirements.txt         # Librerías necesarias para ejecutar el proyecto
