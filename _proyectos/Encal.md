---
layout: single
title: "ENCAL: Estudio Nacional de Calidad de la Atención"
permalink: /proyectos/encal/
author_profile: true
classes: wide
page_navigation: false
---

### Contexto del Proyecto
El Estudio Nacional de Calidad de la Atención (ENCAL) es el instrumento estratégico de evaluación de servicios de salud más extenso del instituto. Su objetivo es la medición multidimensional de la experiencia del usuario, integrando métricas de satisfacción, percepción de calidad técnica, tiempos de espera y trato digno.

### Desafío Técnico y Alcance
Mi responsabilidad consistió en la dirección técnica de la infraestructura de datos para este estudio, transformando **16 años de mediciones aisladas** en un ecosistema de análisis longitudinal coherente.

### Contribución Técnica de Alto Nivel

* **Diseño Estadístico y Muestreo:** Responsable del dimensionamiento y diseño muestral a nivel nacional. Aseguré la representatividad estadística estratificada por niveles de atención y regiones geográficas, garantizando la validez de las inferencias para la toma de decisiones institucionales.
* **Arquitectura de Datos y Armonización Histórica:** Ejecuté la consolidación de series temporales (2009-2025), resolviendo inconsistencias estructurales entre bases de datos masivas. Este proceso de ingeniería permitió, por primera vez, el monitoreo comparativo de indicadores críticos a largo plazo.
* **Optimización de Procesamiento en Big Data:** Debido a la magnitud de los registros y las restricciones de hardware, implementé soluciones de procesamiento mediante **PySpark**. Esto permitió la manipulación de grandes volúmenes de datos directamente en disco, optimizando el uso de memoria y garantizando la escalabilidad del análisis.

### Ecosistema Tecnológico y Visualización
Diseñé una plataforma analítica integral en **Power BI**, utilizando **DAX avanzado** para la creación de métricas comunes empleadas en investigación de mercados.

* **Análisis de Perfiles y Cobertura:** Dashboards dinámicos con segmentación demográfica de los usuarios entrevistados y visualización detallada de las unidades médicas que integraron la muestra, especificando el volumen de entrevistas levantadas por unidad.
* **Análisis de Series de Tiempo:** Implementación de visualizaciones dinámicas para el monitoreo de la evolución histórica de los indicadores (2009-2025), permitiendo identificar tendencias y medir el impacto de cambios en las políticas de atención a lo largo de 16 años.
* **Visualización Geoespacial:** Integración de mapas de regionalización para identificar brechas de calidad por zona geográfica.

---

### Visualización del Tablero Final (Power BI)

A continuación, se presentan capturas de pantalla de la herramienta de Business Intelligence diseñada para el monitoreo de la ENCAL.

#### 1. Carátula y Resumen Ejecutivo
Esta vista ofrece una visión general de los principales KPIs de satisfacción y calidad a nivel nacional, integrando además el perfil demográfico de los usuarios entrevistados.

<img src="{{ site.baseurl }}/assets/images/Caratula.png" alt="Carátula del Tablero ENCAL" style="width:95%; display:block; margin:auto; border-radius:8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">

#### 2. Análisis de Serie Histórica (2009-2025)
Visualización longitudinal que permite identificar tendencias y evaluar el impacto de políticas públicas a lo largo del tiempo.

<img src="{{ site.baseurl }}/assets/images/Serie.png" alt="Serie Histórica ENCAL" style="width:95%; display:block; margin:auto; border-radius:8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">

#### 3. Mapa de Regionalización
Análisis geoespacial para la detección de brechas de calidad por zona geográfica y nivel de atención.

<img src="{{ site.baseurl }}/assets/images/Mapa.png" alt="Mapa de Regionalización ENCAL" style="width:95%; display:block; margin:auto; border-radius:8px; box-shadow: 0 4px 12px rgba(0,0,0,0.15);">

---

### Evidencia Técnica: Procesamiento con PySpark
A continuación, se muestra un fragmento de la arquitectura de datos desarrollada para la gestión de volúmenes masivos de información.

<img src="{{ site.baseurl }}/assets/images/Codigo Encal.png" alt="Pipeline de ETL con PySpark" style="width:70%; display:block; margin:auto; border-radius:10px; box-shadow: 5px 5px 15px rgba(0,0,0,0.1);">

---
[« Volver a Proyectos]({{ site.baseurl }}/proyectos/)

<style>
  .pagination--pager {
    display: none !important;
    visibility: hidden !important;
    height: 0 !important;
    margin: 0 !important;
    padding: 0 !important;
  }
</style>
