---
layout: single
title: "Análisis de Texto y Codificación Automatizada"
permalink: /proyectos/Abiertas/
author_profile: true
classes: wide
page_navigation: false
---

### Contexto del Proyecto
En la investigación de mercados, las respuestas abiertas son la fuente más rica de información, pero su procesamiento suele ser lento, costoso y subjetivo. Este proyecto nació de la necesidad de transformar miles de registros de texto no estructurado en indicadores accionables de Experiencia del Cliente (CX). El objetivo fue desarrollar un sistema capaz de entender y categorizar los motivos raíz de insatisfacción de manera automatizada, garantizando que la voz del cliente se escuche con rigor científico y en tiempo real.

### Desafío Técnico y Alcance
El reto principal fue superar la inconsistencia humana en la codificación manual. Para ello, diseñé un proceso que combina el descubrimiento de temas mediante inteligencia artificial con un motor de clasificación supervisada. El modelo no solo identifica palabras clave, sino que comprende el contexto semántico (sinónimos y variaciones lingüísticas), logrando una precisión superior a los métodos tradicionales. Gracias a este flujo, es posible procesar mediciones mensuales de forma instantánea, manteniendo una base de datos histórica coherente y libre de sesgos de analistas.

### Herramientas y Tecnologías
* **Lenguaje:** Python (Pandas, NumPy)
* **Procesamiento de Lenguaje Natural (NLP):** **BERTopic** para el descubrimiento de temas y **spaCy** para la limpieza y lematización de textos.
* **Modelado de Lenguaje:** **Transformers (BERT)** mediante embeddings multilingües para capturar el significado profundo de los comentarios.
* **Algoritmo de Producción:** **XGBoost**, seleccionado para la clasificación recurrente por su alta eficiencia y capacidad de manejo de clases desbalanceadas.
* **Control de Calidad:** Implementación de un **Umbral de Confianza (Confidence Threshold)** para derivar casos ambiguos a revisión humana (Human-in-the-Loop).

### Desarrollo del Modelo (Python)

El punto de partida del proyecto fue el descubrimiento de los temas subyacentes en el texto no estructurado. Para ello, desarrollé un pipeline de preprocesamiento semántico utilizando spaCy para la limpieza y lematización avanzada. Posteriormente, implementé el algoritmo BERTopic, el cual, apoyado en embeddings de Transformers (BERT), identificó automáticamente los motivos de insatisfacción emergentes, generando así un libro de códigos dinámico y libre de sesgos humanos sobre el que se basaría todo el análisis subsiguiente.

<img src="{{ site.baseurl }}/assets/images/Codigo Abiertas 1.png" alt="Preprocesamiento Semántico y Descubrimiento de Temas con BERTopic" style="width:75%; display:block; margin:auto; border-radius:10px; shadow: 5px 5px 15px rgba(0,0,0,0.15);">

Una vez establecido el marco categórico, el siguiente desafío fue garantizar que el modelo pudiera clasificar nuevas mediciones de forma consistente. Como se observa en este bloque, utilicé las etiquetas generadas por BERTopic para entrenar un clasificador XGBoost de alta eficiencia. En esta fase, me enfoqué en asegurar una división estratificada de los datos para blindar la precisión del algoritmo frente a categorías con pocos ejemplos, logrando un balance óptimo entre sensibilidad (recall) y precisión.

<img src="{{ site.baseurl }}/assets/images/Codigo Abiertas 2.png" alt="Entrenamiento y Validación del Clasificador XGBoost" style="width:75%; display:block; margin:auto; border-radius:10px; shadow: 5px 5px 15px rgba(0,0,0,0.15);">

Finalmente, el verdadero valor estratégico de la solución radica en su capacidad de producción y control de calidad para mediciones recurrentes. Este último script muestra cómo el modelo ya entrenado procesa una base de datos completamente nueva. El aspecto crítico aquí es la implementación automática de un filtro de auditoría que identifica los registros con baja certeza de clasificación (menor al 70%); estos casos son exportados de inmediato para una revisión manual, garantizando la integridad del dato final que llega a la alta dirección.

<img src="{{ site.baseurl }}/assets/images/Codigo Abiertas 3.png" alt="Flujo de Inferencia y Auditoría de Datos" style="width:75%; display:block; margin:auto; border-radius:10px; shadow: 5px 5px 15px rgba(0,0,0,0.15);">

---
[« Volver a Proyectos]({{ site.baseurl }}/proyectos/)
