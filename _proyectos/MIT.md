---
layout: single
title: "Hackatón MIT: Modelo de Predicción Supervisada"
permalink: /proyectos/MIT/
author_profile: true
classes: wide
page_navigation: false
---

### Contexto del Proyecto
Este proyecto, desarrollado durante la especialización del MIT, consistió en enfrentar a diversos equipos internacionales en la predicción de la satisfacción del usuario (Overall Experience). Con total libertad para elegir el stack tecnológico, hicimos varias pruebas implementando múltiples opciones de algoritmos y segmentaciones de la base de datos. También exploramos diferentes formas de tratar los valores perdidos en los datos a pronosticar.

### Desafío Técnico y Alcance
Tras un proceso riguroso de limpieza de datos e ingeniería de variables, el modelo fue sometido a una evaluación a ciegas (Blind Test) utilizando un conjunto de datos externo proporcionado por el MIT, el cual carecía de etiquetas de supervisión.

A través de una sólida estrategia de validación cruzada y optimización de hiperparámetros, logramos una capacidad de generalización superior, alcanzando un Accuracy final del 95% verificado por la institución. Este desempeño nos permitió superar los benchmarks de referencia y mantenernos consistentemente en los primeros lugares del tablero de líderes (Leaderboard), validando la robustez del modelo ante datos completamente inéditos.

### Herramientas y Tecnologías
* **Lenguaje:** Python (Pandas, NumPy)
* **Modelado Comparativo:** Evaluación de múltiples algoritmos, incluyendo **Regresión Logística, Árboles de Decisión y Random Forest**.
* **Algoritmo Final:** **XGBoost** (Extreme Gradient Boosting), seleccionado por su superioridad en precisión y manejo de relaciones no lineales.
* **Procesamiento:** Scikit-Learn (Imputación por mediana, One-Hot Encoding)
* **Validación:** Stratified K-Fold & Early Stopping para prevenir el sobreajuste (*overfitting*).

### Desarrollo del Modelo (Python)
Aquí comparto el bloque de código final. Me enfoqué en limpiar la base de datos de manera que el modelo XGBoost pudiera aprovechar cada variable sin ruido, asegurando que las columnas entre los datos de entrenamiento y los de prueba fueran siempre consistentes.

<img src="{{ site.baseurl }}/assets/images/Codigo MIT.png" alt="Pipeline de Clasificación XGBoost" style="width:70%; display:block; margin:auto; border-radius:10px; shadow: 5px 5px 15px rgba(0,0,0,0.1);">

---
[« Volver a Proyectos]({{ site.baseurl }}/proyectos/)
