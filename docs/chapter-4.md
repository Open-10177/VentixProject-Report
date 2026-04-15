# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
El diseño visual de la plataforma **Ventix** opta por una estética moderna, dinámica y tecnológica. Sus colores transmiten frescura, confianza, claridad y facilidad de uso. Esta propuesta busca reflejar innovación y eficiencia, alineándose con nuestro compromiso de ofrecer soluciones inteligentes y accesibles.

Mediante una interfaz clara, se pretende brindar una experiencia digital intuitiva y agradable, que combine funcionalidad, ligereza y control, mejorando la comodidad del usuario.

En este capítulo, se explicarán los elementos visuales y estéticos que conforman la interfaz de la aplicación Ventix, siguiendo los principios de diseño de experiencia de usuario (UX) e interfaz de usuario (UI), con el objetivo de garantizar accesibilidad, usabilidad y coherencia visual en toda la plataforma

**Branding**

El logo principal de la plataforma Ventrix,  se construye sobre una identidad visual moderna, tecnológica y fluida, que comunica innovación y eficiencia en soluciones de ventilación inteligente. El logotipo presenta formas curvas y dinámicas que indican el flujo de aire, simbolizando movimiento, conectividad y adaptación continua, elementos claves en nuestro sistema inteligente

<p aling="center">
   <img src="-/assets/img/chapter-2/ventixlogo.png" alt="Ventix" width="350px" height="auto"/>
</p>

**Typography**

La tipografía implementada en Ventrix será Manrope, perteneciente a la familia sans serif, en sus variantes Regular, Medium, Semi Bold y Bold. La elección de esta fuente se fundamenta  en su estilo moderno, limpio y tecnológico, el cual se alinea con la identidad visual de la marca. Además, ofrece una excelente legibilidad en distintos dispositivos como móviles, tabletas y ordenadores,garantizando una mejor experiencia de lectura para los usuarios. Asimismo, su disponibilidad a través de Google Fonts permite una carga eficiente y consistente en la aplicación

La jerarquía tipográfica se establece de la siguiente manera para asegurar claridad, orden visual y una adecuada experiencia de usuario.

**Colors**
La paleta de colores de ventrix fue elegida minuciosamente para expresar sensaciones como calma y frescura. Además, se inspira en la tecnología y el aire puro, utilizando una gama de azules y cianes. A continuación, se indicará la distribución estratégicamente en tres categorías principales:

**Paleta principal**

Colores que definen la identidad de Ventrix y se utilizan en los elementos clave de la interfaz.

**Primario (Azul oscuro): #144E73** Color principal de la marca, utilizando en encabezados, botones y elementos destacados.

**Secundario(Azul Medio): #348ABF** empleado en componentes interactivos y elementos activos.

**Terciario (Turquesa): #39A7BF** utilizado para acentos visuales y detalles dinámicos

**Fondo claro: #F0F0F2** Aplicado en fondos generales para mantener lo minimalista y limpieza.

**Complementario (Verde Agua): #79D9BE** Refuerza la frescura y usa en elementos de apoyo

**Colores funcionales**

Reservados para comunicar estados específicos dentro de la aplicación.

**Éxito: Verde (#4CAF50)** Para acciones correctas o confirmaciones.

**Error: Rojo (#F44336)** Para mensajes de error o alertas.

**Advertencia: Amarillo (#FFC107)** Para avisos importantes o notificaciones.

Esta combinación cromática refleja los valores de nuestra marca, transmitiendo claridad, calma, fluidez y seguridad en el monitoreo de los ventiladores del hogar

**Spacing**

El sistema de espaciado en Ventrix sigue una estructura modular y consistente, diseñada para organizar de manera clara la información en el dashboard, la landing page y los componentes interactivos. Este enfoque permite mejorar la legibilidad de datos en tiempo real.
Espaciado Básico: Se utiliza base de 0.5 rem (8px) para los elementos pequeños como iconos, botones, indicadores de estado.

**Margen interno(Padding):** La plataforma diferencia entre los distintos contextos de uso. En la landing page se emplea un espaciado más amplio, entre 4 rem y 6 rem (64px a 96px), con el objetivo de generar secciones visualmente limpias y atractivas. Por otro lado, en el dashboard, donde se visualizan datos como temperatura, CO2 y humedad en tiempo real, se utiliza un padding más reducido, entre 1.5 rem y 2 rem (24px a 32px), permitiendo una interfaz más compacta y eficiente.

**Espaciado entre elementos:** El espaciado entre componentes como controles del ventilador y configuraciones varía entre 1.5rem (24px) y 3 rem (48px). Esto permite mantener un equilibrio entre claridad visual y aprovechamiento de todo el espacio.

**Interlineado del texto:** El line-height se establece en 1.6, asegurando una lectura cómoda tanto en la visualización de datos como en textos informativos dentro de la plataforma.
Este sistema de espaciado garantiza una interfaz clara, ordenada y enfocada en la visualización de los datos, reduciendo la carga visual del usuario.

### 4.1.2. Web Style Guidelines
Las web Style guidelines de Ventix establecen un conjunto de lineamiento que garantizan coherencia visual, funcionalidad y una experiencia de usuario eficiente en toda la plataforma. Nuestro objetivo es priorizar la claridad en la visualización de datos, la accesibilidad y la interacción intuitiva. Asimismo, reflejar la misión de nuestra plataforma: monitoreo y visualización de los ventiladores inteligentes del hogar, ya sea, si el usuario está en el hogar o lejos de la misma.

**Layout:**
Sistema de grid: Ventix utiliza un sistema de cuadrícula flexible que permite organizar los elementos de manera ordenada y adaptable. En la landing page, este sistema facilita la distribución de secciones como beneficios, planes y contactos. En el dashboard, el grid se aplica para organizar los cuadros de datos (CO2, temperatura,humedad) y paneles de control, permitiendo una visualización clara y estructurada de la información en tiempo real.

**Header y Footers:**
El encabezado se mantiene fijo en la parte superior, proporcionando accesos a opciones como navegación principal, contactos, inicio de sesión, entre otros. Esto facilita el acceso a las principales funciones del sistema. El pie de página contiene enlaces relevantes, información de contacto y acceso a soporte.

**Cards:**
Las tarjetas son un componente fundamental en Ventrix, especialmente dentro del dashboard. Se utiliza para mostrar métricas en tiempo real, historial de datos y configuraciones del sistema. Cuentan con bordes semi redondeados y sombras suaves, lo que mejora la legibilidad por la diferencia con con el fondo y permite diferenciar visualmente cada bloque de información.

**Responsive Design:**

**Desktop:** En computadoras, la navegación principal se muestra en la parte superior junto con los accesos de usuario. El contenido se organiza en múltiples columnas, permitiendo visualizar simultáneamente diferentes métricas, gráficos y controles del sistema.

**Tablet:** En tablets, la interfaz se adapta reduciendo el número de columnas y reorganizando los elementos en un formato más compacto. El menú de navegación se puede integrar en un botón para optimizar el espacio, mientras que las tarjetas y controles se ajustan para facilitar la interacción táctil

**Mobile:** En los dispositivos móviles, la interfaz se presenta en una sola columna para obtener una navegación más fluida. El menú se muestra cómo desplegable, y los elementos interactivos como botones o interruptores se diseñan con un tamaño adecuado para facilitar su uso en la pantalla.

**Interaction Design**

**Botones:** Los botones en Ventrix son claros, visibles y fáciles de interactuar. Se utilizan para acciones clave como encender o apagar el ventilador, cambiar entre modo manual y automatico, o configurar parámetros del sistema, incorparan efectos visuales como cambios de color o sombra al interacturar, lo que ayuda al usuario a visualizar el estado del sistema.
**Los formularios:** Los formularios están diseñados de manera simple  y directa, permitiendo al usuario registrarse, iniciar sesión o configurar valores. Además, ayuda a la prevencion de errores, ya que la la plataforma tiene una breve guia en caso si el usuario ingrese informacion incorrecta.

**Images and icons**

**Imagenes** 
Las imagenes implementadas mantienen una estética tecnolgica´y limpia, evitanto los saturación y elementos innecesarios. Esto aporta más al diseño minimalista, permitiendo que el foco principal sea la información y funcionalidad del sistema.

**Íconos**
Los íconos son simples, reconocibles y consistentes en toda la plataforma, representando funciones como ventilación, temperatura y alertas. Esto ayuda a que el usuario reconozca los inconos, facilitando que el usaurio identifique rápidamente cada función.

**Repositorio Central**

**Organización**
Ventrix cuenta con una estructura organizada de archivos que facilita el desarrollo y mantenimiento del sistema.

**Versionado**
Se utiliza un sistema de control de versiones como git, lo que permite mantener un historial de cambios y colaborar de manera eficiente.
## 4.2. Information Architecture.
### 4.2.1. Organization Systems.
### 4.2.2. Labeling Systems.
### 4.2.3. SEO Tags and Meta Tags
### 4.2.4. Searching Systems.
### 4.2.5. Navigation Systems.
## 4.3. Landing Page UI Design.
### 4.3.1. Landing Page Wireframe.
### 4.3.2. Landing Page Mock-up.
## 4.4. Web Applications UX/UI Design.
### 4.4.1. Web Applications Wireframes.
### 4.4.2. Web Applications Wireflow Diagrams.
### 4.4.2. Web Applications Mock-ups.
### 4.4.3. Web Applications User Flow Diagrams.
## 4.5. Web Applications Prototyping.
## 4.6. Domain-Driven Software Architecture.
### 4.6.1. Design-Level Event Storming.
### 4.6.2. Software Architecture Context Diagram.
### 4.6.3. Software Architecture Container Diagrams.
### 4.6.4. Software Architecture Components Diagrams.
## 4.7. Software Object-Oriented Design.
### 4.7.1. Class Diagrams.
## 4.8. Database Design.
### 4.8.1. Database Diagrams
