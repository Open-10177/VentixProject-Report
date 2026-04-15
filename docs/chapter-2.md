# Capítulo II: Requirements Elicitation & Analysis

## 2.1. Competidores.


Para Ventix, hemos identificado tres tipos de competidores que actualmente dominan o influyen en el mercado del confort ambiental:

- Gigantes del Smart Home (Xiaomi, Philips): Ofrecen ventiladores y purificadores con apps robustas pero cerradas.
- Sistemas de Gama Alta (Dyson): Soluciones premium con sensores de alta precisión, pero a precios inalcanzables para el estudiante promedio.
- Proyectos DIY de Nicho: Repositorios en GitHub de control básico de ventiladores, que son abiertos pero carecen de una interfaz web profesional o una API documentada.

### 2.1.1. Análisis competitivo.


<table border="1" cellspacing="0" cellpadding="5">
  <!-- Título principal -->
  <tr>
    <th colspan="6">Competitive Analysis Landscape</th>
  </tr>

  <!-- Explicación -->
  <tr>
    <th>¿Por qué llevar a cabo este análisis?</th>
    <td colspan="5">
      Este análisis se lleva a cabo con la finalidad de poder conocer las diferentes soluciones ya existentes y cómo Ventix se diferencia y podría mostrarse como una mejor opción ante estas.
    </td>
  </tr>

  <!-- Encabezados competidores con imágenes -->
  <tr>
    <th colspan="2">Competidores</th>
    <th>
      Ventix<br>
      <img src="/assets/img/chapter-2/ventixlogo.png" alt="Ventix" width="100">
    </th>
    <th>
      Xiami<br>
      <img src="/assets/img/chapter-2/xiami.png/" alt="Homify" width="100">
    </th>
    <th>
      Dyson<br>
      <img src="/assets/img/chapter-2/631_dyson_logo.jpg" alt="Home Solution" width="100">
    </th>

  </tr>

  <!-- PERFIL -->
  <tr>
    <th rowspan="2">Perfil</th>
    <th>Overview</th>
    <td>Sistema IoT de código abierto que automatiza la ventilación basándose en niveles reales de CO2 y temperatura.</td>
    <td>Ventiladores inteligentes integrados a un ecosistema masivo de domótica (Mi Home).</td>
    <td>Dispositivos de lujo con filtración HEPA y diseño sin aspas de alta ingeniería.</td>
  </tr>
  <tr>
    <th>Ventaja competitiva<br>¿Qué valor ofrece a los clientes?</th>
    <td>Soberanía de datos y Open Source. El usuario es dueño del código y el hardware es de bajo costo y personalizable.</td>
    <td>Ecosistema y conveniencia. Gran integración con otros dispositivos y configuración "Plug & Play".</td>
    <td>Tecnología avanzada y estatus. Purificación de grado médico y diseño industrial icónico.</td>
  </tr>

  <!-- PERFIL DE MARKETING -->
  <tr>
    <th rowspan="2">Perfil de Marketing</th>
    <th>Mercado objetivo</th>
    <td>Estudiantes universitarios y profesionales en modalidad Home Office con interés técnico.</td>
    <td>Usuarios de tecnología que buscan un hogar conectado a precio accesible.</td>
    <td>Clientes de alto poder adquisitivo y personas con problemas respiratorios crónicos.</td>
  </tr>
  <tr>
    <th>Estrategias de marketing</th>
    <td>Marketing de nicho enfocado en la productividad y salud, apoyado en comunidades de software libre.</td>
    <td>Marketing masivo, presencia en retail físico y fidelización por ecosistema.</td>
    <td>Marketing basado en innovación, exclusividad y diseño de alta gama.</td>
  </tr>

  <!-- PERFIL DE PRODUCTO -->
  <tr>
    <th rowspan="3">Perfil de Producto</th>
    <th>Productos & Servicios</th>
    <td>Dashboard Web (Angular), API REST y firmware para hardware DIY.</td>
    <td>Ventiladores físicos con conectividad WiFi y app móvil propietaria.</td>
    <td>Purificadores multifunción con sensores de partículas avanzados.</td>
  </tr>
  <tr>
    <th>Precios & Costos</th>
    <td>Económico. Costo de materiales (BOM) estimado en < $50 USD.</td>
    <td>Moderado. Precios entre $60 y $150 USD dependiendo del modelo.</td>
    <td>Alto. Precios que oscilan entre $400 y $800+ USD.</td>
  </tr>
  <tr>
    <th>Canales de distribución<br>(Web y/o Móvil)</th>
    <td>Web. Repositorio de código y despliegue del frontend en la nube.</td>
    <td>Móvil / Retail. App Mi Home y tiendas físicas/distribuidores.</td>
    <td>Móvil / Retail. App MyDyson y tiendas de lujo/centros comerciales.</td>
  </tr>

  <!-- ANÁLISIS SWOT -->
  <tr>
    <th rowspan="4">Análisis SWOT</th>
    <th>Fortalezas</th>
    <td>Transparencia absoluta, cero dependencia de nubes externas, costo mínimo y enfoque en CO2</td>
    <td>Marca reconocida, estética minimalista y facilidad de uso extremo.</td>
    <td>Mejor tecnología de filtrado del mercado y altísima fidelidad de marca.</td>
  </tr>
  <tr>
    <th>Debilidades</th>
    <td>Requiere que el usuario tenga conocimientos básicos o interés en ensamblar hardware.</td>
    <td>Privacidad cuestionable (datos en servidores externos) y poca flexibilidad de personalización fuera de su app.</td>
    <td>Precio prohibitivo para el estudiante promedio y ecosistema cerrado de repuestos caros.</td>
  </tr>
  <tr>
    <th>Oportunidades</th>
    <td>Crecimiento de la cultura "Maker" y preocupación por la privacidad de datos en el hogar.</td>
    <td>Expansión de su catálogo de sensores para incluir medición de CO2 de forma masiva.</td>
    <td>Implementación de modelos de suscripción para el mantenimiento de filtros.</td>
  </tr>
  <tr>
    <th>Amenazas</th>
    <td>Entrada de marcas chinas a precios agresivos que imiten la automatización por sensores.</td>
    <td>Saturación del mercado de ventiladores inteligentes de bajo costo.</td>
    <td>Soluciones Open Source o alternativas de gama media que demuestren resultados similares en salud.</td>
  </tr>
</table>

### 2.1.2. Estrategias y tácticas frente a competidores.

Luego de haber realizado el análisis de nuestra solución con respecto a soluciones ya existentes, nuestro equipo procederá a plantear estrategias y tácticas que debemos poner en marcha para sobresalir de las otras soluciones.

#### Matriz CAME para el desarrollo de estrategias en base al análisis FODA

| **Análisis FODA cruzado** | **Oportunidades** | **Amenazas** |
|---|---|---|
| **Fortalezas (F)**<br>1. Enfoque en soberanía de datos y privacidad.<br>2. Modelo open source con hardware accesible.<br>3. Especialización en monitoreo de CO₂ y productividad académica/laboral.<br>4. Costos de implementación bajos frente a sistemas comerciales. | **Estrategia (FO) — Estrategias Ofensivas**<br>1. Alianzas con comunidades universitarias y makers para validar prototipos y expandir el ecosistema Ventix.<br>2. Posicionamiento como solución académica y de teletrabajo, destacando impacto en concentración y salud.<br>3. Roadmap de integraciones IoT: sensores de CO₂, humedad y temperatura con APIs abiertas.<br>4. Campañas de concientización sobre “fatiga ambiental” dirigidas a estudiantes y profesionales remotos.<br>5. Estrategia freemium → up-sell: kits básicos para adopción rápida y planes premium para instituciones educativas. | **Estrategia (FA) — Estrategias Defensivas**<br>1. Documentar y comunicar políticas de seguridad y privacidad adaptadas a entornos académicos y laborales.<br>2. Ofrecer soporte local y comunidad activa en GitHub para contrarrestar ecosistemas cerrados.<br>3. Diferenciarse por transparencia y accesibilidad frente a competidores globales (Xiaomi, Dyson).<br>4. Diseñar funcionalidades offline/parciales para minimizar fricción en zonas con conectividad limitada.<br>5. Difundir resultados de pilotos y casos de uso en universidades para contrarrestar la ventaja presupuestal de marcas establecidas. |
| **Debilidades (D)**<br>1. Bajo reconocimiento de marca (startup emergente).<br>2. Recursos limitados frente a gigantes del Smart Home.<br>3. Madurez inicial en integraciones empresariales.<br>4. Necesidad de validación en distintos contextos académicos y laborales. | **Estrategia (DO) — Reorientación**<br>1. Validación rápida con Lean UX: pruebas de usabilidad y pilotos documentados en aulas y oficinas.<br>2. Buscar subvenciones y programas de innovación tecnológica para financiar pilotos.<br>3. Generar contenido técnico y académico: whitepapers, casos de estudio y guías para decisores.<br>4. Priorizar desarrollo de APIs públicas y SDKs para integradores, reduciendo fricción de adopción.<br>5. Crear un programa de partners locales (clubes makers, consultoras) para escalar despliegues sin aumentar plantilla interna. | **Estrategia (DA) — Supervivencia**<br>1. Priorizar seguridad e infraestructura crítica: backups automáticos, alta disponibilidad y pruebas de penetración.<br>2. Política de precios defensiva inicial: kits entry-level competitivos y promociones para ganar masa crítica.<br>3. Obtener certificaciones de seguridad y calidad ambiental como sello de confianza.<br>4. Buscar aceleradoras y socios estratégicos que aporten recursos sin diluir el control del producto.<br>5. Formalizar un plan de gestión de incidentes y comunicación para reducir impacto reputacional. |

## 2.2. Entrevistas

### 2.2.1. Diseño la entrevistas.

**Segmento 1: Estudiantes universitarios en espacios cerrados**

<h4 id="PreguntPersonal">Preguntas Personales:</h4>

¿Cuál es su nombre?

¿Cuál es su edad?

¿Cuál es su cargo dentro del negocio?

¿Qué tipo de negocio administra?

¿Cuántos años lleva operando el negocio?

¿Cuántos trabajadores tiene actualmente?

<h4 id="PreguntEspe">Preguntas específicas:</h4>


¿Sueles cerrar la puerta y ventana por privacidad o para evitar el ruido exterior mientras estudias?

¿Sientes somnolencia o pesadez después de estar más de dos horas estudiando encerrado?

¿Has notado una disminución en tu capacidad de concentración cuando la habitación se siente calurosa o el aire pesado?

¿Te resulta molesto tener que interrumpir tu estudio para levantarte y encender o ajustar un ventilador?

¿Sabías que los niveles altos de $CO_2$ en cuartos cerrados afectan directamente tu memoria y capacidad de aprendizaje?

¿Qué tan dispuesto estarías a armar tu propio dispositivo (DIY) si el costo total fuera menor a 40 dólares?

¿Te genera confianza una plataforma que sea Open Source y te permita ver (o incluso modificar) cómo funciona por dentro?

.

**Segmento 2: Trabajadores en modalidad Home Office**

<h4 id="PreguntPersonal">Preguntas Personales:</h4>

¿Cuál es su nombre?

¿Cuál es su edad?

¿Cuál es su cargo dentro del negocio?

¿Qué tipo de negocio administra?

¿Cuántos años lleva operando el negocio?

¿Cuántos trabajadores tiene actualmente?

<h4 id="PreguntEspe">Preguntas específicas:</h4>

¿Mantienes la puerta cerrada durante tus reuniones para evitar ruidos domésticos?

¿Al terminar tu jornada laboral, sientes un agotamiento mental que no asocies con el estrés, sino con el ambiente físico? 

¿Consideras que tu productividad baja después del mediodía debido al encierro en tu espacio de trabajo? 

¿Cuántas veces al día manipulas el control del ventilador o la ventana para ajustar el clima y qué tan molesto te resulta?

¿Consideras que estas pequeñas tareas manuales rompen tu "estado de flujo" (deep work) o concentración?

¿Te preocupa que los dispositivos "smart" de marcas grandes envíen datos de tu hogar a nubes externas?

¿Prefieres una interfaz web minimalista que puedas revisar desde tu segunda pantalla o una aplicación móvil?

### 2.2.2. Registro de entrevistas

#### Segmento 1:
* Entrevista 1:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:


* Entrevista 2:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:


* Entrevista 3:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:

#### Segmento 2:
* Entrevista 1:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:


* Entrevista 2:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:

* Entrevista 3:

| Nombre                         |     |      
|--------------------------------|-----|
| Apellido                       |     |      
| Edad                           |     |      
| Distrito                       |     |      
| Evidencia                      |     |      
| URL                            |     |      
| Inicio de Entrevista           |     |      
| Fin de entrevista              |     |      
| Estado Civil                   |     |      
| Ocupacion                      |     |      
| Dispositivo de preferencia     |     |      
| Canales de interaccion digital |     |     

Resumen:

### 2.2.3. Análisis de entrevistas 

En esta sección se presenta el análisis detallado de la información recolectada. Para cada segmento, se explican primero los hallazgos estadísticos objetivos y subjetivos, seguidos de la evidencia gráfica correspondiente.

### Segmento 1: Estudiantes Universitarios en Espacios Cerrados  

**Análisis de Características Objetivas y Subjetivas**  

El análisis revela condiciones deficientes en espacios de estudio. Como se detalla en el gráfico a continuación:

Los principales factores que afectan la experiencia de los estudiantes se concentran en la falta de ventilación (25%), la somnolencia tras largas horas de estudio continuo (20%), la disminución de la concentración debido al aire pesado o caluroso (18%), las interrupciones generadas por la necesidad de ajustar ventiladores fisicos (15%) y la percepción de falta de soluciones simples y accesibles (22%).

<img src="/assets/img/chapter-2/grafica 1.png" alt="grafica01" width="650">

### Segmento 2: Tutores o dueños de casa que necesiten monitoriar en el exterior 

**Análisis de Características Objetivas y Subjetivas** 

Los datos confirman una experiencia limitada en la gestión del ambiente doméstico, especialmente cuando el usuario no se encuentra dentro del hogar de manera constante. Como se detalla en el gráfico a continuación:

Los principales factores que afectan la tranquilidad y el control del entorno del hogar se concentran en la limitada ventilación en espacios cerrados (24%), la preocupación por el bienestar de mascotas, niños o personas mayores en ausencia del usuario (22%), la dificultad para supervisar las condiciones ambientales en tiempo real (19%), las interrupciones generadas por la necesidad de realizar ajustes manuales al regresar al hogar (17%) y la desconfianza hacia soluciones tecnológicas que no garantizan privacidad ni control de datos (18%).

<img src="/assets/img/chapter-2/grafica 2.png" alt="grafica02" width="650">

### Análisis Comparativo  

**Contrastación de Segmentos**  

Al comparar ambos grupos, se identifican coincidencias clave para el desarrollo del producto:

Tanto estudiantes como dueños de casa evidencian que los principales factores que afectan su experiencia están relacionados con condiciones ambientales deficientes, especialmente la falta de ventilación y la necesidad de intervención constante para regular el entorno. En ambos segmentos, estos factores representan una proporción relevante dentro del análisis (entre 15% y 25%), lo que refuerza la necesidad de automatizar y centralizar la gestión del ambiente para mejorar la experiencia del usuario. Sin embargo, existe una diferencia clave en la prioridad de sus necesidades. Los estudiantes otorgan mayor importancia a la accesibilidad de soluciones (22%), priorizando herramientas simples, económicas y fáciles de usar que no interrumpan su concentración. Por otro lado, los dueños de casa ponen mayor énfasis en la posibilidad de monitoreo remoto, la seguridad del entorno y la privacidad de la información (22%), considerando fundamental mantener el control del hogar incluso en su ausencia.

Esto define la propuesta de valor del sistema: accesibilidad y simplicidad para estudiantes, y control remoto, seguridad y confianza para dueños de casa.

<img src="/assets/img/chapter-2/grafica resultado final.png" alt="resultado final" width="650">

### Conclusiones y Definición de tipos

**Estudiante ("El Aprendiz Concentrado")**

Rasgo clave: Busca mejorar su rendimiento académico en espacios cerrados.
Sustento: Los factores más influyentes en su experiencia son la falta de ventilación (25%), la somnolencia (20%) y la percepción de falta de soluciones accesibles (22%). Esto evidencia que necesita un entorno cómodo y herramientas simples que no interrumpan su flujo de estudio. La solución debe tener una curva de aprendizaje mínima y un costo accesible.

**Dueño de Casa ("El Supervisor del Hogar")**

Rasgo clave: Necesita monitorear y controlar el ambiente de su hogar de forma remota y segura.
Sustento: Los principales factores que afectan su tranquilidad incluyen la ventilación limitada (24%), la preocupación por el bienestar de los ocupantes del hogar (22%) y la dificultad para supervisar el entorno en tiempo real (19%). Esto indica que prioriza soluciones que le permitan mantener control, seguridad y confianza, especialmente cuando no se encuentra en casa. La solución debe centrarse en monitoreo remoto, automatización y protección de datos.

## 2.3. Needfinding
A partir del análisis de entrevistas y la recolección de información sobre las dinámicas en espacios cerrados de estudio y hogar, se identificaron los principales perfiles de usuarios que interactúan directamente con la solución Ventix. Estos perfiles representan los segmentos clave para el sistema, ya que concentran tanto la necesidad de mejorar la concentración y el confort ambiental como la necesidad de contar con herramientas confiables y seguras para la gestión del aire interior.

## 2.3.1. User Personas  

La construcción de los User Persona permite al equipo de desarrollo comprender mejor sus motivaciones, frustraciones y hábitos, lo que resulta esencial para diseñar funcionalidades adecuadas y experiencias de usuario efectivas.

**Segmento 1: Estudiantes Universitarios en Espacios Cerrados**

Para los estudiantes se elaboró el User Persona Maria Elena Lopez. Se consideraron factores como su edad, rutina académica, tiempo prolongado en habitaciones cerradas y la necesidad de mantener concentración durante largas jornadas de estudio. Sus principales frustraciones giran en torno a la somnolencia y la fatiga ambiental, además de la molestia de tener que interrumpir sus actividades para ajustar manualmente la ventilación. Asimismo, se tomó en cuenta su disposición hacia soluciones simples, económicas y open source, que les permitan confiar en la tecnología sin barreras de complejidad.


**Segmento 2: Dueños de Casa que Monitorean su Hogar**

Para este segmento se elaboró el User Persona Luis Estefano Ruiz. Se consideraron aspectos como su edad, estilo de vida y su responsabilidad en el cuidado del hogar. Sus principales motivaciones están orientadas a garantizar el bienestar de las personas y mascotas dentro de su vivienda, así como a mantener condiciones ambientales adecuadas incluso en su ausencia. Sus frustraciones se relacionan con la imposibilidad de supervisar el entorno en tiempo real, la necesidad de realizar ajustes manuales al regresar a casa y la desconfianza hacia dispositivos inteligentes que comprometen la privacidad. Su perfil refleja una predisposición positiva hacia soluciones tecnológicas open source, siempre que estas sean seguras, confiables y le permitan tener control remoto del hogar de manera sencilla.


### 2.3.2. User Task Matrix

El User Task Matrix presenta las tareas que realizan los User Persona para cumplir sus objetivos en su día a día. Se evalúa la frecuencia y la importancia de cada tarea para identificar dónde el sistema Ventix puede automatizar o mitigar riesgos.

| **Tarea(Task)**                                      | **Estudiante (Maria Elena)** | **Dueño de Casa Hogar (Luis)** |
|------------------------------------------------------|------------------------------|--------------------------------|
|                                                      | Frecuencia                   |                                |
| Monitorear la ventilación de espacios cerrados       | Often                        | High                           |
| Verificar la temperatura de las habitaciones         | Occasionally                 | Medium                         |
| Identificar síntomas de somnolencia o fatiga         | Often                        | High                           |
| Abrir ventanas/puertas para renovar el aire          | Often                        | Medium                         |
| Supervisar el bienestar físico de los residentes     | Rarely                       | Low                            |
| Atender alertas por condiciones ambientales críticas | Rarely                       | High                           |
| Revisar el consumo energético de ventiladores/AC     | Monthly                      | Medium                         |
| Analizar reportes de calidad ambiental histórica     | Rarely                       | Low                            |


**Análisis del Task Matrix**

**Actividades Críticas:** El monitoreo de ventilación es la tarea "Core" para ambos (Importancia High / Frecuencia Often). En María Elena impacta el rendimiento académico y en Luis Estéfano la salud pública de los residentes.

**Punto de Dolor Común:** La tarea de "Abrir ventanas" es muy frecuente, validando el valor de la automatización del ventilador de Ventix para reducir la carga operativa manual.

**Gestión de Riesgos:** Aunque las "Alertas críticas" ocurren ocasionalmente, su importancia High justifica la necesidad del sistema de notificaciones en tiempo real para prevenir incidentes de salud.

## 2.3.3. User Journey Mapping
### Segmento 1 – Estudiante Universitaria (María Elena López)  

El User Journey Mapping de María Elena representa el recorrido actual que experimenta como estudiante universitaria en espacios cerrados, durante sus jornadas de estudio. El mapa ilustra el proceso end-to-end, desde el inicio de sus sesiones académicas hasta la gestión de pausas y la búsqueda de concentración.

En la situación As-Is, María Elena enfrenta un flujo de trabajo ambiental poco optimizado: estudia en habitaciones cerradas, ajusta manualmente ventiladores o ventanas y experimenta somnolencia después de largas horas. Esto genera interrupciones, pérdida de concentración y fatiga ambiental. El Journey busca evidenciar los puntos críticos de su experiencia actual, identificando emociones, tareas, fricciones y oportunidades de mejora a lo largo de cada etapa (Awareness, Data Collection, Daily Study, Concentration, Breaks y Performance). Este análisis servirá como base para diseñar una solución tecnológica que automatice la ventilación, mejore la eficiencia y facilite la concentración en espacios cerrados. 

**Journey Map Segmento 1**  

### Segmento 2 – Dueño o tutor de casa hogar (Luis Estéfano Ruiz)  

El User Journey Mapping de Luis Estéfano describe la experiencia que vive como responsable del hogar, especialmente en situaciones donde necesita supervisar el ambiente doméstico sin estar presente. El mapa detalla las etapas de su recorrido end-to-end, desde que sale de casa hasta que monitorea las condiciones del entorno y toma decisiones en función de la información disponible.

En la situación As-Is, Luis depende de revisiones presenciales y métodos tradicionales como ventiladores o ventanas para mantener el ambiente adecuado. Esto genera incertidumbre cuando no se encuentra en casa, ya que no puede verificar en tiempo real las condiciones en las que se encuentran mascotas, niños o personas mayores. Además, al regresar, debe realizar ajustes manuales, lo que representa incomodidad y pérdida de tiempo. El Journey permite comprender su perspectiva emocional y sus puntos de dolor, evidenciando la necesidad de contar con información remota, confiable y accesible sobre la calidad del aire y el estado del entorno. Este análisis busca sentar las bases para una solución tecnológica que le brinde control, seguridad y tranquilidad, fortaleciendo su confianza en la gestión del hogar.

**Journey Map Segmento 2**  


## 2.3.4. Empathy Mapping  

Para la elaboración de los Empathy Maps, el equipo partió del conocimiento y observaciones recolectadas durante el análisis de los User Persona. Se colocó al centro de cada mapa al usuario correspondiente (María Elena López y Luis Estéfano Ruiz) y se respondieron las preguntas claves sobre su entorno, emociones, comportamientos y necesidades.

### Segmento 1: Estudiantes Universitarios  

**Empathy Mapping 1**  

En este mapa se analizó a María Elena López, una estudiante universitaria que busca mantener concentración y rendimiento académico en espacios cerrados. Se identificó que piensa constantemente en la necesidad de contar con un ambiente fresco y controlado, ya que le preocupa que la fatiga ambiental afecte su memoria y productividad. Escucha a sus compañeros quejarse de somnolencia y observa cómo muchos deben interrumpir sus estudios para ajustar manualmente ventiladores o ventanas. María Elena expresa la necesidad de contar con una solución moderna y accesible que automatice la ventilación, y actúa implementando estrategias básicas como abrir ventanas o usar ventiladores portátiles. Su dolor principal es la pérdida de concentración y la fatiga ambiental, mientras que su ganancia esperada es lograr eficiencia en el estudio, bienestar físico y un mejor control del ambiente.

### Segmento 2: Dueños de casa

**Empathy Mapping 2**  

En este mapa se analizó a Luis Estéfano Ruiz, un usuario que busca garantizar el bienestar y control de su hogar incluso cuando no se encuentra en él. Él piensa constantemente en la seguridad y las condiciones ambientales en las que se encuentran sus mascotas, niños o personas mayores. Escucha a otros usuarios expresar preocupación por no poder supervisar sus hogares en tiempo real y observa que depender de métodos tradicionales no le brinda suficiente tranquilidad. Luis expresa la necesidad de contar con una solución tecnológica confiable y segura, y actúa verificando el estado de su hogar cuando regresa o mediante soluciones limitadas. Su dolor principal es la incertidumbre y la falta de control remoto, mientras que su ganancia esperada es obtener tranquilidad, seguridad y confianza al poder monitorear y gestionar el ambiente del hogar en tiempo real desde cualquier lugar.

## 2.4. Big Picture Event Storming

**Step 1 – Free Exploration**

En esta primera etapa, el equipo realizó una sesión de lluvia de ideas para capturar todos los eventos relevantes dentro del dominio de monitoreo ambiental, sin preocuparse por el orden o la jerarquía. El objetivo principal fue representar los acontecimientos reales del negocio y del entorno del usuario, de manera independiente a cualquier función técnica

![part1 Big Picture.png](../assets/img/chapter-2/part1%20Big%20Picture.png)

**Step 2 – Structured Organization**

Después de listar los eventos, el equipo los organizó en flujos de negocio lógicos que reflejan las principales etapas en la operación . Esta estructura ayudó a identificar los procesos clave y las áreas de mejora que posteriormente podrían abordarse mediante soluciones digitales o de gestión

![Part2 Big Picture.png](../assets/img/chapter-2/Part2%20Big%20Picture.png)

## 2.5. Ubiquitous Language

El Lenguaje Ubicuo de Ventix define los términos técnicos y de negocio que deben utilizarse de manera consistente en el código fuente, la interfaz de usuario y la documentación técnica. Esto elimina ambigüedades entre el equipo de desarrollo y los stakeholders.


| **Término**         | **Definición**                                                                                                   | **Contexto de Uso**  |
|---------------------|------------------------------------------------------------------------------------------------------------------|----------------------|
| Nodo (Node)         | Dispositivo físico o simulado que contiene los sensores y actuadores en un espacio físico.                       | Técnico / Hardware   |
| Umbral (Threshold)  | Valor límite configurado (ppm, °C, %) que dispara una acción automática del sistema.                             | Configuración        |
| PPM (CO2 Level)     | Partes Por Millón; medida estándar utilizada para determinar la calidad del aire y ventilación.                  | Monitoreo            |
| Actuador (Actuator) | El componente físico (ventilador) que realiza una acción mecánica basada en una orden del sistema.               | Funcional            |
| Modo Optimizado     | Estado del sistema donde los umbrales se ajustan automáticamente para maximizar la concentración del estudiante. | Usuario (Estudiante) |
| Soberanía de Datos  | Capacidad del usuario de elegir el almacenamiento local de sus métricas sin dependencia de la nube.              | Privacidad / Ética   |
| Pánico Ambiental    | Estado de alerta máxima disparado por niveles críticos de gases o temperatura extrema.                           | Seguridad (Familiar) |
| Log de Eventos      | Registro histórico de todas las mediciones y acciones automáticas realizadas por el nodo.                        | Reportes             |
| Override Manual     | Acción del usuario que invalida temporalmente la lógica automática para controlar el ventilador a voluntad.      | Control              |

**Beneficios esperados del Ubiquitous Language:**

- **Facilita la comunicación entre desarrolladores, usuarios y administradores del sistema:** Al usar términos como "Umbral" o "Modo Optimizado", el administrador de la casa hogar y el programador de Java hablan el mismo idioma, evitando confusiones sobre qué significa "aire limpio".


- **Mejora la comprensión de las funcionalidades principales del sistema:** Términos como "Override Manual" o "Pánico Ambiental" describen por sí mismos el propósito de la función, permitiendo que un nuevo estudiante entienda la app sin necesidad de un manual extenso.
