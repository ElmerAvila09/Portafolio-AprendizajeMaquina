# Portafolio: Aprendizaje Maquina (No Framework)
## Modelo: Gradiente Descendente
Se realiza un modelo para predecir la cantidad de calorias que contendra un alimento en base a la cantidad carbohidratos, lípidos, proteínas y sodio (en gramos), que contiene el mismo.

## Modelo obtenido
y = 7.001 + 4.089 * x1 + 8.0325 * x2, 3.0313 * x3 - 2.0007 * x4

### Tabla de predicciones, resultado del modelo anterior
| Real | Prediccion    |
| ---- | ------------- |
400    |   387.0|
400    |   387.0|
308    |   275.0|
141    |   134.0|
141    |   134.0|
141    |   134.0|
0      |   7.0|
630    |   626.0|
630    |   626.0|
159    |   159.0|
80     |   89.0|
250    |   236.0|
420    |   365.0|
308    |   275.0|
0      |  7.0|
422    |   397.0|
204    |   198.0|
41     |   51.0|
16     |   13.0|
206    |   186.0|
144    |   144.0|
308    |   275.0|
210    |   179.0|
33     |   43.0|

## Calidad del modelo
Error de prueba/validación: 432.0075

Error de entrenamiento: 6815.549

El modelo obtuvo buenos resultados al momento de realizar predicciones con el dataset predefinido para ello, y aunque, no es igual de bueno en el cálculo del Error con los datos de entrenamiento, se puede que modelo tiene un buen balance pues como se demuestra en la tabla anterior, se tomó una muestra cercana al 10% de los datos y todos ellos demuestran tener buenos resultados de predicción, si bien existe área de mejora, se pueden seguir cambiando los parámetros del modelo para obtener un mejor resultado.
