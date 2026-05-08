![UPC_LOGO.png](assets/img/caratula/UPC_LOGO.png)

# UNIVERSIDAD PERUANA DE CIENCIAS APLICADAS

**Facultad de Ingeniería**

**Carrera:** Ingeniería de Software

**Ciclo Académico:** 2026-10

**Código del Curso:** 1ASI0729

**Curso:** Desarrollo de Aplicaciones Open Source

**NRC:** 10177

**Profesor:** Hugo Allan Mori Paiva

---

## INFORME DE TRABAJO FINAL — TB1

**Startup:** VentixCorp

**Producto:** Ventix

---

### INTEGRANTES:

| Apellidos y Nombres              | Código de Alumno |
|----------------------------------|------------------|
| Cáceres Pizarro, Albino Florencio | U201923820      |
| Sanchez Osorio, Ruth Yanira      | U20241C626       |
| Suarez Chinga, Geraldine         | U20241C804       |
| Taipe Sangama, Jorge Francisco   | U202313458       |

**Lima, Mayo de 2026**

---

# Registro de versiones del informe

| Versión | Fecha      | Autor                           | Descripción de la modificación                                          |
|---------|------------|---------------------------------|-------------------------------------------------------------------------|
| 0.1     | 2026-04-23 | Taipe Sangama, Jorge Francisco  | Creación del documento y estructura inicial del informe.                |
| 0.2     | 2026-04-23 | Suarez Chinga, Geraldine        | Rellenado del documento y avance progresivo del Capítulo I.             |
| 0.3     | 2026-04-25 | Sanchez Osorio, Ruth Yanira     | Elaboración de diagramas y propuesta visual del Landing Page.           |
| 0.4     | 2026-04-28 | Cáceres Pizarro, Albino Florencio | Integración del Landing Page y gestión de ramas en GitHub.            |
| 1.0     | 2026-05-01 | Equipo VentixCorp               | Versión consolidada para entrega del TB1.                               |

---

# Project Report Collaboration Insights

**URL de la organización en GitHub:** https://github.com/Open-10177

**URL del repositorio del informe:** https://github.com/Open-10177/VentixProject-Report

### Reporte de Colaboración de la entrega del TB1:

Durante la primera fase de elaboración del informe, el equipo Ventix centró sus esfuerzos en la construcción de los fundamentos conceptuales, de investigación y diseño inicial del proyecto. Cada integrante asumió un rol activo en la redacción, modelado y documentación de secciones clave del reporte, asegurando una coherencia entre la teoría, la metodología y la propuesta tecnológica. La colaboración se gestionó mediante el repositorio público en GitHub aplicando GitFlow Workflow, con ramas dedicadas para cada capítulo del informe (`docs/chapter-1`, `docs/chapter-2`, etc.) y commits siguiendo la especificación Conventional Commits.

### Desarrollo del informe por integrante:

**Taipe Sangama, Jorge Francisco:** Responsable de la creación del repositorio y la estructura inicial del informe. Lideró la elaboración del Capítulo IV (Product Design), desarrollando el Diagrama de Clases, la arquitectura del sistema y los diagramas de Domain-Driven Software Architecture. Coordinó las reuniones de Sprint Planning y la integración técnica entre los miembros del equipo.

**Suarez Chinga, Geraldine:** Contribuyó en la redacción del Capítulo I (Introducción) y Capítulo II (Requirements Elicitation & Analysis), desarrollando la información sobre antecedentes, problemática, segmentos objetivo y análisis de entrevistas. Participó activamente en la coordinación grupal y en la consolidación de las decisiones de diseño.

**Sanchez Osorio, Ruth Yanira:** Diseñó los Wireframes, Mock-ups y Prototipos de la Landing Page y Web Application en Figma, aportando la propuesta visual y de interacción del producto. Colaboró en la elaboración del Capítulo IV (Product Design), integrando el Design System basado en Material Design.

**Cáceres Pizarro, Albino Florencio:** Participó en la implementación del Landing Page, realizando ajustes en las secciones de Services, Testimonials y Pricing. Gestionó los commits en GitHub (rama `develop`) y resolvió conflictos de merge durante la integración de los capítulos del documento. Contribuyó en el Capítulo V (Product Implementation, Validation & Deployment).

### Capturas de Analíticos de Colaboración en GitHub:

**Figura 1. Overview de contribuciones del equipo en el repositorio del Project Report**

*[Insertar captura del panel Insights > Contributors del repositorio VentixProject-Report]*

*Figura 1. Panel Overview de GitHub mostrando el flujo de commits de los integrantes durante la elaboración del informe TB1. Fuente: GitHub Insights — Repositorio Open-10177/VentixProject-Report.*

**Figura 2. Network Graph del repositorio del informe**

*[Insertar captura del Network Graph del repositorio]*

*Figura 2. Network Graph del repositorio VentixProject-Report en GitHub, evidenciando el flujo de ramas `docs/chapter-*` y su integración a `develop` y `main` siguiendo el modelo GitFlow. Fuente: GitHub — Repositorio Open-10177/VentixProject-Report.*

---

# Contenido

## Tabla de Contenidos

### [Registro de versiones del informe](#registro-de-versiones-del-informe)
### [Project Report Collaboration Insights](#project-report-collaboration-insights)
### [Contenido](#contenido)
### [Student Outcome](#student-outcome)

---

### [Capítulo I: Introducción](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#cap%C3%ADtulo-i-introducci%C3%B3n)
- [1.1. Startup Profile](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#11-startup-profile)
    - [1.1.1. Descripción de la Startup](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#111-descripci%C3%B3n-de-la-startup)
    - [1.1.2. Perfiles de integrantes del equipo](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#112-perfiles-de-integrantes-del-equipo)
- [1.2. Solution Profile](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#12-solution-profile)
    - [1.2.1. Antecedentes y problemática](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#121-antecedentes-y-problem%C3%A1tica)
    - [1.2.2. Lean UX Process](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#122-lean-ux-process)
        - [1.2.2.1. Lean UX Problem Statements](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#1221-lean-ux-problem-statements)
        - [1.2.2.2. Lean UX Assumptions](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#1222-lean-ux-assumptions)
        - [1.2.2.3. Lean UX Hypothesis Statements](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#1223-lean-ux-hypothesis-statements)
        - [1.2.2.4. Lean UX Canvas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#1224-lean-ux-canvas)
- [1.3. Segmentos objetivo](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-1.md#13-segmentos-objetivo)

---

### [Capítulo II: Requirements Elicitation & Analysis](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#cap%C3%ADtulo-ii-requirements-elicitation--analysis)
- [2.1. Competidores](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#21-competidores)
    - [2.1.1. Análisis competitivo](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#211-an%C3%A1lisis-competitivo)
    - [2.1.2. Estrategias y tácticas frente a competidores](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#212-estrategias-y-t%C3%A1cticas-frente-a-competidores)
- [2.2. Entrevistas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#22-entrevistas)
    - [2.2.1. Diseño de entrevistas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#221-dise%C3%B1o-de-entrevistas)
    - [2.2.2. Registro de entrevistas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#222-registro-de-entrevistas)
    - [2.2.3. Análisis de entrevistas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#223-an%C3%A1lisis-de-entrevistas)
- [2.3. Needfinding](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#23-needfinding)
    - [2.3.1. User Personas](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#231-user-personas)
    - [2.3.2. User Task Matrix](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#232-user-task-matrix)
    - [2.3.3. User Journey Mapping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#233-user-journey-mapping)
    - [2.3.4. Empathy Mapping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#234-empathy-mapping)
    - [2.3.5. As-Is Scenario Mapping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#235-as-is-scenario-mapping)
- [2.4. Big Picture Event Storming](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#24-big-picture-event-storming)
- [2.5. Ubiquitous Language](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-2.md#25-ubiquitous-language)

---

### [Capítulo III: Requirements Specification](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-3.md#cap%C3%ADtulo-iii-requirements-specification)
- [3.1. To-Be Scenario Mapping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-3.md#31-to-be-scenario-mapping)
- [3.2. User Stories](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-3.md#32-user-stories)
- [3.3. Impact Mapping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-3.md#33-impact-mapping)
- [3.4. Product Backlog](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-3.md#34-product-backlog)

---

### [Capítulo IV: Product Design](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#cap%C3%ADtulo-iv-product-design)
- [4.1. Style Guidelines](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#41-style-guidelines)
    - [4.1.1. General Style Guidelines](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#411-general-style-guidelines)
    - [4.1.2. Web Style Guidelines](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#412-web-style-guidelines)
- [4.2. Information Architecture](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#42-information-architecture)
    - [4.2.1. Organization Systems](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#421-organization-systems)
    - [4.2.2. Labeling Systems](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#422-labeling-systems)
    - [4.2.3. SEO Tags and Meta Tags](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#423-seo-tags-and-meta-tags)
    - [4.2.4. Searching Systems](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#424-searching-systems)
    - [4.2.5. Navigation Systems](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#425-navigation-systems)
- [4.3. Landing Page UI Design](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#43-landing-page-ui-design)
    - [4.3.1. Landing Page Wireframe](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#431-landing-page-wireframe)
    - [4.3.2. Landing Page Mock-up](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#432-landing-page-mock-up)
- [4.4. Web Applications UX/UI Design](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#44-web-applications-uxui-design)
    - [4.4.1. Web Applications Wireframes](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#441-web-applications-wireframes)
    - [4.4.2. Web Applications Wireflow Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#442-web-applications-wireflow-diagrams)
    - [4.4.3. Web Applications Mock-ups](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#443-web-applications-mock-ups)
    - [4.4.4. Web Applications User Flow Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#444-web-applications-user-flow-diagrams)
- [4.5. Web Applications Prototyping](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#45-web-applications-prototyping)
- [4.6. Domain-Driven Software Architecture](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#46-domain-driven-software-architecture)
    - [4.6.1. Design-Level Event Storming](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#461-design-level-event-storming)
    - [4.6.2. Software Architecture Context Diagram](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#462-software-architecture-context-diagram)
    - [4.6.3. Software Architecture Container Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#463-software-architecture-container-diagrams)
    - [4.6.4. Software Architecture Components Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#464-software-architecture-components-diagrams)
- [4.7. Software Object-Oriented Design](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#47-software-object-oriented-design)
    - [4.7.1. Class Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#471-class-diagrams)
- [4.8. Database Design](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#48-database-design)
    - [4.8.1. Database Diagrams](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-4.md#481-database-diagrams)

---

### [Capítulo V: Product Implementation, Validation & Deployment](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#cap%C3%ADtulo-v-product-implementation-validation--deployment)
- [5.1. Software Configuration Management](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#51-software-configuration-management)
    - [5.1.1. Software Development Environment Configuration](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#511-software-development-environment-configuration)
    - [5.1.2. Source Code Management](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#512-source-code-management)
    - [5.1.3. Source Code Style Guide & Conventions](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#513-source-code-style-guide--conventions)
    - [5.1.4. Software Deployment Configuration](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#514-software-deployment-configuration)
- [5.2. Landing Page, Services & Applications Implementation](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#52-landing-page-services--applications-implementation)
    - **Sprint 1**
        - [5.2.1.1. Sprint Planning 1](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5211-sprint-planning-1)
        - [5.2.1.2. Aspect Leaders and Collaborators](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5212-aspect-leaders-and-collaborators)
        - [5.2.1.3. Sprint Backlog 1](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5213-sprint-backlog-1)
        - [5.2.1.4. Development Evidence for Sprint Review](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5214-development-evidence-for-sprint-review)
        - [5.2.1.5. Execution Evidence for Sprint Review](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5215-execution-evidence-for-sprint-review)
        - [5.2.1.6. Services Documentation Evidence for Sprint Review](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5216-services-documentation-evidence-for-sprint-review)
        - [5.2.1.7. Software Deployment Evidence for Sprint Review](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5217-software-deployment-evidence-for-sprint-review)
        - [5.2.1.8. Team Collaboration Insights during Sprint](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#5218-team-collaboration-insights-during-sprint)

---

### [Conclusiones](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#conclusiones)
- [Conclusiones y recomendaciones](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#conclusiones-y-recomendaciones)

### [Bibliografía](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#bibliograf%C3%ADa)

### [Anexos](https://github.com/Open-10177/VentixProject-Report/blob/main/docs/chapter-5.md#anexos)
- Anexo A: Enlaces de Despliegue y Repositorios
- Anexo B: Videos de Exposiciones

---

# Student Outcome

El curso contribuye al cumplimiento del **Student Outcome ABET:**

**ABET – EAC - Student Outcome 3**

**Criterio:** Capacidad de comunicarse efectivamente con un rango de audiencias.

En el siguiente cuadro se describe las acciones realizadas y enunciados de conclusiones por parte del grupo, que permiten sustentar el haber alcanzado el logro del ABET – EAC - Student Outcome 3.

| Criterio específico                                                       | Acciones realizadas                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                            | Conclusiones                                                                                                                                                                                                                                                                                                                                                                                                                                                                            |
|---------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **Comunica oralmente con efectividad a diferentes rangos de audiencia.**  | **Cáceres Pizarro, Albino Florencio**<br/>**TB1:** Participé en las reuniones de Sprint Planning explicando verbalmente las tareas asignadas a la integración del Landing Page y los conflictos de merge resueltos en GitHub. Adapté el lenguaje técnico para coordinar con compañeros con distinto nivel de familiaridad con Git, asegurando que el equipo comprendiera el flujo de trabajo definido por GitFlow.<br/><br/>**Sanchez Osorio, Ruth Yanira**<br/>**TB1:** Presenté oralmente al equipo las propuestas visuales del Landing Page y los Wireframes de la Web Application, explicando las decisiones de diseño basadas en Material Design. Comuniqué de forma clara los criterios de Design System adaptando la explicación según el rol técnico o de diseño del receptor.<br/><br/>**Suarez Chinga, Geraldine**<br/>**TB1:** Contribuí en la exposición oral del proceso de investigación de usuarios y recolección de datos de las entrevistas. Interpreté frente al equipo las gráficas y estadísticas obtenidas del análisis de entrevistas, comunicando los hallazgos a una audiencia técnica y no técnica.<br/><br/>**Taipe Sangama, Jorge Francisco**<br/>**TB1:** Presenté oralmente el Diagrama de Clases y la Arquitectura de Software del sistema en reuniones del equipo, adaptando el nivel de detalle técnico según el perfil del público. Esto contribuyó a la integración de los componentes en la arquitectura general y permitió alinear la visión técnica entre los miembros con distinto grado de experiencia en Domain-Driven Design.       | **Conclusión TB1:** La comunicación oral fue clave para unificar criterios y garantizar que todos los integrantes comprendieran los objetivos del proyecto. Las presentaciones internas y discusiones guiadas permitieron consolidar decisiones de diseño y técnicas de manera efectiva, fortaleciendo la cohesión del equipo y asegurando que cada miembro pudiera explicar el aporte realizado a audiencias con distintos perfiles.                                                   |
| **Comunica por escrito con efectividad a diferentes rangos de audiencia.** | **Cáceres Pizarro, Albino Florencio**<br/>**TB1:** Redacté los mensajes de commits siguiendo la especificación Conventional Commits para el repositorio de la Landing Page, garantizando que cualquier integrante del equipo o stakeholder externo pudiera comprender los cambios introducidos. Documenté la organización de ramas (`main`, `develop`, `docs/chapter-*`) en el Capítulo V del informe.<br/><br/>**Sanchez Osorio, Ruth Yanira**<br/>**TB1:** Redacté las secciones de Style Guidelines, Information Architecture y Landing Page UI Design del Capítulo IV del informe, adaptando la redacción para que fuera comprensible tanto para audiencias técnicas (desarrolladores) como no técnicas (stakeholders del negocio). Documenté los criterios de Wireframes y Mock-ups con descripciones claras y concisas.<br/><br/>**Suarez Chinga, Geraldine**<br/>**TB1:** Redacté las secciones de antecedentes, problemática, segmentos objetivo y análisis de entrevistas del Capítulo I y II del informe, aplicando un lenguaje accesible y estructurado en formato APA. Esto permitió que la información fuera comprensible para audiencias académicas y para el equipo de desarrollo.<br/><br/>**Taipe Sangama, Jorge Francisco**<br/>**TB1:** Redacté la documentación técnica del Capítulo IV (Domain-Driven Software Architecture, Class Diagrams, Database Design) y del Capítulo V (Software Configuration Management, Sprint 1). Apliqué nomenclatura técnica en inglés siguiendo las convenciones del curso y adapté el nivel de detalle según el lector. | **Conclusión TB1:** La comunicación escrita permitió documentar de manera estructurada las decisiones de diseño, arquitectura e implementación del proyecto Ventix. La aplicación del formato Markdown, el uso de Conventional Commits y la redacción colaborativa en GitHub aseguraron que el informe fuera coherente, trazable y comprensible para audiencias diversas. El uso de nomenclatura técnica en inglés y formato APA reforzó la calidad profesional de los entregables.       |
