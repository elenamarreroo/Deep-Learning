
#  Práctica 1 de Deep Learning - Parte 1 Convolutional Neural Network 
La práctica 1 de Deep Learning - Parte 1 Convolutional Neural Network, contiene 4 Jupyter Notebooks. 

**📕Carpeta Práctica**

1.   _P1_1_CNN.ipynb_, contiene el prelaboratorio, la primera parte de esta práctica consiste en entender los conceptos básicos (capas, regularización, funcione de coste, optimizadores, entrenamiento y evaluación y por último los callbacks). Seguidamente se muestra la estructura del laboratorio en la que se utiliza una CNN con los datos de Cifar10.

Al final del documento se propone un ejercicio y un ejercicio extra. 

2. _P1_1_CNN_explicacion.ipynb_, como P1_1_CNN.ipynb es únicamente una plantilla en este Jupyter tenemos el laboratorio comentado.

**📗Carpeta Ejercicios**

3.   _P1_1_Ej1.ipynb_, Prueba las siguientes configuraciones y realiza: 

    · Una tabla donde apuntes: loss entrenamiento, loss de validación, loss de test, accuracy entrenamiento, accuracy de validación, accuracy de test, número de parámetros. 
    · Para cada capa analiza los tamaños de entrada y de salida.
    · Plotea y analiza las curvas de aprendizaje

Las configuraciones serían las siguientes:

    · Red básica: 4 capas CNN, 1 flatten, 1 capa densa
    · Red básica + Pooling
    · Red básica cambiando el kernel size
    · Red básica cambiando el pooling
    · Red básica + dropout:
    · Red básica + batch normalization:
    · Red básica + regularización de capa:
    · Red básica + loss = 'mae'
    · Red cambiando el LR
    · Red metiendo algún Callback


**📘Carpeta Extras** 

4. _P1_1_Extra1.ipynb_, con lo que has aprendido genera un modelo para resolver el problema de la base de datos cifar100. Guarda la estructura del modelo, las curvas de aprendizaje, loss entrenamiento, loss de validación, loss de test, accuracy entrenamiento, accuracy de validación, accuracy de test, número de parámetros.