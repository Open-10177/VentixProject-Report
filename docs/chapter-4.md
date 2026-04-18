# Capítulo IV: Product Design
## 4.1. Style Guidelines.
### 4.1.1. General Style Guidelines.
El diseño visual de la plataforma **Ventix** opta por una estética moderna, dinámica y tecnológica. Sus colores transmiten frescura, confianza, claridad y facilidad de uso. Esta propuesta busca reflejar innovación y eficiencia, alineándose con nuestro compromiso de ofrecer soluciones inteligentes y accesibles.

Mediante una interfaz clara, se pretende brindar una experiencia digital intuitiva y agradable, que combine funcionalidad, ligereza y control, mejorando la comodidad del usuario.

En este capítulo, se explicarán los elementos visuales y estéticos que conforman la interfaz de la aplicación Ventix, siguiendo los principios de diseño de experiencia de usuario (UX) e interfaz de usuario (UI), con el objetivo de garantizar accesibilidad, usabilidad y coherencia visual en toda la plataforma

**Branding**

El logo principal de la plataforma Ventrix,  se construye sobre una identidad visual moderna, tecnológica y fluida, que comunica innovación y eficiencia en soluciones de ventilación inteligente. El logotipo presenta formas curvas y dinámicas que indican el flujo de aire, simbolizando movimiento, conectividad y adaptación continua, elementos claves en nuestro sistema inteligente

<p align="center">
  <img src="assets/img/chapter-2/ventixlogo.png" alt="ventix-Logo" width="350px" height="auto"/>
</p>


**Typography**

La tipografía implementada en Ventrix será Manrope, perteneciente a la familia sans serif, en sus variantes Regular, Medium, Semi Bold y Bold. La elección de esta fuente se fundamenta  en su estilo moderno, limpio y tecnológico, el cual se alinea con la identidad visual de la marca. Además, ofrece una excelente legibilidad en distintos dispositivos como móviles, tabletas y ordenadores,garantizando una mejor experiencia de lectura para los usuarios. Asimismo, su disponibilidad a través de Google Fonts permite una carga eficiente y consistente en la aplicación

<p align="center">
  <img src="assets/img/Chapter-4/Letra.png" alt="Letras" width="500px" height="auto"/>
</p>

La jerarquía tipográfica se establece de la siguiente manera para asegurar claridad, orden visual y una adecuada experiencia de usuario.

**Colors**
La paleta de colores de ventrix fue elegida minuciosamente para expresar sensaciones como calma y frescura. Además, se inspira en la tecnología y el aire puro, utilizando una gama de azules y cianes. A continuación, se indicará la distribución estratégicamente en tres categorías principales:

**Paleta principal**

Colores que definen la identidad de Ventrix y se utilizan en los elementos clave de la interfaz.

**Primario (Azul oscuro): #144E73** Es color que da seriedad a la marca y se usa en las partes más importantes de la página.

**Secundario(Azul Medio): #348ABF** Se utiliza para resaltar las funciones inteligentes del producto.

**Terciario (Turquesa): #39A7BF** Es el color que llama la atención para que el usuario actúe, ademas de utilizarlo para acentos visuales y detalles dinámicos

**Fondo claro: #F0F0F2** Se usa en casi todo el fondo de la página para que se vea limpia, espaciosa y para que los textos de los clientes y beneficios se lean sin esfuerzo.

**Complementario (Verde Agua): #79D9BE** Sirve para representar la naturaleza y el ahorro, destacando los cuadros que hablan de aire puro, salud y de no gastar luz de más.

**Colores funcionales**

Reservados para comunicar estados específicos dentro de la aplicación.

**Éxito: Verde (#4CAF50)** Para acciones correctas o confirmaciones.

**Error: Rojo (#F44336)** Para mensajes de error o alertas.

**Advertencia: Amarillo (#FFC107)** Para avisos importantes o notificaciones.

<p align="center">
  <img src="assets/img/Chapter-4/paleta_colores.jpeg" alt="Primary Color Palette" width="500px" height="auto"/>
</p>

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

**Organización:**
Ventrix cuenta con una estructura organizada de archivos que facilita el desarrollo y mantenimiento del sistema.

**Versionado:**
Se utiliza un sistema de control de versiones como git, lo que permite mantener un historial de cambios y colaborar de manera eficiente.
## 4.2. Information Architecture.
La arquitectura de la información de Ventix está diseñada para ofrecer una navegación clara e intuitiva, permitiendo a los usuarios comprender rápidamente el funcionamiento de la plataforma y acceder de forma eficiente al monitoreo, la automatización del sistema y el monitoero. Esta estructura busca optimizar tanto la experiencia en la landing page como en el dashboard, facilitando la toma de decisiones basadas en datos a tiempo real.
### 4.2.1. Organization Systems.

* **Jerarquía de contenidos:**
La información de Ventrix está organizada de lo general a lo específico, permitiendo que el usuario priemro comprenda el propósito del sistema y luego profundice en sus funcionalidades. La experiencia comienza con un breve mensaje principal en la sección inicial, seguido de una explicación de la solución, sus característias y beneficios, para finalmente presentar opciones de uso y acceso de la misma.

* **Secciones principales**
La landing page de Ventrix se estructura en secciones clave que guían al usuario a lo largo del recorrido:

    * **Hero:** Es la presentación inicial que muestra el nombre de la marca, una imagen de estilo de vida y la propuesta de valor centrada en ofrecer "Ventilación transparente para espacios productivos".
      
    * **Funciones:** Detalla funcionalidades como monitoreo en tiempo real, activación automática y control remoto.
  Explica cómo el sistema utiliza sensores en tiempo real para ajustar la potencia de ventilación, mantener el aire limpio y asegurar la temperatura ideal con bajo consumo energético. Muestra como Ventrix ayuda a la ventilacion de tu hogar y al uso tanto remoto como automatizado.
      
    * **Beneficios:**  Resalta las tres ventajas principales del sistema: la mejora de la salud mediante la eliminación de contaminantes, el control total del hogar de forma remota y el ahorro de electricidad al funcionar solo cuando es necesario.
      
    * **Misión y Visión:** escribe el propósito de la empresa de crear entornos inteligentes para mejores vidas y su meta de convertirse en un referente de bienestar inteligente.
      
    * **Equipo:** Presenta a los desarrolladores responsables de la creación y el mantenimiento de la aplicación de Ventix.
      
    * **Planes:** Expone las opciones disponibles según las necesidades del usuario.
      
    * **Testimonios y CTA:** Incluye opiniones de usuarios reales, reforzando la confianza y motiva al usuario a registrarse o utilizar el sistema.
      
    * **Contacto:** Finaliza con un formulario para resolver dudas de inmediato y botones de acción.
 
**Agrupación de Contenido:**
El contenido se organiza de manera lógica y visualmente estructurada para facilitar su comprensión. Las funcionalidades del sistema se presentan en tarjetas con bordes semi-ovalados que agrupan información como datos ambientales, configuraciones y acciones disponibles. Asimismo, los beneficios y caracteristicas se muestran en bloques claros que permiten una lectura eficienta.
 
### 4.2.2. Labeling Systems.

* **Nomenclatura:** Venix utiliza un lenguaje claro, directo en los títulos y elementos de la interfaz. Se emplean etiquetas como "Monitoreo en tiempo real", "Activar ventilador", "Modo automático", etc, permitiendo que el usuario comprenda inmediatamente la función de cada elemento.
  
* **Consistencia:** Se mantiene una nomenclatura uniforme en toda la paltaforma, evitando asi confusiones por parte de los usuarios. Por ejemplo, términos como "Planes" o configuracion" se utilizan de manera coherente para una mejor navegación en los títulos de cada sección.

* **Lenguaje Adaptativo:** El contenido en la app esta diseñado para ser comprensible tato como para estudiantes como para los usuarios que lo manejan desde fuera de su casa, que son los principales segmentos de usuarios. Se evita el uso de terminología técnica compleja, enfocandose en beneficios como comodidad, control, automatización y bienestar.
  
### 4.2.3. SEO Tags and Meta Tags
Esta sección define las etiquetas que optimizan la visibilidad del sistema en buscadores y redes sociales.

  * **Web Application (Plataforma de Usuario)** Enfocada en la capacitación de cliente y marketing.
      * Title:
          * **Ventix:** Ventilación inteligente y espacios productivos
      * Metaetiquetas:
          * **Descripción:** Descubre Ventix, el sistema de ventilación inteligente que utiliza sensores en tiempo real para garantizar aire puro, bienestar y ahorro energético en tu hogar.
          * **Keywords:** Ventilación inteligente, aire puro, sensores a tiempo real, ahorro energético, bienestar hogar.
          * **Author:** Equipo de desarrollo Ventrix.
            
  * **Web Application (Plataforma de Usuario)** Enfocada en la capacitación de cliente y marketing.
      * **Title:**
          * Panel de Control - Ventix Evolution.
      * **Metaetiquetas:**
          * **Descripción:** Gestiona de forma remota el clima de tu hogar, visualiza reportes mensuales y configura el modo automático de tus dispositivos Ventix.
          * **Keywords:** gestión remota, monitoreo de aire, reportes avanzados, configuración sensores, smart ventilation.
          * **Author:** Ventix Evolution Team.


### 4.2.4. Searching Systems.

* **Barra de búsqueda:** Dentro del dashboard de Ventix, la barra de búsqueda permite a los usuarios encontrar rápidamente información relacionada con espacios monitoreados, historial de datos o configuraciones especificas.
  
* **Filtros de busquedas:** El sistema incorpora opciones de filtrado que permiten organizar la información como tipo de datos (temperatura, CO2, humedad), rangos de tiempo (día, semana, mes) o espacios monitoreados.

### 4.2.5. Navigation Systems.

* **Navegación global (Landing page):** La navegación principal se encuentra en el encabezado de la plataforma, permitiendo acceder a secciónes como inicio, beneficios, planes, contactos, así como opciones de autenticación. En diapositivos móviles, esta navegación se adapta mediante un menú desplegable
  
* **Navegación Contextual (En la app):** Dentro del sistema, los botones y acciones guían al usuario según el contexto. Por ejemplo, desde la visualización de datos se puede acceder directamente a configuraciones o activar el ventilador en distintos ambientes del hogar, facilitando la interación continua.
  
* **Navegación Secundaria (Accesos adicionales):** Se incluyen accesos adicionales dentro del dashboard, como menús laterales o accesos rápidos, que permiten cambiar entre secciones como historial, configuración, monitoreo de espacios o alertas. Esto mejora la eficiencia del usuario al interactuar con múltiples funcionalidades del sistema.
  
## 4.3. Landing Page UI Design.
El diseño de la interfaz de usuario (UI) de la página de inicio dde Ventix es fundamental para captar la atención de los usuarios y guiarlos hacia una acción clara: comprender y adoptar una solución de ventilación inteligente. Se ha priorizado la creación de una experiencia intuitiva y fluida, asegurando que cada elemento de la página sea interactivo, accesible y fácil de usar, reflejando el compromiso de Ventix con la innovación, la eficiencia y la calridad.

### 4.3.1. Landing Page Wireframe.

El wireframe de la página de inicio de Ventix funciona como un mapa visual que define la estructura, jerarqía y flujo de la información. Las secciones del wireframe están diseñadas para guiar al usuario a través de una experiencia clara y progresiva, desde la comprensión del problema hasta la exploración de las funcionalidade y beneficios de la plataforma.

**Nav y Hero**
Este diseño de Ventix es básicamente la puerta de entrada a una página web, organizado de forma sencilla para que nadie se pierda. En la parte superior tienes el menú de navegación con el logo y botones para moverse por el sitio, mientras que la parte central se divide en dos: a la izquierda, hay espacio para un título potente, una breve explicación y un botón llamativo que invita a la acción; a la derecha, ese cuadro grande con una cruz es el lugar reservado para una buena foto o ilustración que termine de darle vida a la marca. Es una estructura muy clara que busca que, en cuanto alguien entre, entienda de inmediato qué se ofrece y qué paso debe seguir.

<img src="assets/img/Chapter-4/hero.png" alt="hero" width="300px">

**Funciones**
Esta sección, titulada "Funcionalidades", utiliza un formato de carrusel interactivo para mostrar detalladamente cada función del proyecto. En el centro, un panel principal combina una imagen representativa en el cuadro gris oscuro con una explicación clara en el cuadro gris claro, permitiendo que el usuario entienda cada funcionalidad de forma visual y textual al mismo tiempo. Gracias a la flecha lateral, el visitante puede explorar las diferentes herramientas de manera dinámica, mientras que el botón inferior ofrece una vía rápida para obtener más información o comenzar a usarlas.

<img src="assets/img/Chapter-4/demo.png" alt="Services" width="300px">

**Beneficios**
Esta sección está diseñada para resaltar lo mejor de la marca de forma clara y directa. A la izquierda se encuentra el título "Beneficios" para ubicar al usuario, mientras que el resto del espacio lo ocupan tres tarjetas verticales con bordes redondeados, ideales para explicar los puntos clave o ventajas del servicio.

<img src="assets/img/Chapter-4/beneficios.png" alt="Beneficios" width="300px">

**Sobre nosotros**
Esta sección presenta al equipo detrás del proyecto bajo el título central de "Equipo", dándole un rostro humano a la marca. El diseño utiliza una cuadrícula de tarjetas blancas con bordes redondeados que resaltan sobre el fondo oscuro, creando un espacio limpio y ordenado para mostrar la fotografía y el rol de cada miembro.

<img src="assets/img/Chapter-4/integrantes.png" alt="Integrantes" width="300px">

**Misión y visión**
Esta sección está dedicada a explicar el propósito del proyecto a través de su misión y visión, utilizando un diseño que transmite seriedad y enfoque. En la columna de la izquierda, los bloques de texto están reservados para definir los objetivos y la razón de ser de la marca, acompañados de un botón de acción para quienes deseen profundizar en la historia del equipo. A la derecha, el gran recuadro blanco funciona como el espacio ideal para una imagen inspiradora o un gráfico que represente visualmente esos valores, logrando una estructura equilibrada que permite entender de un vistazo hacia dónde se dirige el proyecto.

<img src="assets/img/Chapter-4/demo.png" alt="Equipo" width="300px">

**Planes**
Esta sección de "Planes" organiza las diferentes opciones de suscripción o servicios de la aplicación de una manera muy visual y comparativa. Se utilizan tres columnas principales donde cada una detalla lo que incluye el plan: un título para el nombre del nivel, un icono o precio destacado, y una lista de características para que el usuario sepa exactamente qué beneficios recibe en cada opción.

<img src="assets/img/Chapter-4/planes.png" alt="Planes" width="300px">

**Testimonios**
Esta sección está diseñada para mostrar testimonios de clientes y generar confianza a través de la experiencia de otros. A la izquierda, un espacio para un título llamativo y dos pequeños indicadores permiten saber quién está hablando o navegar entre opiniones, mientras que a la derecha aparecen tarjetas blancas amplias donde se destacan las citas o comentarios de los usuarios.



<img src="assets/img/Chapter-4/contacto" alt="Demo" width="300px">

<img src="assets/img/Chapter-4/referencias.png" alt="referencias" width="300px">

**Contacto**
Esta sección esta diseñada para que le usuario pueda contactarse con un especialista, para resulver sus dudas de inmediato, mediante un formulario donde debes registrar tu nombre, correo y consulta.

<img src="assets/img/Chapter-4/contacto.png" alt="contacto" width="300px">

**Footer**
Este es el pie de página o footer, diseñado para cerrar el sitio con toda la información complementaria organizada de forma clara. A la izquierda destaca nuevamente el nombre de Ventix, mientras que en el centro se distribuyen dos columnas de enlaces que permiten navegar rápidamente hacia secciones secundarias o legales. En la hilera inferior, el diseño reserva espacios específicos para iconos de redes sociales a la izquierda, una barra para derechos de autor o avisos legales en el medio, y una imagen del logo a la derecha, logrando que el usuario tenga todo lo necesario a mano antes de terminar su visita.

<img src="assets/img/Chapter-4/footer.png" alt="referencias" width="300px">

### 4.3.2. Landing Page Mock-up.
**Hero de la aplicación**
Esta sección de apertura presenta el logotipo de Ventix junto al eslogan "Ventilación transparente para espacios productivos". Incluye una barra de navegación para acceso rápido a servicios, testimonios y beneficios, además de un botón de llamado a la acción: "Más información". Visualmente, utiliza elementos que transmiten frescura y claridad.

<img src="assets/img/Chapter-4/hero-m.png" alt="hero" width="300px">

**Funcionalidades**
Bajo el título "Todo lo que necesitas en un solo lugar", se explica cómo el diseño inteligente y las funciones avanzadas ofrecen una experiencia única.

<img src="assets/img/Chapter-4/Servicios-m.png" alt="funcionalidades" width="300px">

**Misión y vision**
Define el propósito estratégico de la organización:
    * **Misión:** "Entornos inteligentes, mejores vidas".
    * **Visión:** "Referente en bienestar inteligente".

<img src="assets/img/Chapter-4/Servicios-m.png" alt="funcionalidades" width="300px">
    
**Testimonios**
Titulada "Menos estrés, más resultados", esta sección comparte las experiencias de los usuarios. Por ejemplo, Amira Sandoval destaca que gracias al modo automático puede olvidarse de ajustar el aire o abrir ventanas, ya que el sistema detecta y actúa cuando el ambiente se siente pesado.

<img src="assets/img/Chapter-4/testimonios-m.png" alt="testimonios" width="300px">

**Beneficios**
Describe las ventajas clave de utilizar el sistema para mejorar la calidad de vida

<img src="assets/img/Chapter-4/beneficios-m.png" alt="beneficios" width="300px">

**Equipo**
Bajo el encabezado "Conoce a nuestro equipo", se presenta a los desarrolladores de la aplicación. Esta sección está diseñada para humanizar la marca y mostrar el talento detrás del software.

<img src="assets/img/Chapter-4/itegrante-m.png" alt="integrantes" width="300px">

**Plan**
Presenta "Un plan a tu medida" con dos opciones principales para desbloquear el potencial total de la herramienta.

<img src="assets/img/Chapter-4/plan-m.png" alt="planes" width="300px">

**contacto**
Sección dedicada a la atención al cliente con el mensaje "Ponte en contacto con nosotros". Incluye un formulario interactivo donde el usuario puede ingresar su nombre, correo y consulta para resolver dudas de inmediato.

<img src="assets/img/Chapter-4/contactos-m.png" alt="contacto" width="300px">

**Foter**
El cierre de la página refuerza la identidad con el nombre "Ventix Smart Ventilation". Contiene enlaces de navegación secundarios, iconos de redes sociales y el aviso legal de derechos reservados para el año 2026.

<img src="assets/img/Chapter-4/footer-mo.png" alt="footer" width="300px">

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.
Se observa la pantalla de bienvenida a la aplicación de Ventix, la cual constituye el primer punto de interacción del usuario con el sistema, presentando una interfaz clara y amigable que introduce la funcionalidad principal de la plataforma

**Pantalla inicial**
Esta es la pantalla de inicio de Ventix. Presenta un diseño limpio con el logo central y un botón de 'Conectar' que permite al usuario ingresar a la aplicación de forma rápida.

<img src="assets/img/Chapter-4/footer-mo.png" alt="footer" width="300px">

**Inicio de sesión**
Es una wireframe de la interfaz de inicio de sesión de Ventix que presenta un diseño minimalista con campos para correo y contraseña. Incluye opciones para recuperar la clave, registrarse y botones circulares para autenticación social en la parte inferior.

<img src="assets/img/Chapter-4/inicio de sesión.png" alt="inicio de seción" width="300px">
<img src="assets/img/Chapter-4/elegir cuenta.png" alt="cuenta" width="300px">

**Recuperación de contraseña**
Este wireframe presenta la interfaz de recuperación de contraseña, centrada en una tarjeta para ingresar el correo electrónico vinculado. Debajo, incluye campos para establecer y confirmar la nueva clave, manteniendo la estética limpia y funcional del sistema.

<img src="assets/img/Chapter-4/recuperar contraseñ5.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperar contraseña.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperar contraseña2.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperar contraseña3.png" alt="recuperacion" width="300px">

**Registro de usuario**
Este wireframe de registro presenta un formulario con campos para datos personales y de contacto, acompañados de un botón de acción principal. Se complementa con un espacio lateral para contenido visual, como para la foto del usuario, y un icono de idioma en la esquina superior derecha.

<img src="assets/img/Chapter-4/cambio de idioma-registro.png" alt="idioma" width="300px">
<img src="assets/img/Chapter-4/seleccionar-usuario.png" alt="idioma" width="300px">

**Registro de diapositivo**
Este wireframe muestra la interfaz de registro de dispositivos, ofreciendo dos métodos principales: escaneo mediante QR o entrada mediante código. Presenta una estructura simétrica con iconos marcadores de posición y breves instrucciones para cada opción.

<img src="assets/img/Chapter-4/registro-diapositivo.png" alt="codigo" width="300px">
<img src="assets/img/Chapter-4/conectado-codigo.png" alt="codigo" width="300px">
<img src="assets/img/Chapter-4/conectando-codigo.png" alt="codigo" width="300px">
<img src="assets/img/Chapter-4/daots del diapositivo.png" alt="datos- diapositivos" width="300px">
<img src="assets/img/Chapter-4/mediante-codigo.png" alt="datos- diapositivos" width="300px">
<img src="assets/img/Chapter-4/mediante qr.png" alt="qr" width="300px">
<img src="assets/img/Chapter-4/conectando-qr.png" alt="codigo" width="300px">
<img src="assets/img/Chapter-4/conectado.png" alt="qr" width="300px">


**Pantalla principal**
Este wireframe del panel principal organiza el control por ambientes y funciones clave, destacando un acceso rápido al historial de datos y la configuración de umbrales. Incluye un menú lateral de navegación y un botón de pánico prominente para emergencias dentro de la interfaz de control.

<img src="assets/img/Chapter-4/menu principal.png" alt="pantalla-principal" width="300px">

**Notificación**
Este wireframe presenta la pantalla de notificaciones, clasificando las alertas bajo una sección de "Importantes" y utilizando barras de marcador de posición para el contenido. Incluye elementos de navegación como una flecha de retorno y un menú de perfil o ajustes en la parte superior derecha.

<img src="assets/img/Chapter-4/notificación.png" alt="notificación" width="300px">

**Historial de datos**
Este wireframe del historial de datos utiliza una disposición de tarjetas para visualizar métricas, destacando un área central amplia ideal para datos sobre el estado del aire en un cierto periodo de tiempo. Se complementa con un panel lateral de detalles y mantiene la coherencia visual mediante la barra de navegación superior con iconos de control.

<img src="assets/img/Chapter-4/historial de datos.png" alt="historial-datos" width="300px">

**Configuración de umbrales**
Este wireframe para la configuración de los umbrales permite ajustar parámetros críticos como la batería mediante una interfaz de tarjetas. El elemento central está reservado para una imagen descriptiva, flanqueada por paneles laterales que organizan los controles y especificaciones técnicas de forma clara.

<img src="assets/img/Chapter-4/configuracion-umbreales.png" alt="configuracio-umbreales" width="300px">
<img src="assets/img/Chapter-4/modo-remoto.png" alt="configuracio-umbreales" width="300px">

**Configuración de perfil**
Este wireframe de la pantalla de configuración organiza los ajustes de usuario en bloques para cambiar correo, contraseña e idioma. Incluye una sección dedicada a cambiar de plan y botones funcionales en la parte inferior para cambiar de cuenta o cerrar sesión.

<img src="assets/img/Chapter-4/configuración-perfil.png" alt="configuració-perfil" width="300px">

**Mapa del hogar**
Este wireframe presenta el mapa del hogar, utilizando un espacio amplio con una "X" para indicar la ubicación del plano o imagen espacial. Sobre este se superpone una ventana emergente de detalle, diseñada para mostrar información específica o controles sobre un área seleccionada del mapa.

<img src="assets/img/Chapter-4/mapa de la casa.png" alt="plano" width="300px">

### 4.4.2. Web Applications Wireflow Diagrams.
Este wireflow integral traza el recorrido completo del usuario, desde la autenticación inicial hasta el control de dispositivos y gestión de datos. Define la jerarquía de navegación conectando el registro con todas las funciones operativas del sistema.

 * *Link del wireflow diagram para una mejor visibilidad*
     * [Wireflow diagram](https://www.figma.com/design/8hSVeN0bsKGAHm1RcFYhMU/wireflow?node-id=0-1&t=zA0w7ayQzJ3J9218-1)

### 4.4.2. Web Applications Mock-ups.

**Pantalla inicial**

<img src="assets/img/Chapter-4/inicio.png" alt="pantalla-principal" width="300px">

**Inicio de sesión**

<img src="assets/img/Chapter-4/login.png" alt="login" width="300px">
<img src="assets/img/Chapter-4/usuarios.png" alt="usuario" width="300px">

**Recuperación de contraseña**

<img src="assets/img/Chapter-4/recuperación-contr1.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperación-contr2.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperación-contr3.png" alt="recuperacion" width="300px">
<img src="assets/img/Chapter-4/recuperación-contr4.png" alt="recuperacion" width="300px">

**Registro de usuario**
<img src="assets/img/Chapter-4/registro.png" alt="idiomas" width="300px">
<img src="assets/img/Chapter-4/registro-idiomas.png" alt="idiomas" width="300px">

**Registro de diapositivo**

<img src="assets/img/Chapter-4/registro-diapositivos.png" alt="registro" width="300px">
<img src="assets/img/Chapter-4/configuracion-diapositivo.png" alt="registro" width="300px">
  * **Mediante codigo*
    <img src="assets/img/Chapter-4/codigo.png" alt="footer" width="300px">
    <img src="assets/img/Chapter-4/conectado--codigo.png" alt="codigo" width="300px">
    <img src="assets/img/Chapter-4/conectando--codigo.png" alt="codigo" width="300px">
    
  * **Mediante QR*
    <img src="assets/img/Chapter-4/codigo.png" alt="qr" width="300px">
    <img src="assets/img/Chapter-4/coectado-qr.png" alt="qr" width="300px">
    <img src="assets/img/Chapter-4/qr.png" alt="qr" width="300px">

**Pantalla principal**

<img src="assets/img/Chapter-4/pantalla-principal.pngg" alt="pantalla-inicial" width="300px">


**Notificación**

<img src="assets/img/Chapter-4/notificaciones-sistema.png" alt="notificación" width="300px">


**Historial de datos**

<img src="assets/img/Chapter-4/historial.png" alt="historial-datos" width="300px">

**Configuración de umbrales**

<img src="assets/img/Chapter-4/codigo.png" alt="footer" width="300px">


**Configuración de perfil**

<img src="assets/img/Chapter-4/configuracion.png" alt="configuración-perfil" width="300px">
<img src="assets/img/Chapter-4/configuracion-idiomas.png" alt="idiomas" width="300px">


**Mapa del hogar**

<img src="assets/img/Chapter-4/plano-casa.png" alt="plano" width="300px">


### 4.4.3. Web Applications User Flow Diagrams.

* **Link del user flow diagrams para una mejor visibilidad*
   *[user diagrams](https://miro.com/app/board/uXjVGg7StrE=/?share_link_id=836653906543)

<img src="assets/img/Chapter-4/userflow--plano.png" alt="userflow-plano" width="300px">
<img src="assets/img/Chapter-4/userflow-configuracion-perfiles.png" alt="userflow-perfil" width="300px">
<img src="assets/img/Chapter-4/userflow-historial.png" alt="userflow-historial" width="300px">
<img src="assets/img/Chapter-4/userflow-ingreso.png" alt="userflow-plataforma" width="300px">
<img src="assets/img/Chapter-4/userflow-notificaciones.png" alt="userflow-notificaciones" width="300px">
<img src="assets/img/Chapter-4/userflow-recuperación.png" alt="userflow-recuperacion" width="300px">
<img src="assets/img/Chapter-4/userflow-registrar-diapositivos.png" alt="userflow diapositivos-nuevos" width="300px">
<img src="assets/img/Chapter-4/userflow-registro.png" alt="userflow-registro" width="300px">
<img src="assets/img/Chapter-4/userflow-umbreales.png" alt="userflow-umbreales" width="300px">

  
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
