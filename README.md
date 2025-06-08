# predicci-n-de-precio-bursatil

Este repositorio contiene el notebook **RNN_Bolsa.ipynb**, donde se desarrolla un ejemplo sencillo de predicción del precio de una acción mediante redes neuronales recurrentes (LSTM).

El cuaderno carga un archivo CSV con las cotizaciones diarias de Google desde 2015 hasta enero de 2023. Los datos se dividen en un conjunto de entrenamiento y otro de prueba, reservando el último mes para validar el modelo.

Tras una breve exploración gráfica de la serie de precios, se prepara la información en forma de secuencias temporales para alimentar una red LSTM creada con Keras. Finalmente se entrenan los pesos, se evalúa el rendimiento en el conjunto de test y se obtiene la predicción del precio de cierre.

El objetivo es ilustrar el proceso básico para aplicar RNN a series temporales bursátiles.
