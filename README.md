# Extensiones de Machine Learning. Aprendizaje por refuerzo.
# Práctica 2. Aprendizaje en entornos complejos.

## Información
- **Alumnos:** López Abad, Jorge; Verdú Chacón, Jesús.
- **Asignatura:** Extensiones de Machine Learning.
- **Curso:** 2024/2025
- **Grupo:** LAVC (id. 6243486)
## Descripción
Este repositorio presenta un estudio sobre el aprendizaje por refuerzo en entornos complejos mediante la evaluación de diferentes algoritmos en dos escenarios clásicos: Frozen Lake y Mountain Car, ambos pertenecientes al framework Gymnasium. El objetivo es comparar métodos tabulares y basados en aproximación para analizar su rendimiento en la toma de decisiones secuenciales.

    Los métodos tabulares que se han utilizado han sido las versiones On-Policy y Off-Policy de Monte Carlo, SARSA y Q-Learning; mientras que los métodos de basados en aproximación usados son SARSA semi-gradiente y Deep Q-Learning.

    Los resultados muestran que los métodos tabulares son adecuados para problemas pequeños y discretos, mientras que en entornos continuos es necesario recurrir a técnicas de aproximación. Se discuten las ventajas y limitaciones de cada enfoque, así como posibles mejoras futuras en la estabilidad y eficiencia del aprendizaje.

## Estructura
En este repositorio solamente se hallan los ficheros Jupyter Notebook donde se han realizado todos los experimentos. Todas las funcionalidades requeridas para poder llevar a cabo cada uno de los experimentos se halla dentro del experimento correspondiente.

Se puede acceder a todos los ficheros desde el Jupyter Notebook _main.ipynb_

## Instalación y uso
No es necesaria realizar ninguna instalación para poder reproducir los experimentos, basta entrar en los ficheros Jupyter Notebook donde se hallan los experimentos y abrirlos en Colab. Todos los experimentos son reproducibles.

## Tecnologías Utilizadas
Hemos desarrollado el código necesario para poder llevar a cabo los experimentos en ficheros en ficheros Jupyter Notebook utilizando el lenguaje de progrmación Python.
