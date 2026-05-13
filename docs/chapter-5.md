# Capítulo V: Product Implementation, Validation & Deployment
## 5.1. Software Configuration Management.
### 5.1.1. Software Development Environment Configuration.

En esta sección se detallan las herramientas utilizadas para la gestión del proyecto, el diseño, el desarrollo, el despliegue y la documentación de la solución.

* Project Management:
  
  * Trello
    Propósito: Gestión de tareas mediante tableros Kanban organizados en columnas (To Do, In Progress, Done).
    
    URL: https://trello.com
    
  * Uxpressia
    Propósito: Creación de mapas de experiencia de usuario para analizar y entender a nuestros usuarios.
    
    URL: https://uxpressia.com
    
  * Lucidchart
    Propósito: Elaboración de diagramas de flujo, wireframes y esquemas de arquitectura de sistemas.
 
    URL: https://lucidchart.com
    
 
 
* Product UX/UI Design:
  
  * Figma
    Propósito: Diseño de interfaces de usuario (UI), prototipado rápido y colaboración en tiempo real entre los miembros del equipo.

    URL: https://figma.com
    
 * Software Development:
   * WebStorm
     Propósito: Editor de código fuente principal utilizado para el desarrollo de la Landing Page (HTML, CSS, JavaScript).

     URL: https://www.jetbrains.com/es-es/webstorm/download/?section=windows
     
 * Deployment Configuration:
   * GitHub Pages Propósito: Publicación y despliegue automático de la Landing Page como sitio web estático directamente desde el repositorio.

     URL: https://pages.github.com
   
 * Software Documentation:
   * GitHub
     Propósito: Almacenamiento de la documentación técnica dentro del repositorio del proyecto, utilizando archivos Markdown (.md).

     URL: https://github.com/

   * Markdown
     Propósito: Formato de escritura utilizado para documentar de forma clara, sencilla y estructurada los detalles del proyecto.

### 5.1.2. Source Code Management.

Nuestro equipo utiliza un flujo de trabajo basado en Git Flow para mantener un control organizado del código. Trabajamos con ramas principales y secundarias que nos permiten desarrollar funcionalidades, corregir errores y preparar versiones de manera sistemática.

- Estructura de Ramas

El proyecto maneja las siguientes ramas:

- `main`: Contiene el código estable listo para producción.
- `dev`: Rama de desarrollo donde se integran las nuevas funcionalidades.
- `feature/*`: Ramas temporales para desarrollar características específicas.

## Control de Versiones

Aplicamos versionado semántico (SemVer) con el formato:

```text
vX.Y.Z
```

- `X (Major)`: Cambios que rompen compatibilidad.
- `Y (Minor)`: Nuevas funcionalidades compatibles.
- `Z (Patch)`: Correcciones de errores.

Las versiones preliminares usan sufijos:

- `alpha`: Para funcionalidades en desarrollo.
- `beta`: Para pruebas internas.
- `rc`: Versiones candidatas a lanzamiento.

- Convención de Commits

Seguimos un formato estricto para los mensajes de commit:

```text
<tipo>(ámbito): descripción breve [#issue]
```

Ejemplos prácticos:

```text
feat(login): implementar autenticación con Google
fix(api): resolver error en endpoint 
docs: actualizar guía de instalación
```

Los tipos de commit principales son:

- `feat`: Nueva funcionalidad.
- `fix`: Corrección de errores.
- `docs`: Cambios en documentación.
- `refactor`: Mejoras de código sin cambiar funcionalidad.
- `test`: Adición o modificación de pruebas.

- Políticas Adicionales

- Todo merge a `main` requiere al menos una revisión aprobada.
- Las ramas principales están protegidas contra pushes directos.
- Cada commit debe referenciar su issue/ticket correspondiente.
- Las releases se etiquetan siguiendo estrictamente SemVer.

### 5.1.3. Source Code Style Guide & Conventions.

Para el desarrollo de la Landing Page, se decidió utilizar el idioma inglés en los nombres de variables, funciones, clases y archivos. Esto permitirá mantener una estructura de código más clara, organizada y escalable a futuro.

- HTML / CSS

Se toma como referencia principalmente el Google HTML/CSS Style Guide para conservar buenas prácticas de desarrollo.

Se emplearán etiquetas semánticas como `<header>`, `<section>`, `<article>`, `<nav>` y `<footer>` para mejorar la organización y estructura del contenido.

Las clases en CSS seguirán la convención kebab-case (por ejemplo: `.main-banner`, `.card-section`).

Los identificadores utilizados serán descriptivos y específicos para facilitar el mantenimiento y comprensión del código.

Las principales etiquetas consideradas en el proyecto son:

- `<div>` para dividir bloques o secciones del contenido.
- `<img>` para mostrar imágenes dentro de la página.
- `<ul>` y `<li>` para construir listas, especialmente en menús de navegación.
- `<a>` para conectar secciones o páginas mediante enlaces.
- `<p>` para mostrar textos descriptivos.
- `<button>` para ejecutar acciones dentro de la interfaz.
- Títulos `<h1>` hasta `<h4>` para organizar la jerarquía de la información.

- JavaScript

Se sigue el Google JavaScript Style Guide para mantener consistencia en el desarrollo.

Respecto a la nomenclatura:

Siempre que sea posible, se utilizarán `const` y `let` en lugar de `var` para mejorar el manejo del alcance de las variables.

Se evitará el uso innecesario de funciones anónimas para facilitar la depuración y lectura del código.

El objetivo será desarrollar un código modular, reutilizable y fácil de mantener.

### 5.1.4. Software Deployment Configuration

Para el despliegue de la Landing Page, se utilizará GitHub Pages como plataforma de publicación. A continuación, se detallan los pasos principales realizados:

- Se creó un repositorio en GitHub con todo el código fuente de la página (HTML, CSS y JavaScript).
- En la rama principal (`main`) se cargaron todos los archivos, verificando que el archivo principal sea `index.html`.
- Dentro de la configuración del repositorio, en la sección Pages, se seleccionó la rama `main` y la carpeta raíz (`root`) como fuente de publicación.
- GitHub generó automáticamente una URL pública para acceder a la Landing Page.
- Se realizaron pruebas para comprobar que estilos, scripts y recursos funcionaran correctamente en producción.

Con esta configuración, cualquier cambio realizado en el repositorio principal se reflejará automáticamente en la versión publicada de la página.

## 5.2. Landing Page, Services & Applications Implementation.

### 5.2.1. Sprint 1

Este informe documenta el progreso inicial del proyecto **Ventix**, una plataforma web orientada al monitoreo ambiental inteligente mediante dispositivos IoT. Durante este sprint, se trabajó en la definición de requisitos mediante historias de usuario funcionales y técnicas, la identificación de epics principales, la organización de los bounded contexts del sistema y la creación de artefactos esenciales para guiar el desarrollo del producto.

Las historias de usuario permitieron definir las funcionalidades clave relacionadas con la landing page, cambio de idioma, visualización de planes, monitoreo ambiental, alertas, gestión de dispositivos y seguridad de usuarios. El objetivo principal fue establecer una base sólida de análisis, diseño y arquitectura para asegurar una comunicación clara entre el equipo de desarrollo y una correcta visualización de los requerimientos iniciales del proyecto.

#### 5.2.1.1. Sprint Planning 1

| Campo | Detalle |
|---|---|
| Sprint | Sprint 1 |
| Fecha | 2026-05-12 |
| Hora | 11:00 AM |
| Ubicación | Virtual |
| Preparado por | Ruth Sanchez |
| Asistentes (a la reunión de planificación) | Equipo de desarrollo Ventix |
| Sprint 1 – Resumen de revisión | Se elaboraron los artefactos esenciales del producto Ventix, incluyendo epics, user stories, estructura de bounded contexts y diagramas iniciales. Además, se avanzó con la implementación de funcionalidades base como la pantalla principal, navegación, monitoreo ambiental, notificaciones, configuración de umbrales y módulo de pagos. |
| Sprint 1 – Resumen de retrospectiva | Refinar las historias de usuario, validar la integración entre módulos y mejorar la experiencia visual de las pantallas principales del sistema. |
| Objetivo y User Stories del Sprint 1 | Objetivo del Sprint: Construir y validar los artefactos fundamentales del proyecto Ventix, definiendo requisitos funcionales y técnicos para guiar el desarrollo de la plataforma de monitoreo ambiental inteligente. |
| Velocidad del Sprint 1 | 10 User Stories |
| Suma de Story Points | 30 Story Points atendidos |

#### 5.2.1.2. Aspect Leaders and Collaborators.

| Integrante del equipo | Código | GitHub | Landing Page | Diseño UI/UX | Angular/HTML/CSS | TypeScript | Documentación |
|---|---|---|---|---|---|---|---|
| Taipe Sangama, Jorge Francisco | U202313458 | jorge | C | L | C | C | L |
| Cáceres Pizarro, Albino Florencio | U201923820 | albino | L | C | L | L | C |
| Sanchez Osorio, Ruth Yanira | U20241C626 | ruth | C | C | C | C | C |
| Suarez Chinga, Geraldine | U20241C804 | geraldine | C | C | C | C | C |

**Leyenda:**  
L = Leader  
C = Collaborator

#### 5.2.1.3. Sprint Backlog 1.

git log --pretty=format:"%h | %ad | %s" --date=short
Mientras tanto, te dejo una versión mejorada y adaptada a Ventix, tomando como referencia “un commit principal por cada bounded context”.

### Sprint 2

| Work-Item / Task | User Story ID | Task ID | Description | Estimation (Hours) | Assigned To | Status |
|---|---|---|---|---:|---|---|
| Work-Item | US08 | T01 | Implementar visualización de datos ambientales en Home: temperatura, CO₂ y humedad | 5 | Cáceres Pizarro, Albino Florencio | Done |
| Work-Item | US19 | T02 | Implementar visualización de ambientes monitoreados | 4 | Taipe Sangama, Jorge Francisco | Done |
| Work-Item | US22 | T03 | Implementar acceso a notificaciones del sistema | 3 | Sanchez Osorio, Ruth Yanira | Done |
| Work-Item | US13-US15 | T04 | Implementar pantalla de configuración de umbrales ambientales | 5 | Suarez Chinga, Geraldine | In-process |
| Work-Item | US02 | T05 | Implementar visualización de planes NORMAL y PLUS en Payment | 4 | Cáceres Pizarro, Albino Florencio | Done |
| Work-Item | US03 | T06 | Implementar selección de plan y navegación al checkout | 4 | Cáceres Pizarro, Albino Florencio | Done |
| Work-Item | US05 | T07 | Integrar cambio de idioma español/inglés | 3 | Taipe Sangama, Jorge Francisco | Done |
| Work-Item | TS-09 | T08 | Implementar bounded context Device para gestión de dispositivos | 5 | Suarez Chinga, Geraldine | Review |
| Work-Item | TS-11 | T09 | Definir estructura inicial del bounded context IAM | 4 | Sanchez Osorio, Ruth Yanira | Review |

#### 5.2.2.4. Development Evidence for Sprint Review

Durante este sprint, se realizaron avances significativos en el desarrollo de la aplicación web principal de **Ventix**. Se implementaron bounded contexts clave para organizar el sistema por responsabilidades, incluyendo monitoreo ambiental, gestión de dispositivos, funcionalidades compartidas y pagos. Además, se integraron vistas principales como Home, notificaciones, configuración de umbrales y el flujo inicial de selección de planes.

A continuación, se presenta una tabla con los commits principales correspondientes al repositorio, considerando un commit representativo por cada bounded context desarrollado.

Durante este sprint, se realizaron avances significativos en el desarrollo de la aplicación web principal de **Ventix**. Se implementaron bounded contexts clave para organizar el sistema por responsabilidades, incluyendo monitoreo ambiental, gestión de dispositivos, funcionalidades compartidas y pagos. Además, se integraron vistas principales como Home, notificaciones, configuración de umbrales y el flujo inicial de selección de planes.

| Repository | Branch | Commit Id | Commit Message | Commit Message Body | Commited on (Date) |
|---|---|---|---|---|---|
| Ventix-Front-End | main | `commit-id` | `feat: create shared bounded context` | Se creó la estructura compartida del proyecto, incluyendo layout, footer, language switcher, vistas Home, About y Page Not Found. | 2026-05-08 |
| Ventix-Front-End | main | `commit-id` | `feat: create monitoring bounded context` | Se implementó la estructura del bounded context Monitoring, incluyendo entidades, endpoints, store y vista de notificaciones para el monitoreo ambiental. | 2026-05-09 |
| Ventix-Front-End | main | `commit-id` | `feat: create device bounded context` | Se desarrolló la estructura del bounded context Device, incluyendo gestión de sensores, configuración de umbrales y vistas relacionadas a dispositivos. | 2026-05-10 |
| Ventix-Front-End | main | `commit-id` | `feat: create payment bounded context` | Se implementó el bounded context Payment, incluyendo dominio, infraestructura, store, selección de planes, checkout, detalle de suscripción y listado de facturas. | 2026-05-12 |
| Ventix-Front-End | main | `commit-id` | `feat: integrate payment navigation` | Se integró el acceso al módulo de pagos desde la navegación principal de la aplicación y se agregó la ruta correspondiente. | 2026-05-12 |

#### 5.2.2.5. Execution Evidence for Sprint Review

Durante este sprint se lograron avances importantes en la aplicación web principal de **Ventix**. La plataforma cuenta con una estructura modular basada en bounded contexts, lo que permite separar responsabilidades y facilitar el mantenimiento del sistema.

Se completaron funcionalidades visuales y de navegación relacionadas con el monitoreo ambiental, la gestión de ambientes, las notificaciones y la configuración de umbrales. Asimismo, se incorporó el módulo de pagos, permitiendo al usuario visualizar planes, seleccionar una opción y acceder al flujo inicial de checkout.

Las evidencias de ejecución recomendadas para el Sprint Review son:
#### 5.2.1.6. Services Documentation Evidence for Sprint Review.
#### 5.2.1.7. Software Deployment Evidence for Sprint Review.
#### 5.2.1.8. Team Collaboration Insights during Sprint.

# Conclusiones
## Conclusiones y recomendaciones.

## Bibliografía

## Anexos

**Anexo A: Enlaces de Despliegue y Repositorios**

A continuación se listan los enlaces a los entornos de producción y los repositorios de código fuente utilizados durante todo el ciclo de vida del proyecto.

| Recurso                     | URL                                                 |
|-----------------------------|-----------------------------------------------------|
| Landing Page (GitHub Pages) | https://open-10177.github.io/Ventix-LandingPage/    |
| Repositorio Landing Page    | https://github.com/Open-10177/Ventix-LandingPage    |
| Repositorio Project Report  | https://github.com/Open-10177/VentixProject-Report  |
