
#  Pr谩ctica 1 de Deep Learning - Parte 1 Convolutional Neural Network 
La pr谩ctica 1 de Deep Learning - Parte 1 Convolutional Neural Network, contiene 4 Jupyter Notebooks. 

**馃摃Carpeta Pr谩ctica**

1.   _P1_1_CNN.ipynb_, contiene el prelaboratorio, la primera parte de esta pr谩ctica consiste en entender los conceptos b谩sicos (capas, regularizaci贸n, funcione de coste, optimizadores, entrenamiento y evaluaci贸n y por 煤ltimo los callbacks). Seguidamente se muestra la estructura del laboratorio en la que se utiliza una CNN con los datos de Cifar10.

Al final del documento se propone un ejercicio y un ejercicio extra. 

2. _P1_1_CNN_explicacion.ipynb_, como P1_1_CNN.ipynb es 煤nicamente una plantilla en este Jupyter tenemos el laboratorio comentado.

**馃摋Carpeta Ejercicios**

3.   _P1_1_Ej1.ipynb_, Prueba las siguientes configuraciones y realiza: 

    路 Una tabla donde apuntes: loss entrenamiento, loss de validaci贸n, loss de test, accuracy entrenamiento, accuracy de validaci贸n, accuracy de test, n煤mero de par谩metros. 
    路 Para cada capa analiza los tama帽os de entrada y de salida.
    路 Plotea y analiza las curvas de aprendizaje

Las configuraciones ser铆an las siguientes:

    路 Red b谩sica: 4 capas CNN, 1 flatten, 1 capa densa
    路 Red b谩sica + Pooling
    路 Red b谩sica cambiando el kernel size
    路 Red b谩sica cambiando el pooling
    路 Red b谩sica + dropout:
    路 Red b谩sica + batch normalization:
    路 Red b谩sica + regularizaci贸n de capa:
    路 Red b谩sica + loss = 'mae'
    路 Red cambiando el LR
    路 Red metiendo alg煤n Callback


**馃摌Carpeta Extras** 

4. _P1_1_Extra1.ipynb_, con lo que has aprendido genera un modelo para resolver el problema de la base de datos cifar100. Guarda la estructura del modelo, las curvas de aprendizaje, loss entrenamiento, loss de validaci贸n, loss de test, accuracy entrenamiento, accuracy de validaci贸n, accuracy de test, n煤mero de par谩metros.