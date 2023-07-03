# Comparación de modelos de predicción de datos de temperatura y humedad procedentes de sensores desplegados en un viñedo

## Descripción

Este proyecto realiza una comparación entre varios modelos de predicciones de series temporales para ver cuál devuelve los mejores resultados.

Se han realizado dos tipos de predicciones, predicciones de un paso de tiempo y predicciones de múltiples pasos de tiempo. Se ha asignado que cada paso de tiempo corresponda a una hora.

En este proyecto se ha considerado más importante las segundas predicciones y se ha hecho más énfasis en ellas, puesto que en las predicciones de una hora podemos asumir que no varía la temperatura.

Este proyecto no dispone de una aplicación web, solo de ficheros con código ejecutable.

Este proyecto se ha presentado como **Trabajo de Fin de Grado en la Universidad de Burgos en Julio de 2023.**

## Funcionamiento

- **Validacion.ipynb**: Fichero en el que se han realizado las llamadas a las APIs empleadas en el proyecto y se ha hecho el preprocesamiento de los datos obtenidos por los sensores. Fichero no funcional actualmente.
- **Graficas.ipynb**: Fichero donde se han representado gráficas de la validez de los datos de cada sensor.
- **Predicciones.ipynb**: Fichero donde se ha hecho la preparación de los datos para el entrenamiento de los modelos, se ha realizado _data windowing_ para poder hacer predicciones de series temporales y se han desarrollado y entrenado los modelos.

**Para entrenar los modelos solo hay que ejecutar el fichero _Predicciones.ipynb_ entero.**

-----

#### Autor: Junhao Zhou
#### Tutores: Alejandro Merino Gómez, Rubén Ruiz González
