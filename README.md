# HousePricePrediction
Proyecto final del curso de simulación, donde se planea predecir el precio de venta de viviendas teniendo en cuenta las caracterısticas esenciales que elevan el valorcomercial y la aceptacion de una poblacion especıfica. (tamano de lote, zonificacion, etc).

- Para ejecutarlo solo se requieren tener en su entorno los datasets que se encuentran al inicio de este notebook.
 - Train.csv: Sirve como dataset de entrenamiento y validación.
 - Test.csv: Dataset con datos reales de prueba.

## Consideraciones y pasos realizados en el notebook
* Pre Análisis
  * Matriz de correlación
  * Descubrimientos
  * Scatter plots
* Valores Faltantes
* Valores atípicos y sesgos
* Validación - Modelos de predicción

<blockquote><p>En este punto es importante no ejecutar las instrucciones para encontrar los mejores paramétros, puesto que ya se realizó y con fines evaluativos consumiría mucho tiempo de ejecución.</p></blockquote>
  
  * Regresión lineal múltiple
  * KNN
  * Random Forest
  * SVR
    + Kernel RBF
    + Kernel Linear
  * Redes neuronales artificiales (MLP)
  
<blockquote><p>Al finalizar estos procesos, se tiene la posibilidad de realizar la predicción con el dataset test proporcionado por Kaggle.com, el cual tiene como nombre X_testReal</p></blockquote>
  
* Conclusiones de validación
* Selección de características
* Extracción de características
