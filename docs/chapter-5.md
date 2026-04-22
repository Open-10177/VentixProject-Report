# Capítulo V: Product Implementation, Validation & Deployment

## 5.1. Software Configuration Management.

En esta sección se describen las decisiones, convenciones y principios adoptados por el equipo para garantizar la coherencia, trazabilidad y control de versiones durante el ciclo de vida del desarrollo de la solución Ventix. Se establecen los lineamientos para la configuración del entorno de desarrollo, gestión del código fuente, convenciones de estilo y configuración de despliegue.

### 5.1.1. Software Development Environment Configuration.

En esta sección se especifican los productos de software utilizados durante el ciclo de vida del proyecto, incluyendo el nombre de cada herramienta, su propósito técnico específico dentro del proyecto Ventix, y la ruta de referencia (para software SaaS) o ruta de descarga (para productos de instalación local). Las herramientas se organizan según las siguientes disciplinas:

1. Project Management
2. Requirements Management
3. Product UX/UI Design
4. Software Development
5. Software Testing
6. Software Documentation

**Project Management**

Esta disciplina se centra en la planificación, seguimiento y control de las actividades del proyecto, asegurando el cumplimiento de los objetivos dentro del tiempo y recurso establecidos

* Trello: Plataforma de gestión visual basada en tableros, listas y tarjetas, utilizada para la organización del Sprint Backlog, gestión de User Stories por estado (To-Do, In-Progress, Done) y colaboración del equipo en la priorización de requisitos del proyecto Ventix.
  Ruta de referencia : https://trello.com

**Requirements Management**

Este proceso se enfoca en la documentación, verificación y seguimiento de los requisitos del proyecto, asegurando que las necesidades de los stakeholders sean satisfechas.


* Trello: Plataforma de gestión visual basada en tableros, listas y tarjetas, utilizada para la organización del Sprint Backlog, gestión de User Stories por estado (To-Do, In-Progress, Done) y colaboración del equipo en la priorización de requisitos del proyecto Ventix.
  Ruta de referencia : https://trello.com

**Product UX/UI Design**

El diseño de la experiencia de usuario y la interfaz de usuario para Ventix contempla un modelo de sitio web responsivo, compatible con navegadores de escritorio y dispositivos móviles. Se utilizan las siguientes herramientas.

1. **UXPressia:** Plataforma para la elaboración de User Personas, Empathy Maps, Customer Journey Maps e Impact Maps de los segmentos objetivo del proyecto Ventix .
Ruta de referencia: https://uxpressia.com/


2. **Miro:** Pizarra digital colaborativa utilizada para sesiones de Big Picture EventStorming y Design-Level EventStorming, facilitando la identificación de Bounded Contexts, Events, Commands y Aggregates del dominio Ventix.
Ruta de referencia: https://miro.com/es/


3. **Figma:** Herramienta de diseño colaborativo para la creación de Wireframes, Mock-ups y Prototipos interactivos del Landing Page y Web Applications de Ventix, aplicando el Design System basado en Material Design.
Ruta de referencia: https://www.figma.com/es-es/


4. **LucidChart:** Aplicación de diagramación colaborativa para la creación de Wireflows, User Flows, diagramas UML (Class Diagrams) y Database Diagrams de la arquitectura de Ventix.
Ruta de referencia: https://www.lucidchart.com/pages/es

**Software Development:**

El desarrollo de software del proyecto Ventix abarca la implementación del Langin Page, Frontend Web Application y Backend Web Services. Se utilizan las siguientes herramientas y tecnologías.

1. **GitHub:** Sistema de control de versiones distribuido y plataforma de hosting para repositorios de código fuente. Gestión de la organización Open-10177, implementación de GitFlow Workflow, Conventional Commits y Semantic Versioning.
Ruta de referencia: https://github.com
    
    Organización del proyecto: https://github.com/Open-10177 


2. **WebStorm:** Entorno de desarrollo integrado (IDE) de JetBrains para la implementación del Frontend utilizando Angular Framework, HTML5, CSS3, JavaScript y TypeScript. Incluye integración con GitHub para control de versiones.
Ruta de descarga: https://www.jetbrains.com/webstorm/

    Licencia de estudiante: https://www.jetbrains.com/community/education/


3. **HTML5, CSS3, JavaScript:** Tecnologías fundamentales para la implementación del Landing Page y estructura base de las Web Applications.
   
    **Referencias:**
   * HTML5: https://html.spec.whatwg.org/
   * CSS3: https://www.w3.org/Style/CSS/
   * JavaScript: https://developer.mozilla.org/es/docs/Web/JavaScript

**Software Testing**

Las pruebas de software permiten evaluar y verificar que los productos desarrollados cumplen con los requisitos especificados y funcionan correctamente.

- **Lenguaje Gherkin:** Lenguaje de dominio específico (DSL) para la redacción de Acceptance Criteria de User Stories en formato estructurado Given-When-Then. Permite definir escenarios de prueba legibles por stakeholders y ejecutables por herramientas de automatización. Los keywords principales son: Feature, Scenario, Given, When, Then, And, But.
  
    Ruta de referencia: https://cucumber.io/docs/gherkin/

**Software Documentation**

La documentación de software permite explicar el funcionamiento, uso y arquitectura de los productos desarrollados, facilitando su mantenimiento y evolución.

- **Markdown:** Lenguaje de marcado ligero para la elaboración del Project Report en el repositorio GitHub. Permite estructurar documentación con formato consistente y compatible con control de versiones.

    Ruta de referencia: https://www.markdownguide.org/
### 5.1.2. Source Code Management.

En esta sección se establecen los medios y esquemas de organización aplicados para el seguimiento de modificaciones del código fuente. Se utiliza GitHub como plataforma y sistema de control de versiones distribuido.

**Repositorio del Proyecto**

| Producto                | URL del Repositorio                                 |
|-------------------------|-----------------------------------------------------|
| Organizacion Open-10177 | https://github.com/Open-10177                       |
| Landing Page            | https://open-10177.github.io/Ventix-LandingPage/    |
| Project Report          | https://github.com/Open-10177/VentixProject-Report  |

**GitFlow Workflow**

Se implementa GitFlow como modelo de flujo de trabajo para el control de versiones, estableciendo una estructura de ramas que facilita el desarrollo paralelo y la gestión de releases.

**Ramas Principales:**

- **main:** Rama principal que contiene el historial oficial de versiones estables listas para producción. Solo recibe merges de release branches y hotfix branches.


- **develop:** Rama de integración donde se consolidan los features completados y probados. Sirve como base para la creación de release branches.

**Ramas Soporte:**

- **feature/<feature-name>:** Ramas creadas a partir de develop para implementar nuevas funcionalidades. Se fusionan de vuelta a develop una vez completadas y revisadas.

- -**release/<version>:** Ramas creadas a partir de develop para preparar una nueva versión de producción. Permiten correcciones menores y ajustes antes del merge a main.

**Convenciones de Nomenclatura para Ramas**

| Tipos de Rama | Formato                                        | Ejemplo                         |
|---------------|------------------------------------------------|---------------------------------|
| Feature       | feature/<bounded-context>-<feature-description>| feature/docs-add-lean-ux-canvas |
| Release       | release/<major.minor.patch>                    | release/1.0.0                   |

**Conventional Commits**

Se aplica la especificación Conventional Commits para los mensajes de commit, siguiendo la estructura:

    <type>[optional scope]: <description>

    [optional body]

    [optional footer(s)]


**Tipos de Commit:***

| Tipo     | Descripcion                                                       |
|----------|-------------------------------------------------------------------|
| feat     | **Nueva funcionalidad para el usuario**                           |
| fix      | **Corrección de un bug**                                          |
| docs     | **Cambios en documentación**                                      |
| style    | **Cambios de formato (espacios, comas, etc.) sin afectar lógica** |
| refactor | **Refactorización de código sin cambiar funcionalidad**           |
| perf     | **Mejoras de rendimiento**                                        |
| test     | **Adición o corrección de pruebas**                               |
| build    | **Cambios en sistema de build o dependencias externas**           |
| chore    | **Tareas de mantenimiento sin afectar código de producción**      |

**Ejemplos de Commits:**

    feat(chapter-1): add lean ux canvas
    fix(auth): resolve token expiration validation issue
    docs(readme): update deployment instructions
    build(deps): upgrade Angular to version 17
    chore(config): update environment variables for production

### 5.1.3. Source Code Style Guide & Conventions.
### 5.1.4. Software Deployment Configuration.
## 5.2. Landing Page, Services & Applications Implementation.
### 5.2.1. Sprint 1
##### 5.2.1.1. Sprint Planning 1.
#### 5.2.1.2. Aspect Leaders and Collaborators.
#### 5.2.1.3. Sprint Backlog 1.
#### 5.2.1.4. Development Evidence for Sprint Review.
#### 5.2.1.5. Execution Evidence for Sprint Review.
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.

# Conclusiones
## Conclusiones y recomendaciones.

## Bibliografía

Allen, J. G., MacNaughton, P., Satish, U., Santanam, S., Vallarino, J., & Spengler, J. D. (2016). Associations of cognitive function scores with carbon dioxide, ventilation, and volatile organic compound exposures in office workers. Environmental Health Perspectives, 124(6), 805–812. https://hero.epa.gov/reference/3976444/ 

Chen, C., Zhao, B., & Ji, W. (2021). A comparative study of ventilation-purification strategies on air quality and energy consumption. Building Simulation, 14(3), 813–825. https://www.sciopen.com/article/10.1007/s12273-020-0694-2

Dave, C., Sivajohan, A., Basmaji, J., & Slessarev, M. (2022). Evidence-based considerations for the design of an open-source ventilator: A systematic review. Critical Care Explorations, 4(7), e0723. https://pmc.ncbi.nlm.nih.gov/articles/PMC9249267/?utm_source=copilot.com 

Eurofins Environment Testing Spain. (2025). Calidad del aire en interiores – Norma UNE 171330:2024. Madrid: Eurofins. https://www.eurofins-environment.es/en/indoor-air-quality/?utm_source=copilot.com

Instituto Nacional de Seguridad y Salud en el Trabajo (INSST). (2003). Notas técnicas de prevención: Ventilación y riesgos en interiores. Madrid: INSST. https://www.insst.es/materias/riesgos/riesgos-ergonomicos/calidad-del-ambiente-interior/documentacion 

Mendell, M. J., Chen, W., Ranasinghe, D. R., Castorina, R., & Kumagai, K. (2024). Carbon dioxide guidelines for indoor air quality: A review. Journal of Exposure Science & Environmental Epidemiology, 34(4), 555–569. https://www.nature.com/articles/s41370-024-00694-7 

Navas-Martín, M. Á., Jiménez-Planet, V., & Cuerdo-Vilches, T. (2024). Working from home and indoor environmental quality: A scoping review. Applied Sciences, 16(1), 250. https://www.mdpi.com/2076-3417/16/1/250 

Pineda-Tobón, D. M., Espinosa-Bedoya, A., & Branch-Bedoya, J. W. (2024). Aquality32: A low-cost, open-source air quality monitoring device leveraging the ESP32. HardwareX, 20, e00607. https://doaj.org/article/a36dfe04d08940e5821139c2fee21dd2?utm_source=copilot.com

World Health Organization. (2006). Air quality guidelines: Global update 2005. WHO/SDE/PHE/OEH/06.02. Geneva: World Health Organization. https://wkc.who.int/resources/publications/i/item/WHO-SDE-PHE-OEH-06.02?utm_source=copilot.com

World Health Organization. (2021). WHO global air quality guidelines: Particulate matter (PM₂.₅ and PM₁₀), ozone, nitrogen dioxide, sulfur dioxide and carbon monoxide. Geneva: World Health Organization. https://www.who.int/publications/i/item/9789240034228/?utm_source=copilot.com 

## Anexos

**Anexo A: Enlaces de Despliegue y Repositorios**

A continuación se listan los enlaces a los entornos de producción y los repositorios de código fuente utilizados durante todo el ciclo de vida del proyecto.

| Recurso                     | URL                                                 |
|-----------------------------|-----------------------------------------------------|
| Landing Page (GitHub Pages) | https://open-10177.github.io/Ventix-LandingPage/    |
| Repositorio Landing Page    | https://github.com/Open-10177/Ventix-LandingPage    |
| Repositorio Project Report  | https://github.com/Open-10177/VentixProject-Report  |
