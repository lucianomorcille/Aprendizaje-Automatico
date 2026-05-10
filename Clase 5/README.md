En este trabajo se aplicaron técnicas de aprendizaje automático utilizando el dataset Heart Disease Dataset con el objetivo de predecir la presencia de enfermedades cardíacas a partir de distintas variables médicas. Para ello, se implementaron los algoritmos Árbol de Decisión y K-Nearest Neighbors (K-NN), permitiendo analizar y comparar el rendimiento de ambos modelos de clasificación.


Durante el desarrollo del proyecto se realizaron tareas de exploración y preparación de datos, entrenamiento de modelos y evaluación mediante métricas como accuracy, matriz de confusión, precision, recall y f1-score. Además, se generaron visualizaciones gráficas para interpretar el comportamiento de los algoritmos y comprender cómo realizan las clasificaciones. El objetivo final fue identificar cuál de los modelos ofrece mejores resultados para este problema de clasificación médica.

## Resultados Árbol de decisión

La matriz de confusión del modelo Árbol de Decisión muestra un rendimiento muy alto en la clasificación de enfermedades cardíacas. El modelo logró clasificar correctamente 159 pacientes sin enfermedad cardíaca y 140 pacientes con enfermedad cardíaca, con muy pocos errores. Además, obtuvo un accuracy cercano al 97%, junto con valores elevados de precision, recall y f1-score. Esto indica que el algoritmo fue capaz de identificar correctamente la mayoría de los casos y presentar un comportamiento muy eficiente para este problema de clasificación médica.

La visualización del Árbol de Decisión representa gráficamente las reglas utilizadas por el modelo para clasificar pacientes con y sin enfermedades cardíacas. Cada nodo muestra una condición basada en variables médicas, como edad, colesterol, frecuencia cardíaca y tipo de dolor de pecho. Además, se observa cómo el árbol divide progresivamente los datos hasta llegar a una predicción final. Los colores permiten identificar la clase predominante en cada nodo, mientras que el índice Gini muestra el nivel de pureza de las clasificaciones.

## Resultados K-NN

La matriz de confusión del modelo K-NN muestra un rendimiento aceptable, aunque inferior al Árbol de Decisión. El modelo clasificó correctamente 130 pacientes sin enfermedad y 129 pacientes con enfermedad cardíaca, pero presentó una mayor cantidad de errores de clasificación, especialmente falsos positivos y falsos negativos. El accuracy obtenido fue aproximadamente del 84%, lo que demuestra que el modelo puede identificar patrones en los datos, aunque con menor precisión general que el Árbol de Decisión.

El gráfico de accuracy según el valor de K permite analizar cómo influye la cantidad de vecinos en el rendimiento del algoritmo K-NN. Se observa que los valores pequeños de K obtienen mejores resultados, alcanzando la mayor precisión con K=1. A medida que el valor de K aumenta, el accuracy disminuye y se estabiliza en valores menores.

## Conclusión

Luego de entrenar y evaluar ambos modelos de aprendizaje automático, se observó que el algoritmo Árbol de Decisión obtuvo un mejor rendimiento general que K-NN para la clasificación de enfermedades cardíacas.

El Árbol de Decisión alcanzó un accuracy cercano al 97%, logrando clasificar correctamente la gran mayoría de los pacientes y presentando muy pocos errores en la matriz de confusión. Además, obtuvo valores muy altos de precision, recall y f1-score, lo que demuestra una excelente capacidad para identificar tanto pacientes con enfermedad cardíaca como pacientes sanos.

Por otro lado, el modelo K-NN obtuvo un accuracy aproximado del 84%. Aunque el algoritmo logró resultados aceptables, presentó una mayor cantidad de falsos positivos y falsos negativos, reduciendo su precisión general en comparación con el Árbol de Decisión.
