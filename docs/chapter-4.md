# Capítulo IV: Product Design
## 4.1. Style Guidelines

### 4.1.1. General Style Guidelines.

El diseño visual de la plataforma **Ventix** opta por una estética moderna, dinámica y tecnológica. Sus colores transmiten frescura, confianza, claridad y facilidad de uso. Esta propuesta busca reflejar innovación y eficiencia, alineándose con nuestro compromiso de ofrecer soluciones inteligentes y accesibles.

Mediante una interfaz clara, se pretende brindar una experiencia digital intuitiva y agradable, que combine funcionalidad, ligereza y control, mejorando la comodidad del usuario.

En este capítulo, se explicarán los elementos visuales y estéticos que conforman la interfaz de la aplicación Ventix, siguiendo los principios de diseño de experiencia de usuario (UX) e interfaz de usuario (UI), con el objetivo de garantizar accesibilidad, usabilidad y coherencia visual en toda la plataforma.

**Branding**

El logo principal de la plataforma Ventix se construye sobre una identidad visual moderna, tecnológica y fluida, que comunica innovación y eficiencia en soluciones de ventilación inteligente. El logotipo presenta formas curvas y dinámicas que indican el flujo de aire, simbolizando movimiento, conectividad y adaptación continua, elementos claves en nuestro sistema inteligente.

**Figura 1. Logotipo principal de Ventix**

![ventixlogo.png](../assets/img/chapter-2/ventixlogo.png)

*Figura 1. Logotipo principal de la plataforma Ventix, con formas curvas y dinámicas que representan el flujo de aire y la conectividad del sistema. Fuente: Elaboración propia.*

**Typography**

La tipografía implementada en Ventix será Manrope, perteneciente a la familia sans serif, en sus variantes Regular, Medium, Semi Bold y Bold. La elección de esta fuente se fundamenta en su estilo moderno, limpio y tecnológico, el cual se alinea con la identidad visual de la marca. Además, ofrece una excelente legibilidad en distintos dispositivos como móviles, tabletas y ordenadores, garantizando una mejor experiencia de lectura para los usuarios. Asimismo, su disponibilidad a través de Google Fonts permite una carga eficiente y consistente en la aplicación.

**Figura 2. Tipografía Manrope aplicada en Ventix**

![Letra.png](../assets/img/Chapter-4/Letra.png)

*Figura 2. Familia tipográfica Manrope aplicada en Ventix, mostrando las variantes Regular, Medium, Semi Bold y Bold utilizadas en la jerarquía visual de la plataforma. Fuente: Google Fonts (https://fonts.google.com/specimen/Manrope).*

La jerarquía tipográfica se establece de la siguiente manera para asegurar claridad, orden visual y una adecuada experiencia de usuario.

**Colors**

La paleta de colores de Ventix fue elegida minuciosamente para expresar sensaciones como calma y frescura. Además, se inspira en la tecnología y el aire puro, utilizando una gama de azules y cianes. A continuación, se indicará la distribución estratégicamente en tres categorías principales:

**Paleta principal**

Colores que definen la identidad de Ventix y se utilizan en los elementos clave de la interfaz.

- **Primario (Azul oscuro): #144E73** Es el color que da seriedad a la marca y se usa en las partes más importantes de la página.
- **Secundario (Azul Medio): #348ABF** Se utiliza para resaltar las funciones inteligentes del producto.
- **Terciario (Turquesa): #39A7BF** Es el color que llama la atención para que el usuario actúe, además de utilizarlo para acentos visuales y detalles dinámicos.
- **Fondo claro: #F0F0F2** Se usa en casi todo el fondo de la página para que se vea limpia, espaciosa y para que los textos de los clientes y beneficios se lean sin esfuerzo.
- **Complementario (Verde Agua): #79D9BE** Sirve para representar la naturaleza y el ahorro, destacando los cuadros que hablan de aire puro, salud y de no gastar luz de más.

**Colores funcionales**

Reservados para comunicar estados específicos dentro de la aplicación.

- **Éxito: Verde (#4CAF50)** Para acciones correctas o confirmaciones.
- **Error: Rojo (#F44336)** Para mensajes de error o alertas.
- **Advertencia: Amarillo (#FFC107)** Para avisos importantes o notificaciones.

**Figura 3. Paleta de colores oficial de Ventix**

![paleta_colores.jpeg](../assets/img/Chapter-4/paleta_colores.jpeg)

*Figura 3. Paleta de colores oficial de Ventix, mostrando los colores primarios, secundarios y funcionales utilizados en la interfaz de la plataforma. Fuente: Elaboración propia.*

Esta combinación cromática refleja los valores de nuestra marca, transmitiendo claridad, calma, fluidez y seguridad en el monitoreo de los ventiladores del hogar.

**Spacing**

El sistema de espaciado en Ventix sigue una estructura modular y consistente, diseñada para organizar de manera clara la información en el dashboard, la landing page y los componentes interactivos. Este enfoque permite mejorar la legibilidad de datos en tiempo real.

**Espaciado Básico:** Se utiliza base de 0.5 rem (8px) para los elementos pequeños como iconos, botones, indicadores de estado.

**Margen interno (Padding):** La plataforma diferencia entre los distintos contextos de uso. En la landing page se emplea un espaciado más amplio, entre 4 rem y 6 rem (64px a 96px), con el objetivo de generar secciones visualmente limpias y atractivas. Por otro lado, en el dashboard, donde se visualizan datos como temperatura, CO2 y humedad en tiempo real, se utiliza un padding más reducido, entre 1.5 rem y 2 rem (24px a 32px), permitiendo una interfaz más compacta y eficiente.

**Espaciado entre elementos:** El espaciado entre componentes como controles del ventilador y configuraciones varía entre 1.5 rem (24px) y 3 rem (48px). Esto permite mantener un equilibrio entre claridad visual y aprovechamiento de todo el espacio.

**Interlineado del texto:** El line-height se establece en 1.6, asegurando una lectura cómoda tanto en la visualización de datos como en textos informativos dentro de la plataforma.

Este sistema de espaciado garantiza una interfaz clara, ordenada y enfocada en la visualización de los datos, reduciendo la carga visual del usuario.

### 4.1.2. Web Style Guidelines

Las Web Style Guidelines de Ventix establecen un conjunto de lineamientos que garantizan coherencia visual, funcionalidad y una experiencia de usuario eficiente en toda la plataforma. Nuestro objetivo es priorizar la claridad en la visualización de datos, la accesibilidad y la interacción intuitiva. Asimismo, reflejar la misión de nuestra plataforma: monitoreo y visualización de los ventiladores inteligentes del hogar, ya sea si el usuario está en el hogar o lejos del mismo.

**Layout:**
Sistema de grid: Ventix utiliza un sistema de cuadrícula flexible que permite organizar los elementos de manera ordenada y adaptable. En la landing page, este sistema facilita la distribución de secciones como beneficios, planes y contactos. En el dashboard, el grid se aplica para organizar los cuadros de datos (CO2, temperatura, humedad) y paneles de control, permitiendo una visualización clara y estructurada de la información en tiempo real.

**Header y Footers:**
El encabezado se mantiene fijo en la parte superior, proporcionando accesos a opciones como navegación principal, contactos, inicio de sesión, entre otros. Esto facilita el acceso a las principales funciones del sistema. El pie de página contiene enlaces relevantes, información de contacto y acceso a soporte.

**Cards:**
Las tarjetas son un componente fundamental en Ventix, especialmente dentro del dashboard. Se utilizan para mostrar métricas en tiempo real, historial de datos y configuraciones del sistema. Cuentan con bordes semi redondeados y sombras suaves, lo que mejora la legibilidad por la diferencia con el fondo y permite diferenciar visualmente cada bloque de información.

**Responsive Design:**

- **Desktop:** En computadoras, la navegación principal se muestra en la parte superior junto con los accesos de usuario. El contenido se organiza en múltiples columnas, permitiendo visualizar simultáneamente diferentes métricas, gráficos y controles del sistema.
- **Tablet:** En tablets, la interfaz se adapta reduciendo el número de columnas y reorganizando los elementos en un formato más compacto. El menú de navegación se puede integrar en un botón para optimizar el espacio, mientras que las tarjetas y controles se ajustan para facilitar la interacción táctil.
- **Mobile:** En los dispositivos móviles, la interfaz se presenta en una sola columna para obtener una navegación más fluida. El menú se muestra como desplegable, y los elementos interactivos como botones o interruptores se diseñan con un tamaño adecuado para facilitar su uso en la pantalla.

**Interaction Design**

- **Botones:** Los botones en Ventix son claros, visibles y fáciles de interactuar. Se utilizan para acciones clave como encender o apagar el ventilador, cambiar entre modo manual y automático, o configurar parámetros del sistema. Incorporan efectos visuales como cambios de color o sombra al interactuar, lo que ayuda al usuario a visualizar el estado del sistema.
- **Formularios:** Los formularios están diseñados de manera simple y directa, permitiendo al usuario registrarse, iniciar sesión o configurar valores. Además, ayudan a la prevención de errores, ya que la plataforma tiene una breve guía en caso de que el usuario ingrese información incorrecta.

**Images and icons**

- **Imágenes:** Las imágenes implementadas mantienen una estética tecnológica y limpia, evitando la saturación y elementos innecesarios. Esto aporta más al diseño minimalista, permitiendo que el foco principal sea la información y funcionalidad del sistema.
- **Íconos:** Los íconos son simples, reconocibles y consistentes en toda la plataforma, representando funciones como ventilación, temperatura y alertas. Esto ayuda a que el usuario reconozca los íconos, facilitando que identifique rápidamente cada función.

**Repositorio Central**

- **Organización:** Ventix cuenta con una estructura organizada de archivos que facilita el desarrollo y mantenimiento del sistema.
- **Versionado:** Se utiliza un sistema de control de versiones como Git, lo que permite mantener un historial de cambios y colaborar de manera eficiente.

## 4.2. Information Architecture.

La arquitectura de la información de Ventix está diseñada para ofrecer una navegación clara e intuitiva, permitiendo a los usuarios comprender rápidamente el funcionamiento de la plataforma y acceder de forma eficiente al monitoreo, la automatización del sistema y el monitoreo. Esta estructura busca optimizar tanto la experiencia en la landing page como en el dashboard, facilitando la toma de decisiones basadas en datos en tiempo real.

### 4.2.1. Organization Systems.

* **Jerarquía de contenidos:**
  La información de Ventix está organizada de lo general a lo específico, permitiendo que el usuario primero comprenda el propósito del sistema y luego profundice en sus funcionalidades. La experiencia comienza con un breve mensaje principal en la sección inicial, seguido de una explicación de la solución, sus características y beneficios, para finalmente presentar opciones de uso y acceso de la misma.

* **Secciones principales:**
  La landing page de Ventix se estructura en secciones clave que guían al usuario a lo largo del recorrido:
    * **Hero:** Es la presentación inicial que muestra el nombre de la marca, una imagen de estilo de vida y la propuesta de valor centrada en ofrecer "Ventilación transparente para espacios productivos".
    * **Funciones:** Detalla funcionalidades como monitoreo en tiempo real, activación automática y control remoto. Explica cómo el sistema utiliza sensores en tiempo real para ajustar la potencia de ventilación, mantener el aire limpio y asegurar la temperatura ideal con bajo consumo energético. Muestra cómo Ventix ayuda a la ventilación de tu hogar y al uso tanto remoto como automatizado.
    * **Beneficios:** Resalta las tres ventajas principales del sistema: la mejora de la salud mediante la eliminación de contaminantes, el control total del hogar de forma remota y el ahorro de electricidad al funcionar solo cuando es necesario.
    * **Misión y Visión:** Describe el propósito de la empresa de crear entornos inteligentes para mejores vidas y su meta de convertirse en un referente de bienestar inteligente.
    * **Equipo:** Presenta a los desarrolladores responsables de la creación y el mantenimiento de la aplicación de Ventix.
    * **Planes:** Expone las opciones disponibles según las necesidades del usuario.
    * **Testimonios y CTA:** Incluye opiniones de usuarios reales, reforzando la confianza y motivando al usuario a registrarse o utilizar el sistema.
    * **Contacto:** Finaliza con un formulario para resolver dudas de inmediato y botones de acción.

**Agrupación de Contenido:**
El contenido se organiza de manera lógica y visualmente estructurada para facilitar su comprensión. Las funcionalidades del sistema se presentan en tarjetas con bordes semi-ovalados que agrupan información como datos ambientales, configuraciones y acciones disponibles. Asimismo, los beneficios y características se muestran en bloques claros que permiten una lectura eficiente.

### 4.2.2. Labeling Systems.

* **Nomenclatura:** Ventix utiliza un lenguaje claro y directo en los títulos y elementos de la interfaz. Se emplean etiquetas como "Monitoreo en tiempo real", "Activar ventilador", "Modo automático", etc., permitiendo que el usuario comprenda inmediatamente la función de cada elemento.
* **Consistencia:** Se mantiene una nomenclatura uniforme en toda la plataforma, evitando así confusiones por parte de los usuarios. Por ejemplo, términos como "Planes" o "Configuración" se utilizan de manera coherente para una mejor navegación en los títulos de cada sección.
* **Lenguaje Adaptativo:** El contenido en la app está diseñado para ser comprensible tanto para estudiantes como para los usuarios que lo manejan desde fuera de su casa, que son los principales segmentos de usuarios. Se evita el uso de terminología técnica compleja, enfocándose en beneficios como comodidad, control, automatización y bienestar.

### 4.2.3. SEO Tags and Meta Tags

Esta sección define las etiquetas que optimizan la visibilidad del sistema en buscadores y redes sociales.

* **Landing Page (Plataforma de Marketing)** Enfocada en la captación de cliente y marketing.
    * **Title:** Ventix: Ventilación inteligente y espacios productivos
    * **Metaetiquetas:**
        * **Descripción:** Descubre Ventix, el sistema de ventilación inteligente que utiliza sensores en tiempo real para garantizar aire puro, bienestar y ahorro energético en tu hogar.
        * **Keywords:** Ventilación inteligente, aire puro, sensores en tiempo real, ahorro energético, bienestar hogar.
        * **Author:** Equipo de desarrollo Ventix.

* **Web Application (Plataforma de Usuario)** Enfocada en el dashboard de monitoreo.
    * **Title:** Panel de Control - Ventix Evolution.
    * **Metaetiquetas:**
        * **Descripción:** Gestiona de forma remota el clima de tu hogar, visualiza reportes mensuales y configura el modo automático de tus dispositivos Ventix.
        * **Keywords:** gestión remota, monitoreo de aire, reportes avanzados, configuración sensores, smart ventilation.
        * **Author:** Ventix Evolution Team.

### 4.2.4. Searching Systems.

* **Barra de búsqueda:** Dentro del dashboard de Ventix, la barra de búsqueda permite a los usuarios encontrar rápidamente información relacionada con espacios monitoreados, historial de datos o configuraciones específicas.
* **Filtros de búsqueda:** El sistema incorpora opciones de filtrado que permiten organizar la información como tipo de datos (temperatura, CO2, humedad), rangos de tiempo (día, semana, mes) o espacios monitoreados.

### 4.2.5. Navigation Systems.

* **Navegación global (Landing page):** La navegación principal se encuentra en el encabezado de la plataforma, permitiendo acceder a secciones como inicio, beneficios, planes, contactos, así como opciones de autenticación. En dispositivos móviles, esta navegación se adapta mediante un menú desplegable.
* **Navegación Contextual (En la app):** Dentro del sistema, los botones y acciones guían al usuario según el contexto. Por ejemplo, desde la visualización de datos se puede acceder directamente a configuraciones o activar el ventilador en distintos ambientes del hogar, facilitando la interacción continua.
* **Navegación Secundaria (Accesos adicionales):** Se incluyen accesos adicionales dentro del dashboard, como menús laterales o accesos rápidos, que permiten cambiar entre secciones como historial, configuración, monitoreo de espacios o alertas. Esto mejora la eficiencia del usuario al interactuar con múltiples funcionalidades del sistema.

## 4.3. Landing Page UI Design.

El diseño de la interfaz de usuario (UI) de la página de inicio de Ventix es fundamental para captar la atención de los usuarios y guiarlos hacia una acción clara: comprender y adoptar una solución de ventilación inteligente. Se ha priorizado la creación de una experiencia intuitiva y fluida, asegurando que cada elemento de la página sea interactivo, accesible y fácil de usar, reflejando el compromiso de Ventix con la innovación, la eficiencia y la claridad.

### 4.3.1. Landing Page Wireframe.

El wireframe de la página de inicio de Ventix funciona como un mapa visual que define la estructura, jerarquía y flujo de la información. Las secciones del wireframe están diseñadas para guiar al usuario a través de una experiencia clara y progresiva, desde la comprensión del problema hasta la exploración de las funcionalidades y beneficios de la plataforma.

**Figura 4. Wireframe de la sección Nav y Hero del Landing Page**

![hero.png](../assets/img/Chapter-4/hero.png)

*Figura 4. Wireframe de la sección Navegación y Hero del Landing Page de Ventix. Muestra la estructura inicial con el menú superior y el área central dividida para el título principal, el llamado a la acción y la imagen representativa de la marca. Fuente: Elaboración propia.*

**Figura 5. Wireframe de la sección Funcionalidades**

![funcionalidad.png](../assets/img/Chapter-4/funcionalidad.png)

*Figura 5. Wireframe de la sección Funcionalidades del Landing Page de Ventix, presentada en formato de carrusel interactivo con un panel central que combina imagen y descripción de cada función. Fuente: Elaboración propia.*

**Figura 6. Wireframe de la sección Beneficios**

![Beneficios2.png](../assets/img/Chapter-4/Beneficios2.png)

*Figura 6. Wireframe de la sección Beneficios del Landing Page, estructurada en tres tarjetas verticales con bordes redondeados que sintetizan las ventajas principales del servicio. Fuente: Elaboración propia.*

**Figura 7. Wireframe de la sección Sobre Nosotros (Equipo)**

![integrantes.png](../assets/img/Chapter-4/integrantes.png)

*Figura 7. Wireframe de la sección Sobre Nosotros del Landing Page, con cuadrícula de tarjetas que muestran fotografías y roles de los integrantes del equipo Ventix. Fuente: Elaboración propia.*

**Figura 8. Wireframe de la sección Misión y Visión**

![demo.png](../assets/img/Chapter-4/demo.png)

*Figura 8. Wireframe de la sección Misión y Visión del Landing Page, con bloques de texto a la izquierda para los valores de la marca y un espacio a la derecha reservado para una imagen inspiradora. Fuente: Elaboración propia.*

**Figura 9. Wireframe de la sección Planes**

![planes2.png](../assets/img/Chapter-4/planes2.png)

*Figura 9. Wireframe de la sección Planes del Landing Page, con dos columnas comparativas que detallan los niveles de suscripción Normal y Plus, incluyendo precios y características. Fuente: Elaboración propia.*

**Figura 10. Wireframe de la sección Testimonios**

![referencias.png](../assets/img/Chapter-4/referencias.png)

*Figura 10. Wireframe de la sección Testimonios del Landing Page, con tarjetas blancas a la derecha que destacan citas de clientes y un espacio de título a la izquierda. Fuente: Elaboración propia.*

**Figura 11. Wireframe de la sección Contacto**

![contacto.png](../assets/img/Chapter-4/contacto.png)

*Figura 11. Wireframe de la sección Contacto del Landing Page, con formulario para que el usuario registre su nombre, correo y consulta para resolver dudas con un especialista. Fuente: Elaboración propia.*

**Figura 12. Wireframe del Footer**

![footerpag.png](../assets/img/Chapter-4/footerpag.png)

*Figura 12. Wireframe del Footer del Landing Page, con espacios reservados para iconos de redes sociales, derechos de autor, avisos legales y el logo de la marca. Fuente: Elaboración propia.*

### 4.3.2. Landing Page Mock-up.

**Figura 13. Mock-up de la sección Hero del Landing Page**

![hero-m.png](../assets/img/Chapter-4/hero-m.png)

*Figura 13. Mock-up de la sección Hero del Landing Page de Ventix, con el logotipo, eslogan "Ventilación transparente para espacios productivos", barra de navegación y botón de llamado a la acción "Más información". Fuente: Elaboración propia en Figma.*

**Figura 14. Mock-up de la sección Funcionalidades**

![Servicios-m.png](../assets/img/Chapter-4/Servicios-m.png)

*Figura 14. Mock-up de la sección Funcionalidades con el título "Todo lo que necesitas en un solo lugar", explicando el diseño inteligente y las funciones avanzadas del sistema. Fuente: Elaboración propia en Figma.*

**Figura 15. Mock-up de la sección Misión y Visión**

![Servicios-m.png](../assets/img/Chapter-4/Servicios-m.png)

*Figura 15. Mock-up de la sección Misión y Visión, presentando "Entornos inteligentes, mejores vidas" como misión y "Referente en bienestar inteligente" como visión de Ventix. Fuente: Elaboración propia en Figma.*

**Figura 16. Mock-up de la sección Testimonios**

![testimonios-m.png](../assets/img/Chapter-4/testimonios-m.png)

*Figura 16. Mock-up de la sección Testimonios titulada "Menos estrés, más resultados", compartiendo experiencias reales de usuarios como Amira Sandoval sobre el modo automático del sistema. Fuente: Elaboración propia en Figma.*

**Figura 17. Mock-up de la sección Beneficios**

![beneficios-m.png](../assets/img/Chapter-4/beneficios-m.png)

*Figura 17. Mock-up de la sección Beneficios del Landing Page, describiendo las ventajas clave de utilizar el sistema Ventix para mejorar la calidad de vida en espacios cerrados. Fuente: Elaboración propia en Figma.*

**Figura 18. Mock-up de la sección Equipo**

![Integrantes2.png](../assets/img/Chapter-4/Integrantes2.png)

*Figura 18. Mock-up de la sección "Conoce a nuestro equipo", presentando a los desarrolladores de la aplicación Ventix con sus fotografías y roles. Fuente: Elaboración propia en Figma.*

**Figura 19. Mock-up de la sección Planes**

![plan-m.png](../assets/img/Chapter-4/plan-m.png)

*Figura 19. Mock-up de la sección "Un plan a tu medida", presentando las dos opciones principales de suscripción para acceder al potencial total de la herramienta. Fuente: Elaboración propia en Figma.*

**Figura 20. Mock-up de la sección Contacto**

![contactos-m.png](../assets/img/Chapter-4/contactos-m.png)

*Figura 20. Mock-up de la sección "Ponte en contacto con nosotros", con formulario interactivo para que el usuario ingrese su nombre, correo y consulta. Fuente: Elaboración propia en Figma.*

**Figura 21. Mock-up del Footer**

![footer-mo.png](../assets/img/Chapter-4/footer-mo.png)

*Figura 21. Mock-up del Footer del Landing Page con la identidad "Ventix Smart Ventilation", enlaces de navegación secundarios, iconos de redes sociales y aviso legal de derechos reservados 2026. Fuente: Elaboración propia en Figma.*

## 4.4. Web Applications UX/UI Design.

### 4.4.1. Web Applications Wireframes.

Se observa la pantalla de bienvenida a la aplicación de Ventix, la cual constituye el primer punto de interacción del usuario con el sistema, presentando una interfaz clara y amigable que introduce la funcionalidad principal de la plataforma.

**Figura 22. Wireframe de la Pantalla Inicial de la Web Application**

![Principal.png](../assets/img/Chapter-4/Principal.png)

*Figura 22. Wireframe de la pantalla de inicio de Ventix, con diseño limpio, logo central y botón "Conectar" que permite al usuario ingresar a la aplicación. Fuente: Elaboración propia.*

**Figura 23. Wireframe de la pantalla de Inicio de Sesión**

![inicio de sesión.png](../assets/img/Chapter-4/inicio%20de%20sesi%C3%B3n.png)

*Figura 23. Wireframe de la interfaz de inicio de sesión de Ventix, con campos para correo y contraseña, opciones para recuperar clave, registrarse y botones para autenticación social. Fuente: Elaboración propia.*

**Figura 24. Wireframe de la pantalla de Selección de Cuenta**

![elegir cuenta.png](../assets/img/Chapter-4/elegir%20cuenta.png)

*Figura 24. Wireframe de la pantalla de selección de cuenta de usuario, permitiendo elegir entre las cuentas registradas previamente para acceder al sistema. Fuente: Elaboración propia.*

**Figura 25. Wireframe de la pantalla de Recuperación de Contraseña — Paso 1**

![recuperar contraseñ5.png](../assets/img/Chapter-4/recuperar%20contrase%C3%B15.png)

*Figura 25. Wireframe del primer paso del flujo de recuperación de contraseña, con tarjeta central para ingresar el correo electrónico vinculado. Fuente: Elaboración propia.*

**Figura 26. Wireframe de la pantalla de Recuperación de Contraseña — Paso 2**

![recuperar contraseña.png](../assets/img/Chapter-4/recuperar%20contrase%C3%B1a.png)

*Figura 26. Wireframe del segundo paso del flujo de recuperación de contraseña, mostrando la confirmación del envío del enlace al correo electrónico. Fuente: Elaboración propia.*

**Figura 27. Wireframe de la pantalla de Recuperación de Contraseña — Paso 3**

![recuperar contraseña2.png](../assets/img/Chapter-4/recuperar%20contrase%C3%B1a2.png)

*Figura 27. Wireframe del tercer paso del flujo de recuperación de contraseña, con campos para establecer la nueva clave de acceso. Fuente: Elaboración propia.*

**Figura 28. Wireframe de la pantalla de Recuperación de Contraseña — Paso 4**

![recuperar contraseña3.png](../assets/img/Chapter-4/recuperar%20contrase%C3%B1a3.png)

*Figura 28. Wireframe del cuarto paso del flujo de recuperación de contraseña, con confirmación final del cambio exitoso de la clave. Fuente: Elaboración propia.*

**Figura 29. Wireframe del Registro de Usuario con Selector de Idioma**

![cambio de idioma-registro.png](../assets/img/Chapter-4/cambio%20de%20idioma-registro.png)

*Figura 29. Wireframe del formulario de registro de usuario con campos para datos personales y de contacto, espacio lateral para foto del usuario e icono de selector de idioma en la esquina superior derecha. Fuente: Elaboración propia.*

**Figura 30. Wireframe de la Selección de Tipo de Usuario**

![seleccionar-usuario.png](../assets/img/Chapter-4/seleccionar-usuario.png)

*Figura 30. Wireframe de la pantalla de selección de tipo de usuario durante el registro, permitiendo elegir entre Estudiante o Dueño de Casa. Fuente: Elaboración propia.*

**Figura 31. Wireframe del Registro de Dispositivo**

![registro-diapositivo.png](../assets/img/Chapter-4/registro-diapositivo.png)

*Figura 31. Wireframe de la interfaz de registro de dispositivos, ofreciendo dos métodos: escaneo mediante código QR o entrada por código manual, con estructura simétrica e instrucciones para cada opción. Fuente: Elaboración propia.*

**Figura 32. Wireframe del Proceso de Conexión por Código**

![conectando-codigo.png](../assets/img/Chapter-4/conectando-codigo.png)

*Figura 32. Wireframe que muestra el proceso de conexión del dispositivo mediante código manual, con indicador de progreso en tiempo real. Fuente: Elaboración propia.*

**Figura 33. Wireframe del Dispositivo Conectado por Código**

![conectado-codigo.png](../assets/img/Chapter-4/conectado-codigo.png)

*Figura 33. Wireframe de confirmación de dispositivo conectado exitosamente mediante código, con detalles del nodo sensor vinculado. Fuente: Elaboración propia.*

**Figura 34. Wireframe de los Datos del Dispositivo**

![daots del diapositivo.png](../assets/img/Chapter-4/daots%20del%20diapositivo.png)

*Figura 34. Wireframe de la pantalla de datos del dispositivo registrado, mostrando información técnica y configuración del nodo sensor en el sistema Ventix. Fuente: Elaboración propia.*

**Figura 35. Wireframe del Registro Mediante Código**

![mediante-codigo.png](../assets/img/Chapter-4/mediante-codigo.png)

*Figura 35. Wireframe del formulario de registro de dispositivo mediante código, con campo de entrada para introducir el identificador único del nodo sensor. Fuente: Elaboración propia.*

**Figura 36. Wireframe del Registro Mediante QR**

![mediante qr.png](../assets/img/Chapter-4/mediante%20qr.png)

*Figura 36. Wireframe del registro de dispositivo mediante código QR, con marco de escaneo para capturar el código del nodo sensor con la cámara. Fuente: Elaboración propia.*

**Figura 37. Wireframe del Proceso de Conexión por QR**

![conectando-qr.png](../assets/img/Chapter-4/conectando-qr.png)

*Figura 37. Wireframe del proceso de conexión del dispositivo mediante escaneo de código QR, con animación de progreso. Fuente: Elaboración propia.*

**Figura 38. Wireframe del Dispositivo Conectado**

![conectado.png](../assets/img/Chapter-4/conectado.png)

*Figura 38. Wireframe de confirmación final de dispositivo IoT conectado correctamente al ecosistema Ventix. Fuente: Elaboración propia.*

**Figura 39. Wireframe de la Pantalla Principal (Dashboard)**

![menu principal.png](../assets/img/Chapter-4/menu%20principal.png)

*Figura 39. Wireframe del dashboard principal de Ventix, con organización del control por ambientes, accesos rápidos al historial de datos, configuración de umbrales, menú lateral de navegación y botón de pánico para emergencias. Fuente: Elaboración propia.*

**Figura 40. Wireframe de la pantalla de Notificaciones**

![notificación.png](../assets/img/Chapter-4/notificaci%C3%B3n.png)

*Figura 40. Wireframe de la pantalla de notificaciones, clasificando alertas bajo la sección "Importantes" con elementos de navegación como flecha de retorno y menú de perfil. Fuente: Elaboración propia.*

**Figura 41. Wireframe del Historial de Datos**

![historial de datos.png](../assets/img/Chapter-4/historial%20de%20datos.png)

*Figura 41. Wireframe del historial de datos con disposición en tarjetas para visualizar métricas, área central amplia para datos de calidad del aire en periodos específicos y panel lateral de detalles. Fuente: Elaboración propia.*

**Figura 42. Wireframe de la Configuración de Umbrales**

![configuracion-umbreales.png](../assets/img/Chapter-4/configuracion-umbreales.png)

*Figura 42. Wireframe para la configuración de umbrales del sistema, permitiendo ajustar parámetros críticos como CO2, temperatura y humedad mediante interfaz de tarjetas. Fuente: Elaboración propia.*

**Figura 43. Wireframe del Modo Remoto**

![modo-remoto.png](../assets/img/Chapter-4/modo-remoto.png)

*Figura 43. Wireframe de la pantalla del modo remoto, permitiendo al dueño de casa monitorear y controlar la ventilación desde cualquier ubicación. Fuente: Elaboración propia.*

**Figura 44. Wireframe de la Configuración de Perfil**

![configuración-perfil.png](../assets/img/Chapter-4/configuraci%C3%B3n-perfil.png)

*Figura 44. Wireframe de la pantalla de configuración del perfil de usuario, con bloques para cambiar correo, contraseña, idioma, plan de suscripción y opciones de cierre de sesión. Fuente: Elaboración propia.*

**Figura 45. Wireframe del Mapa del Hogar**

![mapa de la casa.png](../assets/img/Chapter-4/mapa%20de%20la%20casa.png)

*Figura 45. Wireframe del mapa interactivo del hogar, con espacio amplio para el plano espacial y ventana emergente de detalles para mostrar información o controles sobre cada área seleccionada. Fuente: Elaboración propia.*

### 4.4.2. Web Applications Wireflow Diagrams.

Este wireflow integral traza el recorrido completo del usuario, desde la autenticación inicial hasta el control de dispositivos y gestión de datos. Define la jerarquía de navegación conectando el registro con todas las funciones operativas del sistema.

URL del Wireflow Diagram para una mejor visibilidad: https://www.figma.com/design/8hSVeN0bsKGAHm1RcFYhMU/wireflow?node-id=0-1&t=zA0w7ayQzJ3J9218-1

### 4.4.3. Web Applications Mock-ups.

**Figura 46. Mock-up de la Pantalla Inicial**

![inicio.png](../assets/img/Chapter-4/inicio.png)

*Figura 46. Mock-up de la pantalla inicial de Ventix con el diseño visual final aplicando el Design System y la paleta de colores oficial. Fuente: Elaboración propia en Figma.*

**Figura 47. Mock-up del Inicio de Sesión**

![login.png](../assets/img/Chapter-4/login.png)

*Figura 47. Mock-up de la pantalla de inicio de sesión con campos de correo y contraseña, aplicando los estilos visuales definidos en el Design System de Ventix. Fuente: Elaboración propia en Figma.*

**Figura 48. Mock-up de la Selección de Usuarios**

![usuarios.png](../assets/img/Chapter-4/usuarios.png)

*Figura 48. Mock-up de la pantalla de selección de cuenta de usuario con tarjetas visuales para cada perfil registrado. Fuente: Elaboración propia en Figma.*

**Figura 49. Mock-up de Recuperación de Contraseña — Paso 1**

![recuperación-contr1.png](../assets/img/Chapter-4/recuperaci%C3%B3n-contr1.png)

*Figura 49. Mock-up del primer paso del flujo de recuperación de contraseña con el diseño visual final. Fuente: Elaboración propia en Figma.*

**Figura 50. Mock-up de Recuperación de Contraseña — Paso 2**

![recuperación-contr2.png](../assets/img/Chapter-4/recuperaci%C3%B3n-contr2.png)

*Figura 50. Mock-up del segundo paso del flujo de recuperación de contraseña con confirmación de envío de enlace. Fuente: Elaboración propia en Figma.*

**Figura 51. Mock-up de Recuperación de Contraseña — Paso 3**

![recuperación-contr3.png](../assets/img/Chapter-4/recuperaci%C3%B3n-contr3.png)

*Figura 51. Mock-up del tercer paso del flujo de recuperación de contraseña para establecer la nueva clave. Fuente: Elaboración propia en Figma.*

**Figura 52. Mock-up de Recuperación de Contraseña — Paso 4**

![recuperación-contr4.png](../assets/img/Chapter-4/recuperaci%C3%B3n-contr4.png)

*Figura 52. Mock-up del cuarto paso del flujo de recuperación de contraseña con confirmación final del cambio exitoso. Fuente: Elaboración propia en Figma.*

**Figura 53. Mock-up del Registro de Usuario**

![registro.png](../assets/img/Chapter-4/registro.png)

*Figura 53. Mock-up del formulario de registro de usuario con el diseño visual final aplicando la paleta de colores y tipografía oficial de Ventix. Fuente: Elaboración propia en Figma.*

**Figura 54. Mock-up del Registro con Selector de Idiomas**

![registro-idiomas.png](../assets/img/Chapter-4/registro-idiomas.png)

*Figura 54. Mock-up del formulario de registro con el selector de idiomas (Español/Inglés) para soporte bilingüe (i18n). Fuente: Elaboración propia en Figma.*

**Figura 55. Mock-up del Registro de Dispositivos**

![registro-diapositivos.png](../assets/img/Chapter-4/registro-diapositivos.png)

*Figura 55. Mock-up de la pantalla de registro de dispositivos IoT, con opciones para vincular nuevos nodos sensores al ecosistema Ventix. Fuente: Elaboración propia en Figma.*

**Figura 56. Mock-up de la Configuración del Dispositivo**

![configuracion-diapositivo.png](../assets/img/Chapter-4/configuracion-diapositivo.png)

*Figura 56. Mock-up de la pantalla de configuración del dispositivo recién vinculado, con detalles técnicos y opciones de personalización. Fuente: Elaboración propia en Figma.*

**Figura 57. Mock-up de Conexión Mediante Código**

![codigo.png](../assets/img/Chapter-4/codigo.png)

*Figura 57. Mock-up de la pantalla de ingreso de código manual para vincular un nuevo dispositivo IoT al sistema Ventix. Fuente: Elaboración propia en Figma.*

**Figura 58. Mock-up del Proceso de Conexión por Código**

![conectando--codigo.png](../assets/img/Chapter-4/conectando--codigo.png)

*Figura 58. Mock-up del estado de "conectando" mediante código manual, con indicador de progreso visual. Fuente: Elaboración propia en Figma.*

**Figura 59. Mock-up del Dispositivo Conectado por Código**

![conectado--codigo.png](../assets/img/Chapter-4/conectado--codigo.png)

*Figura 59. Mock-up de confirmación final de dispositivo conectado exitosamente mediante código manual. Fuente: Elaboración propia en Figma.*

**Figura 60. Mock-up del Dispositivo Conectado por QR**

![coectado-qr.png](../assets/img/Chapter-4/coectado-qr.png)

*Figura 60. Mock-up de confirmación de dispositivo conectado exitosamente mediante escaneo de código QR. Fuente: Elaboración propia en Figma.*

**Figura 61. Mock-up del Escaneo de Código QR**

![qr.png](../assets/img/Chapter-4/qr.png)

*Figura 61. Mock-up de la pantalla de escaneo de código QR para vincular un dispositivo IoT, con marco de captura y guías visuales. Fuente: Elaboración propia en Figma.*

**Figura 62. Mock-up de la Pantalla Principal (Dashboard)**

![pantalla-principal.png](../assets/img/Chapter-4/pantalla-principal.png)

*Figura 62. Mock-up del dashboard principal de Ventix, con visualización en tiempo real de CO2, temperatura, humedad, mapa de zonas, batería de dispositivos y accesos a las funciones principales. Fuente: Elaboración propia en Figma.*

**Figura 63. Mock-up de Notificaciones del Sistema**

![notificaciones-sistema.png](../assets/img/Chapter-4/notificaciones-sistema.png)

*Figura 63. Mock-up de la pantalla de notificaciones del sistema, con clasificación de alertas por importancia y diseño visual final. Fuente: Elaboración propia en Figma.*

**Figura 64. Mock-up del Historial de Datos**

![historial.png](../assets/img/Chapter-4/historial.png)

*Figura 64. Mock-up del historial de datos ambientales con visualización gráfica de tendencias por día, semana y mes. Fuente: Elaboración propia en Figma.*

**Figura 65. Mock-up de la Configuración**

![configuracion.png](../assets/img/Chapter-4/configuracion.png)

*Figura 65. Mock-up de la pantalla de configuración de cuenta, con opciones para modificar correo, contraseña, plan y preferencias del usuario. Fuente: Elaboración propia en Figma.*

**Figura 66. Mock-up de la Configuración de Idiomas**

![configuracion-idiomas.png](../assets/img/Chapter-4/configuracion-idiomas.png)

*Figura 66. Mock-up de la configuración de idiomas, permitiendo cambiar entre Español Latinoamericano (es_419) e Inglés (en_US). Fuente: Elaboración propia en Figma.*

**Figura 67. Mock-up del Mapa del Hogar (Plano de Casa)**

![plano-casa.png](../assets/img/Chapter-4/plano-casa.png)

*Figura 67. Mock-up del plano interactivo del hogar, mostrando la ubicación de cada nodo sensor y su estado en tiempo real. Fuente: Elaboración propia en Figma.*

### 4.4.4. Web Applications User Flow Diagrams.

URL del User Flow Diagrams para una mejor visibilidad: https://miro.com/app/board/uXjVGg7StrE=/?share_link_id=836653906543

**Figura 68. User Flow del Plano del Hogar**

![userflow--plano.png](../assets/img/Chapter-4/userflow--plano.png)

*Figura 68. User Flow Diagram del flujo de interacción con el plano del hogar, incluyendo happy path y rutas alternativas para gestionar los nodos sensores en cada zona. Fuente: Elaboración propia en Miro.*

**Figura 69. User Flow de la Configuración de Perfiles**

![userflow-configuracion-perfiles.png](../assets/img/Chapter-4/userflow-configuracion-perfiles.png)

*Figura 69. User Flow Diagram del flujo de configuración del perfil del usuario, incluyendo cambio de datos personales, contraseña e idioma. Fuente: Elaboración propia en Miro.*

**Figura 70. User Flow del Historial de Datos**

![userflow-historial.png](../assets/img/Chapter-4/userflow-historial.png)

*Figura 70. User Flow Diagram del acceso y navegación por el historial de datos ambientales del sistema Ventix. Fuente: Elaboración propia en Miro.*

**Figura 71. User Flow de Ingreso al Sistema**

![userflow-ingreso.png](../assets/img/Chapter-4/userflow-ingreso.png)

*Figura 71. User Flow Diagram del flujo de ingreso al sistema, desde la pantalla inicial hasta la selección de cuenta y acceso al dashboard. Fuente: Elaboración propia en Miro.*

**Figura 72. User Flow de Notificaciones**

![userflow-notificaciones.png](../assets/img/Chapter-4/userflow-notificaciones.png)

*Figura 72. User Flow Diagram del flujo de notificaciones del sistema, mostrando cómo el usuario accede, revisa y gestiona las alertas. Fuente: Elaboración propia en Miro.*

**Figura 73. User Flow de Recuperación de Contraseña**

![userflow-recuperación.png](../assets/img/Chapter-4/userflow-recuperaci%C3%B3n.png)

*Figura 73. User Flow Diagram del flujo completo de recuperación de contraseña, desde la solicitud hasta la confirmación del cambio exitoso. Fuente: Elaboración propia en Miro.*

**Figura 74. User Flow del Registro de Dispositivos**

![userflow-registrar-diapositivos.png](../assets/img/Chapter-4/userflow-registrar-diapositivos.png)

*Figura 74. User Flow Diagram del flujo de registro de dispositivos IoT, contemplando los métodos de QR y código manual. Fuente: Elaboración propia en Miro.*

**Figura 75. User Flow del Registro de Usuario**

![userflow-registro.png](../assets/img/Chapter-4/userflow-registro.png)

*Figura 75. User Flow Diagram del flujo de registro de un nuevo usuario en la plataforma Ventix, incluyendo datos personales y selección de tipo de cuenta. Fuente: Elaboración propia en Miro.*

**Figura 76. User Flow de la Configuración de Umbrales**

![userflow-umbreales.png](../assets/img/Chapter-4/userflow-umbreales.png)

*Figura 76. User Flow Diagram del flujo de configuración de umbrales (CO2, temperatura y humedad) y cambio entre modo automático y manual. Fuente: Elaboración propia en Miro.*

## 4.5. Web Applications Prototyping.

La sección de Web Application Prototyping presenta los prototipos interactivos de la versión Desktop y Mobile Web de Ventix. Este prototipo simula la interacción entre el usuario y la aplicación, es decir, la navegación real dentro de la plataforma recorriendo los principales paths definidos en los User Flow Diagrams.

Las decisiones de interacción tomadas en esta etapa responden a tres criterios fundamentales:

* **Priorización de datos críticos:** Garantizar que los niveles de CO2, humedad y temperatura sean visibles de inmediato para prevenir riesgos.
* **Control intuitivo:** Facilitar la configuración de umbrales y modos de ventilación sin necesidad de conocimientos técnicos avanzados.
* **Seguridad y respuesta rápida:** Inclusión de accesos directos a alertas y un botón de pánico funcional para situaciones de emergencia.

**Criterios que guiaron las decisiones de interacción**

1. **Arquitectura de información basada en prioridades del usuario:** La estructura del contenido se organizó priorizando los datos de los sensores y el estado de los dispositivos en cada ambiente del hogar:
    * Indicadores de temperatura, CO2 y humedad en tiempo real.
    * Estado de funcionamiento de ventiladores.
    * Mapa interactivo donde se ubica cada ventilador y su batería.
    * Historial detallado de datos.
    * Configuración de umbrales de activación.

2. **Navegación clara y consistente:** Se implementó un sistema de navegación que maximiza el espacio de visualización de datos:
    * **En desktop:** Un menú lateral izquierdo persistente que permite el acceso rápido a Home, Mapa, Notificaciones y Configuración.
    * **En mobile:** Una navegación optimizada para pulgar mediante accesos directos y menús simplificados que no obstruyen la lectura de los indicadores.

3. **Interacciones basadas en patrones familiares:** Para reducir la curva de aprendizaje, se utilizaron patrones familiares en aplicaciones de domótica:
    * **Tarjetas de estado:** Cuadros que muestran la información de cada variable, usando colores para indicar si todo está bien o si hay algún riesgo.
    * **Interruptores y deslizadores:** Permiten cambiar entre modos (ahorro y optimizado) y ajustar valores de forma simple.
    * **Vista del espacio:** Un plano del lugar donde se puede ver dónde está cada dispositivo.

4. **Principios de diseño inclusivo:** Tanto el prototipo desktop como el mobile consideran:
    * Tipografías legibles y contrastes adecuados para adultos y jóvenes.
    * Botones amplios para facilitar el toque.
    * Lenguaje visual claro y sencillo para que todo tipo de usuario pueda entender la información y el proceso.

* **Prototipo versión desktop:**
  Los prototipos desktop muestran una interfaz amplia, optimizada para un monitoreo profundo y gestión administrativa de los dispositivos.
    * **Dashboard principal:** Presenta un saludo personalizado, las tres características principales visibles de inmediato (temperatura, nivel de CO2 y porcentaje de humedad), y visualización modular de las zonas de la casa con el estado de batería de cada una.
    * **Navegación lateral:** Un menú persistente con iconos claros para Home, Mapas, Notificaciones, Configuraciones y Registro, orientando al usuario en su navegación.
    * **Secciones modulares:** El contenido se divide en bloques visuales (tarjetas para cada cuarto y estado de ventilación, historial de datos detallado, plano del hogar interactivo, configuración de umbrales y paneles laterales de alertas para notificaciones).

* **Prototipo versión Mobile:**
  La versión móvil prioriza la inmediatez y la usabilidad táctil, manteniendo la esencia visual del desktop pero adaptada a pantallas reducidas.
    * **Home:** Un resumen instantáneo de los niveles clave de calidad del aire, ocupando el espacio central.
    * **Tab-Bar inferior:** Reduce la carga cognitiva y facilita el uso con una sola mano.
    * **Menú hamburguesa:** Incluye secciones secundarias como Ayuda, Acerca de, permisos extendidos o historial extendido. Se evita sobrecargar la pantalla principal.
    * **Interacción táctil optimizada:** Botones grandes y espaciados, facilidad para ajustar los umbrales de manera táctil.

5. **Relación con los User Flow Diagrams:** Cada pantalla del prototipo de Ventix fue diseñada respetando los flujos de usuarios previamente establecidos. Por ejemplo, se diseñaron flujos claros para:
    * Ingresar a la plataforma: Desde la conexión inicial hasta la selección de cuenta.
    * Registrarse en la plataforma: Guía paso a paso desde el inicio hasta el tipo de usuario.
    * Observar el historial de datos: Acceso directo desde el dashboard a la lista histórica detallada.
    * Ingreso a notificaciones y planos: Flujo directo para ver alertas o el plano interactivo de la casa.
    * Configuración de umbrales de manera manual: El camino para cambiar de automático a manual y ajustar parámetros.
    * Subir un dispositivo nuevo: Flujos específicos para QR y código manual con confirmación de éxito.

URL del video del prototipo Desktop: https://youtu.be/sGtuup0EXG0

## 4.6. Domain-Driven Software Architecture.

La arquitectura de software de Ventix se basa en los principios de Domain-Driven Design (DDD), priorizando la lógica del negocio y la consistencia del lenguaje ubicuo sobre las implementaciones técnicas.

En las siguientes secciones se presenta cada nivel del modelo, explicando la estructura, responsabilidades y comunicación entre los elementos que conforman la arquitectura de Ventix.

### 4.6.1. Design-Level Event Storming.

Para identificar los eventos de dominio, es recomendable realizar una sesión de Event Storming. Esta técnica permite visualizar y comprender el flujo de eventos dentro del dominio, facilitando la identificación de los Bounded Context. El desarrollo del proceso del Domain-Driven Design se realizó en la aplicación Miro.

**1. Bounded Context IAM**

El Bounded Context IAM (Identity and Access Management) se encarga de la autenticación, autorización y gestión de identidades dentro del ecosistema Ventix. Administra procesos fundamentales como el registro de estudiantes y dueños de casa, el inicio de sesión seguro, la revocación de sesiones y la asignación de permisos basados en roles específicos. Su propósito es garantizar accesos protegidos y personalizados, asegurando que cada usuario acceda únicamente a sus propios dispositivos y métricas ambientales, manteniendo la integridad y privacidad de la información en toda la plataforma.

**Figura 77. Design-Level Event Storming del Bounded Context IAM**

![IAM Bounded.png](../assets/img/Chapter-4/IAM%20Bounded.png)

*Figura 77. Design-Level Event Storming del Bounded Context IAM, mostrando los eventos de dominio, comandos y agregados relacionados con la gestión de identidad y control de accesos en Ventix. Fuente: Elaboración propia en Miro.*

**2. Bounded Context Monitoring & Automation**

El Bounded Context Monitoring & Automation se encarga de la ingesta de datos en tiempo real, el procesamiento de métricas ambientales y la ejecución de respuestas automáticas dentro del ecosistema Ventix. Administra procesos críticos como la recepción de lecturas de sensores (CO₂, temperatura y humedad), la evaluación de reglas de negocio basadas en umbrales personalizados y la activación o desactivación automática de actuadores (ventiladores). Su propósito es garantizar un entorno saludable y productivo de forma autónoma, permitiendo además el control manual y la supervisión constante de la calidad del aire a través de un dashboard interactivo.

**Figura 78. Design-Level Event Storming del Bounded Context Monitoring & Automation**

![M&A Bounded.png](../assets/img/Chapter-4/M%26A%20Bounded.png)

*Figura 78. Design-Level Event Storming del Bounded Context Monitoring & Automation, mostrando el flujo de eventos relacionados con la ingesta de telemetría, evaluación de umbrales y activación automática de ventiladores. Fuente: Elaboración propia en Miro.*

**3. Bounded Context Device & Asset Management**

El Bounded Context Device & Asset Management se encarga del inventario, vinculación y mantenimiento del hardware dentro del ecosistema Ventix. Administra procesos esenciales como el registro de nuevos nodos físicos, la asociación de dispositivos a usuarios específicos, el monitoreo del estado de la batería y la actualización del firmware. Su propósito es asegurar que la infraestructura tecnológica esté correctamente desplegada y operativa, garantizando que cada sensor y actuador esté vinculado de forma única y segura antes de iniciar cualquier actividad de monitoreo o automatización en la plataforma.

**Figura 79. Design-Level Event Storming del Bounded Context Device & Asset Management**

![D&A Bounded.png](../assets/img/Chapter-4/D%26A%20Bounded.png)

*Figura 79. Design-Level Event Storming del Bounded Context Device & Asset Management, mostrando los eventos relacionados con el ciclo de vida del hardware IoT (registro, vinculación, monitoreo y actualización). Fuente: Elaboración propia en Miro.*

**4. Bounded Context Analytics & Reporting**

El Bounded Context Analytics & Reporting se encarga del procesamiento, análisis y visualización de la información histórica generada dentro del ecosistema Ventix. Administra procesos como el cálculo de tendencias semanales de calidad de aire, la generación de reportes mensuales de salud ambiental y la determinación del "score de concentración" para estudiantes. Su propósito es transformar los datos crudos recolectados por los sensores en información estratégica y comprensible, brindando a los usuarios una visión clara sobre su bienestar, el rendimiento de sus dispositivos y el cumplimiento de sus objetivos de salud a largo plazo.

**Figura 80. Design-Level Event Storming del Bounded Context Analytics & Reporting**

![A&R Bounded.png](../assets/img/Chapter-4/A%26R%20Bounded.png)

*Figura 80. Design-Level Event Storming del Bounded Context Analytics & Reporting, mostrando los eventos relacionados con el cálculo de tendencias, scores de concentración y generación de reportes mensuales. Fuente: Elaboración propia en Miro.*

**5. Bounded Context Payments**

Se ha definido el Bounded Context de Payments para gestionar el ciclo de vida financiero de los usuarios. Este contexto actúa como un adaptador para la pasarela de pagos Stripe, encargándose de la gestión de planes, suscripciones y la persistencia de transacciones. Esta separación asegura que la lógica de negocio core (monitoreo) permanezca agnóstica a los cambios en los proveedores de pago externos.

**Figura 81. Design-Level Event Storming del Bounded Context Payments**

![PaymentBoundedContext.png](../assets/img/Chapter-4/PaymentBoundedContext.png)

*Figura 81. Design-Level Event Storming del Bounded Context Payments, mostrando los eventos de dominio relacionados con la integración con Stripe, gestión de planes, suscripciones y transacciones financieras. Fuente: Elaboración propia en Miro.*

**6. Bounded Context Shared**

El Bounded Context Shared contiene elementos reutilizables y transversales usados por todos los demás contextos, como configuraciones globales, catálogos, constantes, plantillas de comunicación o políticas comunes. Su propósito es evitar duplicidad de lógica y asegurar coherencia en datos y reglas compartidas entre contextos.

**Figura 82. Design-Level Event Storming del Bounded Context Shared**

![Shared Bounded.png](../assets/img/Chapter-4/Shared%20Bounded.png)

*Figura 82. Design-Level Event Storming del Bounded Context Shared, mostrando los elementos transversales reutilizados por todos los contextos del ecosistema Ventix. Fuente: Elaboración propia en Miro.*

### 4.6.2. Software Architecture Context Diagram.

En este nivel se presenta una vista de alto nivel de la arquitectura, donde el foco está en el sistema de software Ventix como una "caja negra" y en las interacciones que mantiene con sus usuarios y con otros sistemas externos.

El context diagram muestra al Ventix Software System como un recuadro en el centro, rodeado por los principales actores y sistemas con los que se comunica:

- **Student:** usuario principal que interactúa con la plataforma para monitorear la calidad del aire en sus áreas de estudio, configurar estados de confort y visualizar sus métricas de concentración y salud ambiental.
- **Home Owner:** usuario responsable de la gestión de los dispositivos en el hogar o institución. Interactúa con Ventix para vincular nuevos nodos sensores, establecer umbrales de alerta y supervisar la seguridad del ambiente de forma remota.
- **IoT Sensor Hardware:** sistema físico externo compuesto por nodos sensores de CO₂, temperatura y humedad. Se comunica con Ventix para enviar telemetría en tiempo real y recibir comandos de activación para los sistemas de ventilación.
- **Payment System (Stripe):** sistema externo encargado de procesar las suscripciones de los planes premium, pagos por adquisición de hardware y la facturación asociada al uso de las funcionalidades avanzadas de la plataforma.

En el diagrama se representan las relaciones entre estos elementos, destacando que tanto el estudiante como el dueño de casa interactúan únicamente con Ventix, mientras que el sistema se encarga de orquestar las integraciones con el hardware físico y los servicios externos (pagos y notificaciones). Esta vista permite entender el alcance del sistema, los límites de responsabilidad y el ecosistema en el que se inserta Ventix antes de entrar a detalles de implementación.

**Figura 83. Software Architecture Context Diagram (C4 Model — Nivel 1)**

![SystemContext.png](../assets/img/Chapter-4/Diagrams/SystemContext.png)

*Figura 83. Diagrama de Contexto del C4 Model para Ventix, mostrando el Ventix Software System como caja negra y sus relaciones con Estudiantes, Dueños de Casa, IoT Sensor Hardware y Stripe Payment System. Fuente: Elaboración propia en Structurizr.*

### 4.6.3. Software Architecture Container Diagrams.

En el nivel de contenedores, la atención se desplaza desde "quién usa el sistema" hacia "cómo se organiza internamente el sistema en aplicaciones y fuentes de datos". El container diagram muestra los elementos de alto nivel de la arquitectura de Ventix, sus responsabilidades principales y la forma en que se comunican entre sí y con los sistemas externos.

La arquitectura lógica de Ventix se estructura en los siguientes contenedores:

- **Landing Page:** aplicación web estática que presenta la propuesta de valor de Ventix, compara los planes (Normal vs. Plus) y guía a nuevos usuarios. Está desarrollada con tecnologías web estándar (HTML, CSS y JavaScript) y se despliega en un entorno orientado a contenido estático.
- **Web Application:** servidor de archivos estáticos (Nginx) responsable de entregar los binarios compilados de la SPA a los navegadores de los clientes.
- **Single Page Application (SPA):** aplicación web principal, implementada en Angular, donde interactúan el Estudiante y el Dueño de Casa. Este contenedor concentra la experiencia de usuario, las interfaces de los dashboards de calidad de aire, la gestión de dispositivos IoT y los paneles de facturación.
- **API Application:** contenedor basado en Spring Cloud Gateway (implementado en Spring Boot) que actúa como punto de entrada único para la SPA. Se encarga del ruteo inteligente de peticiones hacia los microservicios internos y de la validación centralizada de seguridad (tokens JWT), garantizando protección perimetral.
- **Bounded Contexts (Microservices):** backend distribuido implementado mediante Spring Boot REST APIs, que encapsula la lógica de negocio y reglas de validación de cada dominio. Este contenedor agrupa los servicios independientes que gestionan la identidad (IAM), el monitoreo y automatización, la administración de hardware, la generación de analítica y el procesamiento de pagos.
- **Database:** sistema de persistencia basado en MySQL. Aunque físicamente puede estar en un mismo servidor para optimizar recursos iniciales, almacena la información estructurada mediante esquemas lógicamente separados para IAM, Monitoring, Devices, Analytics y Payments, asegurando el aislamiento de los datos y permitiendo escalabilidad técnica futura.

En el diagrama se observa que los usuarios (Estudiante y Dueño de Casa) interactúan con la Landing Page para descubrir el producto e iniciar su registro, lo que a su vez carga la SPA servida por la Web Application. La SPA se comunica exclusivamente con el API Gateway mediante peticiones HTTP/HTTPS utilizando el formato JSON. Además, la SPA inicia flujos directos hacia Stripe (mediante Checkout) para la captura segura de datos de pago. El API Gateway autentica las peticiones y las enruta hacia la suite de Microservicios correspondiente. Los Microservicios interactúan con la Database mediante JDBC para operaciones de lectura y escritura en sus respectivos esquemas. Existen integraciones críticas en el backend: el microservicio de Payments crea cargos y procesa webhooks provenientes de Stripe, mientras que el contexto de Monitoring recibe la telemetría continua empujada (push) por el IoT Sensor Hardware mediante protocolos HTTP o MQTT.

Esta vista permite apreciar claramente el patrón de arquitectura de microservicios adoptado, la separación estricta entre presentación, orquestación (Gateway), lógica de negocio distribuida y persistencia de datos.

**Figura 84. Software Architecture Container Diagram (C4 Model — Nivel 2)**

![Containerslast.png](../assets/img/Chapter-4/Containerslast.png)

*Figura 84. Diagrama de Contenedores del C4 Model para Ventix, mostrando la Landing Page, Web Application (Nginx + SPA Angular), API Gateway (Spring Cloud Gateway), Microservicios (Spring Boot REST APIs), Base de datos MySQL y las integraciones con Stripe e IoT Sensor Hardware. Fuente: Elaboración propia en Structurizr.*

### 4.6.4. Software Architecture Components Diagrams.

En el nivel de componentes se detalla la descomposición interna de los contenedores, mostrando los bloques estructurales que conforman cada uno y las relaciones entre ellos. Dado que la Single Page Application y la Database ya fueron descritas en otros apartados mediante diagramas de clases frontend y de base de datos, en esta sección se pone especial énfasis en el contenedor API Application, donde reside la mayor parte de la lógica de negocio.

El component diagram de la API Application agrupa la arquitectura interna siguiendo los bounded contexts definidos en el dominio de Ventix. Cada módulo backend representa un componente principal dentro del contenedor:

- **IAM Backend:** se encarga de la autenticación, registro de usuarios (Estudiantes y Dueños de Casa), gestión de sesiones, validación de tokens JWT y revocación de acceso.
- **Monitoring & Automation Backend:** recibe la telemetría de los nodos sensores, evalúa las reglas de automatización configurables y detecta niveles críticos de CO2 para disparar comandos de activación de ventilación.
- **Analytics & Reporting Backend:** ofrece capacidades de agregación y consulta de métricas, calculando los concentration scores, produciendo gráficos de tendencias y generando los reportes mensuales de salud institucional.
- **Device & Asset Management Backend:** gestiona el ciclo de vida del hardware, incluyendo el registro de nodos sensores, vinculación de dispositivos a usuarios, monitoreo de batería y seguimiento del stock.
- **Payment Backend:** encapsula el manejo de compras de planes (Normal y Plus), suscripciones recurrentes, facturación y reembolsos, integrándose con el Payment System (Stripe) para la ejecución y confirmación de cobros.
- **Shared Backend:** provee componentes compartidos, utilidades, objetos de valor comunes (como configuraciones globales y filtros de seguridad), clases base e infraestructura transversal utilizada por los demás módulos backend.

En el diagrama se refleja cómo la SPA consume los servicios expuestos por cada módulo backend a través de la API Application, utilizando endpoints REST/HTTPS específicos por contexto para renderizar dashboards, reportes y vistas de gestión. Cada módulo backend accede a la Database para leer y escribir la información correspondiente a su contexto de forma independiente. Algunos módulos se integran con sistemas externos: Payment Backend mantiene una comunicación bidireccional con Stripe (mediante API y webhooks), y Monitoring Backend interactúa con el IoT Sensor Hardware para la ingesta de telemetría. Además, se realizan llamadas internas (REST) entre módulos, como la notificación de pago exitoso desde Payment hacia Device Management. Todos los módulos operativos backend reutilizan capacidades comunes provistas por el Shared Kernel en tiempo de compilación, lo que favorece la consistencia, la reutilización y la reducción de duplicación de código en todo el sistema.

**Figura 85. Software Architecture Components Diagram (C4 Model — Nivel 3)**

![ComponentsLast.png](../assets/img/Chapter-4/Diagrams/ComponentsLast.png)

*Figura 85. Diagrama de Componentes del C4 Model para la API Application de Ventix, mostrando los seis módulos backend (IAM, Monitoring & Automation, Analytics & Reporting, Device & Asset Management, Payment, Shared) y sus interacciones con la SPA, base de datos y sistemas externos. Fuente: Elaboración propia en Structurizr.*

## 4.7. Software Object-Oriented Design.

En esta sección se presenta el diseño orientado a objetos del sistema Ventix, el cual desarrolla con mayor detalle la implementación interna de los componentes identificados en los diagramas C4 del apartado anterior. A partir de los contenedores y componentes definidos (Frontend en Angular, API Application en Spring Boot y Database en MySQL), se derivan diagramas de clases específicos para cada bounded context del dominio, con el objetivo de mostrar:

- **Modelado del Dominio (Backend):** Cómo se estructuran las entidades, agregados, repositorios y servicios dentro de cada microservicio de Spring Boot, asegurando que la lógica de negocio (como las reglas de automatización o el cálculo de scores) esté aislada y protegida, mientras se apoyan en un núcleo compartido para evitar redundancias.
- **Arquitectura de Presentación (Frontend):** Cómo se organizan los componentes, servicios de datos y modelos de vista en Angular para ofrecer una experiencia reactiva al estudiante y al dueño de casa.
- **Diseño de Persistencia (Database):** Cómo se mapean los objetos del dominio a tablas relacionales en MySQL, manteniendo la integridad referencial y el aislamiento de datos por cada contexto.

### 4.7.1. Class Diagrams.

En esta subsección se presentan los diagramas de clases que detallan la estructura interna de los principales componentes para cada bounded context. Estos diagramas complementan al Component Diagram de la API Application y a los contenedores definidos en Structurizr, proporcionando una vista técnica centrada en clases, atributos, métodos y relaciones de herencia y composición.

A nivel de frontend, se modelan las clases en Angular en función de los módulos que consumen los servicios expuestos por la API REST:

- **Frontend completo (Ventix-Web):** muestra la organización general de la capa de presentación, incluyendo el sistema de ruteo y los servicios de comunicación que interactúan con el API Gateway.
- **Shared Frontend:** agrupa componentes visuales reutilizables (como velocímetros de calidad de aire, tarjetas de estado, layouts base), interceptores HTTP y servicios de notificación comunes que sirven como infraestructura de presentación para el resto de los módulos.
- **IAM Frontend:** incluye los formularios y componentes relacionados con el registro de estudiantes y dueños de casa, inicio de sesión y servicios de guardia (AuthGuards) para la protección de rutas.
- **Monitoring Frontend:** detalla las clases que gestionan las vistas en tiempo real de la calidad del aire, indicadores de CO₂ y los componentes de control para la activación manual de ventiladores.
- **Device Mgmt Frontend:** modela los componentes responsables de la vinculación de nuevos nodos sensores mediante códigos ID y la visualización del estado de salud de cada dispositivo físico.
- **Analytics Frontend:** presenta los componentes de interfaz que construyen los dashboards de concentración y gráficas de tendencias ambientales a partir de datos procesados.
- **Payments Frontend:** incluye las clases dedicadas a la gestión de planes de suscripción, integración de la pasarela de pago para el flujo de checkout y visualización de facturas.

A nivel de backend, los diagramas de clases reflejan la implementación detallada en Spring Boot de los módulos definidos como componentes, donde cada uno gestiona su propia lógica y persistencia pero importa capacidades comunes:

- **Backend completo:** ilustra la estructura de la capa de dominio siguiendo los patrones de Domain-Driven Design, mostrando cómo cada microservicio encapsula sus propios agregados, entidades y repositorios de forma aislada, dependiendo transversalmente de una librería compartida.
- **Shared Backend:** concentra clases base como AuditableEntity, utilidades de manejo de excepciones, configuraciones de seguridad compartidas y objetos de valor comunes (como la estructura estándar de una lectura ambiental o de moneda), garantizando consistencia técnica en todo el ecosistema.
- **IAM Backend:** muestra clases como User, Role y AuthToken, junto con los servicios de seguridad encargados de la emisión y validación de credenciales.
- **Monitoring & Automation Backend:** incluye los agregados fundamentales AirQualityReading y AutomationRule, los cuales contienen la lógica para evaluar la telemetría y ejecutar acciones de control sobre el hardware.
- **Device & Asset Backend:** detalla las clases SensorNode y DeviceOwnership, responsables de mantener el registro del hardware y su relación contractual con los usuarios finales.
- **Analytics Backend:** modela las entidades especializadas en datos históricos como TrendAnalysis y ConcentrationScore, optimizadas para la lectura de reportes de bienestar.
- **Payments Backend:** contiene las clases Subscription y Transaction, encargadas de gestionar el ciclo de vida comercial y la integración técnica con los webhooks de Stripe.

#### Diagrama de clases del frontend

**Figura 86. Diagrama de Clases del Frontend Completo (Ventix-Web)**

![frontend-complete-class-diagram.png](../assets/img/Chapter-4/Diagrams/frontend-complete-class-diagram.png)

*Figura 86. Diagrama de Clases UML del frontend completo de Ventix, mostrando la organización general de la capa de presentación en Angular, el sistema de ruteo y los servicios de comunicación con el API Gateway. Fuente: Elaboración propia en LucidChart.*

**Figura 87. Diagrama de Clases del Frontend — Vista dividida (Parte 1)**

![fila-1-columna-1 (1).png](../assets/img/Chapter-4/Diagrams/fila-1-columna-1%20%281%29.png)

*Figura 87. Diagrama de Clases del Frontend de Ventix — Sección dividida (Parte 1), mostrando un detalle ampliado de la primera mitad del diagrama completo para mejor visualización. Fuente: Elaboración propia en LucidChart.*

**Figura 88. Diagrama de Clases del Frontend — Vista dividida (Parte 2)**

![fila-1-columna-2.png](../assets/img/Chapter-4/Diagrams/fila-1-columna-2.png)

*Figura 88. Diagrama de Clases del Frontend de Ventix — Sección dividida (Parte 2), mostrando un detalle ampliado de la segunda mitad del diagrama completo para mejor visualización. Fuente: Elaboración propia en LucidChart.*

#### Diagrama del frontend dividido por contextos

**Figura 89. Diagrama de Clases del Monitoring Frontend**

![MonitoringFrint.png](../assets/img/chapter-5/MonitoringFrint.png)

*Figura 89. Diagrama de Clases UML del Monitoring Frontend de Ventix, mostrando los componentes Angular que gestionan la visualización en tiempo real de CO₂, temperatura, humedad y los controles de activación manual de ventiladores. Fuente: Elaboración propia en LucidChart.*

**Figura 90. Diagrama de Clases del IAM Frontend**

![IAMfront.png](../assets/img/chapter-5/IAMfront.png)

*Figura 90. Diagrama de Clases UML del IAM Frontend de Ventix, mostrando los formularios y componentes relacionados con el registro, inicio de sesión y AuthGuards para protección de rutas. Fuente: Elaboración propia en LucidChart.*

**Figura 91. Diagrama de Clases del Device Management Frontend**

![DeviceFront.png](../assets/img/chapter-5/DeviceFront.png)

*Figura 91. Diagrama de Clases UML del Device & Asset Management Frontend, mostrando los componentes responsables de la vinculación de nodos sensores mediante QR/código y la visualización del estado de los dispositivos. Fuente: Elaboración propia en LucidChart.*

**Figura 92. Diagrama de Clases del Analytics Frontend**

![AnalyticsFront.png](../assets/img/chapter-5/AnalyticsFront.png)

*Figura 92. Diagrama de Clases UML del Analytics & Reporting Frontend, mostrando los componentes de interfaz que construyen los dashboards de concentración y gráficas de tendencias ambientales. Fuente: Elaboración propia en LucidChart.*

**Figura 93. Diagrama de Clases del Payments Frontend**

![PaymentFront.png](../assets/img/chapter-5/PaymentFront.png)

*Figura 93. Diagrama de Clases UML del Payments Frontend, mostrando las clases dedicadas a la gestión de planes de suscripción, integración con Stripe Checkout y visualización de facturas. Fuente: Elaboración propia en LucidChart.*

**Figura 94. Diagrama de Clases del Shared Frontend**

![sharedfront.png](../assets/img/chapter-5/sharedfront.png)

*Figura 94. Diagrama de Clases UML del Shared Frontend de Ventix, mostrando los componentes visuales reutilizables (velocímetros, tarjetas de estado, layouts base), interceptores HTTP y servicios de notificación comunes. Fuente: Elaboración propia en LucidChart.*

#### Diagramas de clases del backend

**Figura 95. Diagrama de Clases del Backend Completo**

![backend-complete-class-diagram.svg](../assets/img/Chapter-4/Diagrams/backend-complete-class-diagram.svg)

*Figura 95. Diagrama de Clases UML del Backend completo de Ventix, ilustrando la estructura de la capa de dominio según los patrones de Domain-Driven Design y la separación entre microservicios independientes con dependencia transversal de la librería compartida. Fuente: Elaboración propia en LucidChart.*

**Figura 96. Diagrama de Clases del Monitoring & Automation Backend**

![MonitoringBackend.png](../assets/img/Chapter-4/Diagrams/MonitoringBackend.png)

*Figura 96. Diagrama de Clases UML del Monitoring & Automation Backend, mostrando los agregados AirQualityReading y AutomationRule junto con la lógica de evaluación de telemetría y control del hardware. Fuente: Elaboración propia en LucidChart.*

**Figura 97. Diagrama de Clases del IAM Backend**

![IAMBackend.png](../assets/img/Chapter-4/Diagrams/IAMBackend.png)

*Figura 97. Diagrama de Clases UML del IAM Backend, mostrando las clases User, Role y AuthToken junto con los servicios de seguridad para emisión y validación de credenciales JWT. Fuente: Elaboración propia en LucidChart.*

**Figura 98. Diagrama de Clases del Device & Asset Management Backend**

![DeviceBackend.png](../assets/img/Chapter-4/Diagrams/DeviceBackend.png)

*Figura 98. Diagrama de Clases UML del Device & Asset Management Backend, detallando las clases SensorNode y DeviceOwnership responsables del registro del hardware y la relación contractual con usuarios. Fuente: Elaboración propia en LucidChart.*

**Figura 99. Diagrama de Clases del Analytics & Reporting Backend**

![AnalyticsBackend.png](../assets/img/Chapter-4/Diagrams/AnalyticsBackend.png)

*Figura 99. Diagrama de Clases UML del Analytics & Reporting Backend, modelando las entidades TrendAnalysis y ConcentrationScore especializadas en datos históricos y reportes de bienestar. Fuente: Elaboración propia en LucidChart.*

**Figura 100. Diagrama de Clases del Payments Backend**

![PaymentBackend.png](../assets/img/Chapter-4/Diagrams/PaymentBackend.png)

*Figura 100. Diagrama de Clases UML del Payments Backend, mostrando las clases Subscription y Transaction encargadas del ciclo de vida comercial e integración con webhooks de Stripe. Fuente: Elaboración propia en LucidChart.*

**Figura 101. Diagrama de Clases del Shared Backend**

![backendshared.png](../assets/img/Chapter-4/Diagrams/backendshared.png)

*Figura 101. Diagrama de Clases UML del Shared Backend, concentrando clases base como AuditableEntity, utilidades de manejo de excepciones, configuraciones de seguridad y objetos de valor comunes. Fuente: Elaboración propia en LucidChart.*

## 4.8. Database Design.

### 4.8.1. Database Diagrams.

**Figura 102. Database Diagram Completo del Sistema Ventix**

![database-complete-diagram.svg](../assets/img/Chapter-4/Diagrams/database-complete-diagram.svg)

*Figura 102. Database Diagram completo del sistema Ventix, mostrando todos los esquemas lógicamente separados (IAM, Payment, Device, Monitoring, Analytics) en una única vista integrada con sus relaciones, primary keys y foreign keys. Fuente: Elaboración propia en Vertabelo.*

**Figura 103. Database Diagram del Esquema IAM**

![iam dataabase.png](../assets/img/Chapter-4/Diagrams/iam%20dataabase.png)

*Figura 103. Database Diagram del esquema IAM (Identity and Access Management), mostrando las tablas de usuarios, roles, permisos y tokens de autenticación con sus relaciones y constraints. Fuente: Elaboración propia en Vertabelo.*

**Figura 104. Database Diagram del Esquema Payments**

![payment database.png](../assets/img/Chapter-4/Diagrams/payment%20database.png)

*Figura 104. Database Diagram del esquema Payments, mostrando las tablas de planes, suscripciones, transacciones y registros de Stripe con sus relaciones y constraints. Fuente: Elaboración propia en Vertabelo.*

**Figura 105. Database Diagram del Esquema Devices**

![device database.png](../assets/img/Chapter-4/Diagrams/device%20database.png)

*Figura 105. Database Diagram del esquema Devices, mostrando las tablas de nodos sensores, vinculación de dispositivos a usuarios y registros de batería con sus relaciones y constraints. Fuente: Elaboración propia en Vertabelo.*

**Figura 106. Database Diagram del Esquema Monitoring**

![monitoring database.png](../assets/img/Chapter-4/Diagrams/monitoring%20database.png)

*Figura 106. Database Diagram del esquema Monitoring, mostrando las tablas de lecturas de sensores (CO₂, temperatura, humedad), umbrales de activación y reglas de automatización con sus relaciones y constraints. Fuente: Elaboración propia en Vertabelo.*

**Figura 107. Database Diagram del Esquema Analytics**

![analytics database.png](../assets/img/Chapter-4/Diagrams/analytics%20database.png)

*Figura 107. Database Diagram del esquema Analytics, mostrando las tablas de tendencias semanales, scores de concentración y reportes mensuales con sus relaciones y constraints. Fuente: Elaboración propia en Vertabelo.*
