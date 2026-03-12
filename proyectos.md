---
layout: single
title: "Portafolio de Proyectos"
permalink: /proyectos/
author_profile: true
---

<style>
  /* 1. MENÚ A LA IZQUIERDA */
  .masthead__menu {
    float: left !important;
    margin-left: 3.5rem !important;
  }

  /* 2. ELIMINAR EL "CORSÉ" DEL TEMA */
  /* Forzamos al contenedor principal a ocupar todo el ancho */
  #main {
    max-width: 100% !important;
    padding: 0 20px !important;
  }

  .page__inner-wrap {
    width: 100% !important;
    max-width: 100% !important;
    display: flex !important;
    align-items: flex-start !important;
  }

  /* 3. REPARTO DE ESPACIO */
  @media (min-width: 64em) {
    .sidebar {
      width: 260px !important;
      min-width: 260px !important;
      margin-right: 40px !important;
      display: block !important;
      position: sticky !important;
      top: 20px;
    }

    .page__content {
      flex: 1 !important; /* Toma todo el espacio que sobra */
      max-width: none !important;
      width: auto !important;
    }
  }

  /* 4. CAJAS DE PROYECTOS */
  .grid-proyectos {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
    gap: 25px;
    margin-top: 30px;
    width: 100%;
  }

  .tarjeta-actuarial {
    border: 1px solid #e1e4e8;
    border-radius: 12px;
    padding: 25px;
    background: #fff;
    box-shadow: 0 4px 6px rgba(0,0,0,0.05);
  }
</style>

Como Actuario con más de **18 años** de trayectoria, he liderado proyectos de alta sensibilidad estratégica para diversas instituciones financieras y organismos internacionales.

<blockquote style="border-left: 5px solid #ff0000; background: #fff5f5; padding: 15px; margin: 20px 0;">
  <strong>Nota de Confidencialidad:</strong> Debido a la naturaleza de los datos manejados y a la vigencia de contratos de confidencialidad (NDA), la mayoría de mis modelos actuariales y análisis predictivos no pueden ser expuestos públicamente.
</blockquote>

---

### Proyectos Destacados

<div class="grid-proyectos">
  <div class="tarjeta-actuarial">
    <h4 style="margin:0"><a href="/proyectos/encal/" style="color: #ff0000; text-decoration: none;">Proyecto ENCAL</a></h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Modelación actuarial avanzada aplicada a sistemas de calidad y cálculo estructural.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Proyecto MIT 1</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Análisis predictivo de mercados con Machine Learning y Python.</p>
  </div>

  <div class="tarjeta-actuarial">
    <h4 style="margin:0; color: #333;">Análisis de Riesgo</h4>
    <p style="font-size: 0.9em; margin-top: 15px; color: #666;">Simulaciones Monte Carlo para evaluación de solvencia estratégica.</p>
  </div>
</div>
