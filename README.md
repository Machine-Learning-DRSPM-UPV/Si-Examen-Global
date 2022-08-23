# Sistemas Inteligentes
## Examen Global


Realize las siguientes actividades utilizando un cuaderno (`notebook`) dentro de la carpeta `notebooks`

  1. En la carpeta `data` se encuentran los conjuntos de datos a analizar.
     1. Apertue los datos.
     2. Analice los datos visualmente para determinar la naturaleza de los datos y determine la cantidad de clases existentes.
     3. Visualize el contenido de los datos.
  2. Detemine la cantidad de clases a clasificar. Muestre explicitamente el listado de etiquetas.
  3.  Genere un clasificador binario mediante `regresión logística` con el  método "One Vs All" donde la clase positiva sea: "Dress".
      1. Determine su `accuracy` y `f1 score` del modelo.
      2. Muestre la matriz de confusión utilizando el conjunto de prueba.
      3. Visualize la gráfica de "ROC AUC" del modelo generado.
      4. Guarde el modelo en la carpeta `models`.
  4. Genere un modelo de clasificación multiclase utilizando una "Máquina de Vector Soporte"
      1. Determine su `accuracy` y `f1 score` del modelo.
      2. Visualice la matriz de confusión de todas las clases utilizando el conjunto de prueba.
      3. Guarde el modelo en la carpeta `models`.
