# 🐍 INTRODUCCIÓN A SCILIT-LEARN: REGRESIÓN, CLASIFICACIÓN Y CLUSTERING

[![Python](https://img.shields.io/badge/Python-3670A0?style=flat&logo=python&logoColor=ffdd54)](https://www.python.org/)  
[![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)](https://scikit-learn.org/)  
[![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)](https://pandas.pydata.org/)  
[![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)](https://numpy.org/)

Este proyecto es una introducción práctica al uso de la biblioteca **Scikit-learn (SKLEARN)**, la principal herramienta de Python para la **construcción y ejecución de Modelos de Machine Learning**.

El objetivo es demostrar cómo se utiliza la librería para cargar datos de prueba, prepararlos y utilizarlos en la creación de los tres tipos fundamentales de modelos: Regresión, Clasificación y Clustering (inferido por la práctica estándar de la librería).

---

## 🧠 Contenido del Proyecto

### 1️⃣ Exploración de la Biblioteca SKLEARN
- **Definición:** SKLEARN es una biblioteca de Python diseñada para **ejecutar o construir Modelos de Machine Learning**.
- **Uso Integrado:** La librería está integrada con el ecosistema de paquetes científicos de Python, incluyendo `NumPy`, `SciPy` y `Matplotlib`.
- **Funcionalidad:** Ofrece soluciones simples y eficientes para problemas de aprendizaje automático, siendo una herramienta versátil para la ciencia y la ingeniería.

### 2️⃣ Carga y Preparación de Datos de Prueba
- **Datasets Integrados:** SKLEARN ofrece **bases de datos internas** con las que se puede trabajar para fines de aprendizaje y prueba.
- **Ejemplo Práctico:** Se importa el módulo `datasets`.
- **Carga del Dataset Diabetes:** Se utiliza la función `datasets.load_diabetes()` para cargar el dataset de diabetes como un ejemplo de datos internos.
- **Estructuración de Datos:** El dataset, que inicialmente se encuentra en formato de diccionario, se transforma en un **DataFrame de Pandas** para facilitar la visualización y el manejo de los datos.

### 3️⃣ Modelado (Inferido de las Capacidades de SKLEARN)
- Aunque el *notebook* se centra en la importación y la exploración de datos, la estructura de la librería está diseñada para implementar:
    * **Regresión:** Para predecir valores continuos (`linear_model` package).
    * **Clasificación:** Para predecir categorías discretas (paquetes como `svm` o `tree`).
    * **Clustering:** Para agrupar datos sin etiquetas (`cluster` package).

---

## 🛠️ Librerías Utilizadas

| Librería       | Uso principal                               |
|----------------|---------------------------------------------|
| **Scikit-learn (SKLEARN)** | Biblioteca fundamental para construir modelos de Machine Learning y acceder a *datasets* de prueba|
| **Pandas**     | Creación y manipulación del DataFrame del dataset de Diabetes|
| **NumPy**      | Manipulación de *arrays* y estructuras de datos internas de SKLEARN (integración clave)|

---

## 🎯 Objetivo del Proyecto
Familiarizar al usuario con la **arquitectura y las funcionalidades básicas de Scikit-learn**, demostrando cómo importar la biblioteca, acceder a sus *datasets* internos (como el de Diabetes), y preparar la información para el desarrollo de cualquier modelo de Machine Learning (Regresión, Clasificación o Clustering).

---

## 📈 Resultados Clave
- Se demuestra la importación exitosa de la librería `sklearn` y sus paquetes internos como `datasets`.
- Se accede y se visualiza la estructura del **Dataset de Diabetes**, confirmando su formato de *array* que es compatible con el modelado de SKLEARN.
- Se realiza la conversión del *array* de datos a un **DataFrame de Pandas** para un manejo más intuitivo de los datos tabulares.

