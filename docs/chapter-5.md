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
# Git Workflow Strategy

## Flujo de Trabajo

El equipo de desarrollo utiliza una estrategia basada en **Git Flow** para mantener una gestión ordenada del código fuente y facilitar el trabajo colaborativo. Este enfoque permite separar el desarrollo de nuevas funcionalidades, correcciones y versiones estables mediante el uso de distintas ramas especializadas.

---

## Estructura de Ramas

El proyecto se organiza utilizando las siguientes ramas:

- **main**  
  Contiene la versión estable del sistema lista para producción.

- **dev**  
  Rama principal de desarrollo donde se integran las funcionalidades antes de ser liberadas.

- **feature/\***  
  Ramas temporales utilizadas para implementar nuevas funcionalidades o mejoras específicas.

## Control de Versiones

El proyecto sigue el estándar de **Versionado Semántico (SemVer)** utilizando el formato:

```text
vX.Y.Z
```

Donde:

- **X (Major)** → Cambios importantes que rompen compatibilidad con versiones anteriores.
- **Y (Minor)** → Incorporación de nuevas funcionalidades compatibles.
- **Z (Patch)** → Corrección de errores y ajustes menores.

### Versiones preliminares

Durante el desarrollo también se emplean sufijos para identificar el estado de una versión:

- **alpha** → Funcionalidades en desarrollo inicial.
- **beta** → Versiones destinadas a pruebas internas.
- **rc (Release Candidate)** → Versión candidata previa al lanzamiento oficial.

## Convención de Commits

Para mantener un historial claro y consistente, los mensajes de commit siguen la siguiente estructura:

```text
<tipo>(ámbito): descripción breve [#issue]
```

### Ejemplos

```text
feat(auth): implementar autenticación JWT [#12]
fix(stock): corregir cálculo de inventario [#25]
docs(readme): actualizar guía de instalación
```

### Tipos de commits utilizados

- **feat** → Implementación de nuevas funcionalidades.
- **fix** → Corrección de errores.
- **docs** → Cambios en documentación.
- **refactor** → Mejoras internas de código sin alterar funcionalidad.
- **test** → Creación o actualización de pruebas.

## Políticas de Desarrollo

Para garantizar la calidad y estabilidad del proyecto, se aplican las siguientes políticas:

- Todo merge hacia la rama `main` requiere al menos una revisión aprobada.
- Las ramas principales están protegidas contra pushes directos.
- Cada commit debe estar relacionado con un issue o ticket correspondiente.
- Las versiones oficiales se etiquetan siguiendo estrictamente el estándar SemVer.

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

## Anexos

**Anexo A: Enlaces de Despliegue y Repositorios**

A continuación se listan los enlaces a los entornos de producción y los repositorios de código fuente utilizados durante todo el ciclo de vida del proyecto.

| Recurso                     | URL                                                 |
|-----------------------------|-----------------------------------------------------|
| Landing Page (GitHub Pages) | https://open-10177.github.io/Ventix-LandingPage/    |
| Repositorio Landing Page    | https://github.com/Open-10177/Ventix-LandingPage    |
| Repositorio Project Report  | https://github.com/Open-10177/VentixProject-Report  |
