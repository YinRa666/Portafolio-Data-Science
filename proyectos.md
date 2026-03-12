---
layout: splash
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MOVER MENÚ A LA IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 3.5rem !important;
  }

  /* 2. FORZAR QUE EL CONTENIDO RESPETE LA FOTO */
  /* Al usar layout splash, el contenido tiende a ocupar todo. 
     Le damos un margen izquierdo para que no choque con tu perfil. */
  .archive, .page__content, .page__inner-wrap {
    margin-left: 300px !important;
    padding-right: 5% !important;
    width: auto !important;
    display: block !important;
  }

  /* 3. CAJAS DE PROYECTOS */
  .contenedor-grid {
    display: flex;
    flex-wrap: wrap;
    gap: 20px;
    margin-top: 30px;
  }

  .tarjeta-actuarial {
    flex: 1 1 300px;
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 25px;
    background: #fff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }

  /* Ajuste para móviles */
  @media (max-width: 768px) {
    .archive, .page__content, .page__inner-wrap {
      margin-left: 0 !important;
    }
  }
</style>

<div style="text-align: justify;">
Como Actuario con más de **18 años** de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

<blockquote style="border-left: 5px solid #ff0000; background: #fff5f5; padding: 15px; margin: 20px 0;">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</blockquote>
</div>

---

### Proyectos Destacados

<div class="contenedor-grid">
  <div class="tarjeta-actuarial">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Modelación actuarial avanzada aplicada a sistemas de calidad.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Análisis predictivo de mercados con Python.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Simulaciones para evaluación de solvencia estratégica.</p>
  </div>
</div>
