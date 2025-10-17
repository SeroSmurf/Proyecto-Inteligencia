# Detección temprana de Supernovas en ALeRCE - ZTF

## Descripción

Este proyecto tiene como objetivo **detectar supernovas de manera temprana** utilizando datos provenientes del **Zwicky Transient Facility (ZTF)**, procesados a través de **ALeRCE**. El enfoque principal del proyecto es implementar un modelo de aprendizaje automático capaz de clasificar eventos astronómicos, tales como supernovas, a partir de las observaciones de ZTF.

El modelo propuesto utiliza redes neuronales profundas para entrenar y evaluar la clasificación de diferentes tipos de fenómenos astronómicos. Las predicciones y la evaluación del modelo se realizan utilizando la matriz de confusión, reportes de precisión, recall, y F1-score, además de aplicar técnicas de validación cruzada y MC-Dropout para obtener una estimación robusta de los resultados.

### Integrantes
- **Franco Serey**
- **Sebastián Reyes**

## Requisitos

Para ejecutar este proyecto asegúrate de tener las siguientes librerías:

- `torch`
- `numpy`
- `scikit-learn`
- `seaborn`
- `matplotlib`
