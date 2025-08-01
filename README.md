Proyecto Sweet Lift Taxi
El objetivo del proyecto Sweet Lift Taxi fue analizar la demanda de servicios tipo Uber durante períodos de lluvia, utilizando datos históricos de la plataforma. Para ello, se entrenaron y compararon varios modelos de aprendizaje automático con el fin de predecir el número de pedidos (num_orders) en función de distintas variables.

Se implementaron modelos como:

Random Forest con diferentes configuraciones de estimadores (n_estimators) y profundidad máxima (max_depth).

Árbol de Decisión ajustado con parámetros específicos.

Gradient Boosting Regressor con varias combinaciones de estimadores y tasas de aprendizaje (learning_rate).

Los resultados mostraron que el mejor rendimiento lo obtuvo el modelo Random Forest con 150 estimadores y profundidad máxima de 20, alcanzando un RMSE de 6.37, lo que indica alta precisión y buena capacidad de generalización. Otros modelos de Random Forest con configuraciones cercanas también fueron competitivos, mientras que el Gradient Boosting obtuvo un RMSE más alto, evidenciando menor desempeño en este caso.

Todos los modelos superaron el objetivo establecido de un RMSE menor a 48, confirmando la calidad de las predicciones.

Tecnologías utilizadas:

Python

Bibliotecas: pandas, numpy, scikit-learn

Técnicas: imputación de datos, entrenamiento y validación de modelos de regresión, ajuste de hiperparámetros.

