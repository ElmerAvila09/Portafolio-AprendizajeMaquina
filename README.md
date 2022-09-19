# Portafolio: Aprendizaje Maquina (No Framework)
## Modelo: Gradiente Descendente
Se realiza un modelo para predecir la cantidad de calorias que contendra un alimento en base a la cantidad carbohidratos, lípidos, proteínas y sodio (en gramos), que contiene el mismo.

## Modelo obtenido
y = 7.0004 + 4.508 * x1 + 8.1739 * x2 + 3.1457 * x3 - 2.0041 * x4

### Tabla de predicciones, resultado del modelo anterior
| Real | Prediccion    |
| ---- | ------------- |
400    |   410.0|
400    |   410.0|
308    |   298.0|
141    |   140.0|
141    |   140.0|
141    |   140.0|
0      |   7.0|
630    |   661.0|
630    |   661.0|
159    |   170.0|
80     |   97.0|
250    |   252.0|
420    |   393.0|
308    |   289.0|
0      |  7.0|
422    |   420.0|
204    |   217.0|
41     |   55.0|
16     |   13.0|
206    |   194.0|
144    |   157.0|
308    |   289.0|
210    |   191.0|
300    |   324.0|
33     |   45.0|

## Calidad del modelo
Error de prueba/validación: 271.02167

Error de entrenamiento: 184.5438

El modelo obtuvo buenos resultados al momento de realizar predicciones con el dataset de entrenamiento, y aunque, no es igual de bueno en el cálculo del Error con los datos de prueba, se puede decir que el modelo tiene un buen balance, el sesgo y la variacion se encuntran entre medio y bajo; además como se observa en la tabla anterior, se tomó una muestra cercana al 10% de los datos y todos ellos demuestran tener buenos resultados de predicción, si bien existe área de mejora, se pueden seguir cambiando los parámetros del modelo para obtener un mejor resultado.
