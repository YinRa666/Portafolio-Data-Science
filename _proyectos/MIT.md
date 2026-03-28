---
layout: single
title: "Hackatón MIT: Modelo de Predicción Supervisada"
permalink: /proyectos/MIT/
author_profile: true
classes: wide
---

### Contexto del Proyecto
Este proyecto, desarrollado durante la especialización del MIT, consistió en enfrentar a diversos equipos internacionales en la predicción de la satisfacción del usuario (Overall Experience). Con total libertad para elegir el stack tecnológico, hicimos varias pruebas implementando múltiples opciones de algoritmos y segmentaciones de la base de datos. También exploramos diferentes formas de tratar los valores perdidos en los datos a pronosticar.

### Desafío Técnico y Alcance
Tras un proceso riguroso de limpieza de datos, ingeniería de variables y entrenamiento con validación cruzada, el modelo destacó por su alto nivel de precisión (Accuracy) al pronosticar sobre la base de datos externa. Con este desempeño, logramos superar los benchmarks de la competencia y mantenernos en los primeros lugares del tablero (Leaderboard).

---

### Herramientas y Tecnologías
* **Lenguaje:** Python (Pandas, NumPy)
* **Modelado:** XGBoost (Extreme Gradient Boosting)
* **Procesamiento:** Scikit-Learn (Imputación por mediana, One-Hot Encoding)
* **Validación:** Stratified K-Fold & Early Stopping para evitar el sobreajuste.

---

### Desarrollo del Modelo (Python)
Aquí comparto el bloque de código final. Me enfoqué en limpiar la base de datos de manera que el modelo XGBoost pudiera aprovechar cada variable sin ruido, asegurando que las columnas entre los datos de entrenamiento y los de prueba fueran siempre consistentes.

![Pipeline de Clasificación XGBoost]({{ site.baseurl }}/assets/images/Codigo MIT.png)

---
[« Volver a Proyectos]({{ site.baseurl }}/proyectos/)
