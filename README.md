# ML Playground

Este repositorio contiene experimentos autocontenidos de *machine learning*. Cada carpeta o notebook explora un problema sencillo utilizando técnicas básicas para comprender conceptos clave.

## Objetivo

La idea es practicar modelos supervisados y no supervisados en conjuntos de datos conocidos. Comenzamos con un ejemplo de clasificación utilizando la **regresión logística**, una extensión del modelo lineal que utiliza la función logística para ajustar una ecuación lineal y "aplastar" su salida entre 0 y 1, de modo que pueda interpretarse como probabilidad【61158358276537†L183-L200】.

Además, se incluye un ejemplo de **Random Forest** para el mismo dataset de cáncer de mama. Los **Random Forests** son conjuntos de árboles de decisión que se combinan para reducir el sobreajuste y mejorar la precisión, especialmente en problemas donde las relaciones no lineales son importantes.

## Estructura

- `notebooks/` – notebooks Jupyter con ejemplos completos.
- `data/` – conjuntos de datos usados en los ejemplos (en caso de que se requiera).
- `src/` – código Python reutilizable (funciones, módulos).
- `tests/` – pruebas unitarias (opcional).

## Uso

1. Clona este repositorio y navega al directorio.
2. Crea un entorno virtual (`python -m venv .venv`) y actívalo.
3. Instala las dependencias básicas: 
   ```bash
   pip install numpy pandas scikit-learn matplotlib
   ```
4. Ejecuta el notebook `notebooks/01_logistic_regression_iris.ipynb` en Jupyter para ver el ejemplo.

5. Para un ejemplo más avanzado, ejecuta `notebooks/02_random_forest_breast_cancer.ipynb`. Este cuaderno carga el dataset de cáncer de mama, entrena un modelo Random Forest y reporta métricas de clasificación.

## Fuentes

- La definición de regresión logística y su uso para clasificación se basa en el capítulo de modelos interpretables【61158358276537†L183-L200】.

- Para el ejemplo de Random Forest se utilizó el dataset **Breast Cancer Wisconsin** proporcionado por `sklearn.datasets`.
