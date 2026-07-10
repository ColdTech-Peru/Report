<div align="center">

<img style="height: 120px" src="assets/chapter01/upc.png" alt="Logo UPC">

### Universidad Peruana de Ciencias Aplicadas
### Carrera de Ingeniería de Software

<br>

## 1ASI0729
## Desarrollo de Aplicaciones Open Source

### NRC
## 11959

# Informe del Trabajo Final

### Docente
## Mori Paiva, Hugo Allan

### Equipo
## ColdTech

<br>

### Proyecto
## Frigora

### Integrantes

| Código | Apellidos y Nombres |
| :---: | :---: |
| u202321264 | Galindo Montero, Alejandro Manuel |
| u202321281 | Perez Tuesta, Gabriel |
| u202221632 | Fajardo Monrroy, Walter Luis |
| u202311912 | Cumba Rengifo, Leonardo Raul |
| u20201f788 | Cuentas Peña, Joaquin Alberto |

<br>

## Período 202610

## Julio 2026

</div>

---

## Registro de Versiones del Informe

| Versión | Fecha | Autor | Descripción de modificación |
| :---: | :---: | :---: | :--- |
| 1.0 | 2026-04-26 | ColdTech | Desarrollo del Capítulo I, Capítulo II, Capítulo III, Capítulo IV y el Sprint 1 del Capítulo V |
| 2.0 | 2026-05-16 | ColdTech | Desarrollo del Sprint 2 |
| 3.0 | 2026-06-20 | ColdTech | Desarrollo del Sprint 3, mejora de la aplicación web y desarrollo del Back-end en Spring Boot.|
| 4.0 | 2026-07-10 | ColdTech | Desarrollo del Sprint 4, correciones de la aplicación web y mejora del Back-end en Spring Boot.|
---

## Project Report Collaboration Insights

| Recurso | URL |
| :--- | :--- |
| Organización del proyecto | https://github.com/ColdTech-Peru |
| Repositorio del reporte | https://github.com/ColdTech-Peru/Report |
| Repositorio de la Landing Page | https://github.com/ColdTech-Peru/Landing-Page |
| Repositorio del Frontend |https://github.com/ColdTech-Peru/Frigora-Frontend|
| Repositorio del Backend | https://github.com/ColdTech-Peru/Frigora-Platform |

Durante la fase de preparación del informe, se llevaron a cabo las siguientes actividades:

**AV1:** Las tareas asignadas al AV1 han sido finalizadas y se encuentran correctamente documentadas en el repositorio de GitHub:

- Se redactaron y crearon los contenidos asignados a cada miembro utilizando el formato Markdown, y se realizaron *Conventional Commits* para documentar el avance en el repositorio.
- Se generaron los recursos necesarios y se agregaron las imágenes al repositorio en la carpeta `assets` correspondiente a cada rama del informe.
- Se organizaron reuniones para coordinar el progreso de los componentes del informe y del Sprint 1, enfocado en el desarrollo de la Landing Page.

<div align="center">
<img src="assets/chapter01/commits informe - 1.png" alt="Commits del informe">
</div>

<br>

**TB1:** Las tareas asignadas al TB1 fueron desarrolladas e integradas correctamente en el Front-End de la aplicación utilizando Angular y Angular Material, manteniendo una arquitectura modular y organizada:

- Se implementaron los distintos módulos funcionales del sistema, incluyendo Dashboard, Monitoring, Asset Management, Reports y Service Requests, utilizando componentes standalone y servicios para el consumo de datos.
- Se desarrollaron operaciones CRUD conectadas mediante `json-server` y `db.json`, permitiendo gestionar información dinámica dentro de la aplicación.
- Se configuraron rutas, filtros, formularios reactivos, componentes visuales y estilos responsivos para mejorar la experiencia de usuario en cada sección del sistema.
- Se realizaron commits utilizando *Conventional Commits* para documentar el progreso del Sprint y mantener trazabilidad del desarrollo en GitHub.
- Se integraron capturas, recursos visuales e insights del Front-End en la documentación técnica del proyecto.

<div align="center">
<img src="assets/chapter01/report-tb1.jpeg" alt="Commits del Front-End TB1" style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**AV2:** Las tareas asignadas al AV2 estuvieron enfocadas en la revisión, modificación y documentación del informe del Sprint, asegurando que la información reflejara correctamente el trabajo realizado:

- Se revisó y actualizó el contenido del informe, corrigiendo y ampliando las secciones correspondientes al avance del Sprint.
- Se documentaron las funcionalidades implementadas, incluyendo capturas de pantalla y evidencias visuales del Front-End y Back-End.
- Se reorganizó la estructura del documento para mantener coherencia y orden entre las distintas secciones del informe.
- Se redactaron las descripciones técnicas de los cambios realizados, detallando el alcance y los aspectos relevantes de cada tarea.
- Se verificó la trazabilidad entre los commits realizados en GitHub y lo documentado en el informe, asegurando consistencia con el progreso real del Sprint.
- Se realizaron ajustes finales de formato y redacción para mejorar la claridad y presentación del documento.
  
<div align="center">
<img src="assets/chapter04/insights3.png" alt="Commits del Reporte AV2" style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

---

## Contenido

- [Informe del Trabajo Final](#informe-del-trabajo-final)
    - [Docente](#docente)
  - [Mori Paiva, Hugo Allan](#mori-paiva-hugo-allan)
    - [Equipo](#equipo)
  - [ColdTech](#coldtech)
    - [Proyecto](#proyecto)
  - [Frigora](#frigora)
    - [Integrantes](#integrantes)
  - [Período 202610](#período-202610)
  - [Julio 2026](#julio-2026)
  - [Registro de Versiones del Informe](#registro-de-versiones-del-informe)
  - [| 3.0 | 2026-06-20 | ColdTech | Desarrollo del Sprint 3, mejora de la aplicación web y desarrollo del Back-end en Spring Boot.](#-30--2026-06-20--coldtech--desarrollo-del-sprint-3-mejora-de-la-aplicación-web-y-desarrollo-del-back-end-en-spring-boot)
  - [Project Report Collaboration Insights](#project-report-collaboration-insights)
  - [Contenido](#contenido)
  - [Student Outcome](#student-outcome)
- [Capítulo I: Introducción](#capítulo-i-introducción)
  - [1.1 Startup Profile](#11-startup-profile)
    - [1.1.1 Descripción de la Startup](#111-descripción-de-la-startup)
    - [1.1.2 Perfiles de integrantes del equipo](#112-perfiles-de-integrantes-del-equipo)
  - [1.2 Solution Profile](#12-solution-profile)
    - [1.2.1 Antecedentes y Problemática](#121-antecedentes-y-problemática)
    - [1.2.2 Lean UX Process](#122-lean-ux-process)
      - [1.2.2.1 Lean UX Problem Statements](#1221-lean-ux-problem-statements)
      - [1.2.2.2 Lean UX Assumptions](#1222-lean-ux-assumptions)
      - [1.2.2.3 Lean UX Hypothesis Statements](#1223-lean-ux-hypothesis-statements)
      - [1.2.2.4 Lean UX Canvas](#1224-lean-ux-canvas)
  - [1.3 Segmentos Objetivos](#13-segmentos-objetivos)
- [Capítulo II: Requirements Elicitation \& Analysis](#capítulo-ii-requirements-elicitation--analysis)
  - [2.1 Competidores](#21-competidores)
    - [2.1.1 Análisis Competitivo](#211-análisis-competitivo)
    - [2.1.2 Estrategias y Tácticas frente a Competidores](#212-estrategias-y-tácticas-frente-a-competidores)
  - [2.2 Entrevistas](#22-entrevistas)
    - [2.2.1 Diseño de Entrevistas](#221-diseño-de-entrevistas)
    - [2.2.2 Registro de Entrevistas](#222-registro-de-entrevistas)
      - [Segmento #1: Negocios con equipos de refrigeración](#segmento-1-negocios-con-equipos-de-refrigeración)
      - [Segmento #2: Técnicos y Empresas de Mantenimiento](#segmento-2-técnicos-y-empresas-de-mantenimiento)
    - [2.2.3 Análisis de Entrevistas](#223-análisis-de-entrevistas)
  - [2.3 Needfinding](#23-needfinding)
    - [2.3.1 User Personas](#231-user-personas)
    - [2.3.2 User Task Matrix](#232-user-task-matrix)
    - [2.3.3 User Journey Mapping](#233-user-journey-mapping)
    - [2.3.4 Empathy Mapping](#234-empathy-mapping)
  - [2.4 Big Picture Event Storming](#24-big-picture-event-storming)
  - [2.5 Ubiquitous Language](#25-ubiquitous-language)
- [Capítulo III: Requirements Specification](#capítulo-iii-requirements-specification)
  - [3.1 To-Be Scenario Mapping](#31-to-be-scenario-mapping)
  - [3.2 User Stories](#32-user-stories)
    - [Épicas del Sistema](#épicas-del-sistema)
    - [User Stories](#user-stories)
  - [3.3 Impact Mapping](#33-impact-mapping)
  - [3.4 Product Backlog](#34-product-backlog)
- [Capítulo IV: Product Design](#capítulo-iv-product-design)
  - [4.1 Style Guidelines](#41-style-guidelines)
    - [4.1.1 General Style Guidelines](#411-general-style-guidelines)
    - [4.1.2 Web Style Guidelines](#412-web-style-guidelines)
  - [4.2 Information Architecture](#42-information-architecture)
    - [4.2.1 Organization Systems](#421-organization-systems)
    - [4.2.2 Labeling Systems](#422-labeling-systems)
    - [4.2.3 SEO Tags and Meta Tags](#423-seo-tags-and-meta-tags)
    - [4.2.4 Searching Systems](#424-searching-systems)
    - [4.2.5 Navigation Systems](#425-navigation-systems)
  - [4.3 Landing Page UI Design](#43-landing-page-ui-design)
    - [4.3.1 Landing Page Wireframe](#431-landing-page-wireframe)
    - [4.3.2 Landing Page Mock-up](#432-landing-page-mock-up)
  - [4.4 Web Applications UX/UI Design](#44-web-applications-uxui-design)
    - [4.4.1 Web Applications Wireframes](#441-web-applications-wireframes)
    - [4.4.2 Web Applications Wireflow Diagrams](#442-web-applications-wireflow-diagrams)
    - [4.4.3 Web Applications Mock-ups](#443-web-applications-mock-ups)
    - [4.4.4 Web Applications User Flow Diagrams](#444-web-applications-user-flow-diagrams)
  - [4.5 Web Applications Prototyping](#45-web-applications-prototyping)
  - [4.6 Domain-Driven Software Architecture](#46-domain-driven-software-architecture)
    - [4.6.1 Design-Level EventStorming](#461-design-level-eventstorming)
    - [4.6.2 Software Architecture Context Diagram](#462-software-architecture-context-diagram)
    - [4.6.3 Software Architecture Container Diagrams](#463-software-architecture-container-diagrams)
    - [4.6.4 Software Architecture Components Diagrams](#464-software-architecture-components-diagrams)
  - [4.7 Software Object-Oriented Design](#47-software-object-oriented-design)
    - [4.7.1 Class Diagrams](#471-class-diagrams)
  - [4.8 Database Design](#48-database-design)
    - [4.8.1 Database Diagrams](#481-database-diagrams)
- [Capítulo V: Product Implementation, Validation \& Deployment](#capítulo-v-product-implementation-validation--deployment)
  - [5.1 Software Configuration Management](#51-software-configuration-management)
    - [5.1.1 Software Development Environment Configuration](#511-software-development-environment-configuration)
    - [5.1.2 Source Code Management](#512-source-code-management)
    - [5.1.3 Source Code Style Guide \& Conventions](#513-source-code-style-guide--conventions)
    - [5.1.4 Software Deployment Configuration](#514-software-deployment-configuration)
  - [5.2 Landing Page, Services \& Applications Implementation](#52-landing-page-services--applications-implementation)
    - [5.2.1 Sprint 1](#521-sprint-1)
      - [5.2.1.1 Sprint Planning 1](#5211-sprint-planning-1)
      - [5.2.1.2 Aspect Leaders and Collaborators](#5212-aspect-leaders-and-collaborators)
      - [5.2.1.3 Sprint Backlog 1](#5213-sprint-backlog-1)
      - [5.2.1.4 Development Evidence for Sprint Review](#5214-development-evidence-for-sprint-review)
      - [5.2.1.5 Execution Evidence for Sprint Review](#5215-execution-evidence-for-sprint-review)
      - [5.2.1.6 Services Documentation Evidence for Sprint Review](#5216-services-documentation-evidence-for-sprint-review)
      - [5.2.1.7 Software Deployment Evidence for Sprint Review](#5217-software-deployment-evidence-for-sprint-review)
      - [5.2.1.8 Team Collaboration Insights during Sprint](#5218-team-collaboration-insights-during-sprint)
    - [5.2.2. Sprint 2](#522-sprint-2)
      - [5.2.2.1.Sprint Planning 2.](#5221sprint-planning-2)
      - [5.2.2.2 Aspect Leaders and Collaborators](#5222-aspect-leaders-and-collaborators)
      - [5.2.2.3.Sprint Backlog 2.](#5223sprint-backlog-2)
      - [5.2.2.4. Development Evidence for Sprint Review](#5224-development-evidence-for-sprint-review)
      - [5.2.2.5. Execution Evidence for Sprint Review](#5225-execution-evidence-for-sprint-review)
      - [5.2.2.6.Services Documentation Evidence for Sprint Review.](#5226services-documentation-evidence-for-sprint-review)
      - [5.2.2.7.Software Deployment Evidence for Sprint Review.](#5227software-deployment-evidence-for-sprint-review)
      - [5.2.2.8.Team Collaboration Insights during Sprint.](#5228team-collaboration-insights-during-sprint)
    - [5.2.3. Sprint 3](#523-sprint-3)
      - [5.2.3.1.Sprint Planning 3.](#5231sprint-planning-3)
      - [5.2.3.2 Aspect Leaders and Collaborators](#5232-aspect-leaders-and-collaborators)
      - [5.2.3.3. Sprint Backlog 3.](#5233-sprint-backlog-3)
      - [5.2.3.4. Development Evidence for Sprint Review](#5234-development-evidence-for-sprint-review)
      - [5.2.3.5. Execution Evidence for Sprint Review](#5235-execution-evidence-for-sprint-review)
      - [5.2.3.6. Services Documentation Evidence for Sprint Review.](#5236-services-documentation-evidence-for-sprint-review)
      - [5.2.3.7. Software Deployment Evidence for Sprint Review.](#5237-software-deployment-evidence-for-sprint-review)
      - [5.2.3.8. Team Collaboration Insights during Sprint.](#5238-team-collaboration-insights-during-sprint)
    - [5.2.4. Sprint 4](#524-sprint-4)
      - [5.2.4.1.Sprint Planning 4.](#5241sprint-planning-4)
      - [5.2.4.2 Aspect Leaders and Collaborators](#5242-aspect-leaders-and-collaborators)
      - [5.2.4.3. Sprint Backlog 4.](#5243-sprint-backlog-4)
- [Sprint Backlog 4](#sprint-backlog-4)
      - [5.2.4.4. Development Evidence for Sprint Review](#5244-development-evidence-for-sprint-review)
      - [5.2.4.5. Execution Evidence for Sprint Review](#5245-execution-evidence-for-sprint-review)
  - [Register](#register)
  - [Login](#login)
- [Owner View:](#owner-view)
  - [Dashboard](#dashboard)
  - [Sites](#sites)
  - [Monitoring](#monitoring)
  - [Services](#services)
  - [Report](#report)
- [Provider View:](#provider-view)
  - [Dashboard](#dashboard-1)
  - [Technicians](#technicians)
  - [Service Hub](#service-hub)
  - [Services](#services-1)
      - [5.2.4.6. Services Documentation Evidence for Sprint Review](#5246-services-documentation-evidence-for-sprint-review)
    - [Interventions](#interventions)
    - [Reviews](#reviews)
    - [Technicians](#technicians-1)
    - [Authentication](#authentication)
    - [Alert](#alert)
    - [Users](#users)
    - [Service Request](#service-request)
    - [Site](#site)
    - [Reporting](#reporting)
    - [Equipment](#equipment)
      - [5.2.4.7. Software Deployment Evidence for Sprint Review](#5247-software-deployment-evidence-for-sprint-review)
      - [5.2.4.8. Team Collaboration Insights during Sprint](#5248-team-collaboration-insights-during-sprint)
  - [5.3. Validation Interviews.](#53-validation-interviews)
    - [5.3.1. Diseño de Entrevistas.](#531-diseño-de-entrevistas)
- [Guía de Entrevista — Frigora](#guía-de-entrevista--frigora)
  - [Preguntas Comunes](#preguntas-comunes)
  - [Segmento 1 — Negocios con Equipos de Refrigeración](#segmento-1--negocios-con-equipos-de-refrigeración)
  - [Segmento 2 — Técnicos y Empresas de Mantenimiento](#segmento-2--técnicos-y-empresas-de-mantenimiento)
    - [5.3.2. Registro de Entrevistas.](#532-registro-de-entrevistas)
      - [Segmento #1: Negocios con equipos de refrigeración](#segmento-1-negocios-con-equipos-de-refrigeración-1)
      - [Segmento #2: Técnicos y Empresas de Mantenimiento](#segmento-2-técnicos-y-empresas-de-mantenimiento-1)
    - [5.3.3. Evaluaciones según heurísticas.](#533-evaluaciones-según-heurísticas)
      - [UX Heuristics \& Principles Evaluation](#ux-heuristics--principles-evaluation)
      - [SITE o APP A EVALUAR](#site-o-app-a-evaluar)
      - [TAREAS A EVALUAR](#tareas-a-evaluar)
      - [ESCALA DE SEVERIDAD](#escala-de-severidad)
      - [TABLA RESUMEN](#tabla-resumen)
      - [DESCRIPCIÓN DE PROBLEMAS](#descripción-de-problemas)
        - [PROBLEMA #1: El nombre del producto se confunde con el nombre de una persona](#problema-1-el-nombre-del-producto-se-confunde-con-el-nombre-de-una-persona)
        - [PROBLEMA #2: Cálculo de factura inconsistente con el detalle de la orden](#problema-2-cálculo-de-factura-inconsistente-con-el-detalle-de-la-orden)
        - [PROBLEMA #3: Estado de pago contradictorio entre vistas del mismo pedido](#problema-3-estado-de-pago-contradictorio-entre-vistas-del-mismo-pedido)
        - [PROBLEMA #4: Datos de Conductor y Vehículo no visibles para el comprador](#problema-4-datos-de-conductor-y-vehículo-no-visibles-para-el-comprador)
        - [PROBLEMA #5: Datos de prueba (placeholders) visibles en producción](#problema-5-datos-de-prueba-placeholders-visibles-en-producción)
        - [PROBLEMA #6: Mezcla de idiomas dentro de la misma pantalla](#problema-6-mezcla-de-idiomas-dentro-de-la-misma-pantalla)
        - [PROBLEMA #7: Bug de cálculo de tiempo relativo ("NaNmo ago")](#problema-7-bug-de-cálculo-de-tiempo-relativo-nanmo-ago)
        - [PROBLEMA #8: Unidad de cantidad ilegible en formulario de solicitud (versión español)](#problema-8-unidad-de-cantidad-ilegible-en-formulario-de-solicitud-versión-español)
        - [PROBLEMA #9: Ambigüedad en el formato numérico de cantidades](#problema-9-ambigüedad-en-el-formato-numérico-de-cantidades)
        - [PROBLEMA #10: Unidad de volumen inconsistente entre módulos ("MT" vs. "L")](#problema-10-unidad-de-volumen-inconsistente-entre-módulos-mt-vs-l)
        - [PROBLEMA #11: Cifra de ingresos truncada en el dashboard de reportes](#problema-11-cifra-de-ingresos-truncada-en-el-dashboard-de-reportes)
        - [PROBLEMA #12: Indicador de estado sin etiqueta de texto en tabla de clientes](#problema-12-indicador-de-estado-sin-etiqueta-de-texto-en-tabla-de-clientes)
        - [PROBLEMA #13: Dashboard del proveedor no refleja actividad reciente](#problema-13-dashboard-del-proveedor-no-refleja-actividad-reciente)
        - [PROBLEMA #14: Uso de Yape como método de pago para montos B2B muy elevados](#problema-14-uso-de-yape-como-método-de-pago-para-montos-b2b-muy-elevados)
        - [PROBLEMA #15: Transacción de ejemplo de un volumen no representativo del modelo B2B](#problema-15-transacción-de-ejemplo-de-un-volumen-no-representativo-del-modelo-b2b)
        - [PROBLEMA #16: Error ortográfico recurrente "premiun"](#problema-16-error-ortográfico-recurrente-premiun)
        - [PROBLEMA #17: Falta de indicación de campos obligatorios en el formulario de registro de cuenta](#problema-17-falta-de-indicación-de-campos-obligatorios-en-el-formulario-de-registro-de-cuenta)
        - [PROBLEMA #18: Gráficos sin valores ni leyenda claros](#problema-18-gráficos-sin-valores-ni-leyenda-claros)
      - [Conclusión general de la sesión](#conclusión-general-de-la-sesión)
    - [5.4. Video About-the-Product.](#54-video-about-the-product)
  - [Conclusiones y recomendaciones](#conclusiones-y-recomendaciones)
  - [Video About-the-Team](#video-about-the-team)
  - [Anexos](#anexos)

---

## Student Outcome

El curso contribuye al cumplimiento del Student Outcome ABET:

**ABET – EAC - Student Outcome 3**

> *Al finalizar el curso, el estudiante comunica resultados y proceso de ingeniería aplicado para el ciclo de desarrollo y despliegue de una solución web distribuida bajo una arquitectura orientada a servicios, que satisface requisitos para empresas o público en general, con un enfoque innovador e inclusivo, desplegada sobre plataformas Server Side o Cloud, haciendo uso de tecnologías open-source basadas en el lenguaje de programación Java para la lógica de lado servidor y tecnologías open-source para los componentes de la aplicación.*

| Criterio específico | Acciones realizadas | Conclusiones |
| :--- | :--- | :--- |
| **Comunica oralmente con efectividad a diferentes rangos de audiencia** | **Galindo Montero, Alejandro Manuel**<br>**AV1:** Fortaleció la comunicación oral al participar en la elaboración del capítulo dos, el diseño del modelo C4 y el apoyo en el desarrollo de la landing page, transmitiendo conceptos técnicos de manera clara según el nivel de la audiencia.<br>**TB1:** Desarrolló el módulo de **Service Requests** del frontend, explicando el flujo de solicitudes, las operaciones CRUD y la conexión con `json-server` mediante `db.json`.<br>**AV2:** Fortaleció la comunicación oral al explicar el desarrollo de la vista de **Proveedores** y del módulo de **Service Requests**, además del despliegue del Front-End, Back-End y base de datos, detallando el proceso de integración y la corrección de errores encontrados de manera clara para distintos niveles de audiencia.<br>**TB2:** Expuso el proceso de integración entre el Front-End y el Back-End del módulo de **Service Requests**, describiendo el consumo de servicios REST, la validación del flujo de datos, la resolución de errores detectados durante las pruebas y las mejoras implementadas para garantizar la estabilidad y el correcto funcionamiento del sistema.<br><br>**Perez Tuesta, Gabriel**<br>**AV1:** Redactó descripciones técnicas para los diagramas de Wireflow y Userflow, transformando conceptos de diseño en lenguaje formal apto para un informe académico.<br>**TB1:** Desarrolló el módulo de **Reports**, presentando el funcionamiento de formularios, filtros dinámicos, vistas de detalle y operaciones CRUD implementadas en Angular con conexión a `db.json`.<br>**AV2:** Fortaleció la comunicación oral al exponer el desarrollo del bounded context de **Reporting**, explicando su implementación tanto en el Front-End como en el Back-End de manera clara y comprensible.<br>**TB2:** Explicó la integración completa del bounded context de **Reporting**, detallando el consumo de la API, la sincronización entre el Front-End y el Back-End, la validación de respuestas, la corrección de incidencias detectadas durante las pruebas funcionales y las optimizaciones implementadas para mejorar la estabilidad del sistema.<br><br>**Cuentas Peña, Joaquin**<br>**AV1:** Planteó las user stories y diseñó el sprint de la entrega, planificando el product backlog y proyectando las necesidades de los segmentos en el desarrollo de la aplicación.<br>**TB1:** Implementó el módulo de **Assets Management**, comunicando la organización de activos, visualización de datos y funcionamiento dinámico del frontend conectado mediante `json-server`.<br>**AV2:** Fortaleció la comunicación oral al exponer el desarrollo del bounded context de **Assets Management** tanto en el Front-End como en el Back-End, explicando su funcionamiento de manera clara.<br>**TB2:** Presentó el proceso de integración del módulo de **Assets Management** con los servicios del Back-End, explicando el intercambio de información, la validación de operaciones CRUD, la identificación y corrección de errores funcionales, así como las mejoras aplicadas para optimizar el desempeño y la experiencia de uso del sistema.<br><br>**Cumba Rengifo, Leonardo Raúl**<br>**AV1:** Participó en la elaboración del Capítulo I, el análisis Lean UX y el diseño de la landing page, logrando explicar conceptos técnicos y de negocio de forma efectiva según el contexto.<br>**TB1:** Desarrolló el módulo de **Monitoring**, explicando la visualización de estados, métricas y monitoreo de equipos usando datos simulados desde `db.json`.<br>**AV2:** Fortaleció la comunicación oral al exponer el desarrollo del bounded context de **Monitoring** en el Front-End y el Back-End, explicando su implementación de manera clara.<br>**TB2:** Explicó la integración del módulo de **Monitoring** con el Back-End, describiendo el consumo de servicios, la actualización de información, el proceso de depuración de errores y las mejoras realizadas para garantizar la confiabilidad del monitoreo dentro de la plataforma.<br><br>**Fajardo Monrroy, Walter Luis**<br>**AV1:** Organizó el sprint en base a las user stories generadas y contribuyó a la realización y despliegue de la landing page.<br>**TB1:** Implementó el **Dashboard** principal del frontend, presentando métricas, tarjetas y visualizaciones dinámicas para facilitar la interpretación de información operativa.<br>**AV2:** Fortaleció la comunicación oral al exponer el desarrollo de los bounded contexts de **Dashboard** y **Feedback**, explicando su implementación en el Front-End y el Back-End de manera clara para distintos tipos de audiencia.<br>**TB2:** Expuso la integración del **Dashboard** y **Feedback** con los servicios del Back-End, detallando el consumo de información, la sincronización de componentes, la corrección de errores detectados durante la integración y las mejoras implementadas para asegurar un funcionamiento estable y consistente del sistema. | **AV1:** El equipo logró comunicar oralmente con efectividad al presentar la problemática, el proceso de needfinding y las soluciones propuestas mediante wireframes, mockups y la demostración de la landing page desplegada, transmitiendo ideas técnicas de manera clara según el tipo de audiencia.<br><br>**TB1:** El equipo fortaleció la comunicación oral mediante la exposición funcional del frontend desarrollado en Angular, explicando el funcionamiento de módulos interactivos, operaciones CRUD y consumo de datos simulados mediante `json-server` y `db.json`.<br><br>**AV2:** El equipo fortaleció la comunicación oral al exponer el desarrollo de los bounded contexts de **Reporting**, **Assets Management**, **Monitoring**, **Dashboard**, **Feedback**, **Service Requests** y **Proveedores**, así como el despliegue e integración del Front-End, el Back-End y la base de datos, transmitiendo el progreso técnico de manera clara según el tipo de audiencia.<br><br>**TB2:** El equipo fortaleció la comunicación oral al presentar el proceso de integración completa entre el Front-End y el Back-End, explicando el consumo de servicios REST, la validación de funcionalidades, la resolución de errores identificados durante las pruebas de integración y las mejoras implementadas para garantizar la estabilidad, consistencia y correcto funcionamiento de toda la plataforma. |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia** | **Galindo Montero, Alejandro Manuel**<br>**AV1:** La redacción de documentación y la organización de información técnica le permitieron estructurar ideas de forma clara y coherente, adaptando el contenido para distintos tipos de audiencia.<br>**TB1:** Documentó el funcionamiento del módulo de **Service Requests**, describiendo componentes, endpoints y flujo de datos conectados mediante `db.json`.<br>**AV2:** Documentó el desarrollo de la vista de **Proveedores** y del módulo de **Service Requests**, así como el proceso de despliegue e integración entre el Front-End, el Back-End y la base de datos, describiendo de forma clara la configuración realizada y la resolución de errores encontrados.<br>**TB2:** Documentó el proceso de integración del Front-End con el Back-End para el módulo de **Service Requests**, describiendo los endpoints consumidos, el flujo de comunicación entre capas, las validaciones implementadas, las incidencias detectadas durante las pruebas y las soluciones aplicadas para asegurar la estabilidad del sistema.<br><br>**Perez Tuesta, Gabriel**<br>**AV1:** Sintetizó procesos técnicos complejos en instrucciones directas, diferenciando claramente los perfiles de Administrador y Proveedor.<br>**TB1:** Documentó la implementación del módulo de **Reports**, incluyendo formularios, filtros, operaciones CRUD y arquitectura frontend desarrollada en Angular.<br>**AV2:** Documentó el desarrollo del bounded context de **Reporting**, describiendo su arquitectura e implementación tanto en el Front-End como en el Back-End.<br>**TB2:** Elaboró la documentación técnica de la integración del bounded context de **Reporting**, detallando la comunicación entre el Front-End y el Back-End, los servicios REST implementados, la estructura de intercambio de datos, las correcciones realizadas y las mejoras incorporadas durante el proceso de integración.<br><br>**Cuentas Peña, Joaquin**<br>**AV1:** El product backlog permitió enfocarse en las tareas más importantes para la entrega, comunicando ideas de forma eficaz.<br>**TB1:** Redactó la documentación funcional del módulo de **Assets Management**, organizando procesos de gestión de activos y comportamiento dinámico del frontend.<br>**AV2:** Documentó el desarrollo del bounded context de **Assets Management**, describiendo su arquitectura e implementación en el Front-End y el Back-End.<br>**TB2:** Documentó la integración del módulo de **Assets Management** con el Back-End, describiendo los servicios implementados, las validaciones efectuadas, el flujo de información entre componentes, la resolución de errores y las mejoras realizadas para optimizar el funcionamiento del sistema.<br><br>**Cumba Rengifo, Leonardo Raúl**<br>**AV1:** Contribuyó en la elaboración del Capítulo I, el Solution Profile, el proceso Lean UX y la definición de segmentos, estructurando ideas de forma clara y coherente.<br>**TB1:** Documentó el módulo de **Monitoring**, describiendo la visualización de estados, métricas y consumo de datos desde `json-server`.<br>**AV2:** Documentó el desarrollo del bounded context de **Monitoring**, describiendo su arquitectura e implementación en el Front-End y el Back-End.<br>**TB2:** Elaboró la documentación de la integración del módulo de **Monitoring**, describiendo el consumo de servicios, la sincronización de datos, las pruebas realizadas, la corrección de incidencias y las mejoras implementadas para garantizar el correcto monitoreo del sistema.<br><br>**Fajardo Monrroy, Walter Luis**<br>**AV1:** Comunicó adecuadamente la división de tiempos del proyecto mediante la metodología SCRUM usando sprints.<br>**TB1:** Elaboró la documentación del **Dashboard**, describiendo la estructura visual, componentes y organización de indicadores en el frontend.<br>**AV2:** Documentó el desarrollo de los bounded contexts de **Dashboard** y **Feedback**, describiendo su implementación y funcionamiento dentro del sistema.<br>**TB2:** Documentó la integración de los módulos **Dashboard** y **Feedback** con el Back-End, describiendo la arquitectura implementada, el consumo de servicios, la corrección de errores detectados durante las pruebas de integración y las mejoras aplicadas para optimizar la estabilidad y el rendimiento de la plataforma. | **AV1:** El equipo fortaleció su comunicación escrita mediante documentación estructurada que incluyó el análisis de la problemática, el proceso de needfinding, wireframes, mockups y diagramas de clases y base de datos.<br><br>**TB1:** El equipo fortaleció la comunicación escrita mediante la documentación del frontend desarrollado en Angular, incluyendo componentes, vistas, formularios, filtros y operaciones CRUD conectadas mediante `json-server` y `db.json`, explicando de manera clara la arquitectura y flujo de datos del sistema.<br><br>**AV2:** El equipo fortaleció la comunicación escrita mediante la documentación de los bounded contexts implementados en este sprint (**Reporting**, **Assets Management**, **Monitoring**, **Dashboard**, **Feedback** y **Service Requests**), así como del proceso de despliegue, integración y corrección de errores entre el Front-End, el Back-End y la base de datos.<br><br>**TB2:** El equipo fortaleció la comunicación escrita mediante la documentación detallada del proceso de integración entre el Front-End y el Back-End, describiendo la arquitectura cliente-servidor implementada, el consumo de APIs REST, la validación de funcionalidades, la resolución de incidencias detectadas durante las pruebas de integración y las mejoras realizadas para incrementar la estabilidad, mantenibilidad y confiabilidad de la solución desarrollada. |

---

# Capítulo I: Introducción

## 1.1 Startup Profile

### 1.1.1 Descripción de la Startup

**ColdTech** es una startup que desarrolla una aplicación web orientada al monitoreo y gestión inteligente de equipos de refrigeración mediante sensores IoT. La plataforma permite supervisar en tiempo real variables como la temperatura, el rendimiento y el consumo energético, además de generar alertas preventivas, almacenar el historial de funcionamiento y facilitar la programación del mantenimiento.

La solución está dirigida a negocios y organizaciones que dependen de la cadena de frío — supermercados, minimarkets, restaurantes, laboratorios y empresas de los sectores alimentario y farmacéutico — con el propósito de reducir fallas inesperadas, disminuir costos operativos y evitar pérdidas de productos.

> **Misión:** Brindar una solución tecnológica inteligente que permita a las empresas proteger sus productos, optimizar el funcionamiento de sus equipos de refrigeración y mejorar la gestión de su mantenimiento.
>
> **Visión:** Ser una startup líder en el mercado peruano en soluciones digitales para el monitoreo y mantenimiento de equipos de refrigeración, destacando por la innovación, confiabilidad y aporte a la eficiencia operativa.

---

### 1.1.2 Perfiles de integrantes del equipo

<div align="center">

| **Integrante**            | **Galindo Montero Alejandro Manuel**        									    |
| :------------------------ | :-------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202321264                                   										|
| **Carrera**               | Ingeniería de Software                       										|
| **Descripción**           | Mi nombre es Alejandro Manuel Galindo Montero, tengo 20 años y curso la carrera de Ingeniería de Software. Me considero una persona creativa y responsable. En mis tiempos libres me gusta aprender cosas nuevas. En este proyecto apoyaré con todos los conocimientos que he adquirido en los últimos años.   												|
| **Foto**                  | <img src="assets/chapter01/AlejandroGalindo.png" alt="" width="200" height="200"> |

---


| **Integrante**            | **Cumba Rengifo Leonardo Raul**        									    |
| :------------------------ | :-------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202311912                           										|
| **Carrera**               | Ingeniería de Software                       										|
| **Descripción**           | Mi nombre es Cumba Rengifo Leonardo Raul, tengo 20 años y curso la carrera de Ingeniería de Software.Me quiere enfocarse en backend o en DBA. En la actualidad me gustaria especialiarse en DBA o como arquitecto de sofware            .   												|
| **Foto**                  | <img src="assets/chapter01/FotoPerfilLeonardo.png" alt="" width="200" height="200"> |

---

| **Integrante**            | **Perez Tuesta, Gabriel**        									    |
| :------------------------ | :-------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202321281                           										|
| **Carrera**               | Ingeniería de Software                       										|
| **Descripción**           | Mi nombre es Gabriel Perez Tuesta, tengo 23 años y curso la carrera de Ingeniería de Software. Me gustaria enfocarme en el desarrollo web y movil, tengo conocimientos promedios en Javascript, React, Vue y Next JS         .   												|
| **Foto**                  | <img width="200" height="200" src="https://github.com/user-attachments/assets/98296ec4-9fb6-456c-a507-544377c1f691" />
 

---

| **Integrante**            | Fajardo Monrroy, Walter Luis        									    |
| :------------------------ | :-------------------------------------------------------------------------------- |
| **Código del Estudiante** | u202221632                           										|
| **Carrera**               | Ingeniería de Software                       										|
| **Descripción**           | Soy Walter Luis Fajardo Monrroy, cuento con 20 años y por motivos de estudio residente en Lima. Soy estudiante de la carrera de ingeniería de software, en mi formación como estudiante durante estos ciclos adquirí conocimientos en programación principalmente con lenguaje C++ y python, También cuanto con conocimientos en patrones de software al momento de realizar mis proyectos, además de experiencia realizando diagramas de clases y empleando el DDD (Diseño orientado a objetos). Las habilidades primarias para resaltar serán la responsabilidad y resiliencia frente a las adversidades. Cuento con experiencia en organización y trabajo grupal lo cual emplearé para beneficio del equipo.         .   												|
| **Foto**                  | <img src="assets/chapter01/walter.png" alt="" width="200" height="200">


---

| **Integrante**            | Cuentas Peña, Joaquin Alberto      									    |
| :------------------------ | :-------------------------------------------------------------------------------- |
| **Código del Estudiante** | u20201f788                          										|
| **Carrera**               | Ingeniería de Software                       										|
| **Descripción**           | Soy Joaquin Alerto Cuentas Peña, cuento con 22 años. Soy estudiante de la UPC de la carrera de Ingeniería de Software y me encuentro cursando el sexto ciclo. Cuento con habilidades de programación en C++ y Python, así como aptitudes para el desarrollo en UX y UI. Asimismo, en cuanto a habilidades extracurriculares, he contribuido en proyectos con edición de video y fomentando una actitud colaborativa en el equipo.   												|
| **Foto**                  | <img src="assets/chapter01/fotojoaquin.jpg" alt="" width="200" height="200">

</div>

---

## 1.2 Solution Profile

### 1.2.1 Antecedentes y Problemática

| Dimensión | Descripción |
| :--- | :--- |
| **What — ¿Cuál es el problema?** | Los negocios que dependen de equipos de refrigeración presentan un control limitado sobre su funcionamiento, lo que ocasiona fallas inesperadas, alto consumo energético y mantenimiento tardío, generando pérdidas económicas y afectando la continuidad operativa. |
| **When — ¿Cuándo sucede?** | El problema puede presentarse en cualquier momento durante la operación diaria, especialmente cuando no existe monitoreo continuo ni mantenimiento preventivo. Su impacto aumenta ante fallas imprevistas o demoras en la atención técnica. |
| **Where — ¿Dónde ocurre?** | En negocios y organizaciones que utilizan equipos de refrigeración para conservar productos, principalmente en los sectores de alimentos, comercio y salud. Tiene especial relevancia en Lima por la concentración de este tipo de actividades. |
| **Who — ¿Quiénes están involucrados?** | Los dueños y administradores de negocios (que sufren las pérdidas por fallas) y los técnicos y proveedores de mantenimiento (que necesitan información oportuna para actuar de forma eficiente). |
| **Why — ¿Cuál es la causa?** | La falta de herramientas tecnológicas accesibles que permitan supervisar en tiempo real el estado de los equipos, generar alertas y organizar mantenimientos de manera preventiva. |
| **How — ¿Cómo se llegó a esta situación?** | Por una gestión tradicional y reactiva del mantenimiento, basada en revisiones manuales o acciones correctivas después de que ocurre una falla. |
| **How Much — ¿Cuánto es el impacto financiero?** | El impacto puede ser alto: incluye pérdidas de productos, costos de reparación de emergencia, mayor consumo energético y afectación en la calidad del servicio. |

---

### 1.2.2 Lean UX Process

#### 1.2.2.1 Lean UX Problem Statements

**Dominio del problema**
El problema se ubica en la gestión y supervisión de equipos de refrigeración dentro de negocios que dependen de la cadena de frío. Actualmente, muchas empresas operan sin un sistema digital que les permita monitorear en tiempo real variables críticas como la temperatura, el rendimiento y el consumo energético.

**Segmentos de cliente**
- **Segmento #1:** Empresas con alta dependencia de sistemas de refrigeración, que buscan reducir pérdidas y optimizar su operación.
- **Segmento #2:** Empresas de mantenimiento, que necesitan herramientas digitales para mejorar la gestión de sus servicios.

**Puntos de dolor**
- *Segmento #1:* Fallas inesperadas, pérdidas de productos, consumo energético elevado y falta de visibilidad sobre el estado real de los equipos. Gestión reactiva del mantenimiento.
- *Segmento #2:* Dificultad para organizar servicios, acceder al historial técnico y mejorar los tiempos de respuesta.

**Brecha detectada**
Existe una brecha por la falta de una solución integrada que permita centralizar el monitoreo en tiempo real, la generación de alertas preventivas, el historial de funcionamiento y la gestión del mantenimiento. Muchas organizaciones aún dependen de controles manuales o acciones correctivas post-falla.

---

#### 1.2.2.2 Lean UX Assumptions

| Categoría | Descripción |
| :--- | :--- |
| **Problem Assumptions** | Muchas empresas no cuentan con herramientas digitales para monitorear sus equipos. La gestión del mantenimiento suele ser reactiva, detectando fallas tarde y generando pérdidas innecesarias. |
| **Segmento #1** | Necesitan conocer en tiempo real el estado de sus equipos, valoran las alertas preventivas y están interesados en contar con un historial de funcionamiento para tomar mejores decisiones. |
| **Segmento #2** | Necesitan centralizar la información técnica de sus clientes. Un acceso rápido al historial y alertas mejora su tiempo de respuesta y les permite diferenciarse con un servicio más preventivo. |
| **Solution Assumptions** | Una aplicación web integrada con IoT puede resolver el problema al ofrecer monitoreo en tiempo real, alertas preventivas, historial y gestión del mantenimiento en una sola plataforma. |
| **Value Assumptions** | Para el Segmento #1: reducción de pérdidas y optimización energética. Para el Segmento #2: mejor gestión y servicio técnico más confiable. |
| **Adoption Assumptions** | Los primeros usuarios serán empresas en Lima con dependencia directa de la cadena de frío que hayan experimentado problemas por fallas o mantenimiento deficiente. |

---

#### 1.2.2.3 Lean UX Hypothesis Statements

| # | Hipótesis |
| :---: | :--- |
| **H1** | Si las empresas cuentan con monitoreo en tiempo real de temperatura, rendimiento y consumo, entonces podrán detectar anomalías con mayor anticipación y reducir fallas críticas. |
| **H2** | Si estas empresas reciben alertas preventivas y disponen de un historial de mantenimiento, entonces mejorarán la planificación y optimizarán la continuidad de sus operaciones. |
| **H3** | Si las empresas de mantenimiento tienen acceso centralizado al historial técnico y alertas, entonces responderán más rápido y ofrecerán un servicio más eficiente. |
| **H4** | Si se integra en una sola plataforma el monitoreo, alertas, historial y gestión del mantenimiento, los usuarios la percibirán como más útil que los métodos manuales actuales. |
| **H5** | Si la plataforma ayuda a prevenir fallas y reducir pérdidas, las empresas estarán más dispuestas a adoptarla como parte de su operación diaria. |
| **H6** | Si la solución se implementa inicialmente en Lima, será más factible validar la propuesta de valor y obtener retroalimentación temprana. |
| **H7** | La solución será exitosa si los usuarios logran reducir incidencias críticas, mejorar el control de equipos y optimizar la gestión del mantenimiento. |

---

#### 1.2.2.4 Lean UX Canvas

<div align="center">
<img src="assets/chapter01/1-2-2-4.png" alt="Lean UX Canvas" style="max-width: 80%; height: auto;">

[`https://miro.com/welcomeonboard/WmZsK25CaFdYd041RFo5ejBKempQYXIveC85TmZaaUlpUGJrUUJ1VU1NUFVJVkp0NHVycks3UEZCK1M2WFV1TlVtazV5QmFNS1pGNllwTHh1bzRVMG0vZThsQTVOL0EwQlJwbEN0Y3NrQWVzSHUwWXk0OFgvTzBMSWJRMHF3eU9hWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE=?share_link_id=957048471438`](https://miro.com/welcomeonboard/WmZsK25CaFdYd041RFo5ejBKempQYXIveC85TmZaaUlpUGJrUUJ1VU1NUFVJVkp0NHVycks3UEZCK1M2WFV1TlVtazV5QmFNS1pGNllwTHh1bzRVMG0vZThsQTVOL0EwQlJwbEN0Y3NrQWVzSHUwWXk0OFgvTzBMSWJRMHF3eU9hWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE=?share_link_id=957048471438)
</div>

---

## 1.3 Segmentos Objetivos

La solución está dirigida a dos segmentos principales relacionados con la gestión y el mantenimiento de equipos de refrigeración.

**Segmento #1: Empresas con alta dependencia de sistemas de refrigeración**
Supermercados, minimarkets, restaurantes, laboratorios, boticas, y empresas del sector alimentario y farmacéutico. Perfil demográfico: propietarios, administradores, jefes de operaciones o encargados de logística, adultos en edad laboral, ubicados en zonas urbanas con actividad económica formal. Su principal necesidad es reducir pérdidas por fallas, mantener condiciones adecuadas de conservación y optimizar costos.

**Segmento #2: Empresas de mantenimiento**
Técnicos y empresas especializadas en instalación, revisión y mantenimiento de equipos de refrigeración. Perfil demográfico: técnicos, supervisores y responsables de servicio con conocimientos operativos y técnicos del sector. Su principal necesidad es contar con herramientas que les permitan organizar mejor sus servicios, acceder al historial técnico y mejorar sus tiempos de respuesta.

---

# Capítulo II: Requirements Elicitation & Analysis

## 2.1 Competidores

| Competidor | Descripción |
| :--- | :--- |
| **Copeland** | Empresa reconocida en refrigeración comercial e industrial. Combina hardware, sensores y plataformas digitales para monitorear equipos a distancia, optimizar el consumo energético y anticipar fallas. Orientada a grandes empresas. |
| **Monnit** | Soluciones IoT simples y accesibles mediante sensores inalámbricos para monitorear temperatura y humedad en tiempo real. Atractiva para pequeñas y medianas empresas por su facilidad de uso. |
| **ELPRO** | Orientado a sectores exigentes como el farmacéutico y laboratorios. Destaca por su alta precisión y cumplimiento de normativas estrictas en la cadena de frío. |

### 2.1.1 Análisis Competitivo

<table>
  <tr>
    <th colspan="2">Competitive Analysis Landscape</th>
    <th>Frigora</th>
    <th>Copeland</th>
    <th>Monnit</th>
    <th>ELPRO</th>
  </tr>
  <tr>
    <td rowspan="2"><strong>Perfil</strong></td>
    <td>Overview</td>
    <td>Plataforma que simplifica la gestión de refrigeración: monitoreo en tiempo real y contacto con técnicos.</td>
    <td>Soluciones completas para grandes sistemas de refrigeración con enfoque en eficiencia y control.</td>
    <td>Sensores y plataforma sencilla para monitoreo ambiental en tiempo real.</td>
    <td>Soluciones de monitoreo altamente precisas para entornos críticos.</td>
  </tr>
  <tr>
    <td>Ventaja competitiva</td>
    <td>Integra monitoreo, gestión y resolución de problemas con técnicos en un solo lugar.</td>
    <td>Alta capacidad tecnológica y experiencia industrial.</td>
    <td>Fácil de instalar, usar y mantener.</td>
    <td>Alto nivel de confiabilidad y cumplimiento de estándares.</td>
  </tr>
  <tr>
    <td rowspan="2"><strong>Perfil de Marketing</strong></td>
    <td>Mercado Objetivo</td>
    <td>Restaurantes, minimarkets, farmacias y técnicos independientes.</td>
    <td>Grandes empresas y cadenas comerciales.</td>
    <td>Pequeñas y medianas empresas.</td>
    <td>Empresas farmacéuticas y laboratorios.</td>
  </tr>
  <tr>
    <td>Estrategias de Marketing</td>
    <td>Redes sociales, demostraciones gratuitas y alianzas locales.</td>
    <td>Estrategias B2B y relaciones con grandes industrias.</td>
    <td>Venta directa online.</td>
    <td>Ferias y certificaciones.</td>
  </tr>
  <tr>
    <td rowspan="3"><strong>Perfil de Producto</strong></td>
    <td>Productos & Servicios</td>
    <td>Monitoreo en tiempo real, alertas, historial de equipos y conexión con técnicos.</td>
    <td>Sistemas avanzados hardware + software para control de refrigeración.</td>
    <td>Sensores IoT + plataforma de monitoreo en la nube.</td>
    <td>Equipos y software para monitoreo con alta precisión.</td>
  </tr>
  <tr>
    <td>Precios & Costos</td>
    <td>Modelo accesible con versión gratuita y pagos según uso.</td>
    <td>Soluciones costosas para grandes empresas.</td>
    <td>Suscripciones económicas.</td>
    <td>Costos altos por especialización.</td>
  </tr>
  <tr>
    <td>Canales de distribución</td>
    <td>Plataforma web y aplicación móvil.</td>
    <td>Soluciones empresariales y plataformas digitales.</td>
    <td>Web y app móvil.</td>
    <td>Web y app móvil.</td>
  </tr>
  <tr>
    <td rowspan="4"><strong>Análisis SWOT</strong></td>
    <td>Fortalezas</td>
    <td>Plataforma completa y fácil de entender.</td>
    <td>Tecnología avanzada y gran experiencia.</td>
    <td>Bajo costo y facilidad de uso.</td>
    <td>Alta precisión y confiabilidad.</td>
  </tr>
  <tr>
    <td>Debilidades</td>
    <td>Depende de la adopción de los usuarios.</td>
    <td>Complejo y costoso para muchos negocios.</td>
    <td>Menor cantidad de funcionalidades avanzadas.</td>
    <td>Enfocado a un nicho específico.</td>
  </tr>
  <tr>
    <td>Oportunidades</td>
    <td>Crecimiento de la digitalización e IoT en negocios.</td>
    <td>Expansión en más industrias.</td>
    <td>Aumento de adopción de IoT.</td>
    <td>Mayor regulación en cadena de frío.</td>
  </tr>
  <tr>
    <td>Amenazas</td>
    <td>Competencia de soluciones ya posicionadas.</td>
    <td>Nuevas startups más flexibles.</td>
    <td>Competidores con más funciones.</td>
    <td>Alternativas más económicas.</td>
  </tr>
</table>

*Objetivo del análisis: Entender mejor el mercado, comparar lo que ofrecen otras soluciones y encontrar oportunidades para que Frigora se diferencie y aporte mayor valor.*

### 2.1.2 Estrategias y Tácticas frente a Competidores

**1. Diferenciación**
- **Solución integral:** Frigora integra monitoreo, gestión y resolución de problemas en un mismo lugar, permitiendo no solo detectar fallas sino actuar rápidamente.
- **Trazabilidad completa:** Cada equipo cuenta con un historial claro de uso, fallas y mantenimientos para mejorar la toma de decisiones.
- **Interfaz intuitiva:** Diseñada para ser simple incluso para usuarios sin experiencia tecnológica.

**2. Marketing**
- Marketing digital y demostraciones gratuitas para llegar a negocios sin compromiso inicial.
- Contenido educativo sobre la importancia del monitoreo preventivo.
- Beneficios para usuarios recurrentes como estrategia de fidelización.

**3. Precios**
- Modelo Freemium con versión gratuita para facilitar la adopción inicial.
- Pagos según uso para reducir el riesgo y facilitar la decisión de compra.

**4. Expansión**
- Inicio en Lima con expansión progresiva a otras ciudades.
- Alianzas con técnicos y proveedores locales para fortalecer la red de servicios.

---

## 2.2 Entrevistas

### 2.2.1 Diseño de Entrevistas

**Preguntas — Segmento 1: Negocios con equipos de refrigeración**

1. ¿Qué tipo de equipos de refrigeración usas en tu negocio?
2. ¿Con qué frecuencia sueles tener problemas con estos equipos?
3. Cuando ocurre una falla, ¿qué es lo primero que haces?
4. ¿Te resulta difícil encontrar un técnico confiable cuando lo necesitas?
5. ¿Qué tanto te afecta una falla en tus equipos (pérdidas, retrasos)?
6. ¿Sueles hacer mantenimiento preventivo o solo cuando algo falla?
7. ¿Cómo llevas el control del mantenimiento de tus equipos?
8. ¿Te gustaría poder monitorear tus equipos o recibir alertas antes de que fallen?
9. ¿Qué te gustaría que tenga una herramienta que te ayude con esto?
10. ¿Pagarías por una solución que te ayude a evitar fallas? ¿Qué precio te parecería razonable?

**Preguntas — Segmento 2: Empresas de mantenimiento**

1. ¿Qué tipo de trabajos técnicos realizas con mayor frecuencia?
2. ¿Cómo sueles conseguir nuevos clientes actualmente?
3. ¿Qué es lo más complicado de gestionar tu trabajo día a día?
4. ¿Cómo organizas tus citas o servicios?
5. ¿Prefieres hacer mantenimiento preventivo o correctivo? ¿Por qué?
6. ¿Qué problemas sueles tener con los clientes?
7. ¿Te gustaría recibir solicitudes de trabajo técnico de forma más organizada?
8. ¿Qué herramientas usas actualmente para tu trabajo?
9. ¿Te ayudaría tener información previa del equipo antes de atender un servicio?
10. ¿Usarías una plataforma que te conecte con más clientes? ¿Qué tendría que tener para convencerte?

---

### 2.2.2 Registro de Entrevistas

#### Segmento #1: Negocios con equipos de refrigeración

**Entrevista 1**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Mauricio Mego |
| **Edad** | 24 años |
| **Distrito** | Magdalena del Mar |
| **Duración** | 3:54 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQCD75JaCB67Rqbnmgayr_P2AUStbuDTZL4pS3Bs8Pi0i7U?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jroC0y`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQCD75JaCB67Rqbnmgayr_P2AUStbuDTZL4pS3Bs8Pi0i7U?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=jroC0y) |

<div align="center">
<img src="assets/chapter02/entrevista-segmento1.png" alt="Entrevista 1 - Segmento 1" width="600">
</div>

**Resumen:** Mauricio administra un negocio de alimentos junto a su padre, donde almacenan carnes, pescados y otros productos que requieren refrigeración. Sufrió una pérdida considerable por una falla causada por falta de mantenimiento. Actualmente revisa personalmente los equipos cada semana y contacta a un técnico externo cuando detecta problemas. Considera muy útil contar con alertas automáticas y estaría dispuesto a adquirir una aplicación como Frigora.

---

**Entrevista 2**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Luis Tufiño |
| **Edad** | 23 años |
| **Distrito** | Callao |
| **Duración** | 4:56 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQDZkODby7uhQan7j_z8SCM2ATeyic0cs-MYQQtCmIvQo_g?e=sTADdU`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQDZkODby7uhQan7j_z8SCM2ATeyic0cs-MYQQtCmIvQo_g?e=sTADdU) |

<div align="center">
<img src="assets/chapter02/EntrevistaLuis.png" alt="Entrevista 2 - Segmento 1" width="600">
</div>

**Resumen:** Luis Tufiño es técnico independiente en refrigeración comercial que atiende bodegas, cafeterías y minimarkets. Consigue clientes por Facebook, WhatsApp y recomendaciones, pero sin herramienta formal. Maneja sus citas desde el celular, lo que genera cruces de horario. Considera útil una plataforma que le permita recibir solicitudes ordenadas, ver la ubicación del cliente y conocer el problema del equipo de antemano.

---

**Entrevista 3**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Yañez Santos, Leo Giovany |
| **Edad** | 23 años |
| **Distrito** | San Miguel |
| **Duración** | 3:00 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQC_otKeZKFGSKvVxXwwDgeYAQsNe01VMeNUPILFlSE3bWM?e=E1fSXe`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQC_otKeZKFGSKvVxXwwDgeYAQsNe01VMeNUPILFlSE3bWM?e=E1fSXe) |

<div align="center">
<img src="assets/chapter02/EntrevistaLeo.png" alt="Entrevista 3 - Segmento 1" width="600">
</div>

**Resumen:** Leo Giovany es técnico independiente que atiende restaurantes y minimarkets, realizando principalmente mantenimiento y reparaciones. Organiza sus servicios con WhatsApp y notas, lo que puede generar desorden. Su principal dificultad es coordinar trabajos y optimizar el tiempo. Considera útil una plataforma que le permita organizar solicitudes y acceder a más oportunidades de trabajo.

---

#### Segmento #2: Técnicos y Empresas de Mantenimiento

**Entrevista 1**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Rodrigo Miraval |
| **Edad** | 23 años |
| **Distrito** | San Miguel |
| **Duración** | 6:06 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQCFgFrdwoegSLowSXkH1f6lAZwWJrUrzUCI62S3ebngTik?e=9m4dHD`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQCFgFrdwoegSLowSXkH1f6lAZwWJrUrzUCI62S3ebngTik?e=9m4dHD) |

<div align="center">
<img src="assets/chapter04/SSRodrigo.png" alt="Entrevista 1 - Segmento 2" width="600">
</div>

**Resumen:** Rodrigo lleva más de un año como técnico de mantenimiento de equipos. Revisa personalmente el estado de los equipos cada semana y considera que lo más difícil es el mantenimiento completo cuando no hubo prevención adecuada. Estaría dispuesto a adquirir Frigora, ya que mejoraría su alcance de clientes y le permitiría analizar constantemente los equipos en etapa preventiva.

---

**Entrevista 2**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Mark Josue Febres Reategui |
| **Edad** | 23 años |
| **Distrito** | San Miguel |
| **Duración** | 3:33 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321281_upc_edu_pe/IQAQ6wZvP8AVSZd18on9ueNJAUNs6rvILt1vcYaPbctgJUA?e=1bQxpw`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321281_upc_edu_pe/IQAQ6wZvP8AVSZd18on9ueNJAUNs6rvILt1vcYaPbctgJUA?e=1bQxpw) |

<div align="center">
<img src="assets/chapter02/entrevista2-segmento2.png" alt="Entrevista 2 - Segmento 2" width="600">
</div>

**Resumen:** Mark lidera un equipo de técnicos y se encarga de la captación de clientes y la logística operativa. La entrevista revela una dependencia crítica de procesos manuales y falta de información técnica previa al servicio. Existe alta disposición para adoptar Frigora, valorando especialmente la centralización de órdenes de trabajo y el acceso a datos históricos del equipo como factores clave para transicionar de un modelo reactivo a uno preventivo.

---

**Entrevista 3**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Alvaro Pinto |
| **Edad** | 27 años |
| **Distrito** | Lima |
| **Duración** | 4:39 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202221632_upc_edu_pe/IQDLCyieBm7QQbTmgm29OOXnAXAevqOoyC-D_P3kS7gz0QU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=0e3js6`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202221632_upc_edu_pe/IQDLCyieBm7QQbTmgm29OOXnAXAevqOoyC-D_P3kS7gz0QU?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=0e3js6) |

<div align="center">
<img src="assets/chapter02/entrevista3-segmento2.png" alt="Entrevista 3 - Segmento 2" width="600">
</div>

**Resumen:** Álvaro Pinto es técnico de mantenimiento de equipos de refrigeración con clientes regulares establecidos. Invierte mucho tiempo en visitas presenciales rutinarias para verificar el funcionamiento de equipos. La parte más desgastante ocurre con fallas imprevistas, ya que llegar "a ciegas" a un equipo descompuesto retrasa enormemente el diagnóstico. Estaría muy interesado en usar Frigora para conocer las fallas de antemano y ampliar su capacidad operativa.

---

### 2.2.3 Análisis de Entrevistas

**Segmento #1: Negocios con equipos de refrigeración**

Estos negocios no cuentan con herramientas tecnológicas para el monitoreo de sus equipos y actúan de manera reactiva ante fallas. Esto genera pérdidas económicas, interrupciones en el servicio y, en algunos casos, riesgos sanitarios. El mantenimiento es informal, no existe control adecuado del estado de los equipos y hay dificultad para encontrar técnicos confiables rápidamente.

**Segmento #2: Técnicos y empresas de mantenimiento**

Consiguen clientes principalmente a través de redes sociales y recomendaciones informales. Organizan sus servicios de manera manual, lo que genera desorden, pérdida de tiempo y dificultades para coordinar múltiples trabajos. Carecen de información previa sobre los equipos, lo que afecta su eficiencia. Existe una necesidad clara de herramientas que les permitan organizar mejor su trabajo y acceder a más oportunidades de forma estructurada.

---

## 2.3 Needfinding

### 2.3.1 User Personas

**Segmento #1: Negocios con equipos de refrigeración**

<div align="center">
<img src="assets/chapter02/UserPersona-Segmento1.png" alt="User Persona - Segmento 1" style="max-width: 90%;">
</div>

**Segmento #2: Empresas de mantenimiento**

<div align="center">
<img src="assets/chapter02/UserPersona-Segmento2.png" alt="User Persona - Segmento 2" style="max-width: 90%;">
</div>

### 2.3.2 User Task Matrix

Las tareas fueron identificadas a partir del análisis cualitativo de entrevistas y evaluadas según frecuencia e importancia para cada perfil: **Renato** (Segmento 1: negocios de refrigeración) y **André** (Segmento 2: empresas de mantenimiento).

| Tarea | Renato — Frecuencia | Renato — Importancia | André — Frecuencia | André — Importancia |
| :--- | :---: | :---: | :---: | :---: |
| Revisar estado de los equipos de refrigeración | Alta | Alta | Media | Alta |
| Recibir alertas de fallas o anomalías | Alta | Alta | Alta | Alta |
| Contactar a un técnico para mantenimiento | Media | Alta | — | — |
| Programar mantenimiento preventivo | Media | Alta | Alta | Alta |
| Revisar historial de mantenimiento | Media | Media | Alta | Alta |
| Registrar servicios realizados | — | — | Alta | Alta |
| Organizar agenda de servicios técnicos | — | — | Alta | Alta |
| Recibir solicitudes de nuevos trabajos | — | — | Alta | Alta |
| Evaluar estado del equipo antes del servicio | Baja | Media | Alta | Alta |
| Monitorear múltiples equipos desde una plataforma | Alta | Alta | Media | Alta |
| Calificar el servicio recibido / realizado | Baja | Media | Media | Media |

### 2.3.3 User Journey Mapping

**Segmento #1: Negocios con equipos de refrigeración**

<div align="center">
<img src="assets/chapter02/UserJourneyMapping-Segmento1.png" alt="User Journey Mapping - Segmento 1" style="max-width: 90%;">
</div>

**Segmento #2: Técnicos y empresas de mantenimiento**

<div align="center">
<img src="assets/chapter02/UserJourneyMapping-Segmento2.png" alt="User Journey Mapping - Segmento 2" style="max-width: 90%;">
</div>

### 2.3.4 Empathy Mapping

**Segmento #1: Negocios con equipos de refrigeración**

<div align="center">
<img src="assets/chapter02/EmpathyMap-Segmento1.png" alt="Empathy Map - Segmento 1" style="max-width: 90%;">
</div>

**Segmento #2: Empresas de mantenimiento**

<div align="center">
<img src="assets/chapter02/EmpathyMap-Segmento2.png" alt="Empathy Map - Segmento 2" style="max-width: 90%;">
</div>

## 2.4 Big Picture Event Storming

Se utilizaron post-its en LucidChart para mapear los eventos significativos del flujo operativo actual, desde la detección de fallas hasta el seguimiento post-servicio, identificando procesos clave, actores involucrados y oportunidades de mejora.

<div align="center">
<img src="assets/chapter02/BigPictureEventStorming.jpg" alt="Big Picture Event Storming" style="max-width: 90%;">
</div>

## 2.5 Ubiquitous Language

| Término | Definición |
| :--- | :--- |
| **User Profile** | Perfil del usuario dentro de la plataforma. |
| **Smart Dashboard** | Interfaz central donde los usuarios monitorean equipos, reciben alertas y gestionan servicios. |
| **Performance Report** | Informe técnico con historial de uso, consumo energético, temperatura y fallas de cada equipo. |
| **Maintenance Schedule** | Calendario para programar mantenimientos preventivos o correctivos. |
| **Failure Alert** | Notificación automática ante anomalías críticas como sobrecalentamiento o cortes de energía. |
| **Equipment Inventory** | Registro de todos los equipos con sus datos técnicos y ubicación. |
| **Service Provider** | Técnico o empresa que brinda mantenimiento, instalación o reparación de equipos. |
| **Technical History** | Registro detallado de todas las intervenciones realizadas a un equipo. |
| **Work Order** | Documento digital con las tareas asignadas a un técnico para una visita de servicio. |
| **Service Coordination** | Proceso de conexión entre clientes y proveedores según disponibilidad y necesidad. |
| **Real-Time Monitoring** | Supervisión constante del estado operativo del equipo (temperatura, consumo, uso). |
| **Cold Equipment** | Unidad de refrigeración para conservar productos: congeladoras, cámaras, vitrinas. |
| **Preventive Maintenance** | Servicio planificado para evitar fallas y extender la vida útil del equipo. |
| **Corrective Maintenance** | Servicio realizado para solucionar una falla existente en un equipo. |
| **Energy Consumption** | Registro del uso eléctrico de los equipos para detectar anomalías y optimizar recursos. |
| **Client Portfolio** | Lista de negocios atendidos por un proveedor, con sus datos y equipos registrados. |
| **Service Zone** | Área donde un proveedor puede atender equipos con rapidez y eficiencia. |
| **Notification** | Mensajes enviados automáticamente sobre mantenimientos, fallas o cambios importantes. |
| **Automatic Report Generation** | Función que crea informes técnicos sin intervención manual. |

---

# Capítulo III: Requirements Specification

## 3.1 To-Be Scenario Mapping

**Segmento #1: Negocios con equipos de refrigeración**

<div align="center">
<img src="assets/chapter04/seg1tobe.png" alt="To-Be Scenario Mapping - Segmento 1" style="max-width: 95%;">
<p><em>Figura 1: To-Be Scenario Mapping — Negocios con equipos de refrigeración.</em></p>
</div>

**Segmento #2: Técnicos y empresas de mantenimiento**

<div align="center">
<img src="assets/chapter03/To Be Scenario Mapping Segmento 2 - Técnicos y empresas de mantenimiento.png" alt="To-Be Scenario Mapping - Segmento 2" style="max-width: 95%;">
<p><em>Figura 2: To-Be Scenario Mapping — Técnicos y empresas de mantenimiento.</em></p>
</div>

## 3.2 User Stories

### Épicas del Sistema

| ID | Título | Descripción |
| :---: | :--- | :--- |
| EP-01 | Gestión de Cuentas de Usuario | Todo lo necesario para que los usuarios puedan crear, acceder y administrar sus perfiles de forma segura. |
| EP-02 | Gestión y Monitoreo de Equipos | Funcionalidad para que los clientes agreguen, editen y monitoreen sus equipos de refrigeración. |
| EP-03 | Proceso de Solicitudes de Servicio | Ciclo completo de las solicitudes de servicio, desde la solicitud hasta el seguimiento post-servicio. |
| EP-04 | Análisis e Informes de Datos | Generación de reportes sobre rendimiento de equipos, consumo energético y eficiencia de servicios. |
| EP-05 | Sistema de Alertas y Notificaciones | Sistema de alertas automáticas a clientes y empresarios sobre fallas, mantenimientos y progreso de servicios. |
| EP-06 | Página de Aterrizaje y Experiencia Inicial | Landing page que comunica la propuesta de valor y facilita el primer contacto con el equipo comercial. |

### User Stories

| ID | Título | Descripción | Criterios de Aceptación | Epic |
| :--- | :--- | :--- | :--- | :---: |
| **US-01** | Registro de usuario | Como nuevo usuario, quiero registrarme en la plataforma para acceder a ella y empezar a gestionar mis equipos. | **E1 — Éxito:** Dado que el usuario completa el formulario con datos correctos, cuando envía el registro, entonces la cuenta es creada exitosamente.<br>**E2 — Email duplicado:** Dado que el usuario ingresa un email ya registrado, cuando envía el formulario, entonces el sistema muestra un mensaje de error. | EP-01 |
| **US-02** | Inicio de sesión | Como usuario, quiero iniciar sesión en mi cuenta para utilizar sus funcionalidades. | **E1 — Éxito:** Dado que el usuario tiene una cuenta activa e ingresa datos correctos, cuando inicia sesión, entonces accede al panel principal.<br>**E2 — Error:** Dado que el usuario ingresa datos incorrectos, cuando intenta acceder, entonces el sistema muestra un mensaje de error. | EP-01 |
| **US-03** | Gestionar equipos de refrigeración | Como cliente, quiero gestionar mis equipos de refrigeración para mantener un registro y control detallado de cada uno. | **E1 — Registro:** Dado que el usuario ingresa los datos del equipo, cuando los guarda, entonces el equipo se registra correctamente.<br>**E2 — Actualización:** Dado que el usuario modifica los datos de un equipo, cuando guarda los cambios, entonces la información se actualiza correctamente. | EP-02 |
| **US-04** | Recibir notificaciones de estado del equipo | Como cliente, quiero recibir notificaciones automáticas sobre el estado de mis equipos para tomar acciones rápidas ante fallas o mantenimientos próximos. | **E1 — Falla:** Dado que el sistema detecta una falla en el equipo del usuario, cuando se procesa la alerta, entonces el cliente recibe una notificación inmediata.<br>**E2 — Preventivo:** Dado que el usuario tiene un mantenimiento próximo programado, cuando se aproxima la fecha, entonces el cliente es notificado con antelación. | EP-05 |
| **US-05** | Analizar consumo energético | Como cliente, quiero ver y comparar el consumo energético de mis equipos para evaluar su eficiencia. | **E1 — Individual:** Dado que el usuario tiene equipos registrados, cuando solicita los datos de consumo, entonces el sistema muestra un informe detallado.<br>**E2 — Comparativo:** Dado que el usuario selecciona múltiples equipos, cuando solicita la comparación, entonces el sistema genera una vista comparativa. | EP-04 |
| **US-06** | Solicitar servicios de mantenimiento | Como cliente, quiero solicitar servicios de mantenimiento y reparación para recibir atención oportuna con confirmación del servicio. | **E1 — Solicitud:** Dado que el usuario requiere un servicio y lo detalla en el sistema, cuando lo envía, entonces la solicitud se registra y se notifica al equipo.<br>**E2 — Confirmación:** Dado que el usuario envió una solicitud, cuando el sistema la procesa, entonces el cliente recibe confirmación con los detalles del servicio. | EP-03 |
| **US-07** | Seguimiento del progreso del servicio | Como cliente, quiero hacer seguimiento al avance de mi servicio para saber en qué etapa se encuentra. | **E1 — Visualización:** Dado que el usuario tiene una solicitud activa, cuando accede al sistema, entonces se presenta el estado actualizado del servicio.<br>**E2 — Actualización:** Dado que el usuario espera una actualización de estado, cuando ésta ocurre, entonces el sistema lo refleja en tiempo real. | EP-03 |
| **US-08** | Ver reporte del servicio realizado | Como cliente, quiero ver el reporte detallado de un servicio completado para conocer qué intervenciones se realizaron. | **E1 — Generación:** Dado que el usuario tiene un servicio completado, cuando lo consulta, entonces el sistema muestra un reporte detallado de las intervenciones.<br>**E2 — Envío:** Dado que el usuario tiene un reporte generado, cuando el sistema lo procesa, entonces lo envía automáticamente por correo electrónico. | EP-04 |
| **US-09** | Alertas sobre solicitudes de servicio | Como empresario, quiero recibir alertas cuando un cliente solicite un servicio para responder de manera oportuna. | **E1 — Solicitud recibida:** Dado que el cliente envía una solicitud de servicio, cuando el sistema la registra, entonces el empresario recibe una alerta.<br>**E2 — Preventivo:** Dado que el cliente solicita un mantenimiento preventivo, cuando se registra, entonces el empresario es alertado. | EP-05 |
| **US-10** | Ver historial de servicios | Como empresario, quiero consultar el historial de servicios por cliente y equipo para tener trazabilidad completa de las atenciones realizadas. | **E1 — Visualización:** Dado que el usuario empresario accede al historial, cuando lo consulta, entonces puede ver el historial completo de servicios.<br>**E2 — Filtrado:** Dado que el usuario aplica un filtro por cliente o equipo, cuando lo ejecuta, entonces el historial se actualiza con los resultados correspondientes. | EP-04 |
| **US-11** | Seguimiento a solicitudes de servicio | Como empresario, quiero hacer seguimiento detallado a las solicitudes asignadas a mis técnicos para controlar el avance de cada una. | **E1 — Ver estado:** Dado que el usuario empresario accede al sistema, cuando consulta las solicitudes, entonces puede ver el estado actualizado de cada una.<br>**E2 — Actualización:** Dado que el técnico actualiza una solicitud, cuando guarda los cambios, entonces el sistema muestra el nuevo estado en tiempo real. | EP-03 |
| **US-12** | Registrar y gestionar técnicos | Como empresario, quiero registrar técnicos para incluirlos en mi equipo de trabajo. | **E1 — Registro exitoso:** Dado que el usuario empresario ingresa los datos completos del técnico, cuando guarda el registro, entonces el técnico queda registrado correctamente.<br>**E2 — Datos incompletos:** Dado que el usuario deja campos obligatorios vacíos, cuando intenta guardar, entonces el sistema no permite la operación. | EP-01 |
| **US-13** | Consultar perfil de un técnico | Como empresario, quiero consultar el perfil de cada técnico para ver sus datos y métricas de rendimiento. | **E1 — Información completa:** Dado que el usuario empresario selecciona un técnico, cuando accede a su perfil, entonces puede visualizar sus datos y métricas de rendimiento.<br>**E2 — Sin evaluaciones:** Dado que el usuario consulta un técnico sin evaluaciones registradas, cuando accede a su perfil, entonces las métricas de rendimiento no son visibles. | EP-01 |
| **US-14** | Asignar técnicos a servicios | Como empresario, quiero asignar un técnico a una solicitud de servicio para garantizar su atención oportuna. | **E1 — Asignación:** Dado que el usuario empresario recibe una solicitud, cuando selecciona un técnico y confirma, entonces el técnico queda asignado al servicio.<br>**E2 — Notificación:** Dado que el usuario empresario confirma la asignación, cuando el sistema la procesa, entonces el técnico recibe una notificación con los detalles del servicio. | EP-03 |
| **US-15** | Reporte de desempeño de técnicos | Como empresario, quiero generar reportes de desempeño de mis técnicos para evaluar su productividad y calidad de servicio. | **E1 — Generación:** Dado que el usuario empresario solicita un reporte de desempeño, cuando el sistema lo procesa, entonces genera un informe detallado.<br>**E2 — Descarga:** Dado que el usuario tiene un reporte generado, cuando desea descargarlo, entonces el sistema permite descargarlo en formato PDF. | EP-04 |
| **US-16** | Configurar alertas de mantenimiento | Como empresario, quiero configurar alertas automáticas de mantenimiento preventivo para asegurar la atención oportuna de los equipos. | **E1 — Configuración:** Dado que el usuario empresario ingresa los parámetros de la alerta, cuando los guarda, entonces la alerta se configura correctamente en el sistema.<br>**E2 — Actualización:** Dado que el usuario desea modificar una alerta existente, cuando realiza los cambios, entonces la alerta queda actualizada. | EP-05 |
| **US-17** | Visualizar clientes y servicios asociados | Como empresario, quiero ver un listado de clientes con sus servicios asociados para organizar y planificar el trabajo del equipo. | **E1 — Acceso:** Dado que el usuario empresario accede a la funcionalidad, cuando la consulta, entonces puede visualizar el listado de clientes y sus servicios asociados.<br>**E2 — Filtrado:** Dado que el usuario aplica un filtro por estado, cuando lo ejecuta, entonces la lista se actualiza con los resultados correspondientes. | EP-04 |
| **US-18** | Visualizar equipos asignados a clientes | Como empresario, quiero visualizar los equipos entregados a cada cliente para darles seguimiento. | **E1 — Acceso:** Dado que el usuario empresario accede al listado de equipos, cuando lo consulta, entonces puede visualizarlos correctamente.<br>**E2 — Filtrado:** Dado que el usuario aplica filtros sobre el listado, cuando los ejecuta, entonces la lista muestra los resultados correspondientes. | EP-02 |
| **US-19** | Notificaciones de eventos importantes | Como cliente, quiero recibir notificaciones sobre eventos importantes de mi servicio para estar informado de cualquier cambio o complicación. | **E1 — Problema reportado:** Dado que el técnico reporta una complicación durante el servicio, cuando el sistema la registra, entonces el cliente recibe una notificación que requiere su atención.<br>**E2 — Progreso:** Dado que el servicio del cliente cambia de estado, cuando ocurre el cambio, entonces el sistema envía una notificación al cliente. | EP-05 |
| **US-20** | Visualizar la propuesta de valor | Como visitante, quiero conocer la propuesta de valor de la plataforma para evaluar si se ajusta a mis necesidades. | **E1 — Visible:** Dado que el visitante accede a la página principal, cuando la carga, entonces se presenta claramente la propuesta de valor.<br>**E2 — Orientada:** Dado que el visitante pertenece al sector, cuando navega la página, entonces encuentra conceptos de gestión inteligente relevantes para su negocio. | EP-06 |
| **US-21** | Explorar soluciones por rubro | Como visitante, quiero explorar las soluciones que ofrece la plataforma según mi tipo de negocio para identificar si cubre mis necesidades operativas. | **E1 — Refrigeración:** Dado que el visitante explora las soluciones disponibles, cuando navega la sección, entonces encuentra descripciones específicas para negocios de refrigeración.<br>**E2 — Mantenimiento:** Dado que el visitante explora las soluciones disponibles, cuando navega la sección, entonces encuentra información relevante para empresas de mantenimiento. | EP-06 |
| **US-22** | Comprender las funcionalidades clave | Como visitante, quiero entender las funcionalidades principales de la plataforma para evaluar si se adaptan a mi operación. | **E1 — Acceso:** Dado que el visitante revisa las características de la plataforma, cuando las consulta, entonces identifica las opciones clave disponibles.<br>**E2 — Valor:** Dado que el visitante lee las descripciones de cada función, cuando las analiza, entonces comprende el beneficio que aporta cada una. | EP-06 |
| **US-23** | Conocer misión y visión | Como visitante, quiero conocer la misión y visión de la empresa para entender su enfoque y valores. | **E1 — Misión:** Dado que el visitante accede al contenido corporativo, cuando lo revisa, entonces encuentra una descripción clara de la misión de la empresa.<br>**E2 — Visión:** Dado que el visitante accede al contenido estratégico, cuando lo revisa, entonces encuentra la visión a futuro de la empresa. | EP-06 |
| **US-24** | Contactar con el equipo de ventas | Como visitante empresario, quiero contactar fácilmente con el equipo de ventas para obtener información y comenzar el proceso de contratación. | **E1 — Canal de contacto:** Dado que el visitante tiene interés en contactar, cuando busca la opción, entonces encuentra un canal de contacto claramente visible.<br>**E2 — Redirección:** Dado que el visitante selecciona la opción de contacto, cuando hace clic, entonces llega a un canal funcional como un formulario de contacto. | EP-06 |
| **US-25** | Acceder a la plataforma web (CTA) | Como usuario registrado, quiero encontrar un acceso directo a la plataforma desde la página de inicio para ingresar de forma rápida sin buscar la URL. | **E1 — Visibilidad:** Dado que el usuario visita la página principal, cuando la carga, entonces encuentra una opción clara de acceso a la plataforma.<br>**E2 — Redirección:** Dado que el usuario selecciona la opción de acceso, cuando hace clic, entonces es redirigido a la página de inicio de sesión. | EP-06 |
| **TS-01** | Alertas críticas vía API | Como desarrollador, quiero implementar un endpoint que exponga alertas críticas para activar notificaciones automáticas en el sistema. | **E1 — Éxito:** Dado que el sistema procesa una alerta crítica, cuando se ejecuta el endpoint, entonces se envía la notificación al usuario correspondiente.<br>**E2 — Deshabilitado:** Dado que el servicio de notificaciones está deshabilitado, cuando se intenta enviar, entonces no se envía la notificación y se registra en el historial. | EP-05 |
| **TS-02** | Solicitudes de mantenimiento (API) | Como desarrollador, quiero implementar un endpoint para crear solicitudes de mantenimiento para permitir su registro desde el frontend y otros servicios. | **E1 — Éxito:** Dado que el sistema recibe un POST a `/api/v1/service-requests` con datos válidos, cuando procesa la solicitud, entonces responde con código 201 y la solicitud queda guardada.<br>**E2 — Datos incompletos:** Dado que el sistema recibe la solicitud con un campo obligatorio faltante, cuando la procesa, entonces responde con código 400 e indica "Invalid data". | EP-03 |
| **TS-03** | Registro de intervenciones técnicas (API) | Como desarrollador, quiero implementar un endpoint para registrar intervenciones técnicas para almacenar el detalle de cada atención realizada. | **E1 — Éxito:** Dado que el sistema recibe un POST a `/api/v1/interventions` con datos válidos, cuando procesa la solicitud, entonces responde con código 201 y el registro queda almacenado.<br>**E2 — Técnico inexistente:** Dado que el sistema recibe la solicitud con un ID de técnico no existente, cuando la procesa, entonces responde con código 404 indicando "Technician not found". | EP-03 |
| **TS-04** | Registro de usuarios (API RESTful) | Como desarrollador, quiero exponer un endpoint para registrar nuevos usuarios para garantizar la validación de correo único y formato de contraseña desde el backend. | **E1 — Éxito:** Dado que el sistema recibe un POST a `/api/v1/users` con datos válidos, cuando procesa la solicitud, entonces responde con código 201 y el usuario queda registrado.<br>**E2 — Email duplicado:** Dado que el sistema recibe la solicitud con un correo ya registrado, cuando la procesa, entonces responde con código 400 indicando "Email already registered". | EP-01 |
| **TS-05** | Consulta de estado de servicios (API) | Como desarrollador, quiero crear un endpoint para consultar el estado de solicitudes en tiempo real para que el cliente pueda ver el avance actualizado de su servicio. | **E1 — Éxito:** Dado que el sistema recibe un GET a `/api/v1/requests/{id}` con un ID válido, cuando procesa la solicitud, entonces responde con código 200 y el estado actual del servicio.<br>**E2 — No encontrado:** Dado que el sistema recibe la solicitud con un ID inexistente, cuando la procesa, entonces responde con código 404 indicando "Request not found". | EP-03 |

## 3.3 Impact Mapping

**Segmento 1 — Negocios con equipos de refrigeración**

<div align="center">
<img src="assets/chapter04/Impact1.png" alt="Impact Mapping - Segmento 1" style="max-width: 80%;">
<p><em>Figura 1: Impact Mapping — Segmento 1.</em></p>
</div>

**Segmento 2 — Empresas de mantenimiento**

<div align="center">
<img src="assets/chapter04/Impact2.png" alt="Impact Mapping - Segmento 2" style="max-width: 80%;">
<p><em>Figura 2: Impact Mapping — Segmento 2.</em></p>
</div>

## 3.4 Product Backlog

Para la estimación de esfuerzo se usa la escala de Fibonacci (1, 2, 3, 5, 8) donde: **1** = tarea sencilla, **2** = complejidad moderada, **3** = mayor tiempo y esfuerzo, **5** = tarea compleja, **8** = alta complejidad con impacto en varias áreas.

[Ver tablero en Trello](https://trello.com/invite/b/69edc7316e396d01726fc9c1/ATTIc41d50b3166de3cd176b5b3c82be8c51F5BBF481/frigora-product-backlog)

<div align="center">
<img src="assets/chapter05/Product Backlog - Sprint1.png" alt="Product Backlog" style="max-width: 95%;">
<p><em>Figura 1: Product Backlog.</em></p>
</div>

| Orden | ID | Título | Story Points | Epic |
| :---: | :---: | :--- | :---: | :---: |
| 1 | US-20 | Visualizar la propuesta de valor principal | 1 | EP-06 |
| 2 | US-21 | Explorar soluciones específicas para mi rubro | 2 | EP-06 |
| 3 | US-22 | Comprender las funcionalidades clave | 2 | EP-06 |
| 4 | US-23 | Conocer la misión y visión | 1 | EP-06 |
| 5 | US-24 | Contactar con el equipo de ventas | 3 | EP-06 |
| 6 | US-25 | Acceder a la plataforma web (Call to Action) | 1 | EP-06 |
| 7 | TS-04 | Registrar nuevo usuario a través de API RESTful | 3 | EP-01 |
| 8 | US-01 | Registro de usuario | 3 | EP-01 |
| 9 | US-02 | Inicio de sesión | 2 | EP-01 |
| 10 | US-12 | Registrar y gestionar técnicos | 5 | EP-01 |
| 11 | US-13 | Consultar el perfil de un técnico | 2 | EP-01 |
| 12 | US-03 | Gestionar equipos de refrigeración | 5 | EP-02 |
| 13 | US-18 | Visualizar equipos asignados a clientes | 3 | EP-02 |
| 14 | TS-02 | Creación de solicitudes de mantenimiento (API) | 3 | EP-03 |
| 15 | US-06 | Solicitar y gestionar servicios de mantenimiento | 5 | EP-03 |
| 16 | TS-05 | Consulta de estado de servicios por API | 2 | EP-03 |
| 17 | US-09 | Recepción de alertas sobre solicitudes de servicio | 3 | EP-05 |
| 18 | US-14 | Asignar técnicos a servicios | 3 | EP-03 |
| 19 | TS-03 | Registro de intervenciones técnicas por API RESTful | 3 | EP-03 |
| 20 | US-07 | Dar seguimiento al progreso del servicio | 3 | EP-03 |
| 21 | US-11 | Realizar seguimiento a solicitudes de servicio | 3 | EP-03 |
| 22 | TS-01 | Gestión de alertas críticas vía API | 5 | EP-05 |
| 23 | US-19 | Recibir notificaciones de eventos importantes | 5 | EP-05 |
| 24 | US-04 | Recibir notificaciones de estado del equipo | 5 | EP-05 |
| 25 | US-16 | Configurar alertas de mantenimiento | 5 | EP-05 |
| 26 | US-08 | Ver reporte de servicio realizado | 3 | EP-04 |
| 27 | US-10 | Ver historial de servicios | 3 | EP-04 |
| 28 | US-17 | Visualizar clientes y servicios asociados | 3 | EP-04 |
| 29 | US-05 | Analizar el consumo energético de equipos | 8 | EP-04 |
| 30 | US-15 | Generar reporte de desempeño de técnicos | 8 | EP-04 |

---

# Capítulo IV: Product Design

## 4.1 Style Guidelines

### 4.1.1 General Style Guidelines

**Branding:** Frigora es una aplicación para empresas dependientes de sistemas de refrigeración. El objetivo es optimizar el proceso de supervisión y mantenimiento mediante tecnología IoT, aplicando buenas prácticas de UX/UI, pruebas gratuitas y actualizaciones continuas.

**Tipografía:** Se usa *Roboto Serif* por su claridad y legibilidad. Para el cuerpo de texto, *Inter 14px* con interlineado 1.5. Los tamaños se adaptan según jerarquía: títulos, subtítulos y párrafos.

**Colores:** Variantes de azul que conectan con el core de negocio (refrigeración/tecnología) y blanco para limpieza visual.

**Espaciado:**
- Entre secciones principales: mínimo 20px
- Entre encabezados y párrafos: 16px
- Entre párrafos consecutivos: 14px
- Botones e inputs: mínimo 10px entre elementos

**Tono de comunicación:**

| Dimensión | Nivel Adoptado |
| :--- | :--- |
| Divertido / Serio | Medio-Serio |
| Formal / Casual | Semi-Formal |
| Respetuoso / Irreverente | Muy Respetuoso |
| Entusiasta / Sereno | Sereno y Empático |

**Lenguaje:** Claro y directo, orientado a la acción, con terminología técnica consistente en alertas, reportes y documentación.

### 4.1.2 Web Style Guidelines

**Diseño Responsive** — Breakpoints:

| Dispositivo | Ancho mínimo | Ejemplo de uso |
| :--- | :---: | :--- |
| Mobile | ≥ 320px | Teléfonos |
| Tablet | ≥ 768px | iPad / tablets |
| Laptop | ≥ 1024px | Monitores y laptops |
| Widescreen | ≥ 1440px | Pantallas grandes o TV |

**Navegación:** Menú hamburguesa en dispositivos móviles; menú horizontal en pantallas mayores.

**Imágenes:** Formatos JPEG y PNG con compresión optimizada para mantener calidad sin afectar el rendimiento.

**Interacción:** Animaciones sutiles para mostrar imágenes y textos informativos según la interacción del usuario.

---

## 4.2 Information Architecture

### 4.2.1 Organization Systems

- **Jerárquica:** Dashboard principal — alertas críticas primero, luego indicadores de consumo y reportes históricos.
- **Secuencial:** Flujos de registro de equipos, creación de solicitudes y configuración de alertas.
- **Matricial:** Comparación de datos energéticos y desempeño de equipos.

### 4.2.2 Labeling Systems

**Principios:** Etiquetas de 1–3 palabras, descriptivas y directas; terminología consistente en toda la plataforma; lenguaje comprensible para empresarios y técnicos.

| Área | Etiquetas principales |
| :--- | :--- |
| Navegación global | Inicio, Equipos, Servicios, Reportes, Alertas, Administración, Ayuda |
| Landing Page | Bienvenido a Frigora, Soluciones, Funcionalidades, Casos de uso, Contáctanos |
| Gestión de equipos | Añadir equipo, Control remoto, Ajustar temperatura, Historial |
| Servicios | Solicitudes, Progreso, Confirmación, Historial |
| Reportes | Consumo, Comparar, Descargar, Desempeño técnico |
| Acciones | Crear cuenta, Iniciar sesión, Solicitar servicio, Ver reporte, Configurar alerta, Cerrar sesión |

### 4.2.3 SEO Tags and Meta Tags

**Landing Page**
- *Title:* Gestión inteligente de equipos de refrigeración
- *Meta Description:* Optimiza la gestión de tu cadena de frío con monitoreo en tiempo real, alertas automáticas y mantenimiento predictivo.
- *Keywords:* gestión de refrigeración, mantenimiento predictivo, monitoreo en tiempo real, cadena de frío, eficiencia energética

**Web Application**
- *Title:* Monitoreo y gestión de tus equipos de refrigeración
- *Meta Description:* Supervisa el estado de tus equipos, recibe alertas inmediatas y gestiona servicios de mantenimiento desde una sola plataforma.
- *Keywords:* monitoreo de refrigeración, gestión de equipos, alertas preventivas, mantenimiento en línea, reportes energéticos

### 4.2.4 Searching Systems

**Opciones de búsqueda:** Barra de búsqueda con resultados instantáneos, filtros por tipo de equipo, estado, fecha de última revisión y rango de consumo energético. Los resultados muestran nombre del equipo, estado, próxima fecha de mantenimiento y consumo, con opción de ordenación por relevancia o estado.

### 4.2.5 Navigation Systems

**Páginas principales:** Inicio (dashboard), Funcionalidades, Beneficios, Nosotros, Contacto.

---

## 4.3 Landing Page UI Design

### 4.3.1 Landing Page Wireframe

El wireframe define la estructura de cada sección: Header con logo y navegación, Hero con la propuesta de valor, Beneficios, Sobre Nosotros, Testimonios, Contacto (formulario) y Footer.

<div align="center">
<img src="assets/chapter04/Wireframelandig1.png" alt="Landing Page Wireframe - Parte 1" style="max-width: 90%;">
<img src="assets/chapter04/Wireframelandig2.png" alt="Landing Page Wireframe - Parte 2" style="max-width: 90%;">
</div>

### 4.3.2 Landing Page Mock-up

**Inicio**
<div align="center">
<img src="https://github.com/user-attachments/assets/75bbbb20-f061-4ea6-ac8c-ba1b5e70b7fa" alt="Mockup - Inicio" style="max-width: 90%;">
</div>

**Beneficios**
<div align="center">
<img src="https://github.com/user-attachments/assets/d93291ed-4b81-4a8d-a38a-8e83ba530120" alt="Mockup - Beneficios" style="max-width: 90%;">
</div>

**Sobre Nosotros**
<div align="center">
<img src="https://github.com/user-attachments/assets/d6735def-48f6-4bed-b896-3fe6843a318a" alt="Mockup - Sobre Nosotros" style="max-width: 90%;">
</div>

**Testimonios**
<div align="center">
<img src="https://github.com/user-attachments/assets/f1846c94-0bcf-4d50-9c08-148693d3cc2f" alt="Mockup - Testimonios" style="max-width: 90%;">
</div>

**Contacto**
<div align="center">
<img src="https://github.com/user-attachments/assets/585897a3-2efb-4703-9a18-f39c8c98f0dd" alt="Mockup - Contacto" style="max-width: 90%;">
</div>

---

## 4.4 Web Applications UX/UI Design

### 4.4.1 Web Applications Wireframes

**Login**
<div align="center">
<img src="https://github.com/user-attachments/assets/f8eba668-5b29-4317-92bd-d07570c62406" alt="Wireframe - Login" style="max-width: 85%;">
</div>

**Register**
<div align="center">
<img src="https://github.com/user-attachments/assets/638e27ee-ab38-4c2a-b0cb-565c98138df8" alt="Wireframe - Register" style="max-width: 85%;">
</div>

**Dashboard**
<div align="center">
<img src="https://github.com/user-attachments/assets/4add6717-b7ce-44db-ba1a-60bddde802f5" alt="Wireframe - Dashboard" style="max-width: 85%;">
</div>

**Sitios y Equipos**
<div align="center">
<img src="https://github.com/user-attachments/assets/f17af867-75d0-4660-95c3-9a97eac66073" alt="Wireframe - Sitios y Equipos" style="max-width: 85%;">
</div>

**Detalle de Equipos**
<div align="center">
<img src="https://github.com/user-attachments/assets/fa74beef-af78-462f-87a9-a087be9657c1" alt="Wireframe - Detalle de Equipos" style="max-width: 85%;">
</div>

**Alertas**
<div align="center">
<img src="https://github.com/user-attachments/assets/6dd4799b-df2d-46cb-b0c6-a48e536ef4ba" alt="Wireframe - Alertas" style="max-width: 85%;">
</div>

**Órdenes**
<div align="center">
<img src="https://github.com/user-attachments/assets/416899ae-b828-4542-9130-dea0a0bc9535" alt="Wireframe - Órdenes" style="max-width: 85%;">
</div>

**Reportes**
<div align="center">
<img src="https://github.com/user-attachments/assets/e6e5b72f-bd00-4726-b76d-3cf081dbfd58" alt="Wireframe - Reportes" style="max-width: 85%;">
</div>

**Administración**
<div align="center">
<img src="https://github.com/user-attachments/assets/269d62b2-093a-4afe-bc41-87ac98364dc5" alt="Wireframe - Administración" style="max-width: 85%;">
</div>

### 4.4.2 Web Applications Wireflow Diagrams

<div align="center">
<img src="https://github.com/user-attachments/assets/b8557b3c-47e5-4edd-9764-331ab5674a4b" alt="Wireflow Diagram" style="max-width: 95%;">
</div>

### 4.4.3 Web Applications Mock-ups

**Login**
<div align="center">
<img src="https://github.com/user-attachments/assets/8de5c432-6eb8-4df9-b261-7ce80cc77db1" alt="Mockup - Login" style="max-width: 90%;">
</div>

**Register**
<div align="center">
<img src="https://github.com/user-attachments/assets/80abd5c1-c90a-4b35-9882-868495678a23" alt="Mockup - Register" style="max-width: 90%;">
</div>

**Dashboard**
<div align="center">
<img src="https://github.com/user-attachments/assets/b3a42712-8580-4887-bfcb-36213852cb8b" alt="Mockup - Dashboard" style="max-width: 90%;">
</div>

**Sitios y Equipos**
<div align="center">
<img src="https://github.com/user-attachments/assets/8d014062-4521-41d8-93d6-18b7df16c8e4" alt="Mockup - Sitios y Equipos" style="max-width: 90%;">
</div>

**Detalle de Equipos**
<div align="center">
<img src="https://github.com/user-attachments/assets/2bfb1b77-2225-4266-9392-bfe2b8f67803" alt="Mockup - Detalle de Equipos" style="max-width: 90%;">
</div>

**Alertas**
<div align="center">
<img src="https://github.com/user-attachments/assets/fdb90bda-b9f1-434c-bf08-98a8f1da0903" alt="Mockup - Alertas" style="max-width: 90%;">
</div>

**Órdenes**
<div align="center">
<img src="https://github.com/user-attachments/assets/4bda5c9b-8a1b-4bee-bad3-8a9db3b1c7a4" alt="Mockup - Órdenes" style="max-width: 90%;">
</div>

**Reportes**
<div align="center">
<img src="https://github.com/user-attachments/assets/3ded40c0-93de-407d-8b8e-de7db880d80a" alt="Mockup - Reportes" style="max-width: 90%;">
</div>

**Administración**
<div align="center">
<img src="https://github.com/user-attachments/assets/9f813615-b974-4ee9-8584-ef3f3347fc6b" alt="Mockup - Administración" style="max-width: 90%;">
</div>

### 4.4.4 Web Applications User Flow Diagrams

<div align="center">
<img src="https://github.com/user-attachments/assets/eaa2feb0-4592-4554-921d-f47f8df9d228" alt="User Flow Diagram" style="max-width: 95%;">
</div>

## 4.5 Web Applications Prototyping

La sección de prototipado muestra un modelo interactivo y funcional que permite simular el flujo de usuario, la navegación y las interacciones principales, validando que el diseño sea intuitivo antes del desarrollo final.

**Repositorio:** https://github.com/ColdTech-Peru/Report

## 4.6 Domain-Driven Software Architecture

### 4.6.1 Design-Level EventStorming

**Segmento 1**
<div align="center">
<img src="assets/chapter04/even1.png" alt="Event Storming - Segmento 1" style="max-width: 90%;">
</div>

**Segmento 2**
<div align="center">
<img src="assets/chapter04/even2.png" alt="Event Storming - Segmento 2" style="max-width: 90%;">
</div>

[Ver en Miro](https://miro.com/welcomeonboard/QlBWbmlOR2twVG5zbldnNXk2TDBXMUV1bmxRbGN2clFSQUMyL0lwUGZZL0swRHNJSTBsYkVsTGV5S1Z3am5STkRiMlZ3YWVoRnN5M2svUUFlRm1kYjQ1SXZOeitBdHBNWnorSFlKY2VwWUlLMVIxZ3VPVm5oakdmd0hKT0FQWmtzVXVvMm53MW9OWFg1bkJoVXZxdFhRPT0hdjE=?share_link_id=723339078935)

### 4.6.2 Software Architecture Context Diagram

<div align="center">
<img src="assets/chapter04/FrigoraContextDiagram.png" alt="Context Diagram" style="max-width: 90%;">
<p><em>Figura 1: Context Diagram.</em></p>
</div>

### 4.6.3 Software Architecture Container Diagrams

<div align="center">
<img src="assets/chapter04/c4-container.png" alt="Container Diagram" style="max-width: 90%;">
<p><em>Figura 2: Container Diagrams.</em></p>
</div>

### 4.6.4 Software Architecture Components Diagrams

<div align="center">
<img src="assets/chapter04/ApiRestComponentDiagram.png" alt="API REST Component Diagram" style="max-width: 90%;">
<p><em>Figura 3: API REST Component Diagrams.</em></p>

<img src="assets/chapter04/AssetsManagementComponentDiagram.png" alt="Assets Management Component Diagram" style="max-width: 90%;">
<p><em>Figura 4: Assets Management BC Component Diagrams.</em></p>

<img src="assets/chapter04/DashboardComponentDiagram.png" alt="Dashboard Component Diagram" style="max-width: 90%;">
<p><em>Figura 5: Dashboard BC Component Diagrams.</em></p>

<img src="assets/chapter04/MonitoringComponentDiagram.png" alt="Monitoring Component Diagram" style="max-width: 90%;">
<p><em>Figura 6: Monitoring BC Component Diagrams.</em></p>

<img src="assets/chapter04/ReportingComponentDiagram.png" alt="Reporting Component Diagram" style="max-width: 90%;">
<p><em>Figura 7: Reporting BC Component Diagrams.</em></p>

<img src="assets/chapter04/ServicesComponentDiagram.png" alt="Services Component Diagram" style="max-width: 90%;">
<p><em>Figura 8: Services BC Component Diagrams.</em></p>

<img src="assets/chapter04/TechniciansComponentDiagram.png" alt="Technicians Component Diagram" style="max-width: 90%;">
<p><em>Figura 9: Technicians BC Component Diagrams.</em></p>
</div>

## 4.7 Software Object-Oriented Design

### 4.7.1 Class Diagrams

<div align="center">
<img src="assets/chapter04/frigora-class-diagram.png" alt="Class Diagram" style="max-width: 95%;">
<p><em>Figura 1: Class Diagram.</em></p>
</div>

## 4.8 Database Design

### 4.8.1 Database Diagrams

El diagrama ER representa las entidades principales del sistema Frigora, sus atributos y las relaciones entre usuarios, técnicos, negocios, equipos, métricas, alertas y órdenes.

<div align="center">
<img src="assets/chapter04/databasediagram.png" alt="Database Diagram" style="max-width: 95%;">
<p><em>Figura 1: Database Diagram.</em></p>
</div>

---

# Capítulo V: Product Implementation, Validation & Deployment

## 5.1 Software Configuration Management

### 5.1.1 Software Development Environment Configuration

**Project Management**

| Plataforma | Descripción | Enlace |
| :--- | :--- | :--- |
| Trello | Seguimiento detallado del progreso de tareas y designación de responsables. | https://trello.com |
| Discord / WhatsApp | Comunicación interna del equipo para reuniones y mensajes rápidos. | https://discord.com |
| GitHub | Organización centralizada del código fuente y control de versiones. | https://github.com |

**Requirement Management**

| Plataforma | Descripción | Enlace |
| :--- | :--- | :--- |
| UXPressia | Creación y validación de wireframes, mockups y prototipos interactivos. | https://uxpressia.com |
| Miro | Visualización y desarrollo de escenarios As-Is y To-Be. | https://miro.com |

**Product UX/UI Design**

| Plataforma | Descripción | Enlace |
| :--- | :--- | :--- |
| Figma | Herramienta principal para diseño colaborativo de wireframes, mockups y prototipos. | https://www.figma.com |

**Software Development**

| Tecnología | Descripción | Enlace |
| :--- | :--- | :--- |
| HTML | Define la estructura y contenido de la página web. | https://www.w3schools.com/html |
| CSS | Gestiona la presentación visual y el estilo. | https://www.w3schools.com/css |
| JavaScript | Añade interactividad y dinamismo. | https://www.w3schools.com/js |
| Visual Studio Code | IDE para escritura, edición y depuración de código. | https://code.visualstudio.com |
| JetBrains ToolBox | Gestión de IDEs: IntelliJ IDEA, WebStorm, Rider. | https://www.jetbrains.com/toolbox-app |

**Software Documentation**

| Plataforma | Descripción |
| :--- | :--- |
| GitHub | Gestión de la documentación en repositorios y organizaciones. |
| Markdown | Formato base para la presentación y documentación del proyecto. |

### 5.1.2 Source Code Management

Se utiliza la estrategia **GitHub Flow** con las siguientes ramas principales:

- **`main`:** Código de producción (CSS, imágenes, JavaScript e `index.html`). Siempre estable y listo para despliegue.
- **`gh-pages`:** Rama de despliegue automático en GitHub Pages.

**Convenciones de nomenclatura:**

| Tipo | Prefijo | Formato | Ejemplo |
| :--- | :--- | :--- | :--- |
| Característica | `feature/` | `feature/nombre-descriptivo` | `feature/login-ui` |
| Lanzamiento | `release/` | `release/x.y.z` | `release/1.0.0` |
| Corrección urgente | `hotfix/` | `hotfix/x.y.z-descripcion` | `hotfix/1.0.1-fix-login` |

**Repositorios:**
- Organización: https://github.com/ColdTech-Peru
- Landing Page: https://github.com/ColdTech-Peru/Landing-Page
- Informe: https://github.com/ColdTech-Peru/Report

### 5.1.3 Source Code Style Guide & Conventions

**Nomenclatura:**
- Variables y funciones JS: `camelCase` (ej. `myVariable`, `initializeVideos()`)
- Constantes JS: `SNAKE_CASE` (ej. `VIDEO_CONFIG`)
- Archivos: minúsculas con guiones (ej. `index.html`, `style.css`)

**HTML — Etiquetas utilizadas:** `<!DOCTYPE html>`, `<html>`, `<head>`, `<meta>`, `<title>`, `<link>`, `<body>`, `<header>`, `<nav>`, `<section>`, `<footer>`, y etiquetas semánticas complementarias (`<h1>`–`<h5>`, `<p>`, `<div>`, `<ul>`, `<li>`, `<a>`, `<img>`, `<button>`, `<script>`).

**CSS — Propiedades clave:** `width`, `height`, `padding`, `font-family`, `font-size`, `font-weight`, `font-style`, `text-align`, `color`, `background-color`.

### 5.1.4 Software Deployment Configuration

Para publicar en **GitHub Pages**:

1. Organizar archivos en la carpeta raíz (`index.html`, `styles.css`, `index.js`, imágenes en `assets/images/`).
2. Subir archivos al repositorio mediante commit.
3. Ir a **Settings → Pages**, seleccionar rama `main` y carpeta raíz `/root`.
4. GitHub Pages realiza el despliegue automático y genera una URL pública.

---

## 5.2 Landing Page, Services & Applications Implementation

### 5.2.1 Sprint 1

#### 5.2.1.1 Sprint Planning 1

| Campo | Detalle |
| :--- | :--- |
| **Fecha** | 2026-04-23 |
| **Hora** | 1:00 PM |
| **Lugar** | Presencial — UPC, sede San Miguel |
| **Preparado por** | Alejandro Galindo |
| **Asistentes** | Alejandro Galindo, Walter Fajardo, Leonardo Cumba, Joaquin Cuentas, Gabriel Perez |
| **Sprint 1 Goal** | Desarrollar la landing page garantizando adaptabilidad a distintos dispositivos, coherencia visual y soporte multilenguaje. El objetivo se valida cuando el usuario puede cambiar idioma fácilmente, navegar sin errores y verificar que los elementos gráficos y textuales estén correctamente alineados. |
| **Sprint 1 Velocity** | 15 |
| **Sum of Story Points** | 15 |

**Review Summary:** Se avanzó en la definición inicial de la plataforma y se establecieron lineamientos clave para el desarrollo de la landing page.

**Retrospective Summary:** El equipo compartió ideas sobre el rubro, segmentos objetivo, beneficios y funcionalidades principales. Las tareas se organizaron eficientemente con avances visibles en el informe y la landing page.

#### 5.2.1.2 Aspect Leaders and Collaborators

| Team Member | GitHub Username | Diseño visual y maquetación | Responsividad y pruebas | Implementación multilenguaje |
| :--- | :--- | :---: | :---: | :---: |
| Galindo Montero, Alejandro Manuel | AlejandroG12970 | C | L | L |
| Fajardo, Walter | walterfajardo | L | C | C |
| Cumba, Leonardo | LeonardoC72 | C | C | L |
| Cuentas, Joaquin | joaCUPE | C | L | C |
| Perez, Gabriel | Gabyoko | C | C | C |

*L = Leader, C = Collaborator*

#### 5.2.1.3 Sprint Backlog 1

[Ver tablero en Trello](https://trello.com/invite/b/69edc7316e396d01726fc9c1/ATTIfe4224969e7f89d8cf52d5f416485b4519519493/frigora-product-backlog)

<div align="center">
<img src="assets/chapter05/Product Backlog - Sprint1.png" alt="Sprint Backlog 1" style="max-width: 95%;">
<p><em>Figura 1: Sprint Backlog 1.</em></p>
</div>

| US ID | US Título | Task ID | Task Título | Descripción | Horas | Asignado | Estado |
| :---: | :--- | :---: | :--- | :--- | :---: | :--- | :---: |
| US-20 | Visualizar propuesta de valor | UT-01 | Crear sección "Hero" | Diseñar y añadir la sección Hero que comunique el monitoreo inteligente IoT. | 2 | Walter Fajardo | Done |
| US-21 | Explorar soluciones por rubro | UT-01 | Crear sección "Soluciones" | Redactar y maquetar tarjetas de soluciones para supermercados, laboratorios y sector alimentario. | 3 | Joaquin Cuentas | Done |
| US-22 | Comprender funcionalidades clave | UT-01 | Crear sección "Características" | Diseñar la sección con telemetría, alertas preventivas y control de temperatura. | 3 | Alejandro Galindo | Done |
| US-23 | Conocer misión y visión | UT-01 | Crear sección "Nosotros" | Añadir sección visual que refleje la misión y visión de la startup. | 1.5 | Gabriel Perez | Done |
| US-24 | Contactar equipo de ventas | UT-01 | Diseñar formulario de "Contacto" | Maquetar formulario con Nombre, RUC, Teléfono y Mensaje. | 2 | Leonardo Cumba | Done |
| US-24 | Contactar equipo de ventas | UT-02 | Definir flujo de validación | Prototipar mensajes de éxito/error al enviar el formulario. | 1.5 | Gabriel Perez | Done |
| US-25 | Acceder a la plataforma (CTA) | UT-01 | Crear Navbar y botón CTA | Añadir barra de navegación con botón "Ingresar" que redirija al Login. | 1 | Leonardo Cumba | Done |

#### 5.2.1.4 Development Evidence for Sprint Review

| Repositorio | Rama | Commit ID | Mensaje | Descripción |
| :--- | :--- | :---: | :--- | :--- |
| ColdTech-Peru/LandingPage | master | f331259 | feat: cambiar script.js a index.js | Renombramiento del archivo de scripts para cumplir convenciones del proyecto. |
| ColdTech-Peru/LandingPage | master | f57b84b | JS | Creación y vinculación del archivo de lógica JavaScript interactiva. |
| ColdTech-Peru/LandingPage | master | fdf1625 | feature: add images | Integración de recursos gráficos y activos visuales para la landing page. |
| ColdTech-Peru/LandingPage | master | 7e6df51 | feature: hero and benefit section update | Ajustes en el maquetado de la sección Hero y actualización de textos de beneficios. |
| ColdTech-Peru/LandingPage | master | c4d382c | feat: correct footer | Corrección de alineación y validación de enlaces en el pie de página. |
| ColdTech-Peru/LandingPage | master | 1c227de | feat: change footer | Reestructuración del diseño del footer para mejorar la experiencia de navegación. |
| ColdTech-Peru/LandingPage | master | 3e69af4 | feat: add style.css | Implementación de la hoja de estilos CSS inicial con identidad visual y tipografía. |
| ColdTech-Peru/LandingPage | master | 13d089c | html | Creación de la estructura semántica base del `index.html`. |
| ColdTech-Peru/LandingPage | master | 5b6714b | primer commit1 | Inicialización del repositorio y carga de archivos fundamentales. |

#### 5.2.1.5 Execution Evidence for Sprint Review

**Inicio — Sección Hero**
<div align="center">
<img src="assets/chapter05/Inicio.png" alt="Landing - Inicio" style="max-width: 90%;">
</div>

**Beneficios — Panel dinámico por segmento**
<div align="center">
<img src="assets/chapter05/Beneficios.png" alt="Landing - Beneficios" style="max-width: 90%;">
</div>

**Sobre Nosotros — Misión y visión**
<div align="center">
<img src="assets/chapter05/sobre nosotros.png" alt="Landing - Sobre Nosotros" style="max-width: 90%;">
</div>

**Testimonios — Casos de éxito**
<div align="center">
<img src="assets/chapter05/testimonios.png" alt="Landing - Testimonios" style="max-width: 90%;">
</div>

**Contacto — Formulario B2B**
<div align="center">
<img src="assets/chapter05/contactanos.png" alt="Landing - Contacto" style="max-width: 90%;">
</div>

#### 5.2.1.6 Services Documentation Evidence for Sprint Review

<div align="center">
<img src="assets/chapter05/5216.png" alt="Services Documentation" style="max-width: 90%;">
</div>

#### 5.2.1.7 Software Deployment Evidence for Sprint Review

Landing Page desplegada en GitHub Pages: **https://coldtech-peru.github.io/Landing-Page/**

<div align="center">

| Sección | Captura |
| :---: | :---: |
| Inicio | ![Inicio](assets/chapter05/Inicio.png) |
| Beneficios | ![Beneficios](assets/chapter05/Beneficios.png) |
| Sobre Nosotros | ![Sobre Nosotros](assets/chapter05/sobre%20nosotros.png) |
| Testimonios | ![Testimonios](assets/chapter05/testimonios.png) |
| Contacto | ![Contacto](assets/chapter05/contactanos.png) |

</div>

#### 5.2.1.8 Team Collaboration Insights during Sprint

<div align="center">
<img src="assets/chapter05/Team Collaboration Insights during Sprint - 1.png" alt="Collaboration Insights 1" style="max-width: 90%;">
<img src="assets/chapter05/Team Collaboration Insights during Sprint -2 .png" alt="Collaboration Insights 2" style="max-width: 90%;">
</div>

---

### 5.2.2. Sprint 2

#### 5.2.2.1.Sprint Planning 2.

| Sprint 2 | Sprint 2 |
|---|---|
| **Sprint Planning Background** |  |
| **Date** | 2026-05-07 |
| **Time** | 17:00 PM |
| **Location** | Via Discord |
| **Prepared By** | Alejandro Galindo |
| **Attendees to planning meeting** |   Galindo Montero, Alejandro Manuel  , Perez Tuesta,  Gabriel  ,  Fajardo Monrroy, Walter Luis  ,Cumba Rengifo, Leonardo Raul y    Cuentas Peña, Joaquin Alberto  |
| **Sprint 2 Review Summary** | En este sprint, nos enfocamos en desarrollar el front-end y en realizar la implementación inicial de la plataforma Frigora. Completamos las funciones principales de la página, ofreciendo a los usuarios una primera experiencia de navegación y exploración del servicio de refrigeración. El equipo cumplió con los objetivos de entrega dentro del plazo previsto, estableciendo además los cimientos de la interfaz gráfica para futuras iteraciones. |
| **Sprint 2 Retrospective Summary** | Durante el sprint, a pesar de estar enfocado en el desarrollo técnico, permitió identificar oportunidades para mejorar nuestra dinámica de trabajo en equipo. En la retrospectiva, se destacó la necesidad de ajustar la duración de las reuniones diarias, redistribuir las tareas de acuerdo con las especialidades del equipo e incorporar una planificación individual con hitos verificables. Estas medidas tienen como objetivo incrementar la eficiencia en las próximas iteraciones. |
| **Sprint Goal & User Stories**  
| **Sprint 2 Goal** | Nuestro enfoque de desarrollo se centra en la creación e implementación de la interfaz front-end de Frigora, con el objetivo de proporcionar una experiencia de navegación fluida e intuitiva, mostrar las principales funcionalidades de la plataforma y disponer de una página de inicio funcional que comunique de manera efectiva el valor diferencial del servicio. |
| **Sprint 2 Velocity** | 36 |
| **Sum of Story Points** | 51 |


#### 5.2.2.2 Aspect Leaders and Collaborators

Durante este segundo sprint, el equipo se enfocó principalmente en el desarrollo, mejora estructural y visual de las aplicaciones del Frontend, asegurando su correcto funcionamiento en distintos dispositivos (diseño responsive), la integración coherente de componentes visuales e interactivos, así como la implementación de funcionalidades dinámicas que mejoran la experiencia del usuario.

Con el objetivo de optimizar la organización y la colaboración del equipo, se elaboró la matriz de Liderazgo y Colaboración (LACX), la cual asigna responsabilidades y roles específicos a cada miembro del equipo en relación con los aspectos clave abordados durante el Sprint.

| Team Member <br> (Last Name, First Name) | Github Username | Implementacion de la gestión de equipos de refrigeracion (Frontend Applications) <br> Leader (L) / Collaborator (C) | Responsive y pruebas en distintos dispositivos <br> Leader (L) / Collaborator (C) | Despliegue de la aplicación web <br> Leader (L) / Collaborator (C) |
|---|---|---|---|---|
|Galindo Montero, Alejandro Manuel |AlejandroG12970 | L | L | L |
|Perez Tuesta,  Gabriel| Gabyoko | C | C | C |
|Fajardo Monrroy, Walter Luis  | WalterFajardo | C | C | C |
|Cumba Rengifo, Leonardo Raul  | LeonardoC72 | C | C | C |
|Cuentas Peña, Joaquin Alberto  | JoaCUPE | C | C | C |



#### 5.2.2.3.Sprint Backlog 2.
El objetivo principal de este Sprint es elaborar el Frontend de nuestra plataforma. Para ello, dividimos el desarrollo de esta según las User Stories pertenecientes a la Epic enfocada en la aplicacion web. La plataforma elegida para ser la herramienta de control de tareas fue Trello, el cuál se presenta una captura de pantalla de nuestro tablero y su enlace público.

<img width="1919" height="812" alt="Sprint2trello" src="https://github.com/user-attachments/assets/758e408f-6618-4f91-abef-eeeb5c8d3dab" />


Trello link: https://trello.com/invite/b/6a063f21d0fef018a6fdea7e/ATTI06db17776210086dc9611a5aebb7143cEB975F35/sprint-02

| User Story ID | User Story Título | Task ID | Task Título | Descripción | Estimación (Horas) | Asignado a | Estado (To do/ In-Process/ To-Review/ Done) |
| :---: | :--- | :---: | :--- | :--- | :---: | :--- | :---: |
| **US-01** | Registro de usuario | **UT-01** | Diseñar formulario de registro | Crear la interfaz de registro solicitando datos básicos del usuario y validaciones iniciales. | 3 | [Walter Fajardo] | To do |
| **US-02** | Inicio de sesión | **UT-01** | Implementar pantalla de login | Diseñar la vista de inicio de sesión con validación de credenciales y acceso a la plataforma. | 2 | [Leonardo Cumba] | To do |
| **US-03** | Gestionar equipos de refrigeración | **UT-01** | Crear módulo de gestión de equipos | Diseñar formularios y tablas para registrar, editar y visualizar equipos de refrigeración. | 4 | [Joaquin Cuentas] | To do |
| **US-05** | Analizar el consumo energético de equipos | **UT-01** | Diseñar dashboard energético | Crear gráficos y paneles visuales para comparar el consumo energético de equipos. | 5 | [Alejandro Galindo] | To do |
| **US-07** | Dar seguimiento al progreso del servicio | **UT-01** | Implementar vista de seguimiento | Diseñar una pantalla que permita visualizar el estado y progreso de los servicios técnicos. | 3 | [Gabriel Perez] | To do |
| **US-08** | Ver reporte de servicio realizado | **UT-01** | Crear vista de reporte técnico | Diseñar la interfaz para mostrar reportes detallados de servicios realizados. | 3 | [Walter Fajardo] | To do |
| **US-10** | Ver historial de servicios | **UT-01** | Implementar historial de servicios | Crear tabla o listado cronológico de servicios realizados por cliente o equipo. | 3 | [Leonardo Cumba] | To do |
| **US-12** | Registrar y gestionar técnicos | **UT-01** | Crear módulo de técnicos | Diseñar formularios y vistas para registrar, editar y administrar técnicos. | 4 | [Joaquin Cuentas] | To do |
| **US-13** | Consultar el perfil de un técnico | **UT-01** | Diseñar perfil de técnico | Implementar pantalla con información, métricas y desempeño del técnico. | 2 | [Alejandro Galindo] | To do |
| **US-17** | Visualizar clientes y servicios asociados | **UT-01** | Crear vista de clientes y servicios | Diseñar listado de clientes junto con sus servicios asociados y estado actual. | 3 | [Gabriel Perez] | To do |
| **US-18** | Visualizar equipos asignados a clientes | **UT-01** | Implementar listado de equipos asignados | Crear una vista donde se visualicen los equipos vinculados a cada cliente. | 3 | [Walter Fajardo] | To do |
| **US-25** | Acceder a la plataforma web (Call to Action) | **UT-01** | Crear Navbar y botón CTA | Añadir la barra de navegación superior con el botón "Ingresar" que redirija a la futura vista de Login. | 1 | [Leonardo Cumba] | Done |


#### 5.2.2.4. Development Evidence for Sprint Review

En este segundo Sprint hemos realizado la implementación del frontend de nuestra solución **Frigora**, desarrollada por la startup **ColdTech**. Durante esta entrega, el equipo se enfocó en construir las principales vistas de la aplicación, considerando el **Dashboard** como una vista global del sistema y el módulo de **Monitoring** como un bounded context independiente orientado al seguimiento de equipos, aparatos y alertas. La siguiente tabla muestra los commits realizados durante el desarrollo.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Committed on (Date) |
|---|---|---|---|---|---|
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(sites): add sites list view | Implemented the frontend view to display registered sites in the Frigora platform. | 03/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(sites): add site registration form | Created the frontend form for registering new sites in the system. | 04/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(services): add services list view | Developed the frontend screen to display available services and their basic information. | 05/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(services): add service creation form | Implemented the frontend form for creating new service records. | 06/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(services): add service detail view | Created the service detail screen to visualize service information in a structured way. | 07/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(monitoring): add equipment monitoring view | Implemented the frontend view to display monitored refrigeration equipment and device status. | 08/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(monitoring): add monitoring creation form | Created the frontend form to register new monitoring records for equipment tracking. | 09/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(monitoring): add monitoring detail view | Developed the detail screen to review monitoring data, device information and equipment status. | 10/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(alerts): add alerts view | Implemented the frontend view for displaying alerts generated from monitoring events. | 11/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(reports): add reports list view | Implemented the frontend screen to display generated reports in the platform. | 12/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(reports): add report creation form | Created the frontend form for registering new service or monitoring reports. | 13/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(reports): add report detail view | Developed the frontend detail view to show report information clearly. | 14/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | feat(dashboard): add global dashboard view | Implemented the global dashboard view to provide a general overview of the Frigora platform. | 15/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | chore(frontend): organize sprint review evidence | Added and organized frontend evidence images for the Sprint Review documentation. | 15/05/2026 |
| 1ASI0729-2610-ColdTech/Frigora-Frontend | develop | N/A | merge: integrate frontend sprint changes into develop | Final integration of the frontend views developed during the sprint. | 16/05/2026 |


#### 5.2.2.5. Execution Evidence for Sprint Review

En el Sprint 2 se desplegó la primera versión de la Web Application de Frigora, implementando funcionalidades esenciales como el dashboard del usuario, lugares, equipos que posee el usuario, las solicitudes de servicio de mantenimiento, las alertas y los reportes generados. Estas funcionalidades permiten a los usuarios hacer uso de herramientas que permitan mejorar la gestión de equipos de refrigeración para su posterior mantenimiento y seguimiento. A continuación, se presentan las evidencias:

Dashboard:

<div align="center">
  <img src="assets/chapter05/dashboard.png"
       alt="Dashboard view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Sites:

<div align="center">
  <img src="assets/chapter05/sitiosactualisados.png"
       alt="Sites list view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Sites created:

<div align="center">
  <img src="assets/chapter05/sitiosadd2.png"
       alt="Site creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Equipments:

<div align="center">
  <img src="assets/chapter05/monitoring.png"
       alt="Monitoring dashboard view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Equipments detail:

<div align="center">
  <img src="assets/chapter05/monitorningdetail.png"
       alt="Monitoring detail view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Equipments created:

<div align="center">
  <img src="assets/chapter05/monitoringadd.png"
       alt="Monitoring record creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Service Requests:

<div align="center">
  <img src="assets/chapter05/Services.png"
       alt="Services list view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Service Requests detail:

<div align="center">
  <img src="assets/chapter05/Servicesdetail.png"
       alt="Service detail view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Service Requests created:

<div align="center">
  <img src="assets/chapter05/ServicesADd.png"
       alt="Service creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Alerts:

<div align="center">
  <img src="assets/chapter05/Alerts.png"
       alt="Alerts list view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Reports:

<div align="center">
  <img src="assets/chapter05/Reports.png"
       alt="Reports list view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Reports detail:

<div align="center">
  <img src="assets/chapter05/ReportDetail.png"
       alt="Report detail view"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Reports created:

<div align="center">
  <img src="assets/chapter05/Reportadd.png"
       alt="Report creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


#### 5.2.2.6.Services Documentation Evidence for Sprint Review.

Durante este Sprint, nos enfocamos en documentar los servicios web (APIs) diseñados para Frigora utilizando OpenAPI. Cabe destacar que, para el backend, estamos usando un `db.json` (JSON Server) desplegado en Render. El objetivo fue asegurar que los endpoints relacionados con el alcance del Sprint estén correctamente descritos, incluyendo acciones soportadas, parámetros, sintaxis de las solicitudes y ejemplos de respuestas. Esta documentación facilita la futura integración con el frontend y servirá como referencia para mantenimiento.

 **Logros alcanzados en este Sprint**

* Definición de los principales endpoints del sistema.
* Especificación de métodos HTTP, ejemplos de request y response, y parámetros de entrada.
* Generación de la definición OpenAPI (a nivel de diseño) para los endpoints identificados.
* Preparación de ejemplos de uso de la API con datos de muestra para demostrar el comportamiento esperado.

**Endpoints documentados**

| Endpoints |
| :--- |
| `tenants` |
| `users` |
| `technicians` |
| `sites` |
| `equipments` |
| `sensors` |
| `readings` |
| `alerts` |
| `serviceRequests` |
| `reviews` |
| `notifications` |
| `logs` |
| `dashboard` |
| `system` |

<div align="center">
  <img src="assets/chapter05/dbjson-evidence.png"
       alt="Service creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link del Fake API desplegado en Render: https://fake-api-0233.onrender.com/

#### 5.2.2.7.Software Deployment Evidence for Sprint Review.

Durante este sprint se preparó el despliegue del frontend de Frigora en un entorno público, configurando la integración continua entre el repositorio de código y la plataforma de hosting.

**Actualización de la URL de la API**
Se actualizó la configuración del frontend para que dejara de consumir datos desde localhost y utilizara la URL pública del servidor backend desplegado en Render.

**Configuración en la plataforma de despliegue**
Se creó una cuenta en Vercel y se conectó el repositorio de GitHub del frontend. La plataforma detectó automáticamente que se trataba de una aplicación Angular y definió la configuración base de construcción.

**Variables de entorno para la API**
La URL de la API se configuró como una variable de entorno (secreto) en Vercel, evitando exponerla directamente en el código fuente. De esta forma, los cambios futuros en la URL pueden gestionarse desde la plataforma sin modificar el código.

**Despliegue continuo**
Con la configuración lista, se generó un despliegue público de la aplicación. Vercel habilitó el mecanismo de despliegue continuo, por lo que cada vez que se actualiza el código en GitHub, la aplicación se reconstruye y se publica automáticamente.

URL de la landing page (GitHub Pages): https://coldtech-peru.github.io/Landing-Page/
URL de la aplicación web (frontend): https://frigora-frontend.vercel.app/

**Evidencia de despliegue del Frontend en Vercel:**

<div align="center">
  <img src="assets/chapter05/vercel-evidence.png"
       alt="Service creation form"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

#### 5.2.2.8.Team Collaboration Insights during Sprint.

Insights del Landing Page:

<div align="center">
  <img src="assets/chapter05/in_landing.png"
       alt="Landing page insights"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<br>

Insights del Front-End:

<div align="center">
  <img src="assets/chapter05/in_front.png"
       alt="Frontend insights"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

---

### 5.2.3. Sprint 3

#### 5.2.3.1.Sprint Planning 3.

| Sprint 3                           | Sprint 3                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Sprint Planning Background**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Date**                           | 2026-06-02                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Time**                           | 17:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Location**                       | Via Discord                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Prepared By**                    | Alejandro Galindo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Attendees to planning meeting**  | Galindo Montero, Alejandro Manuel; Perez Tuesta, Gabriel; Fajardo Monrroy, Walter Luis; Cumba Rengifo, Leonardo Raul; Cuentas Peña, Joaquin Alberto                                                                                                                                                                                                                                                                                                                                              |
| **Sprint 3 Review Summary**        | Durante este sprint se desarrollaron las principales funcionalidades de Frigora tanto en frontend como en backend. Se implementaron módulos para la gestión de usuarios, técnicos, equipos de refrigeración y solicitudes de mantenimiento, además de mejorar la experiencia de navegación de la plataforma. El equipo logró integrar diversos componentes del sistema y validar los flujos principales de negocio, obteniendo una versión funcional que servirá como base para futuras mejoras. |
| **Sprint 3 Retrospective Summary** | La retrospectiva permitió identificar oportunidades de mejora relacionadas con la distribución de tareas, la coordinación entre frontend y backend y la planificación de actividades individuales. Asimismo, se concluyó que una definición más detallada de los criterios de aceptación y revisiones periódicas de integración contribuirán a reducir retrabajos y optimizar el avance en los siguientes sprints.                                                                               |
| **Sprint Goal & User Stories**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Sprint 3 Goal**                  | Implementar las funcionalidades principales de Frigora mediante el desarrollo e integración del frontend y backend de la plataforma. El objetivo fue habilitar la gestión de usuarios, técnicos, equipos de refrigeración y solicitudes de mantenimiento, además de proporcionar una interfaz intuitiva que permita a los usuarios interactuar eficientemente con los servicios ofrecidos por el sistema.                                                                                        |
| **Sprint 3 Velocity**              | 36                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Sum of Story Points**            | 51                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |


#### 5.2.3.2 Aspect Leaders and Collaborators

Durante este tercer sprint, el equipo se enfocó principalmente en el desarrollo del Backend, asegurando su correcto funcionamiento con la aplicación web, la integración coherente de componentes visuales e interactivos, así como la implementación de funcionalidades dinámicas que mejoran la experiencia del usuario.

Con el objetivo de optimizar la organización y la colaboración del equipo, se elaboró la matriz de Liderazgo y Colaboración (LACX), la cual asigna responsabilidades y roles específicos a cada miembro del equipo en relación con los aspectos clave abordados durante el Sprint.

| Team Member <br> (Last Name, First Name) | Github Username | Implementacion de la gestión de equipos de refrigeracion (Web Services) <br> Leader (L) / Collaborator (C) | Responsive y pruebas en distintos dispositivos <br> Leader (L) / Collaborator (C) | Despliegue del backend <br> Leader (L) / Collaborator (C) |
|---|---|---|---|---|
|Galindo Montero, Alejandro Manuel |AlejandroG12970 | L | L | L |
|Perez Tuesta,  Gabriel| Gabyoko | C | C | C |
|Fajardo Monrroy, Walter Luis  | WalterFajardo | C | C | C |
|Cumba Rengifo, Leonardo Raul  | LeonardoC72 | C | C | C |
|Cuentas Peña, Joaquin Alberto  | JoaCUPE | C | C | C |



#### 5.2.3.3. Sprint Backlog 3.

El objetivo principal de este Sprint es elaborar el Backend y mejorar el Frontend de nuestra plataforma. Para ello, dividimos el desarrollo de esta según las User Stories pertenecientes a la Epic enfocada en la aplicacion web. La plataforma elegida para ser la herramienta de control de tareas fue Trello, el cuál se presenta una captura de pantalla de nuestro tablero y su enlace público.


| User Story ID | User Story Título                                  |  Task ID  | Task Título                               | Descripción                                                                                             | Estimación (Horas) | Asignado a          | Estado (To do/ In-Process/ To-Review/ Done) |
| :-----------: | :------------------------------------------------- | :-------: | :---------------------------------------- | :------------------------------------------------------------------------------------------------------ | :----------------: | :------------------ | :-----------------------------------------: |
|   **US-01**   | Registro de usuario                                | **UT-01** | Diseñar formulario de registro            | Crear la interfaz de registro solicitando datos básicos del usuario y validaciones iniciales.           |          3         | [Walter Fajardo]    |                     Done                    |
|   **US-02**   | Inicio de sesión                                   | **UT-01** | Implementar pantalla de login             | Diseñar la vista de inicio de sesión con validación de credenciales y acceso a la plataforma.           |          2         | [Leonardo Cumba]    |                     Done                    |
|   **US-03**   | Gestionar equipos de refrigeración                 | **UT-01** | Crear módulo de gestión de equipos        | Diseñar formularios y tablas para registrar, editar y visualizar equipos de refrigeración.              |          4         | [Joaquin Cuentas]   |                     Done                    |
|   **US-06**   | Solicitar y gestionar servicios de mantenimiento   | **UT-01** | Crear módulo de solicitudes de servicio   | Diseñar formularios y vistas para registrar, editar y gestionar solicitudes de mantenimiento.           |          4         | [Alejandro Galindo] |                     Done                    |
|   **US-07**   | Dar seguimiento al progreso del servicio           | **UT-01** | Implementar vista de seguimiento          | Diseñar una pantalla que permita visualizar el estado y progreso de los servicios técnicos.             |          3         | [Gabriel Perez]     |                     Done                    |
|   **US-09**   | Recepción de alertas sobre solicitudes de servicio | **UT-01** | Implementar sistema de alertas            | Crear notificaciones visuales para informar cambios importantes en las solicitudes de servicio.         |          3         | [Walter Fajardo]    |                     Done                    |
|   **US-12**   | Registrar y gestionar técnicos                     | **UT-01** | Crear módulo de técnicos                  | Diseñar formularios y vistas para registrar, editar y administrar técnicos.                             |          4         | [Joaquin Cuentas]   |                     Done                    |
|   **US-13**   | Consultar el perfil de un técnico                  | **UT-01** | Diseñar perfil de técnico                 | Implementar pantalla con información, métricas y desempeño del técnico.                                 |          2         | [Alejandro Galindo] |                     Done                    |
|   **US-14**   | Asignar técnicos a servicios                       | **UT-01** | Implementar asignación de técnicos        | Desarrollar la funcionalidad para asignar técnicos a solicitudes de mantenimiento.                      |          3         | [Gabriel Perez]     |                     Done                    |
|   **US-18**   | Visualizar equipos asignados a clientes            | **UT-01** | Implementar listado de equipos asignados  | Crear una vista donde se visualicen los equipos vinculados a cada cliente.                              |          3         | [Walter Fajardo]    |                     Done                    |
|   **US-20**   | Visualizar la propuesta de valor principal         | **UT-01** | Diseñar sección principal de Landing Page | Implementar el banner principal destacando la propuesta de valor de Frigora.                            |          1         | [Leonardo Cumba]    |                     Done                    |
|   **US-21**   | Explorar soluciones específicas para mi rubro      | **UT-01** | Crear sección de soluciones               | Diseñar la sección que presenta las soluciones ofrecidas para diferentes tipos de clientes.             |          2         | [Gabriel Perez]     |                     Done                    |
|   **US-22**   | Comprender las funcionalidades clave               | **UT-01** | Implementar sección de funcionalidades    | Mostrar las funcionalidades principales de la plataforma mediante tarjetas informativas.                |          2         | [Walter Fajardo]    |                     Done                    |
|   **US-23**   | Conocer la misión y visión                         | **UT-01** | Diseñar sección institucional             | Crear una sección informativa con la misión y visión de la empresa.                                     |          1         | [Joaquin Cuentas]   |                     Done                    |
|   **US-24**   | Contactar con el equipo de ventas                  | **UT-01** | Implementar formulario de contacto        | Crear un formulario para que los usuarios puedan comunicarse con el equipo comercial.                   |          3         | [Alejandro Galindo] |                     Done                    |
|   **US-25**   | Acceder a la plataforma web (Call to Action)       | **UT-01** | Crear Navbar y botón CTA                  | Añadir la barra de navegación superior con el botón "Ingresar" que redirija a la futura vista de Login. |          1         | [Leonardo Cumba]    |                     Done                    |
|   **TS-02**   | Creación de solicitudes de mantenimiento (API)     | **UT-01** | Implementar endpoint de solicitudes       | Desarrollar los endpoints necesarios para registrar y consultar solicitudes de mantenimiento.           |          3         | [Walter Fajardo]    |                     Done                    |
|   **TS-04**   | Registrar nuevo usuario a través de API RESTful    | **UT-01** | Implementar endpoint de registro          | Desarrollar el servicio backend para registrar usuarios y validar información de entrada.               |          3         | [Leonardo Cumba]    |                     Done                    |
|   **TS-05**   | Consulta de estado de servicios por API            | **UT-01** | Implementar endpoint de consulta          | Crear los endpoints para consultar el estado actual de los servicios registrados.                       |          2         | [Alejandro Galindo] |                     Done                    |

<div align="center">
  <img src="assets/chapter05/sprint-backlog3.png"
       alt="Sprint Backlog 3"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

#### 5.2.3.4. Development Evidence for Sprint Review

En esta sección se presentan los ultimos commits realizados en el repositorio de backend y frontend durante el sprint 3.

**Backend**

| Rama | Commit Hash | Mensaje | Fecha |
|---|---|---|---|
| develop | `5484848` | update frigora-platform | 03/06/2026 |
| develop | `b3620a5` | update frigora-platform | 03/06/2026 |
| develop | `3b67e0a` | update bounded context: Reporting pe | 07/06/2026 |
| develop | `2c17d55` | feat: add bc assets-management | 11/06/2026 |
| develop | `467957e` | feat: update assets management | 11/06/2026 |
| develop | `0314809` | feat: add service-request & IAM bounded contexts | 15/06/2026 |
| develop | `934cf40` | fix: comments with wrong namespace | 15/06/2026 |
| develop | `32d4a15` | feat: add delete method to service-requests & update enum Roles to accept any string | 16/06/2026 |
| develop | `ad9aa48` | fix: show example schema for service-requests & users bc | 16/06/2026 |
| develop | `a23e44a` | fix: add serialization to enums for frontend filters | 16/06/2026 |
| develop | `6b33e30` | create bounded context: Technicians | 17/06/2026 |
| develop | `e8081f3` | feat: update sites | 18/06/2026 |
| develop | `20de589` | feat: update assets-management bc | 18/06/2026 |
| develop | `dd29072` | feat: add feedback | 18/06/2026 |
| develop | `7651bf3` | Merge pull request #1 from ColdTech-Peru/feature/service-requests — Feature/service requests | 18/06/2026 |
| develop | `a1dbcbe` | Merge pull request #3 from ColdTech-Peru/feature/technicians — create bounded context: Technicians | 18/06/2026 |

**Frontend**

| Rama | Commit Hash | Mensaje | Fecha |
|---|---|---|---|
| develop | `c5028ce` | Initial commit | 04/05/2026 |
| develop | `d1643d3` | feat: add initial template | 05/05/2026 |
| develop | `bcfc459` | feat: add monitoring bounded context | 11/05/2026 |
| develop | `f34b712` | feat: add assets-management bc | 14/05/2026 |
| develop | `a113b45` | feat: add endpoint site | 14/05/2026 |
| develop | `0a40a4c` | feat: add domain and infrastructure | 14/05/2026 |
| develop | `70765a3` | BC Report | 14/05/2026 |
| develop | `17c17bb` | feat: add application | 14/05/2026 |
| develop | `3ab7795` | BC Report (cherry picked from commit 70765a3) | 14/05/2026 |
| develop | `2b6296a` | Revert "BC Report" — reverts commit 70765a3 | 14/05/2026 |
| develop | `e5d234a` | feat: add components | 14/05/2026 |
| develop | `79de5c1` | feature: structure project | 14/05/2026 |
| develop | `16c0af5` | feature: aggregate domain/model section | 14/05/2026 |
| develop | `705f903` | feature: update domain/model | 14/05/2026 |
| develop | `66d79ed` | feature: aggregate infrastructure | 14/05/2026 |
| develop | `a43b822` | feat: implement monitoring bounded context | 14/05/2026 |
| develop | `4f56ec3` | feature: update domain/model | 14/05/2026 |
| develop | `0311324` | feature: update infrastructure | 14/05/2026 |
| develop | `283c3dc` | feat: add service-request bounded context | 14/05/2026 |


#### 5.2.3.5. Execution Evidence for Sprint Review

Para esta entrega hemos mejorado nuestro Frontend para que el usuario pueda registrarse como dueño de negocio o proveedor de servicios de mantenimiento y luego loguearse para entrar a la aplicación web. Hemos también implementado las vistas para el proveedor y mejorado las vistas que ya habían sido realizadas en el anterior sprint. Se presentará la evidencia de la ejecución del Frontend desplegado y conectado con el backend desplegado a continuación:

**Register**

<div align="center">
  <img src="assets/chapter05/Register.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Login**

<div align="center">
  <img src="assets/chapter05/Login.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Dashboard del dueño de negocio**

<div align="center">
  <img src="assets/chapter05/dashboard-owner.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Sites actualizado con boton de eliminar**

<div align="center">
  <img src="assets/chapter05/sites2.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Detalles del site actualizado**

<div align="center">
  <img src="assets/chapter05/sites-detail.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Formulario del site actualizado conectado con Leaflet para añadir ubicación**

<div align="center">
  <img src="assets/chapter05/sites-new.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Solicitud de servicio actualizado con el tecnico asignado, proveedor, opciones para cancelar servicio y calificar técnico**

<div align="center">
  <img src="assets/chapter05/service-request-owner.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Detalle de solicitud de servicio actualizado con intervenciones mostradas al dueño de negocio**

<div align="center">
  <img src="assets/chapter05/service-request-detail.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Dashboard para los proveedores de servicios de mantenimiento**

<div align="center">
  <img src="assets/chapter05/dashboard-provider.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Gestión de tecnicos**

<div align="center">
  <img src="assets/chapter05/technicians.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Hub de solicitudes de servicio para proveedores**

<div align="center">
  <img src="assets/chapter05/service-hub.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Lista de solicitudes de servicio para proveedores de servicios de mantenimiento**

<div align="center">
  <img src="assets/chapter05/provider-service-request.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Vista de solicitudes completadas para proveedores**

<div align="center">
  <img src="assets/chapter05/completed-services.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Vista de solicitudes canceladas o denegadas para proveedores**

<div align="center">
  <img src="assets/chapter05/canceled-services.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Vista de solicitudes en progreso para proveedores**

<div align="center">
  <img src="assets/chapter05/inprogress-services.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Registro de intervenciones desde la vista del proveedor**

<div align="center">
  <img src="assets/chapter05/intervention-log.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Detalle de las intervenciones**

<div align="center">
  <img src="assets/chapter05/intervention-detail.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Cuadro de dialogo para calificar técnico**

<div align="center">
  <img src="assets/chapter05/review-service.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Vista de la reseña publicada**

<div align="center">
  <img src="assets/chapter05/review-detail.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


#### 5.2.3.6. Services Documentation Evidence for Sprint Review.

En esta sección se mostrará la evidencia de toda la documentación relacionada a la primera versión de nuestro backend realizado en Spring Boot, que ya se encuentra conectada con nuestra aplicación web y está recibiendo y mostrando toda la data. A continuación se mostrará un cuadro con todos los bounded contexts, sus endpoints y verbos http.

| Verbo HTTP | Endpoint | Descripción |
|---|---|---|
| **Autenticación** | | |
| POST | `/api/v1/authentication/sign-up` | Registro de usuario |
| POST | `/api/v1/authentication/sign-in` | Inicio de sesión |
| **Usuarios** | | |
| GET | `/api/v1/users` | Obtener todos los usuarios |
| GET | `/api/v1/users/{id}` | Obtener un usuario por su id |
| GET | `/api/v1/users/role/{role}` | Obtener usuarios por rol |
| **Técnicos** | | |
| GET | `/api/v1/technicians/{technicianId}` | Obtener un técnico por ID |
| PUT | `/api/v1/technicians/{technicianId}` | Actualizar un técnico |
| DELETE | `/api/v1/technicians/{technicianId}` | Eliminar un técnico |
| GET | `/api/v1/technicians` | Obtener todos los técnicos |
| POST | `/api/v1/technicians` | Crear un nuevo técnico |
| **Sitios** | | |
| GET | `/api/v1/sites` | Obtener todos los sitios |
| POST | `/api/v1/sites` | Crear un nuevo sitio |
| GET | `/api/v1/sites/{id}` | Obtener un sitio por su Id |
| DELETE | `/api/v1/sites/{id}` | Eliminar un sitio |
| **Equipos** | | |
| GET | `/api/v1/equipment` | Obtener todos los equipos |
| POST | `/api/v1/equipment` | Crear un nuevo equipo |
| GET | `/api/v1/equipment/{id}` | Obtener un equipo por su Id |
| DELETE | `/api/v1/equipment/{id}` | Eliminar un equipo |
| **Solicitudes de Servicio** | | |
| POST | `/api/v1/service-requests` | Crear una solicitud de servicio |
| PATCH | `/api/v1/service-requests/{serviceRequestId}/reject` | Rechazar una solicitud de servicio |
| PATCH | `/api/v1/service-requests/{serviceRequestId}/complete` | Completar una solicitud de servicio |
| PATCH | `/api/v1/service-requests/{serviceRequestId}/cancel` | Cancelar una solicitud de servicio |
| PATCH | `/api/v1/service-requests/{serviceRequestId}/assign-technician` | Asignar técnico a una solicitud de servicio |
| PATCH | `/api/v1/service-requests/{serviceRequestId}/accept` | Aceptar una solicitud de servicio |
| GET | `/api/v1/service-requests/{serviceRequestId}` | Obtener una solicitud de servicio por Id |
| DELETE | `/api/v1/service-requests/{serviceRequestId}` | Eliminar una solicitud de servicio |
| GET | `/api/v1/service-requests/requester/{requesterId}` | Obtener solicitudes de servicio por Id de solicitante |
| GET | `/api/v1/service-requests/provider/{providerId}` | Obtener solicitudes de servicio por Id de proveedor |
| **Intervenciones** | | |
| POST | `/api/v1/interventions` | Registrar una intervención |
| GET | `/api/v1/interventions/{interventionId}` | Obtener una intervención por Id |
| GET | `/api/v1/interventions/serviceRequest/{serviceRequestId}` | Obtener intervenciones por Id de solicitud de servicio |
| **Alertas** | | |
| GET | `/api/v1/alert` | Obtener todas las alertas o por Tenant/Equipo |
| POST | `/api/v1/alert` | Crear una nueva alerta |
| PATCH | `/api/v1/alert/{id}/acknowledge` | Confirmar (acknowledge) una alerta |
| GET | `/api/v1/alert/{id}` | Obtener una alerta por Id |
| DELETE | `/api/v1/alert/{id}` | Eliminar una alerta |
| **Reportes** | | |
| GET | `/api/v1/reports/{reportId}` | Obtener un reporte por ID |
| PUT | `/api/v1/reports/{reportId}` | Actualizar un reporte |
| DELETE | `/api/v1/reports/{reportId}` | Eliminar un reporte |
| GET | `/api/v1/reports` | Obtener todos los reportes |
| POST | `/api/v1/reports` | Crear un nuevo reporte |
| **Reseñas** | | |
| GET | `/api/v1/reviews` | Obtener todas las reseñas |
| POST | `/api/v1/reviews` | Crear una reseña |
| GET | `/api/v1/reviews/{reviewId}` | Obtener una reseña por Id |
| GET | `/api/v1/reviews/service-request/{serviceRequestId}` | Obtener reseñas por Id de solicitud de servicio |


**Intervenciones**

<div align="center">
  <img src="assets/chapter05/interventions-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/intervention-1.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/intervention-2.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/intervention-3.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Reseñas**

<div align="center">
  <img src="assets/chapter05/reviews-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


<div align="center">
  <img src="assets/chapter05/review1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/review2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/review3.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/review4.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>



**Técnicos**

<div align="center">
  <img src="assets/chapter05/technicians-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/tec1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/tec2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/tec3.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/tec4.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/tec5.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


**Autenticación**

<div align="center">
  <img src="assets/chapter05/authentication-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/aut1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/aut2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Alertas**

<div align="center">
  <img src="assets/chapter05/alert-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/alert1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/alert2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/alert3.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/alert4.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/alert5.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


**Usuarios**

<div align="center">
  <img src="assets/chapter05/users-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/us1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/us2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Solicitudes de servicio**

<div align="center">
  <img src="assets/chapter05/service-request-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s3.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s4.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s5.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s6.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s7.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s8.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s9.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/s10.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Sitio**

<div align="center">
  <img src="assets/chapter05/site-swagger.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/site1.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/site2.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/site3.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/site4.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>
**Reportes**

<div align="center">
  <img src="assets/chapter05/reporting-swagger.png"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/r1.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/r2.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/r3.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/r4.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/r5.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Equipos**

<div align="center">
  <img src="assets/chapter05/equipment-swagger.png"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/eq1.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/eq2.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/eq3.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/eq4.jpeg"
       alt="Backend"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

#### 5.2.3.7. Software Deployment Evidence for Sprint Review.

Para el Sprint 3, hemos desplegado nuevamente nuestro Frontend y también nuestra primera versión de nuestra plataforma en Spring Boot y la base de datos. No hemos necesitado del Fake Api, ya que nuestra aplicación web ya está conectada al backend y toda la data se dirige hacia allá.

**Evidencia de despliegue del Frontend en Vercel:**

<div align="center">
  <img src="assets/chapter05/frontend-deploy.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link del Frontend desplegado: https://frigora-frontend.vercel.app/

**Evidencia del despliegue del Backend en Render:**

<div align="center">
  <img src="assets/chapter05/backend-deploy.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link del backend desplegado: https://frigora-platform.onrender.com/

**Evidencias del despliegue de la base de datos MySQL en Railway:**

<div align="center">
  <img src="assets/chapter05/database-deploy.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

<div align="center">
  <img src="assets/chapter05/database-deploy2.png"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


#### 5.2.3.8. Team Collaboration Insights during Sprint.

**Insights del repositorio donde desarrollamos el Front-end de Frigora:**

<div align="center">
  <img src="assets/chapter05/commits-front.png"
       alt="Insights"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Insights del repositorio donde desarrollamos el Back-end de Frigora:**

<div align="center">
  <img src="assets/chapter05/commits-back.png"
       alt="Insights"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


### 5.2.4. Sprint 4

#### 5.2.4.1.Sprint Planning 4.

| Sprint 4                           | Sprint 4                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| ---------------------------------- | ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ |
| **Sprint Planning Background**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Date**                           | 2026-07-08                                                                                                                                                                                                                                                                                                                                                                                                                                                                                       |
| **Time**                           | 18:00 PM                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| **Location**                       | Via Discord                                                                                                                                                                                                                                                                                                                                                                                                                                                                                      |
| **Prepared By**                    | Alejandro Galindo                                                                                                                                                                                                                                                                                                                                                                                                                                                                                |
| **Attendees to planning meeting**  | Galindo Montero, Alejandro Manuel; Perez Tuesta, Gabriel; Fajardo Monrroy, Walter Luis; Cumba Rengifo, Leonardo Raul; Cuentas Peña, Joaquin Alberto                                                                                                                                                                                                                                                                                                                                              |
| **Sprint 4 Review Summary**        | Se realizó el despliegue del Frontend y Backend, implementando funcionalidades orientadas al primer y segundo segmento objetivo. |
| **Sprint 4 Retrospective Summary** | El equipo acordó encargarse de las tareas asignadas y colaborar con las demás áreas del proyecto del Frontend y Backend para alcanzar nuestro objetivo.                                                                               |
| **Sprint Goal & User Stories**     |                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                  |
| **Sprint 3 Goal**                  | El objetivo de este sprint es completar la integración principal de Frigora conectando directamente el frontend con el backend. Esto implica enlazar la página con la aplicación de usuario y establecer la comunicación operativa con el sistema de gestión de datos. Con esta conexión final, los usuarios podrán ingresar y navegar sin problemas desde la página de inicio hasta la aplicación central, mientras que el backend proporcionará el soporte necesario para manejar entidades clave como equipos, solicitudes de servicio, técnicos, reportes y alertas. La integración entre la interfaz y el sistema de datos confirmará que ambos lados de la aplicación funcionan juntos, marcando un paso crucial hacia la finalización de la plataforma.                                                                                      |
| **Sprint 3 Velocity**              | 36                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |
| **Sum of Story Points**            | 51                                                                                                                                                                                                                                                                                                                                                                                                                                                                                               |


#### 5.2.4.2 Aspect Leaders and Collaborators

Durante este cuarto sprint, el equipo se enfocó principalmente en la consolidación de la plataforma, priorizando la resolución de errores detectados en sprints previos, el reforzamiento de la seguridad mediante el control de accesos y el refinamiento general de las funcionalidades para asegurar un sistema estable.

Con el objetivo de optimizar la organización y la colaboración del equipo, se actualizó la matriz de Liderazgo y Colaboración (LACX), la cual asigna responsabilidades y roles específicos a cada miembro del equipo en relación con los aspectos clave abordados durante este cuarto Sprint.

| Team Member <br> (Last Name, First Name) | Github Username | Resolución de errores de sprints previos <br> Leader (L) / Collaborator (C) | Seguridad, control de accesos y optimización de rendimiento <br> Leader (L) / Collaborator (C) | Refinamiento de funcionalidades y ajustes finales <br> Leader (L) / Collaborator (C) |
|---|---|---|---|---|
|Galindo Montero, Alejandro Manuel |AlejandroG12970 | L | L | L |
|Perez Tuesta, Gabriel| Gabyoko | C | C | C |
|Fajardo Monrroy, Walter Luis | WalterFajardo | C | C | C |
|Cumba Rengifo, Leonardo Raul | LeonardoC72 | C | C | C |
|Cuentas Peña, Joaquin Alberto | JoaCUPE | C | C | C |

#### 5.2.4.3. Sprint Backlog 4.

El objetivo principal de este Sprint es consolidar la plataforma mediante la resolución de errores detectados en sprints previos, el reforzamiento de la seguridad mediante el control de accesos y el refinamiento general de las funcionalidades para asegurar un sistema estable. Para ello, dividimos el desarrollo de esta según las User Stories pertenecientes a la Epic enfocada en la optimización y estabilización de la aplicación web. La plataforma elegida para ser la herramienta de control de tareas fue Trello, del cual se presenta una captura de pantalla de nuestro tablero y su enlace público.

# Sprint Backlog 4

| User Story ID | User Story Título | Task ID | Task Título | Descripción | Estimación (Horas) | Asignado a | Estado (To do/ In-Process/ To-Review/ Done) |
| :-----------: | :---------------- | :-----: | :---------- | :---------- | :----------------: | :--------- | :-----------------------------------------: |
| **US-05** | Analizar el consumo energético de equipos | **UT-01** | Implementar dashboard energético | Desarrollar gráficos e indicadores para analizar y comparar el consumo energético de los equipos monitoreados. | 8 | Alejandro Galindo | Done |
| **US-08** | Ver reporte de servicio realizado | **UT-01** | Implementar reporte técnico | Desarrollar la vista que muestra el detalle completo de los servicios de mantenimiento realizados. | 3 | Leonardo Cumba | Done |
| **US-10** | Ver historial de servicios | **UT-01** | Implementar historial de servicios | Desarrollar el historial cronológico de mantenimientos realizados para cada cliente y equipo. | 3 | Joaquin Cuentas | Done |
| **US-11** | Realizar seguimiento a solicitudes de servicio | **UT-01** | Implementar seguimiento de solicitudes | Desarrollar la vista que permita consultar el estado y avance de las solicitudes de mantenimiento. | 3 | Gabriel Perez | Done |
| **US-15** | Generar reporte de desempeño de técnicos | **UT-01** | Implementar reporte de desempeño | Desarrollar reportes con métricas de productividad, tiempos de atención y servicios completados por técnico. | 8 | Alejandro Galindo | Done |
| **US-17** | Visualizar clientes y servicios asociados | **UT-01** | Implementar vista de clientes | Desarrollar un listado que relacione clientes con los servicios de mantenimiento asociados. | 3 | Gabriel Perez | Done |
| **US-19** | Recibir notificaciones de eventos importantes | **UT-01** | Implementar centro de notificaciones | Desarrollar un módulo que muestre eventos importantes relacionados con equipos y servicios. | 5 | Leonardo Cumba | Done |
| **TS-01** | Gestión de alertas críticas vía API | **UT-01** | Implementar API de alertas | Desarrollar los endpoints REST para registrar y consultar alertas críticas generadas por el sistema IoT. | 5 | Joaquin Cuentas | Done |
| **TS-03** | Registro de intervenciones técnicas por API RESTful | **UT-01** | Implementar API de intervenciones | Desarrollar los endpoints REST para registrar las intervenciones realizadas por los técnicos durante un servicio. | 3 | Walter Fajardo | Done |

<img width="1424" height="799" alt="Sprint4" src="https://github.com/user-attachments/assets/4376992a-1429-4e96-974e-4a29c5b6fa6c" />

link trello:
https://trello.com/invite/b/6a500d8fb191a398d872829b/ATTI000e5730796bbf45f562e702eb4cca5b2D538505/sprint-4



#### 5.2.4.4. Development Evidence for Sprint Review

En esta sección se presentan los últimos commits realizados en el repositorio de backend y frontend durante el sprint 4.

**Backend**

| Rama | Commit Hash | Mensaje | Fecha |
|---|---|---|---|
| develop | `5484848` | update frigora-platform | 03/06/2026 |
| develop | `b3620a5` | update frigora-platform | 03/06/2026 |
| develop | `3b67e0a` | update bounded context: Reporting pe | 07/06/2026 |
| develop | `2c17d55` | feat: add bc assets-management | 11/06/2026 |
| develop | `467957e` | feat: update assets management | 11/06/2026 |
| develop | `0314809` | feat: add service-request & IAM bounded contexts | 15/06/2026 |
| develop | `934cf40` | fix: comments with wrong namespace | 15/06/2026 |
| develop | `32d4a15` | feat: add delete method to service-requests & update enum Roles to accept any string | 16/06/2026 |
| develop | `ad9aa48` | fix: show example schema for service-requests & users bc | 16/06/2026 |
| develop | `a23e44a` | fix: add serialization to enums for frontend filters | 16/06/2026 |
| develop | `6b33e30` | create bounded context: Technicians | 17/06/2026 |
| develop | `e8081f3` | feat: update sites | 18/06/2026 |
| develop | `20de589` | feat: update assets-management bc | 18/06/2026 |
| develop | `dd29072` | feat: add feedback | 18/06/2026 |
| develop | `7651bf3` | Merge pull request #1 from ColdTech-Peru/feature/service-requests — Feature/service requests | 18/06/2026 |
| develop | `a1dbcbe` | Merge pull request #3 from ColdTech-Peru/feature/technicians — create bounded context: Technicians | 18/06/2026 |

**Frontend**

| Rama | Commit Hash | Mensaje | Fecha |
|---|---|---|---|
| develop | `af065f9` | feat: update sites and equipment API endpoints to get them by ownerId. Update login view and add upload file method for interventions | 06/07/2026 |
| develop | `c747e17` | fix: update store to load sites and equipments in form | 06/07/2026 |
| develop | `9e71aee` | fix: add leaflet marker images | 06/07/2026 |
| develop | `1a994d9` | fix: update dashboard with fake IoT data, fix ack on alerts & add new translations | 07/07/2026 |
| develop | `0923ee3` | fix: fix trend-chart.ts | 07/07/2026 |
| develop | `a0fca17` | fix: update trend-chart.ts | 07/07/2026 |
| develop | `70b7629` | fix: update trend-chart.ts | 07/07/2026 |
| develop | `903877e` | fix: update trend-chart.ts to show fake IoT data | 07/07/2026 |
| develop | `bad04c6` | fix: add fake temperature trend to simulate IoT | 07/07/2026 |
| develop | `286d29d` | feat(equipments): add translation to equipment-detail.component.html | 07/07/2026 |
| develop | `b5f0499` | fix: add insert photo evidence section for interventions | 07/07/2026 |
| develop | `a7d0aa7` | fix: improve code quality | 07/07/2026 |

#### 5.2.4.5. Execution Evidence for Sprint Review
En el Sprint 4 se desplegó la última versión de la Web Application de Frigora, implementando mejoras complementarias y esenciales para garantizar la eficiencia de cada una de las secciones de la aplicación. A continuación, se presentan las evidencias:


## Register
<div align="center">
  <img src="assets/chapter04/register.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Login
<div align="center">
  <img src="assets/chapter04/login.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

# Owner View:

## Dashboard

Main Dashboard View:

<div align="center">
  <img src="assets/chapter04/dashboard.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Sites

Main Sites View:

<div align="center">
  <img src="assets/chapter04/sites.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Site details:

<div align="center">
  <img src="assets/chapter04/sitedetail.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

New Sites:

<div align="center">
  <img src="assets/chapter04/newsites.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Monitoring

Equipment:

<div align="center">
  <img src="assets/chapter04/monitoriing.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Detail Equipment:

<div align="center">
  <img src="assets/chapter04/viewmonitoring.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Add Equipment:

<div align="center">
  <img src="assets/chapter04/addmonitoring.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Alert:

<div align="center">
  <img src="assets/chapter04/alert.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Services

Main Service View :

<div align="center">
  <img src="assets/chapter04/service.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Detail Service:

<div align="center">
  <img src="assets/chapter04/viewservice.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

New Service:

<div align="center">
  <img src="assets/chapter04/newservices.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Detail Intervention:

<div align="center">
  <img src="assets/chapter05/detalleintervenciones.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Report

Main Report View:

<div align="center">
  <img src="assets/chapter04/reporting.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Detail Report:

<div align="center">
  <img src="assets/chapter04/viewreport.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Edit Report:

<div align="center">
  <img src="assets/chapter04/editreport.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Create Report:

<div align="center">
  <img src="assets/chapter04/createreporting.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>


# Provider View:

## Dashboard

Main Dashboard View:

<div align="center">
  <img src="assets/chapter04/dashboardp.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Technicians

Main Techicians View:

<div align="center">
  <img src="assets/chapter04/technicians.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Edit Technicians:

<div align="center">
  <img src="assets/chapter04/edit technicians.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Service Hub

Main Service Hub View:

<div align="center">
  <img src="assets/chapter04/services hub.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## Services

Services List:

<div align="center">
  <img src="assets/chapter04/servicelist.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Completed Service:

<div align="center">
  <img src="assets/chapter04/completeservice.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Canceled Service:

<div align="center">
  <img src="assets/chapter04/canceledservice.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

In-Progress Services:

<div align="center">
  <img src="assets/chapter04/inprogresservice.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

#### 5.2.4.6. Services Documentation Evidence for Sprint Review

**Interventions**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :------------------------------- | :------------------------------------------- |
| POST | /api/v1/interventions | Registrar una intervención |
| GET | /api/v1/interventions/{interventionId} | Obtener intervención por ID |
| GET | /api/v1/interventions/serviceRequest/{serviceRequestId} | Obtener intervenciones por Service Request ID |

---

**Reviews**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :---------------------------------------------- | :--------------------------------------- |
| GET | /api/v1/reviews | Obtener todas las reseñas |
| POST | /api/v1/reviews | Crear una reseña |
| GET | /api/v1/reviews/{reviewId} | Obtener reseña por ID |
| GET | /api/v1/reviews/service-request/{serviceRequestId} | Obtener reseñas por Service Request ID |

---

**Technicians**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :---------------------------------------- | :-------------------------------------- |
| GET | /api/v1/technicians/{technicianId} | Obtener técnico por ID |
| PUT | /api/v1/technicians/{technicianId} | Actualizar técnico |
| DELETE | /api/v1/technicians/{technicianId} | Eliminar técnico |
| GET | /api/v1/technicians | Obtener todos los técnicos |
| POST | /api/v1/technicians | Crear un nuevo técnico |

---

**Authentication**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :---------------------------------------- | :---------------- |
| POST | /api/v1/authentication/sign-up | Registrarse |
| POST | /api/v1/authentication/sign-in | Iniciar sesión |

---

**Alerts**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :----------------------------------------- | :----------------------------------------------------------- |
| GET | /api/v1/alert | Obtener todas las alertas del usuario actual o filtradas por Equipment ID |
| POST | /api/v1/alert | Crear una nueva alerta |
| PATCH | /api/v1/alert/{id}/acknowledge | Marcar una alerta como reconocida |
| GET | /api/v1/alert/{id} | Obtener alerta por ID |
| DELETE | /api/v1/alert/{id} | Eliminar alerta |

---

**Users**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :-------------------------------- | :-------------------------------- |
| GET | /api/v1/users | Obtener todos los usuarios |
| GET | /api/v1/users/{id} | Obtener usuario por ID |
| GET | /api/v1/users/role/{role} | Obtener usuarios por rol |

---

**ServiceRequests**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :---------------------------------------------------------------- | :----------------------------------------- |
| POST | /api/v1/service-requests | Crear una solicitud de servicio |
| PATCH | /api/v1/service-requests/{serviceRequestId}/reject | Rechazar una solicitud |
| PATCH | /api/v1/service-requests/{serviceRequestId}/complete | Completar una solicitud |
| PATCH | /api/v1/service-requests/{serviceRequestId}/cancel | Cancelar una solicitud |
| PATCH | /api/v1/service-requests/{serviceRequestId}/assign-technician | Asignar un técnico a la solicitud |
| PATCH | /api/v1/service-requests/{serviceRequestId}/accept | Aceptar una solicitud |
| GET | /api/v1/service-requests/{serviceRequestId} | Obtener solicitud por ID |
| DELETE | /api/v1/service-requests/{serviceRequestId} | Eliminar solicitud |
| GET | /api/v1/service-requests/requester/{requesterId} | Obtener solicitudes por Requester ID |
| GET | /api/v1/service-requests/provider/{providerId} | Obtener solicitudes por Provider ID |

---

**Site**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :------------------------------------ | :-------------------------------- |
| GET | /api/v1/sites | Obtener todos los sitios del usuario actual |
| POST | /api/v1/sites | Crear un nuevo sitio |
| GET | /api/v1/sites/{id} | Obtener sitio por ID |
| DELETE | /api/v1/sites/{id} | Eliminar sitio |
| GET | /api/v1/sites/by-owner/{ownerId} | Obtener sitios por Owner ID |

---

**Reporting**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :-------------------------------- | :----------------------------------------- |
| GET | /api/v1/reports/{reportId} | Obtener reporte por ID |
| PUT | /api/v1/reports/{reportId} | Actualizar reporte |
| DELETE | /api/v1/reports/{reportId} | Eliminar reporte |
| GET | /api/v1/reports | Obtener todos los reportes del usuario actual |
| POST | /api/v1/reports | Crear un nuevo reporte |

---

**Equipment**

| Verbo HTTP | Endpoint | Descripción |
| :--------: | :------------------------------------- | :--------------------------------------- |
| GET | /api/v1/equipment | Obtener todos los equipos del usuario actual |
| POST | /api/v1/equipment | Crear un nuevo equipo |
| GET | /api/v1/equipment/{id} | Obtener equipo por ID |
| DELETE | /api/v1/equipment/{id} | Eliminar equipo |
| GET | /api/v1/equipment/by-owner/{ownerId} | Obtener equipos por Owner ID |

### Interventions

<div align="center">
  <img src="assets/chapter05/interventionsswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Reviews

<div align="center">
  <img src="assets/chapter05/reviewsswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Technicians

<div align="center">
  <img src="assets/chapter05/techniciansswaggerswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Authentication

<div align="center">
  <img src="assets/chapter05/authenticationsswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Alert

<div align="center">
  <img src="assets/chapter05/alertswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Users

<div align="center">
  <img src="assets/chapter05/userswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Service Request

<div align="center">
  <img src="assets/chapter05/servicerequestswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Site

<div align="center">
  <img src="assets/chapter05/siteswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Reporting

<div align="center">
  <img src="assets/chapter05/reportingswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

### Equipment

<div align="center">
  <img src="assets/chapter05/equipmentswagger.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

#### 5.2.4.7. Software Deployment Evidence for Sprint Review

Para esta entrega, desplegamos una la versión final del FrontEnd, ultima versión del backend y nuestra base de datos para que pueda ser conectada en nuestra plataforma.

**Despliegue del FrontEnd en Vercel**

<div align="center">
  <img src="assets/chapter05/frontend-deployment.png"
       alt="Frontend deployment"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link: https://frigora-frontend.vercel.app/

**Despliegue del BackEnd en Render**

<div align="center">
  <img src="assets/chapter05/backend-deployment.png"
       alt="Backend deployment"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link: https://frigora-platform.onrender.com/swagger-ui/index.html

**Despliegue de la base de datos en Railway**

<div align="center">
  <img src="assets/chapter05/database-deployment.png"
       alt="Database deployment"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

**Despliegue de la landing page en Github Pages**

<div align="center">
  <img src="assets/chapter05/database-deployment.png"
       alt="Database deployment"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link: https://coldtech-peru.github.io/Landing-Page/

#### 5.2.4.8. Team Collaboration Insights during Sprint

Frontend:

<div align="center">
  <img src="assets/chapter05/front.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Backend:

<div align="center">
  <img src="assets/chapter05/back.jpeg"
       alt="Frontend apps"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

## 5.3. Validation Interviews.

### 5.3.1. Diseño de Entrevistas.

# Guía de Entrevista — Frigora

**Objetivo:** Validar la usabilidad y propuesta de valor de la plataforma según el perfil del entrevistado.

## Preguntas Comunes

1. ¿La landing page te dejó claro para qué sirve Frigora?
2. ¿El registro e inicio de sesión fueron rápidos y sin errores?
3. ¿Navegaste el panel principal sin dificultad?
4. ¿Los cambios de configuración (idioma, tema) se mantuvieron al recargar?
5. ¿Tuviste algún problema técnico durante la prueba?
6. ¿Faltó alguna funcionalidad que esperabas encontrar?

---

## Segmento 1 — Negocios con Equipos de Refrigeración

**Flujo:** Registrar sitios y equipos → Monitorear alertas → Crear service request → Calificar técnico → Ver dashboard y reportes.

**Sitios y equipos**
1. ¿Registrar un sitio y agregar equipos fue sencillo e intuitivo?
2. ¿La información mostrada por equipo (estado, modelo) es relevante para tu operación?

**Monitoreo y alertas**

3. ¿La visualización en tiempo real (temperatura, humedad, consumo) es clara?
4. ¿Las alertas (alta temperatura, apertura prolongada, falla eléctrica) fueron fáciles de interpretar y llegaron a tiempo?

**Service request**

5. ¿Crear una solicitud de servicio y asociarla a un equipo fue claro?
6. ¿Pudiste hacer seguimiento del estado de tu solicitud en todo momento?

**Calificación**

7. ¿Encontraste fácilmente la opción para calificar al técnico una vez completado el servicio?
8. ¿Los criterios de calificación reflejan lo que realmente te importa evaluar?

**Dashboard y reportes**

9. ¿El dashboard te da una visión general útil de tus equipos y sitios?
10. ¿Los reportes (consumo, temperatura, horas de funcionamiento) son accesibles y fáciles de interpretar?

---

## Segmento 2 — Técnicos y Empresas de Mantenimiento

**Flujo:** Ver solicitudes → Aceptar y asignar técnico → Registrar intervención → Completar servicio → Ver reportes.

**Solicitudes**

1. ¿La información de cada solicitud (equipo, problema, urgencia) fue suficiente para decidir aceptarla?
2. ¿El proceso para aceptar y asignar un técnico fue intuitivo?

**Intervención y cierre**

3. ¿Registrar la intervención (trabajo realizado, observaciones) fue claro y completo?
4. ¿Cerrar una solicitud como completada fue sencillo?

**Historial**

5. ¿Accediste fácilmente al historial de intervenciones previas por equipo?
6. ¿La información del historial es suficiente para planificar la siguiente intervención?

**Dashboard y reportes**

7. ¿El dashboard te da una visión útil del estado de solicitudes y técnicos?
8. ¿Los reportes de rendimiento por técnico y equipos por cliente son claros y útiles?


### 5.3.2. Registro de Entrevistas.

#### Segmento #1: Negocios con equipos de refrigeración

**Entrevista 1**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Luis Tufiño |
| **Edad** | 23 años |
| **Distrito** | Callao |
| **Duración** | 8:52 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQAag8hJH5WvQZxc7NZyruusAbKitXv0kuUzK9zCA5NgTWQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iSBIvs`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQAag8hJH5WvQZxc7NZyruusAbKitXv0kuUzK9zCA5NgTWQ?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=iSBIvs) |

<div align="center">
<img width="894" height="469" alt="Luis" src="https://github.com/user-attachments/assets/d466dcfc-066a-41d7-9ce4-fe944af61d82" />
</div>


**Resumen:** 

- El usuario indicó que el proceso para registrar sitios y equipos fue sencillo y fácil de entender. Destacó que la información mostrada de cada equipo le permite llevar un mejor control de sus operaciones.Consideró que la visualización en tiempo real y las alertas son claras y oportunas, lo que le ayuda a reaccionar rápidamente ante posibles fallas.Además, señaló que la creación y seguimiento de solicitudes de servicio es intuitiva y valoró positivamente el dashboard y los reportes, ya que le brindan una visión general del estado de sus equipos y del consumo energético. Como mejora, sugirió incorporar notificaciones adicionales por correo electrónico o teléfono.

---

**Entrevista 2**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Alessandro Aguilar |
| **Edad** | 25 |
| **Distrito** | San Martín |
| **Duración** | 6:43 min |
| **Enlace** |  [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202221632_upc_edu_pe/IQBqZnNsFq9cQ6SpKRxbGu9rAfLHBPWzNjZA5UtmoUlghT0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=eUMvL8`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202221632_upc_edu_pe/IQBqZnNsFq9cQ6SpKRxbGu9rAfLHBPWzNjZA5UtmoUlghT0?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=eUMvL8)   |

<div align="center">
<img width="894" height="469" alt="image" src="assets/chapter04/imagen entrevista.jpg" />
</div>

**Resumen:** 

- El usuario tuvo una experiencia bastante fluida al interactuar con el módulo de registro de instalaciones y dispositivos. Hizo hincapié en que la visibilidad de los datos mejora significativamente su control operativo. De igual forma, percibe un gran valor en las alertas oportunas y la visualización en vivo, ya que son factores clave para una capacidad de respuesta inmediata ante problemas técnicos. La generación de solicitudes de soporte le pareció muy amigable; a la par, validó positivamente los reportes y el dashboard como fuentes de consulta esenciales para el monitoreo energético y de estado. Finalmente, concluyo que nuestro producto le pareció útil para su labor.
  
---

**Entrevista 3**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Arturo Axel Saravia Huaricancha |
| **Edad** | 20 |
| **Distrito** | Los olivos |
| **Duración** | 6:31 min |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQCTDSP3F5mPTLSUS2D7HEGUAdeZyrlXFi187pTy-q7CD5M?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=T5RvoL`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQCTDSP3F5mPTLSUS2D7HEGUAdeZyrlXFi187pTy-q7CD5M?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=T5RvoL) |



<div align="center">
<img width="584" height="327" alt="ArturoEntrevista" src="https://github.com/user-attachments/assets/a01d1ba8-8e27-4039-b1fd-bfdc00787909" />
</div>


**Resumen:** 

- El usuario comentó que la plataforma le permitió registrar sitios y equipos de forma sencilla y mantener un mejor control de sus activos. Destacó que la visualización en tiempo real y las alertas facilitan la detección temprana de problemas. Asimismo, indicó que la gestión y seguimiento de las solicitudes de servicio es clara y que los dashboards y reportes proporcionan información útil para la toma de decisiones. Como mejora, sugirió incorporar notificaciones por correo electrónico y la posibilidad de agregar comentarios adicionales al momento de calificar a los técnicos.
---

#### Segmento #2: Técnicos y Empresas de Mantenimiento

**Entrevista 1**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Mark Josue Febres Reategui  |
| **Edad** | 25 |
| **Distrito** | Dueñas |
| **Duración** | 4:51 |
| **Enlace** | https://1drv.ms/v/c/6bb6365728706c6d/IQAMI-YwbIJ2R6ONY6Qn38vLAZfOVsGWbz0Gb8XpW0Wyi5A?e=s5yutd |

<div align="center">
<img width="894" height="469" alt="image" src="assets/chapter05/entrevista-mark.png" />
</div>

**Resumen:**

La experiencia general fue satisfactoria, ya que todas las funcionalidades evaluadas resultaron claras y fáciles de utilizar. La información de las solicitudes permitió tomar decisiones adecuadas, el registro y cierre de intervenciones fue intuitivo, el historial proporcionó contexto útil para futuras acciones y tanto el dashboard como los reportes ofrecieron información relevante para la gestión y seguimiento de las operaciones de mantenimiento.

---

**Entrevista 2**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Diego Avalos |
| **Edad** | 23 años |
| **Distrito** | Asia |
| **Duración** | 4:25 |
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQCDMg6KHU81SobE_H8BDw98ASpGMlljHiqL_muFYdUxBAg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PjKFU6`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQCDMg6KHU81SobE_H8BDw98ASpGMlljHiqL_muFYdUxBAg?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=PjKFU6) |


<div align="center">
  <img src="assets/chapter05/diegooo.png"
       alt="Entrevista Diego"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);"/>
</div>


**Resumen:** 

La experiencia general fue exitosa, ya que todas las funcionalidades evaluadas resultaron claras y fáciles de utilizar. La información de las opciones para un técnicos ayudaron al entrevistado a cumplir el flujo que le permite desarrollar todo su trabajo desde inicio a fin. Asimismo el entrevistado señaló el registro y cierre de intervenciones como las opciones más intuitivas en el proceso.

---

**Entrevista 3**

| Campo | Detalle |
| :--- | :--- |
| **Nombre** | Yañez Santos, Leo Giovany |
| **Edad** | 23 años |
| **Distrito** | San Miguel |
| **Duración** | 5:56 min|
| **Enlace** | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQBfHdHPUuaJTqzoIcxPdmByAdSFfvRImpLn80WstCFmyKw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SwOtNt`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202311912_upc_edu_pe/IQBfHdHPUuaJTqzoIcxPdmByAdSFfvRImpLn80WstCFmyKw?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJPbmVEcml2ZUZvckJ1c2luZXNzIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXciLCJyZWZlcnJhbFZpZXciOiJNeUZpbGVzTGlua0NvcHkifX0&e=SwOtNt) |

<div align="center">
<img width="894" height="469" alt="Leo" src="https://github.com/user-attachments/assets/f42616bf-f6a6-4e73-8424-432aed7e40da" />
</div>

**Resumen:** 


- El usuario comentó que la información de las solicitudes es suficiente para comprender el problema y priorizar las atenciones según su urgencia. Mencionó que el proceso para aceptar y asignar servicios es claro y que el registro de las intervenciones resulta completo y sencillo. También destacó la utilidad del historial de mantenimiento para conocer fallas recurrentes y preparar futuras visitas técnicas. Finalmente, señaló que el dashboard y los reportes permiten monitorear el estado de las solicitudes y evaluar el desempeño de los técnicos. Como oportunidad de mejora, sugirió añadir la posibilidad de adjuntar fotografías o documentos en el historial de intervenciones y disponer de filtros por especialidad o disponibilidad de los técnicos.

---

### 5.3.3. Evaluaciones según heurísticas.

---

#### UX Heuristics & Principles Evaluation

**Usability – Inclusive Design – Information Architecture**

| Campo | Valor |
|---|---|
| **CARRERA** | Ingeniería de Software |
| **CURSO** | Desarrollo de Aplicaciones Open Source |
| **SECCIÓN** | 11959
| **PROFESORES** | Hugo Allan Mori |
| **AUDITOR** | ColdTech (Frigora) |
| **CLIENTE(S)** | PrimeFuel |


---

#### SITE o APP A EVALUAR

**FullTank (PrimeFuel)** — Web Application B2B de intermediación de combustible (Proveedor/Distribuidor ↔ Comprador/Solicitante).

---

#### TAREAS A EVALUAR

El alcance de esta evaluación incluye la revisión de la usabilidad de las siguientes tareas:

1. Creación de una solicitud de combustible (Buyer)
2. Revisión y aceptación/rechazo de solicitudes pendientes (Provider)
3. Asignación de conductor y vehículo, y despacho de un pedido (Provider)
4. Confirmación de recepción de un pedido (Buyer)
5. Pago de un pedido y visualización de factura (Buyer)
6. Registro de un nuevo producto en inventario (Provider)
7. Registro de un nuevo conductor (Provider)
8. Registro de cuenta nueva (Provider/Buyer)
9. Revisión de reportes y analítica (Provider/Buyer)
10. Revisión de notificaciones

No están incluidas en esta versión de la evaluación las siguientes tareas:

1. Flujo de login / recuperación de contraseña (no se proveyeron capturas)
2. Gestión de equipos del comprador (catálogo de equipos) en detalle
3. Cancelación de pedidos y flujo de rechazo de solicitudes
4. Versión móvil / responsive (todas las capturas corresponden a escritorio)

---

#### ESCALA DE SEVERIDAD

| Nivel | Descripción |
|---|---|
| **1** | Problema superficial: puede ser fácilmente superado por el usuario o ocurre con muy poca frecuencia. No necesita ser arreglado a no ser que exista disponibilidad de tiempo. |
| **2** | Problema menor: puede ocurrir un poco más frecuentemente o es un poco más difícil de superar para el usuario. Se le debería asignar una prioridad baja para resolverlo de cara al siguiente release. |
| **3** | Problema mayor: ocurre frecuentemente o los usuarios no son capaces de resolverlo. Es importante que sea corregido y se le debe asignar una prioridad alta. |
| **4** | Problema muy grave: un error de gran impacto que impide al usuario continuar con el uso de la herramienta. Es imperativo que sea corregido antes del lanzamiento. |

---

#### TABLA RESUMEN

| # | Problema | Severidad | Heurística/Principio violado(a) |
|---|---|---|---|
| 1 | El nombre del producto se confunde con el nombre de una persona ("Franchesco Bernandini") en el selector y resumen de la solicitud de combustible | 4 | Usability: Match entre el sistema y el mundo real |
| 2 | Cálculo de factura inconsistente: el "Subtotal" se deriva restando el IGV del Total en vez de multiplicar Cantidad × Precio Unitario, generando montos de línea incorrectos | 4 | Usability: Prevención de errores / Consistencia de datos |
| 3 | Estado de pago contradictorio entre la vista del proveedor ("Pendiente de pago") y la factura del mismo pedido ("PAID") | 4 | Usability: Visibilidad del estado del sistema |
| 4 | Datos de Conductor y Vehículo "Not assigned" en la vista del comprador mientras la vista del proveedor del mismo pedido sí los muestra asignados | 3 | Usability: Consistencia y estándares |
| 5 | Datos de prueba (placeholders sin sentido) visibles en producción: descripciones de producto, nombre de conductor "Jose el Carry", placa "AHd-sdgsdg" | 3 | Usability: Estética y diseño minimalista / Profesionalismo |
| 6 | Mezcla de idiomas dentro de la misma pantalla o lista (notificaciones, badges de sector) | 2 | Usability: Consistencia y estándares |
| 7 | Bug de fecha relativa: notificaciones muestran "NaNmo ago" en vez del tiempo transcurrido | 3 | Usability: Prevención de errores |
| 8 | Unidad de cantidad ilegible/rota en el formulario de solicitud en español: "Cantidad (—)" en vez de "Cantidad (L)" | 2 | Usability: Visibilidad del estado del sistema |
| 9 | Ambigüedad en formato numérico de cantidad solicitada ("23.000" interpretado como 23 000 L) sin separador de miles explícito ni confirmación clara | 3 | Usability: Prevención de errores |
| 10 | Unidad de volumen inconsistente entre módulos: "Total Volume (MT)" en Reportes vs. Litros (L) en el resto de la aplicación | 2 | Information Architecture: ¿Es comprensible? (Labeling Systems) |
| 11 | Cifra de ingresos truncada / con error de formato ("S/ 7,735,703.0") en el dashboard de reportes | 2 | Usability: Visibilidad del estado del sistema |
| 12 | Indicador de "Estado" en tabla de Mejores Clientes mostrado solo como una pastilla de color sin etiqueta de texto | 2 | Usability: Reconocimiento antes que recuerdo |
| 13 | Dashboard del proveedor muestra "Active Orders: 0" y "Pending Requests: 0" inmediatamente después de que el comprador registró 3 solicitudes activas | 3 | Usability: Visibilidad del estado del sistema |
| 14 | Método de pago "YAPE" utilizado para transacciones B2B de gran magnitud (S/ 875,000.00), incompatible con los límites reales de esa billetera digital | 2 | Usability: Match entre el sistema y el mundo real |
| 15 | Transacción de ejemplo de solo 4 litros de Diesel B5 en un contexto de catálogo B2B industrial | 1 | Usability: Match entre el sistema y el mundo real |
| 16 | Error ortográfico recurrente "premiun" en vez de "premium" en nombre de producto | 1 | Usability: Consistencia y estándares |
| 17 | Formulario de registro de cuenta no marca campos obligatorios, a diferencia de otros formularios del mismo sistema (p. ej. registro de conductor) que sí usan asterisco | 2 | Usability: Consistencia y estándares / Prevención de errores |
| 18 | Gráficos de barras y de dona sin valores numéricos visibles ni leyenda clara sobre los datos representados | 2 | Information Architecture: ¿Es comprensible? |

---

#### DESCRIPCIÓN DE PROBLEMAS

##### PROBLEMA #1: El nombre del producto se confunde con el nombre de una persona

**Severidad:** 4

**Heurística violada:** Usability - Match entre el sistema y el mundo real

**Problema:**
En el panel "Create Fuel Request" / "Crear Solicitud de Combustible", el selector "Select a product" muestra como opción **"Franchesco Bernandini"**, un nombre propio de persona, en lugar de un nombre de producto de combustible (por ejemplo "Gasohol 84"). Esta misma etiqueta se replica en el "Order Summary" como valor del campo "Product". En el listado de "Products offered" se puede confirmar que el producto correspondiente sí es Gasohol 84, pero su nombre comercial visible está mal asignado y muestra el nombre de una persona, junto con una descripción sin sentido ("aklfjalkjfslkajflakj"). Esto genera confusión grave: el comprador no puede identificar qué combustible está solicitando.

**Recomendación:**
Verificar el mapeo de datos del catálogo de productos: el campo que alimenta el nombre visible del producto parece estar tomando un campo de "contacto" o "responsable" en lugar del campo "nombre de producto". Reemplazar los datos de prueba (placeholders) por nombres de producto reales y consistentes (p. ej. "Gasohol 84") antes de cualquier entrega o demostración.

---

##### PROBLEMA #2: Cálculo de factura inconsistente con el detalle de la orden

**Severidad:** 4

**Heurística violada:** Usability - Prevención de errores / Consistencia de datos

**Problema:**
En las facturas generadas (`Invoice`), el campo "AMOUNT" de la línea de detalle no corresponde a `Cantidad × Precio unitario`. Por ejemplo, en uno de los pedidos: 25 000 L × S/ 35.00 = S/ 875,000.00, pero el sistema muestra "Amount: S/ 741,525.42" y luego calcula el IGV (18%) sobre esa cifra incorrecta para finalmente llegar al Total correcto (S/ 875,000.00) por una vía de cálculo inversa (como si el Total ya incluyera el IGV y se derivara el subtotal restándolo). El mismo patrón se repite en otro pedido (4 L × S/16.20 debería ser S/64.80, pero se muestra "S/54.92") y en otro más (20 000 L × S/40.00 debería ser S/800,000.00, pero se muestra "S/677,966.10"). Si bien el "Total" final suele coincidir con lo esperado, el desglose intermedio (Subtotal e IGV) es matemáticamente incorrecto y puede generar desconfianza o problemas contables/tributarios reales si esta factura se usa formalmente.

**Recomendación:**
Corregir la lógica de cálculo de la factura: `Subtotal = Cantidad × Precio Unitario`, `IGV = Subtotal × 18%`, `Total = Subtotal + IGV`. Verificar con pruebas unitarias que el monto de línea (AMOUNT) siempre sea igual a QTY × UNIT PRICE.

---

##### PROBLEMA #3: Estado de pago contradictorio entre vistas del mismo pedido

**Severidad:** 4

**Heurística violada:** Usability - Visibilidad del estado del sistema

**Problema:**
Para un mismo pedido, la vista de "Detalle de Orden" del proveedor muestra el estado **"Pendiente de pago"** / "Esperando el pago del comprador", mientras que en esa misma instancia de tiempo la factura accesible desde el módulo de Pagos del comprador ya exhibe el badge **"PAID"** en verde. Esta contradicción se repite de forma sistemática en al menos tres pedidos distintos de las capturas, lo que sugiere un problema de sincronización entre el módulo de Pedidos (lado proveedor) y el módulo de Pagos (lado comprador), no un caso aislado.

**Recomendación:**
Implementar una única fuente de verdad para el estado de pago del pedido (idealmente en el backend), de forma que cualquier vista —proveedor o comprador— consulte el mismo estado actualizado. Considerar actualización en tiempo real (websockets o polling) para reflejar cambios de estado sin requerir recarga manual.

---

##### PROBLEMA #4: Datos de Conductor y Vehículo no visibles para el comprador

**Severidad:** 3

**Heurística violada:** Usability - Consistencia y estándares

**Problema:**
Una vez que el proveedor asigna conductor y vehículo a un pedido despachado (visible correctamente en su propia vista, p. ej. "Marcos Perez" y "Volvo FH-3000"), la vista equivalente del comprador para el mismo pedido sigue mostrando **"Driver: Not assigned"** y **"Vehicle: Not assigned"**, incluso en distintos idiomas de interfaz. Esto resta confianza al comprador, que no puede verificar quién transporta su pedido ni en qué vehículo, información relevante para el seguimiento de la entrega.

**Recomendación:**
Revisar el endpoint o la consulta que alimenta el detalle de orden en la vista del comprador, asegurando que incluya los campos `driver` y `vehicle` ya asignados por el proveedor, en lugar de mostrar siempre el valor por defecto "Not assigned".

---

##### PROBLEMA #5: Datos de prueba (placeholders) visibles en producción

**Severidad:** 3

**Heurística violada:** Usability - Estética y diseño minimalista / Profesionalismo

**Problema:**
Se identifican múltiples elementos de datos de relleno (placeholder/lorem-ipsum) que no fueron reemplazados antes de las capturas: la descripción del proveedor "jfaeljfalkfjalsfjaef", la descripción de producto "aklfjalkjfslkajflakj", el conductor con nombre "Jose el Carry" y la placa de vehículo "AHd-sdgsdg". Estos textos no aportan información real y, de aparecer ante un usuario o cliente potencial, comunican falta de cuidado y profesionalismo en el producto.

**Recomendación:**
Reemplazar todos los datos semilla (seed data) de demostración por información realista y representativa antes de cualquier entrega, demo o despliegue visible a terceros.

---

##### PROBLEMA #6: Mezcla de idiomas dentro de la misma pantalla

**Severidad:** 2

**Heurística violada:** Usability - Consistencia y estándares

**Problema:**
En el panel de notificaciones con interfaz en español, los textos de las notificaciones individuales aparecen en inglés ("New Request", "Order Delivered", "Payment Received"). De forma inversa, en otra captura con interfaz en inglés, la primera notificación aparece en español ("Solicitud enviada"). En la tabla "Mejores Clientes" en español, el badge de sector se muestra en inglés ("TRANSPORT"). Esta mezcla aleatoria de idiomas, sin relación con el selector EN/ES visible en la barra superior, genera una experiencia inconsistente y poco confiable, especialmente relevante dado que el enunciado del proyecto exige soporte i18n (en_US / es_419) de forma completa.

**Recomendación:**
Auditar todos los textos generados dinámicamente (notificaciones, etiquetas de catálogo) para asegurar que respeten el idioma seleccionado por el usuario, utilizando claves de traducción (i18n keys) en lugar de cadenas de texto fijas en el código o en los datos semilla.

---

##### PROBLEMA #7: Bug de cálculo de tiempo relativo ("NaNmo ago")

**Severidad:** 3

**Heurística violada:** Usability - Prevención de errores

**Problema:**
En el panel de Notificaciones, la marca de tiempo relativa de cada notificación muestra el texto **"NaNmo ago"** en lugar de un valor legible como "hace 5 minutos" o "2h ago". Esto evidencia un error en el cálculo de diferencia de fechas (probablemente una operación aritmética sobre una fecha indefinida o mal formateada que produce `NaN`, concatenada con el sufijo "mo ago").

**Recomendación:**
Revisar la función de formateo de fecha relativa; validar que las fechas de origen (timestamp de la notificación) sean válidas antes de calcular la diferencia, y mostrar un valor de respaldo (p. ej. la fecha completa) si el cálculo no puede resolverse.

---

##### PROBLEMA #8: Unidad de cantidad ilegible en formulario de solicitud (versión español)

**Severidad:** 2

**Heurística violada:** Usability - Visibilidad del estado del sistema

**Problema:**
En el formulario "Crear Solicitud de Combustible" en español, la etiqueta del campo de cantidad se muestra como **"Cantidad (—)"**, con un carácter no legible en lugar de la unidad de medida. La versión en inglés del mismo formulario sí muestra correctamente "Quantity (L)". Esto deja al usuario sin saber en qué unidad debe ingresar la cantidad.

**Recomendación:**
Corregir la cadena de traducción al español para que incluya explícitamente la unidad: "Cantidad (L)".

---

##### PROBLEMA #9: Ambigüedad en el formato numérico de cantidades

**Severidad:** 3

**Heurística violada:** Usability - Prevención de errores

**Problema:**
El campo "Cantidad (L)" muestra el valor **"23.000"**, que en formato latinoamericano podría leerse como 23 (con tres decimales) o como 23 000 según convención de separador de miles. El panel contiguo indica "El equipo necesita: 23000 L", lo que sugiere que el sistema interpreta "23.000" como 23 000 litros. Sin una aclaración visual (separador de miles consistente, o un step/formato explícito en el input), el usuario podría ingresar o interpretar mal una cantidad, con un impacto económico significativo dado que el "Total estimado" depende directamente de este valor (S/ 1,035,000.00 en este caso).

**Recomendación:**
Aplicar un formato de número consistente con separadores de miles claros (p. ej. "23,000" o "23 000" según configuración regional) y considerar mostrar el valor en palabras o con una unidad clara junto al campo, además de una validación que compare la cantidad solicitada contra el stock disponible y la necesidad del equipo antes de habilitar el envío.

---

##### PROBLEMA #10: Unidad de volumen inconsistente entre módulos ("MT" vs. "L")

**Severidad:** 2

**Heurística violada:** Information Architecture - ¿Es comprensible? (Labeling Systems)

**Problema:**
En el módulo de "Reports" / "Reportes & Analítica" (Provider), la columna "Total Volume" se etiqueta en toneladas métricas ("142,500.0 MT", "89,340.5 MT"), mientras que en absolutamente todo el resto de la aplicación (catálogo, pedidos, facturas) el combustible se mide y muestra en litros (L). Esta inconsistencia de unidades entre módulos puede llevar a interpretaciones erróneas sobre los volúmenes reales manejados por cada cliente, además de ser una unidad poco habitual para combustibles líquidos minoristas/industriales medidos por volumen.

**Recomendación:**
Unificar la unidad de medida del volumen de combustible en toda la aplicación (recomendado: Litros, consistente con el resto del producto), o, si se requiere manejar distintas unidades por tipo de cliente/sector, indicarlo explícitamente y permitir su conversión visible.

---

##### PROBLEMA #11: Cifra de ingresos truncada en el dashboard de reportes

**Severidad:** 2

**Heurística violada:** Usability - Visibilidad del estado del sistema

**Problema:**
La tarjeta "TOTAL SALES REVENUE" muestra el valor **"S/ 7,735,703.0"**, que aparenta estar cortado por el ancho de la tarjeta (un dígito decimal faltante o mal renderizado), mientras que la pantalla equivalente en "Your Clients Reports" sí muestra correctamente "S/ 7,735,703" sin decimales. Esta inconsistencia visual entre componentes que muestran el mismo dato sugiere un problema de truncamiento de texto o de formato de número no controlado en una de las dos vistas.

**Recomendación:**
Revisar el contenedor de la tarjeta de KPI para que el texto no se corte (`overflow`, `font-size` responsivo, o `text-overflow: ellipsis` controlado) y unificar el formato numérico (con o sin decimales) entre ambas pantallas.

---

##### PROBLEMA #12: Indicador de estado sin etiqueta de texto en tabla de clientes

**Severidad:** 2

**Heurística violada:** Usability - Reconocimiento antes que recuerdo

**Problema:**
En la tabla "Mejores Clientes", la columna "Estado" muestra únicamente una pequeña pastilla de color naranja, sin ningún texto que indique qué representa ese estado (p. ej. "Activo", "Pendiente", "Inactivo"). El usuario debe memorizar o inferir el significado del color, lo cual viola el principio de reconocimiento antes que recuerdo y además es problemático en términos de accesibilidad (no debe depender solo del color para transmitir significado).

**Recomendación:**
Añadir una etiqueta de texto visible junto al indicador de color (como sí ocurre en la tabla equivalente "Client Portfolio", donde el estado se muestra como texto: "ACTIVE", "PENDING", "INACTIVE").

---

##### PROBLEMA #13: Dashboard del proveedor no refleja actividad reciente

**Severidad:** 3

**Heurística violada:** Usability - Visibilidad del estado del sistema

**Problema:**
Inmediatamente después de que el comprador envía exitosamente 3 solicitudes de combustible (visibles en la columna izquierda de la captura, todas registradas con su Request ID), el "Provider Dashboard" del lado derecho muestra **"PENDING REQUESTS: 0"** y **"ACTIVE ORDERS: 0"**. Esta discrepancia entre la actividad real y el resumen del dashboard podría hacer que el proveedor no se entere de solicitudes pendientes que requieren su atención.

**Recomendación:**
Verificar que los contadores del dashboard del proveedor consulten datos en tiempo real (o se actualicen automáticamente tras cada solicitud nueva), en lugar de depender de una carga de página obsoleta o de una agregación con retraso (cache desincronizado).

---

##### PROBLEMA #14: Uso de Yape como método de pago para montos B2B muy elevados

**Severidad:** 2

**Heurística violada:** Usability - Match entre el sistema y el mundo real

**Problema:**
Las capturas de "Payment History" muestran pagos de **S/ 875,000.00** registrados con el método **"YAPE"**, una billetera digital peruana orientada a pagos entre personas y comercios pequeños, con límites de transacción muy por debajo de esa cifra en la realidad. Esto resulta poco realista para una plataforma B2B industrial que mueve montos de seis cifras, y podría confundir a evaluadores o usuarios sobre los métodos de pago efectivamente soportados o sobre la seriedad del flujo transaccional.

**Recomendación:**
Para transacciones de este volumen, considerar y mostrar métodos de pago corporativos más realistas (transferencia bancaria, línea de crédito, pago contra factura a 30/60 días, tarjeta corporativa), reservando Yape u otras billeteras móviles para escenarios de menor monto si la plataforma decide soportar pagos mixtos B2B/B2C.

---

##### PROBLEMA #15: Transacción de ejemplo de un volumen no representativo del modelo B2B

**Severidad:** 1

**Heurística violada:** Usability - Match entre el sistema y el mundo real

**Problema:**
La factura de ejemplo de pago muestra una compra de solo **4 L** de Diesel B5, una cantidad propia de un consumidor final en un grifo minorista y no de una operación B2B entre empresas de transporte/logística/minería, que es el segmento objetivo declarado de la plataforma (según las demás pantallas, donde los pedidos van de 300 L a 25 000 L). Si bien es un único caso aislado de bajo impacto, contrasta con el resto de los datos de la aplicación.

**Recomendación:**
Ajustar los datos de ejemplo de facturación para que reflejen consistentemente cantidades industriales/comerciales, coherentes con el resto del sistema.

---

##### PROBLEMA #16: Error ortográfico recurrente "premiun"

**Severidad:** 1

**Heurística violada:** Usability - Consistencia y estándares

**Problema:**
El nombre de producto "Diesel B5 premiun" contiene un error ortográfico recurrente; la palabra correcta en inglés (idioma adoptado para nombres de producto, según otras pantallas) es "premium". Este error se repite consistentemente en todas las pantallas donde aparece el producto, incluyendo el formulario de creación del mismo, lo que indica que el error está en el dato de origen, no es un error de transcripción puntual.

**Recomendación:**
Corregir el nombre del producto en la base de datos / catálogo a "Diesel B5 Premium".

---

##### PROBLEMA #17: Falta de indicación de campos obligatorios en el formulario de registro de cuenta

**Severidad:** 2

**Heurística violada:** Usability - Consistencia y estándares / Prevención de errores

**Problema:**
El formulario de registro de cuenta ("Account Type", "Company Information", "User Account") no utiliza ningún indicador visual (como el asterisco rojo) para señalar qué campos son obligatorios, a diferencia del formulario "Register New Driver" del mismo sistema, donde todos los campos sí están marcados con un asterisco rojo junto a la etiqueta. Esta inconsistencia entre formularios puede llevar a que el usuario no sepa de antemano qué información es indispensable antes de enviar el formulario de registro.

**Recomendación:**
Aplicar el mismo patrón de marcado de campos obligatorios (asterisco rojo) de forma consistente en todos los formularios del sistema, incluyendo el de registro de cuenta.

---

##### PROBLEMA #18: Gráficos sin valores ni leyenda claros

**Severidad:** 2

**Heurística violada:** Information Architecture - ¿Es comprensible?

**Problema:**
Varios gráficos del módulo de Reportes (gráfico de barras "Sales trend", gráfico de dona "Gasto por Tipo de Combustible", gráfico de barras "Ingresos por Tipo de Combustible") no muestran valores numéricos directamente sobre las barras/segmentos ni una leyenda detallada visible en la captura, dificultando que el usuario interprete con precisión la magnitud representada sin pasar el cursor sobre cada elemento (cuya interacción no puede confirmarse en una captura estática, pero que de no existir constituye una barrera de comprensión).

**Recomendación:**
Incluir etiquetas de datos (data labels) visibles sobre los elementos gráficos principales, o al menos un tooltip accesible y persistente, junto con una leyenda clara que indique unidades y períodos representados.

---

#### Conclusión general de la sesión

La aplicación **FullTank (PrimeFuel)** demuestra una arquitectura de flujo de pedidos sólida en su estructura general (solicitud → aceptación → despacho → confirmación → pago → factura), con buena segmentación de roles (Comprador/Solicitante vs. Proveedor/Distribuidor) y vistas duales bien diferenciadas por color e identificación de rol en el header. Sin embargo, se identificaron **problemas de severidad alta (4)** relacionados con la integridad de los datos mostrados —específicamente el mapeo erróneo de nombre de producto y los cálculos incorrectos de facturación— que deben resolverse antes de cualquier entrega o demostración formal, ya que afectan directamente la confianza del usuario en la exactitud económica de la plataforma. Asimismo, se recomienda una limpieza exhaustiva de datos de prueba (seed data) y una revisión de sincronización de estado entre las vistas de comprador y proveedor para un mismo pedido.


### 5.4. Video About-the-Product.

En este video se mostraron las principales funcionalidades de la aplicación, así como el propósito de nuestro producto y el alcance que tiene.

<div align="center">
  <img src="assets/chapter05/abouttheproduct.png"
       alt="About The Product"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link del video: [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQDGDLnIK8O6RZj35jZ6adW0AWDV_x76LAIZBgrpXqgmH60?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=8rpPcW`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQDGDLnIK8O6RZj35jZ6adW0AWDV_x76LAIZBgrpXqgmH60?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=8rpPcW)


## Conclusiones y recomendaciones

- Durante el Sprint se logró implementar las funcionalidades principales de Frigora tanto a nivel de frontend como de backend, permitiendo contar con una versión funcional de la plataforma capaz de gestionar información relacionada con usuarios, técnicos, equipos y servicios de mantenimiento.

- La integración entre la interfaz de usuario y los servicios backend permitió validar el flujo completo de varias funcionalidades del sistema, reduciendo riesgos de integración y detectando tempranamente posibles inconsistencias entre los modelos de datos y la experiencia de usuario.

- La definición de endpoints REST, junto con la implementación de módulos específicos para cada entidad del sistema, contribuyó a establecer una arquitectura organizada y escalable que facilitará el desarrollo de nuevas funcionalidades en futuras iteraciones.

- El uso de Scrum, Trello y GitHub permitió mantener una adecuada coordinación entre los miembros del equipo, favoreciendo la distribución de tareas, el seguimiento del progreso y la integración continua de los avances realizados durante el Sprint.

- La implementación simultánea de frontend y backend permitió obtener una versión más cercana al producto final, haciendo posible validar procesos completos de negocio en lugar de únicamente aspectos visuales o prototipos de interfaz.

- El Sprint permitió consolidar la base tecnológica de Frigora, dejando preparados los componentes necesarios para incorporar funcionalidades avanzadas como analítica de consumo energético, generación de reportes y sistemas de notificaciones en las siguientes iteraciones.


## Video About-the-Team

En este video hemos explicado las actividades y como hemos trabajado en equipo durante el desarrollo de nuestro producto Frigora.

<div align="center">
  <img src="assets/chapter05/abouttheteam.png"
       alt="About The Team"
       style="max-width: 90%; border-radius: 12px; box-shadow: 0 4px 12px rgba(0,0,0,0.2);">
</div>

Link del video: [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBBugoy_-XnQ6jwLUoHZ-YWAYTfKVYWk_x891LYGv_WTjg?e=D1S3Q8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBBugoy_-XnQ6jwLUoHZ-YWAYTfKVYWk_x891LYGv_WTjg?e=D1S3Q8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D)

---

## Anexos

| Recurso | URL |
| :--- | :--- |
| Organización del proyecto | https://github.com/ColdTech-Peru |
| Repositorio del reporte | https://github.com/ColdTech-Peru/Report |
| Repositorio de la Landing Page | https://github.com/ColdTech-Peru/Landing-Page |
| Repositorio del Frontend |https://github.com/ColdTech-Peru/Frigora-Frontend|
| Repositorio del Backend | https://github.com/ColdTech-Peru/Frigora-Platform |
| Frontend desplegado | https://frigora-frontend.vercel.app/ |
| Fake API desplegado | https://fake-api-0233.onrender.com/ |
| Landing Page desplegada | https://coldtech-peru.github.io/Landing-Page/ |
| Backend desplegado | https://frigora-platform.onrender.com/ |
| Video de exposición AV1 | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQAwVSq8fQjySJapi2zSl6heAXLBV3ex_fNvqulDDFLlPh8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=h9sTbw`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u20201f788_upc_edu_pe/IQAwVSq8fQjySJapi2zSl6heAXLBV3ex_fNvqulDDFLlPh8?nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D&e=h9sTbw) |
| Video AV2 | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBVRZ0G1whGSqBKDTGPR81pASFd9HwcxJW7oGQpl_YesdM?e=4xgzuP&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBVRZ0G1whGSqBKDTGPR81pASFd9HwcxJW7oGQpl_YesdM?e=4xgzuP&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| Video About-The-Product | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQDGDLnIK8O6RZj35jZ6adW0AWDV_x76LAIZBgrpXqgmH60?e=eLGBJH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQDGDLnIK8O6RZj35jZ6adW0AWDV_x76LAIZBgrpXqgmH60?e=eLGBJH&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |
| Video About-The-Team | [`https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBBugoy_-XnQ6jwLUoHZ-YWAYTfKVYWk_x891LYGv_WTjg?e=D1S3Q8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D`](https://upcedupe-my.sharepoint.com/:v:/g/personal/u202321264_upc_edu_pe/IQBBugoy_-XnQ6jwLUoHZ-YWAYTfKVYWk_x891LYGv_WTjg?e=D1S3Q8&nav=eyJyZWZlcnJhbEluZm8iOnsicmVmZXJyYWxBcHAiOiJTdHJlYW1XZWJBcHAiLCJyZWZlcnJhbFZpZXciOiJTaGFyZURpYWxvZy1MaW5rIiwicmVmZXJyYWxBcHBQbGF0Zm9ybSI6IldlYiIsInJlZmVycmFsTW9kZSI6InZpZXcifX0%3D) |



