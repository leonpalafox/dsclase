

- [Introducción](#introduccion)
- [Objetivo](#objetivo)
- [Estructura del Curso:](#estrctura-del-curso)
	- [Horas de Clase](#horas-de-clase)
	- [Sitio web de la clase](#sitio-web)
	- [Horas de Oficina](#horas-de-oficina)
- [Evaluación](#evaluacion)
- [Absentismo](#absentismo)
- [Temario](#temario)
- [Slides](#slides)
- [Tareas](#tareas)
- [Libros de Texto](#libros-de-texto)
- [Material Especial requerido para la clase](#material-especial-para-clase)
- [Políticas](#politicas)


# Introduccion

En esta clase estudiaremos las diferentes técnicas de Machine Learning y sus apliaciones. Se veran tecnicas básicas y el estado del arte, asi como técnicas para evaluar cada algoritmo con diferentes sets de datos.

# Objetivo

Los estudiantes serán capaces de implementar y validar diferentes técnicas de Machine Learning en diferentes sets de datos relacionados a distintos campos. los estudiantes aprenderan la diferencia entre aprendizaje sueprvisado y no supervisado.

# Estructura del Curso

## Horas de clase

Esta clase será diario de 7:00 p.m a 10:00 p.m.

## Sitio web

Clases, tareas, temario y políticas de calificaciones se encuentran disponibles en el sitio web: https://leonpalafox.github.io/claseml/

## Horas de oficina

Estaré disponible antes de la clase en mi oficina (Ingenieria 24), o haciendo una cita al correo electornico lpalafox@up.edu.mx.

# Evaluacion

La evaluación consistirá en:

- El proyecto final será el 60% de la evaluación final.
    - El proyecto final consistira en el uso de un técnica de Machine Learning en un set de datos de su preferencia, con su correspondiente diseño y evaluación.
	- Pueden hacer equipos de hasta tres personas.
	- Necesitan hacer un reporte de 3-5 paginas sobre el set de datos, el diseño y las variables usadas.

- El restante 40% será distribuido de la siguiente forma:
	- Dos examenes. 
	- Dos tareas.
  - Participación en clase


# Absentismo
Es obligatorio atender a todas las sesiones.

En caso de alguna situación extraordinaria se deberá platicarlo con el profesor.

# Temario

1.	[Introducción](http://nbviewer.jupyter.org/github/leonpalafox/MLClass/blob/master/Chapter1Introduction/Introduction.ipynb?flush_cache=true) (Dia 1)
    1. Qué es Machine Learning?
    2. Aplicaciones Modernas de Machine Learning.
    3. [Python-Pandas Introduction.](http://nbviewer.jupyter.org/github/leonpalafox/MLClass/blob/master/Chapter1Introduction/Introduction_PythonPandas.ipynb?flush_cache=true)
2.	Bases teóricas (Dia 2)
    1. [Álgebra de Matrices](http://nbviewer.jupyter.org/github/leonpalafox/MLClass/blob/master/Chapter2Fundamentals/MatrixAlgebra.ipynb)
    2. [Distribuciones probabilísticas](http://nbviewer.jupyter.org/github/leonpalafox/MLClass/blob/master/Chapter2Fundamentals/Probability%20Distributions.ipynb)
3.	Aprendizaje supervisado. (Dia 3,4)
    1. [Regresiones](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter3Regression/Regression.ipynb)
        1. [Ejemplo 2](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter3Regression/Regression2.ipynb)
        2. [Ejemplo 3](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter3Regression/House Prices Analysis.ipynb)    2. Clasificadores
        1. [Maquinas de Soporte Vectorial](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter4SVMs/SVMNotebook.ipynb)
        2. Redes Neuronales Artificiales
        3. [Deep Learning]
        4. Convolutional Neural Networks
		          1. [Clasificador usando Tensorflow]
		          2. [CNN usando Tensorflow]
4. Métodos de Validación (Dia 5)
    1. [Validación Curzada](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter6Validation/CrossValidationRegression.ipynb)
    2. Analisis de Bias-Variance
    3. [ROC y AUC]
6. Aprendizaje no supervisado (Dia 6,7)
    1. Clustering
        1. [K-Means](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter7Clustering/EjemplodeKMeans.ipynb)
        2. Aplicaciones
    2. Técnicas de reducción de dimensionalidad
        1. [Análisis de componentes principales](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter8PCAICA/PCA Analysis.ipynb)
        2. [Análisis de componentes independientes](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter8PCAICA/ICA analysis.ipynb)
        3. [T-SNE](http://nbviewer.jupyter.org/github/leonpalafox/mlclase/blob/master/Chapter8TSNE/TSNEDemo.ipynb)
8. Examen Final y Entrega de Proyectos (Dia 8)

# Slides

- [Clase 1 - Intro, Historia](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture1.pdf)
- [Clase 2 - Fundamentos, Regresión Lineal?](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture2.pdf)
- [Clase 3/4 - Regresión Lineal, SVMs](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture3.pdf)
- [Clase 5 - Métodos de Validación](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture4.pdf)
- [Clase 6 - Aprendizaje No Supervisado](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture5.pdf)
- [Clase 7 - Aprendizaje No Supervisado/ICA](https://github.com/leonpalafox/mlclase/blob/master/Slides/UPML01_Lecture6.pdf)



# Tareas

- [Tarea 1 - Aprendizaje Supervisado](https://github.com/leonpalafox/mlclase/blob/master/tareas/HW1.pdf)

# Libros de texto

El curso no requiere de libros de texto adjuntos, sin embargo, los siguientes libros son útiles para dar seguimiento al curso:

- Bishop, Christopher M. Pattern recognition and machine learning. Springer, 2006. 
- Rogers, Simon, and Mark Girolami. A first course in machine learning. CRC Press, 2011. (http://www.dcs.gla.ac.uk/~srogers/firstcourseml/)
- James, Gareth, et al. An introduction to statistical learning. New York: Springer, 2013. (http://www-bcf.usc.edu/~gareth/ISL/)
- Petersen, Kaare Brandt, and Michael Syskind Pedersen. The matrix cookbook. Technical University of Denmark 7 (2008): 15. (https://www.math.uwaterloo.ca/~hwolkowi/matrixcookbook.pdf)

# Material especial para la clase

Se require una computadora con Python instalado.

# Politicas

Se pueden utilizar teléfonos y bipers, siempre y cuando no molestén al resto del salón.




