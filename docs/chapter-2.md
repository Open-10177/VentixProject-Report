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
El análisis revela condiciones ambientales deficientes en espacios de estudio. Como se detalla en el gráfico a continuación:  

El 100% de los estudiantes entrevistados suele cerrar puertas y ventanas por privacidad o ruido, lo que limita la ventilación. Un 80% manifestó sentir somnolencia o pesadez después de dos horas de estudio continuo, y un 70% reconoció que su concentración disminuye cuando el aire se siente pesado o caluroso. El 60% considera molesto tener que interrumpir el estudio para ajustar un ventilador, mientras que un 40% lo ve como una rutina inevitable. A nivel subjetivo, el 90% mostró interés en soluciones simples y económicas, y un 70% expresó confianza en plataformas open source que les permitan entender cómo funciona el sistema.  

//grafica

### Segmento 2: Profesionales en Modalidad Home Office  

**Análisis de Características Objetivas y Subjetivas** 
Los datos confirman una experiencia deficiente en espacios laborales domésticos. Como se detalla en el gráfico a continuación:  

El 100% de los profesionales entrevistados mantiene la puerta cerrada durante reuniones para evitar ruidos, lo que reduce la circulación de aire. Un 75% reportó agotamiento mental al final de la jornada, asociado más al ambiente físico que al estrés laboral. El 80% considera que su productividad baja después del mediodía debido al encierro, y el 70% indicó que manipular varias veces al día ventiladores o ventanas rompe su estado de concentración. Subjetivamente, el 60% expresó preocupación por la privacidad en dispositivos smart comerciales, mientras que el 100% valoró la idea de una solución open source con interfaz web minimalista y transparente.  

//grafica 

### Análisis Comparativo  

**Contrastación de Segmentos**  
Al comparar ambos grupos, encontramos coincidencias vitales para el producto: 

Tanto estudiantes como profesionales reconocen la necesidad de **automatizar y centralizar la gestión ambiental**. Sin embargo, existe una diferencia en la percepción de la “preocupación”, los estudiantes priorizan la **simplicidad y bajo costo** como factor decisivo, mientras que los profesionales ponen mayor énfasis en la **privacidad y transparencia de datos**.  

Esto define nuestra propuesta de valor: **eficiencia y accesibilidad para estudiantes, soberanía de datos y confianza para profesionales**.  

//grafica 

### Conclusiones y Definición de Arquetipos  

**User Persona Estudiante ("El Aprendiz Concentrado")**  
Rasgo clave: Busca mejorar su rendimiento académico en espacios reducidos.  
Sustento: El 80% reporta somnolencia y pérdida de concentración, y el 90% exige soluciones simples y económicas. La solución debe tener una curva de aprendizaje mínima y un costo accesible.  

**User Persona Profesional ("El Teletrabajador Precavido")**  
Rasgo clave: Necesita control y transparencia para reducir la ansiedad y mantener productividad.  
Sustento: El 75% reporta agotamiento físico por el ambiente y el 100% valora la soberanía de datos. La solución debe centrarse en notificaciones en tiempo real y en la privacidad del usuario.  

## 2.3. Needfinding

A partir del análisis de entrevistas y la recolección de información sobre las dinámicas en espacios cerrados de estudio y trabajo, se identificaron los principales perfiles de usuarios que interactúan directamente con la solución **Ventix**. Estos perfiles representan los segmentos clave para el sistema, ya que concentran tanto la necesidad de mejorar la concentración y el confort ambiental como la necesidad de contar con herramientas confiables y transparentes para la gestión del aire interior.  

## 2.3.1. User Personas  

La construcción de los *User Persona* permite al equipo de desarrollo comprender mejor sus motivaciones, frustraciones y hábitos, lo que resulta esencial para diseñar funcionalidades adecuadas y experiencias de usuario efectivas.  

**1) Segmento 1: Estudiantes Universitarios en Espacios Cerrados**  
Para los estudiantes se elaboró el User Persona **Maria Elena Lopez**. Se consideraron factores como su edad, rutina académica, tiempo prolongado en habitaciones cerradas y la necesidad de mantener concentración durante largas jornadas de estudio. Sus principales frustraciones giran en torno a la somnolencia y la fatiga ambiental, además de la molestia de tener que interrumpir sus actividades para ajustar manualmente la ventilación. Asimismo, se tomó en cuenta su disposición hacia soluciones simples, económicas y open source, que les permitan confiar en la tecnología sin barreras de complejidad.  

//
<br>  

**2) Segmento 2: Profesionales en Modalidad Home Office**  
Para los profesionales se elaboró el User Persona **Luis Estefano Ruiz**. Se consideraron aspectos como su edad, ocupación y su rol en la gestión de espacios de trabajo domésticos. Sus principales motivaciones están orientadas a mantener productividad y confort ambiental durante la jornada laboral, mientras que sus frustraciones se relacionan con la pérdida de concentración por manipular constantemente ventiladores o ventanas y la desconfianza hacia dispositivos smart que envían datos a nubes externas. Su perfil refleja una predisposición positiva hacia soluciones digitales open source, siempre que estas sean transparentes, confiables y fáciles de integrar en su rutina diaria.  

//

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


## 2.3.3. User Journey Mapping
### Segmento 1 – Estudiante Universitaria (María Elena López)  

El User Journey Mapping de María Elena representa el recorrido actual que experimenta como estudiante universitaria en espacios cerrados, durante sus jornadas de estudio. El mapa ilustra el proceso end-to-end, desde el inicio de sus sesiones académicas hasta la gestión de pausas y la búsqueda de concentración.  

En la situación As-Is, María Elena enfrenta un flujo de trabajo ambiental poco optimizado: estudia en habitaciones cerradas, ajusta manualmente ventiladores o ventanas y experimenta somnolencia después de largas horas. Esto genera interrupciones, pérdida de concentración y fatiga ambiental.  

El Journey busca evidenciar los puntos críticos de su experiencia actual, identificando emociones, tareas, fricciones y oportunidades de mejora a lo largo de cada etapa (Awareness, Data Collection, Daily Study, Concentration, Breaks y Performance). Este análisis servirá como base para diseñar una solución tecnológica que automatice la ventilación, mejore la eficiencia y facilite la concentración en espacios cerrados.  

**Journey Map Segmento 1**  

### Segmento 2 – Profesional en Home Office (Luis Estéfano Ruiz)  

El User Journey Mapping de Luis Estéfano describe la experiencia completa que vive como trabajador remoto, desde el inicio de su jornada laboral hasta la recepción de notificaciones sobre el ambiente físico de su espacio de trabajo. El mapa detalla las etapas de su recorrido end-to-end, reflejando las acciones, pensamientos, emociones y frustraciones que enfrenta actualmente sin contar con una plataforma digital centralizada.  

En la situación As-Is, Luis depende de medios tradicionales como ventiladores manuales y apertura de ventanas para regular el ambiente. Esto provoca interrupciones constantes, pérdida de concentración y una sensación de agotamiento físico que no siempre se relaciona con el estrés laboral.  

El Journey permite comprender su perspectiva emocional y sus puntos de dolor, mostrando los momentos clave en los que necesita información rápida, confiable y accesible sobre la calidad del aire. Este análisis busca sentar las bases para una futura solución tecnológica que le brinde productividad, transparencia y confianza, fortaleciendo su vínculo con el bienestar en el trabajo remoto.  

**Journey Map Segmento 2**  


## 2.3.4. Empathy Mapping  

Para la elaboración de los Empathy Maps, el equipo partió del conocimiento y observaciones recolectadas durante el análisis de los User Persona. Se colocó al centro de cada mapa al usuario correspondiente (María Elena López y Luis Estéfano Ruiz) y se respondieron las preguntas claves sobre su entorno, emociones, comportamientos y necesidades.  

### Segmento 1: Estudiantes Universitarios  

**Empathy Mapping 1**  

En este mapa se analizó a María Elena López, una estudiante universitaria que busca mantener concentración y rendimiento académico en espacios cerrados. Se identificó que piensa constantemente en la necesidad de contar con un ambiente fresco y controlado, ya que le preocupa que la fatiga ambiental afecte su memoria y productividad. Escucha a sus compañeros quejarse de somnolencia y observa cómo muchos deben interrumpir sus estudios para ajustar manualmente ventiladores o ventanas. María Elena expresa la necesidad de contar con una solución moderna y accesible que automatice la ventilación, y actúa implementando estrategias básicas como abrir ventanas o usar ventiladores portátiles. Su dolor principal es la pérdida de concentración y la fatiga ambiental, mientras que su ganancia esperada es lograr eficiencia en el estudio, bienestar físico y un mejor control del ambiente.  

### Segmento 2: Profesionales en Home Office  

**Empathy Mapping 2**  

En este mapa se analizó a Luis Estéfano Ruiz, un profesional que busca mantener productividad y bienestar mientras trabaja desde casa. Él piensa en la tranquilidad que le daría tener acceso rápido y claro a la calidad del aire en su espacio de trabajo. Escucha a colegas compartir la frustración por la falta de concentración y observa que depender de ventiladores o ventanas no siempre es suficiente. Luis suele expresar la necesidad de contar con una aplicación confiable y fácil de usar, y actúa ajustando manualmente el ambiente varias veces al día. Su dolor principal es la interrupción constante y el agotamiento físico, mientras que su ganancia esperada es tener confianza, productividad y control al poder consultar la información ambiental en tiempo real desde cualquier lugar.  

## 2.4. Big Picture Event Storming.
## 2.5. Ubiquitous Language.
