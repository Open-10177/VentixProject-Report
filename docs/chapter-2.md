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

#### Fortalezas y Oportunidades:

- Diferenciación técnica: Enfoque en la soberanía de datos (privacidad) y monitoreo especializado de $CO_2$ para la productividad.


- Crecimiento orgánico: Aprovechamiento de la cultura Wellness y el respaldo de la comunidad Open Source para mejorar el software sin costos añadidos.

#### Aprovechamiento de Debilidades y Amenazas de los Competidores:

- Seguridad y Costo: Posicionamiento como alternativa local-first frente a la inseguridad de nubes externas (Xiaomi) y como opción democrática frente a los precios prohibitivos de la competencia premium (Dyson).


- UX Superior: Superar la complejidad de los proyectos DIY mediante una interfaz profesional en Angular y una API documentada.

#### Estrategias de Marketing:

- Nicho Técnico y de Salud: Difusión en comunidades de desarrolladores (GitHub/Dev.to) y campañas de concientización sobre fatiga ambiental dirigidas a estudiantes en exámenes y trabajadores remotos.


- Alianzas Maker: Colaboración con clubes tecnológicos universitarios para validar y expandir el ecosistema Ventix.

#### Costos y Precios:

Inversión mínima: Software gratuito (Open Source) con un costo de hardware (BOM) accesible de entre  35 USD y 50 USD.

Ventaja económica: Reducción de costos de hasta un 90% en comparación con sistemas comerciales inteligentes de gama media y alta.

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

## 2.3. Needfinding
### 2.3.1. User Personas
### 2.3.2. User Task Matrix
|                  |                    |                    |
|------------------|--------------------|--------------------|
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |
|                  |                    |                    |


### 2.3.3. User Journey Mapping.
### 2.3.4. Empathy Mapping.
## 2.4. Big Picture Event Storming.
## 2.5. Ubiquitous Language.
