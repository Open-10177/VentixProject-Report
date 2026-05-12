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
