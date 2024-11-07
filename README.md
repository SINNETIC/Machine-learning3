# Machine-learning3

En este documento, se encuentra la guia 3 del curso machine learning.

Se inicia con una base de datos que evalua variables predictoras de niveles de obesidad en paises de américa latina, particularmente Mexico y Perú.

Se trabaja un analisis descriptivo univariado y limpieza de atipicos
Se aislan variables cuantitativas y se analiza su matriz de correlación con pruebas de Kaiser Meyer y Olkim y pruebas de esfericidad de Bartlet. todo indica que podemos hacer PCA.

Se genera un PCA reduciendo las variables a 4, no colineales y con distribución simetrica.

Con estas variables, se proponen dos modelos de clustering, uno jerarquico y otro kmedias. En ambos casos se probaron alternativas entre 2 y 11 segmentos.

Se usa la variable cluster para hacer una regresión logística contra el nivel de obesidad. Se parte la base en entrenamiento y test y se ejecuta la regresión.

Se evidencia que kmedias en seis segmentos es un modelo pertinente, con buen indicador de silueta.

Se producen boxblot de todas las variables cuantitativas y Anovas con post hoc para definir las caracteristicas estadísticamente significativas en los segmentos

Se cierra con definición de clusters.
