# MIAX11-ANN

Material preparado para las clases de Redes Neuronales del máster MIAX: Edición 11 

Autores:

* Christian Oliva Moya

* Luis Fernando Lago Fernández

<hr>

## Contenido del repositorio

* `data` incluye algunos ficheros CSV para trabajar durante la parte práctica de las clases.

* `notebooks` incluye los notebooks que estamos usando como práctica durante las clases. En particular, un notebook tendrá el siguiente nombre: `<BLOQUE>_<N>_<DESCRIPCION>.ipynb`, donde `<BLOQUE>` será el bloque del temario que tiene relación con el notebook, `<N>` es simplemente un ordinal y `<DESCRIPCION>` da nombre al notebook. Por ejemplo, el notebook `2_1_linear_regression.ipynb` es el primer notebook del bloque 2.

* `slides` incluye las diapositivas que se están viendo durante las clases.

## Temario

* **Bloque 1: Introducción a numpy: Broadcasting**
  * Notebook *1_1_intro*. Introcucción al curso. Ejercicios básicos de numpy.

* **Bloque 2: Regresión Lineal y Regresión Logística mediante descenso por gradiente**
  * Notebook *2_1_linear_regression*. Implementación manual de una regresión lineal. Comparación con `LinearRegressor` y `SGDRegressor` de Sklearn.
  * Notebook *2_2_logistic_regression*. Implementación manual de una regresión logística. Reducción de dimensionalidad con PCA.

* **Bloque 3: Redes neuronales artificiales**
  * Notebook *3_1_red_neuronal_completa*. Implementación manual de una red neuronal completa para clasificación y regresión.