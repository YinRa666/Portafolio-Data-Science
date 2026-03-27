---
layout: single
title: "ENCAL: Estudio Nacional de Calidad de la Atención"
permalink: /proyectos/encal/
author_profile: true
classes: wide
---

# ENCAL: Estudio Nacional de Calidad de la Atención

### Contexto del Proyecto
El Estudio Nacional de Calidad de la Atención (ENCAL) es el instrumento estratégico de evaluación de servicios de salud más extenso del instituto. Su objetivo es la medición multidimensional de la experiencia del usuario, integrando métricas de satisfacción, percepción de calidad técnica, tiempos de espera y trato digno.

### Desafío Técnico y Alcance
Mi responsabilidad consistió en la dirección técnica de la infraestructura de datos para este estudio, transformando **16 años de mediciones aisladas** en un ecosistema de análisis longitudinal coherente.

### Contribución Técnica de Alto Nivel

* **Arquitectura de Datos y Armonización Histórica:** Ejecuté la consolidación de series temporales (2009-2025), resolviendo inconsistencias estructurales entre bases de datos masivas. Este proceso de ingeniería permitió, por primera vez, el monitoreo comparativo de indicadores críticos a largo plazo.
* **Diseño Estadístico y Muestreo:** Responsable del dimensionamiento y diseño muestral a nivel nacional. Aseguré la representatividad estadística estratificada por niveles de atención (primero, segundo y tercer nivel) y regiones geográficas, garantizando la validez de las inferencias para la toma de decisiones institucionales.
* **Optimización de Procesamiento en Big Data:** Debido a la magnitud de los registros y las restricciones de hardware, implementé soluciones de procesamiento mediante **PySpark**. Esto permitió la manipulación de grandes volúmenes de datos directamente en disco, optimizando el uso de memoria y garantizando la escalabilidad del análisis.

### Ecosistema Tecnológico y Visualización
Diseñé una plataforma analítica integral en **Power BI**, utilizando **DAX avanzado** para la creación de métricas complejas de investigación de mercados.

* **Visualización Geoespacial:** Integración de mapas de regionalización para identificar brechas de calidad por zona geográfica.
* **Análisis de Perfiles:** Dashboards dinámicos con segmentación demográfica de entrevistados y estatus operativo de unidades médicas.

---

### 📊 Visualización del Tablero Final (Power BI)

A continuación, se presentan capturas de pantalla de la herramienta de Business Intelligence diseñada para el monitoreo de la ENCAL.

#### 1. Carátula y Resumen Ejecutivo
Esta vista ofrece una visión general de los principales KPIs de satisfacción y calidad a nivel nacional.

![Carátula del Tablero ENCAL]({{ site.baseurl }}/assets/images/Caratula.png)

#### 2. Análisis de Serie Histórica (2009-2025)
Visualización longitudinal que permite identificar tendencias y evaluar el impacto de políticas públicas a lo largo del tiempo.

![Serie Histórica ENCAL]({{ site.baseurl }}/assets/images/Serie.png)

#### 3. Mapa de Regionalización
Análisis geoespacial para la detección de brechas de calidad por zona geográfica y nivel de atención.

![Mapa de Regionalización EN
