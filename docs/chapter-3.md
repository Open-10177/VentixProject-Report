# Capítulo III: Requirements Specification
## 3.1. To-Be Scenario Mapping

Segmento 1: Estudiantes y trabajadores Home Office

| Fase | Doing (Qué hace) | Thinking (Qué piensa) | Feeling (Qué siente) |
|------|------------------|----------------------|----------------------|
| Monitoreo del ambiente | Revisa desde la app o dashboard los niveles de CO₂, temperatura y humedad en su espacio de estudio o trabajo en tiempo real. | “Quiero saber si el aire donde estoy es adecuado sin tener que estar adivinando.” | Curioso y más consciente de su entorno. |
| Detección de condiciones críticas | El sistema detecta automáticamente niveles altos de CO₂ o aumento de temperatura y envía alertas o recomendaciones. | “No me había dado cuenta de que el ambiente estaba afectando mi concentración.” | Sorprendido pero aliviado al entender lo que ocurre. |
| Automatización del control ambiental | El sistema activa automáticamente la ventilación o dispositivos conectados sin intervención del usuario. | “Ya no tengo que interrumpir lo que estoy haciendo para ajustar el ambiente.” | Cómodo y con mayor fluidez en sus actividades. |
| Continuidad y optimización | Continúa estudiando o trabajando mientras el sistema regula el ambiente de forma autónoma y registra datos históricos. | “Ahora puedo concentrarme mejor sin preocuparme por el aire.” | Enfocado, productivo y con mayor bienestar. |

Segmento 2: Tutores o dueños de casa (monitoreo remoto)

| Fase | Doing (Qué hace) | Thinking (Qué piensa) | Feeling (Qué siente) |
|------|------------------|----------------------|----------------------|
| Monitoreo remoto del hogar | Revisa desde su celular el estado de ventilación y calidad del aire en diferentes ambientes de la casa. | “Quiero asegurarme de que mi casa tenga un ambiente saludable incluso cuando no estoy ahí.” | Tranquilo y con sensación de control. |
| Recepción de alertas | Recibe notificaciones cuando algún ambiente presenta niveles altos de CO₂ o mala ventilación. | “Es importante saber si algún cuarto necesita ventilación antes de que afecte a alguien.” | Preocupado pero informado. |
| Control remoto del sistema | Activa o ajusta la ventilación de forma remota desde la aplicación móvil o web. | “Puedo corregir el problema sin necesidad de estar físicamente en casa.” | Seguro y en control. |
| Supervisión y análisis | Revisa reportes históricos del estado del aire en el hogar para tomar decisiones de mejora. | “Ahora puedo entender mejor cómo se comporta la ventilación en mi casa.” | Confiado y tranquilo respecto al bienestar del hogar. |


## 3.2. User Stories.

| US ID | Título | Descripción | Criterios de Aceptación | EPIC |
|------|--------|-------------|--------------------------|------|
| US01 | Menú de navegación | Como visitante quiero acceder a un menú superior para navegar entre secciones del sistema. | Escenario 1: Carga correcta. Dado que el usuario ingresa a la landing page, cuando el sistema carga completamente, entonces se muestra el menú con opciones (Inicio, Beneficios, Planes, Contacto, Login). Escenario 2: Interacción fluida. Dado que el usuario hace clic en una opción, cuando selecciona un enlace, entonces el sistema navega a la sección correspondiente sin recarga completa de página. | EP01 |
| US02 | Visualización de planes y beneficios | Como visitante quiero ver los planes disponibles con precios y características. | Escenario 1: Datos disponibles. Dado que existen planes registrados, cuando el usuario accede a la sección, entonces se muestran tarjetas comparativas con precio, beneficios y límites. Escenario 2: Sin datos. Dado que no hay planes activos, entonces se muestra mensaje “No hay planes disponibles”. | EP01 |
| US03 | Selección de plan | Como visitante quiero seleccionar un plan antes de registrarme. | Escenario 1: Selección válida. Dado que el usuario elige un plan, cuando confirma, entonces el sistema guarda la selección y la muestra en el registro. Escenario 2: Cambio de plan. Dado que el usuario cambia de opción, entonces el sistema reemplaza el plan sin perder datos ingresados. | EP01 |
| US04 | Visualización del equipo | Como visitante quiero ver información del equipo de desarrollo. | Escenario 1: Datos cargados. Dado que existe información del equipo, cuando el usuario accede a la sección, entonces se muestran nombres, roles y descripciones. Escenario 2: Interacción. Dado que el usuario selecciona un miembro, entonces se muestra información extendida. | EP01 |
| US05 | Cambio de idioma | Como usuario quiero cambiar el idioma entre español e inglés. | Escenario 1: Cambio exitoso. Dado que el usuario selecciona idioma, cuando confirma, entonces toda la interfaz cambia dinámicamente. Escenario 2: Persistencia. Dado que el usuario recarga la página, entonces el sistema mantiene el idioma seleccionado. | EP01 |
| US06 | Formulario de contacto | Como visitante quiero enviar consultas desde la landing page. | Escenario 1: Envío correcto. Dado que el usuario completa campos obligatorios, cuando envía el formulario, entonces el sistema registra la consulta y muestra confirmación. Escenario 2: Error de validación. Dado que hay campos vacíos o inválidos, entonces el sistema muestra mensajes por campo. | EP02 |
| US07 | Redes sociales | Como visitante quiero acceder a redes sociales del sistema. | Escenario 1: Acceso correcto. Dado que el usuario hace clic en un icono, cuando selecciona red social, entonces se abre en nueva pestaña. Escenario 2: Disponibilidad. Dado que carga el footer, entonces se muestran íconos activos oficiales. | EP02 |
| US08 | Visualización de datos en tiempo real | Como usuario quiero ver CO₂, temperatura y humedad en tiempo real. | Escenario 1: Datos activos. Dado que sensores están conectados, cuando el usuario abre dashboard, entonces se muestran datos en tiempo real con actualización automática. Escenario 2: Sin señal. Dado que no hay conexión, entonces se muestra “sin datos” o último valor registrado. | EP03 |
| US09 | Historial ambiental | Como usuario quiero ver historial de datos ambientales. | Escenario 1: Datos existentes. Dado que existen registros, cuando el usuario accede, entonces se muestran gráficos por periodo (día/semana/mes). Escenario 2: Sin datos. Dado que no hay registros, entonces se muestra mensaje informativo. | EP03 |
| US10 | Activación automática por CO₂ | Como usuario quiero que el ventilador se active automáticamente si el CO₂ es alto. | Escenario 1: Activación. Dado que CO₂ supera umbral, cuando el sistema detecta el valor, entonces activa ventilador automáticamente. Escenario 2: Normalización. Dado que CO₂ baja, entonces el sistema evalúa apagado. | EP03 |
| US11 | Activación por temperatura | Como usuario quiero activación automática por temperatura alta. | Escenario 1: Activación. Dado que temperatura supera umbral, cuando el sistema detecta el valor, entonces activa ventilador. Escenario 2: Estabilidad. Dado que baja temperatura, entonces evalúa desactivación. | EP03 |
| US12 | Apagado automático | Como usuario quiero que el ventilador se apague en condiciones normales. | Escenario 1: Apagado. Dado que CO₂ y temperatura están normales, entonces el sistema apaga ventilador. Escenario 2: Condición mixta. Dado que un valor sigue alto, entonces permanece encendido. | EP03 |
| US13 | Configuración de umbral CO₂ | Como usuario quiero definir el nivel de CO₂ permitido. | Escenario 1: Guardado correcto. Dado que el usuario ingresa valor válido, cuando guarda, entonces el sistema actualiza configuración. Escenario 2: Error. Dado que el valor es inválido, entonces muestra mensaje de validación. | EP03 |
| US14 | Configuración de temperatura | Como usuario quiero configurar el umbral de temperatura. | Escenario 1: Guardado correcto. Dado que el usuario ingresa valor válido, entonces se guarda configuración. Escenario 2: Error de rango, entonces sistema rechaza valor. | EP03 |
| US15 | Configuración de humedad | Como usuario quiero definir umbral de humedad. | Escenario 1: Guardado correcto. Dado que el usuario ingresa valor válido, entonces se actualiza sistema. Escenario 2: Valor inválido, entonces sistema muestra error. | EP03 |
| US16 | Control manual del ventilador | Como usuario quiero encender/apagar el ventilador manualmente. | Escenario 1: Acción manual. Dado que usuario presiona botón, entonces ventilador cambia estado inmediatamente. Escenario 2: Estado repetido, entonces sistema evita duplicación de acción. | EP03 |
| US17 | Modo automático/manual | Como usuario quiero alternar entre modo automático y manual. | Escenario 1: Modo manual. Dado que usuario activa manual, entonces sistema ignora sensores. Escenario 2: Modo automático, entonces sistema retoma control por sensores. | EP03 |
| US18 | Modo ahorro | Como usuario quiero reducir consumo energético automáticamente. | Escenario 1: Activación. Dado que no hay actividad, entonces sistema reduce ventilación. Escenario 2: Reactivación, entonces vuelve a modo normal. | EP03 |
| US19 | Múltiples espacios | Como usuario quiero monitorear varios ambientes. | Escenario 1: Visualización. Dado que existen dispositivos vinculados, entonces sistema muestra lista de espacios. Escenario 2: Selección, entonces muestra datos individuales. | EP03 |
| US20 | Modo optimizado | Como estudiante quiero optimización automática del ambiente. | Escenario 1: Activación. Dado que usuario inicia modo estudio, entonces sistema ajusta ventilación automáticamente. Escenario 2: Finalización, entonces vuelve a modo normal. | EP03 |
| US21 | Prioridad automática | Como usuario quiero que el sistema actúe sin intervención en casos críticos. | Escenario 1: Activación crítica. Dado que condiciones son peligrosas, entonces sistema activa ventilador sin intervención manual. | EP03 |
| US22 | Notificaciones de CO₂ alto | Como usuario quiero alertas de aire contaminado. | Escenario 1: Alerta enviada. Dado que CO₂ supera umbral, entonces sistema envía notificación. Escenario 2: Normalización, entonces se detienen alertas. | EP04 |
| US23 | Monitoreo remoto | Como usuario quiero ver mi hogar desde cualquier lugar. | Escenario 1: Acceso remoto. Dado que usuario inicia sesión fuera del hogar, entonces ve datos en tiempo real. Escenario 2: Offline, entonces muestra último dato registrado. | EP04 |
| US24 | Botón de pánico | Como usuario quiero acceso rápido a emergencias. | Escenario 1: Activación crítica. Dado que hay valores peligrosos, entonces sistema muestra contactos de emergencia. Escenario 2: Sin alerta, botón permanece inactivo. | EP04 |
| US25 | Control remoto ventilador | Como usuario quiero encender ventilador desde cualquier lugar. | Escenario 1: Activación remota. Dado que usuario envía comando, entonces ventilador se enciende. Escenario 2: Fallo conexión, entonces sistema muestra error. | EP04 |
| US26 | Notificación de inactividad | Como usuario quiero alertas si el sistema deja de funcionar. | Escenario 1: Falla detectada. Dado que no hay datos, entonces sistema envía alerta. Escenario 2: Reconexión, entonces notifica normalización. | EP04 |
| US27 | Notificación temperatura extrema | Como usuario quiero alertas de calor extremo. | Escenario 1: Alerta enviada. Dado que temperatura supera límite, entonces sistema notifica. Escenario 2: Normalización, entonces detiene alertas. | EP04 |
| US28 | Confirmación de acciones remotas | Como usuario quiero confirmación de acciones ejecutadas. | Escenario 1: Confirmación. Dado que acción remota se ejecuta, entonces sistema notifica éxito. Escenario 2: Error, entonces notifica fallo. | EP04 |
| US29 | Registro de cambios manuales | Como usuario quiero saber si alguien cambia el sistema manualmente. | Escenario 1: Cambio detectado. Dado que se modifica modo manualmente, entonces se envía alerta. Escenario 2: Sin cambios, entonces no hay notificación. | EP04 |
| US30 | Evaluación de estabilidad | Como usuario quiero saber si el ambiente es estable. | Escenario 1: Estabilidad. Dado que datos son constantes, entonces sistema muestra “estable”. Escenario 2: Variación alta, entonces muestra “inestable”. | EP04 |

Technical Stories

| TS ID | Título | Descripción | Criterios de Aceptación | Relacionado con (EPIC ID) |
|------|--------|-------------|------------------------|--------------------------|
| TS-01 | Obtener perfil por ID | Como desarrollador, quiero obtener el perfil de un usuario por su ID, para recuperar información detallada del usuario dentro del sistema Ventix. | **Escenario 1: Perfil existente** Dado que el endpoint `/api/v1/users/{id}` está disponible y el usuario existe, cuando se realiza una petición GET con un ID válido, entonces el sistema responde con status 200, retorna los datos del usuario (nombre, email, tipo de usuario, configuración de monitoreo y dispositivos vinculados) y tiempo de respuesta menor a 2 segundos. **Escenario 2: Perfil inexistente** Dado que el ID no existe, cuando se realiza la consulta, entonces el sistema responde con status 404 y mensaje “Usuario no encontrado”. | EP-05 |
| TS-02 | Actualizar perfil por ID | Como desarrollador, quiero actualizar los datos de un usuario, para mantener su información y preferencias de monitoreo actualizadas. | **Escenario 1: Actualización válida** Dado que el endpoint `/api/v1/users/{id}` está disponible y el usuario existe, cuando se envía un PUT con datos válidos (nombre, email, tipo de usuario, preferencias de ventilación), entonces el sistema valida los datos, actualiza el perfil y retorna status 200 con la información actualizada. **Escenario 2: Usuario inexistente** Cuando se intenta actualizar un ID no registrado, entonces el sistema responde con status 404 y mensaje de error. | EP-05 |
| TS-03 | Obtener todos los usuarios | Como desarrollador, quiero listar todos los usuarios registrados, para gestionar el acceso y monitoreo del sistema Ventix. | **Escenario 1: Lista con datos** Dado que existen usuarios registrados, cuando se realiza un GET a `/api/v1/users`, entonces el sistema retorna status 200 con una lista de usuarios (tipo: estudiante, hogar, familiar remoto, etc.). **Escenario 2: Lista vacía** Dado que no existen usuarios, entonces el sistema retorna status 204 sin contenido. | EP-05 |
| TS-04 | Obtener datos de sensores | Como desarrollador, quiero obtener los datos de sensores ambientales, para visualizar condiciones de CO₂, temperatura y humedad. | **Escenario 1: Datos disponibles** Dado que existen lecturas en `/api/v1/sensors`, cuando se realiza un GET, entonces el sistema retorna status 200 con datos de CO₂, temperatura, humedad, timestamp y ubicación del sensor. **Escenario 2: Sin datos** Entonces retorna status 204 indicando ausencia de registros. | EP-03 |
| TS-05 | Registrar lectura de sensor | Como desarrollador, quiero registrar datos de sensores en tiempo real, para alimentar el sistema de monitoreo ambiental. | **Escenario 1: Registro válido** Dado que el endpoint `/api/v1/sensors/data` recibe datos válidos (CO₂, temperatura, humedad, deviceId), cuando se envía un POST, entonces el sistema almacena la lectura y retorna status 201. **Escenario 2: Datos incompletos** Entonces retorna status 400 indicando campos faltantes. | EP-03 |
| TS-06 | Obtener sensor por ID | Como desarrollador, quiero obtener información de un sensor específico, para visualizar su estado y ubicación. | **Escenario 1: Sensor existente** Cuando se consulta `/api/v1/sensors/{id}`, entonces el sistema retorna status 200 con datos del sensor (estado, ubicación, última lectura). **Escenario 2: No existe** Entonces retorna status 404 con mensaje “Sensor no encontrado”. | EP-03 |
| TS-07 | Actualizar configuración del sensor | Como desarrollador, quiero actualizar la configuración de un sensor, para ajustar umbrales de CO₂, temperatura y humedad. | **Escenario 1: Actualización correcta** Cuando se envía PUT con nuevos umbrales válidos, entonces el sistema actualiza la configuración y retorna status 200. **Escenario 2: Error de validación** Si los valores están fuera de rango, entonces retorna 400 con mensaje de error. | EP-03 |
| TS-08 | Eliminar sensor | Como desarrollador, quiero eliminar sensores registrados, para mantener el sistema limpio y organizado. | **Escenario 1: Eliminación válida** Cuando se envía DELETE con ID existente, entonces el sistema elimina el sensor y retorna status 204. **Escenario 2: No existe** Entonces retorna 404. | EP-03 |
| TS-09 | Obtener dispositivos vinculados | Como desarrollador, quiero obtener los dispositivos (sensores/ventiladores) vinculados a un usuario, para gestionar el ecosistema IoT de Ventix. | **Escenario 1: Dispositivos existentes** GET `/api/v1/devices` retorna 200 con lista de dispositivos vinculados al usuario. **Escenario 2: Sin dispositivos** retorna 204 sin contenido. | EP-05 |
| TS-10 | Obtener dispositivo por ID | Como desarrollador, quiero obtener un dispositivo específico, para ver su estado y tipo (sensor o ventilador). | **Escenario 1: Existe** retorna 200 con información del dispositivo. **Escenario 2: No existe** retorna 404. | EP-05 |
| TS-11 | Autenticación de usuario | Como desarrollador, quiero autenticar usuarios, para garantizar acceso seguro al sistema Ventix. | **Escenario 1: Credenciales válidas** POST `/api/v1/auth/login` retorna 200 con token JWT, rol de usuario y expiración. **Escenario 2: Credenciales inválidas** retorna 401 con mensaje “Credenciales incorrectas”. | EP-05 |
| TS-12 | Registro de usuario | Como desarrollador, quiero registrar nuevos usuarios, para permitir acceso al sistema de monitoreo ambiental Ventix. | **Escenario 1: Registro exitoso** POST `/api/v1/auth/register` con datos válidos (email, contraseña, tipo de usuario) retorna 201 y crea el usuario. **Escenario 2: Email duplicado** retorna 400 con mensaje “El correo ya está registrado”. | EP-05 |

## 3.3. Impact Mapping.

## 3.4. Product Backlog.

| Orden | User Story ID | Título | Descripción | Story Points |
|------|--------------|--------|-------------|--------------|
| 1 | US-01 | Menú de navegación | Como visitante de la Landing Page, quiero poder acceder a un menú de navegación para explorar fácilmente las secciones del sistema Ventix. | 3 |
| 2 | US-02 | Visualización de beneficios y planes | Como visitante, quiero ver los beneficios del sistema Ventix junto a sus características para evaluar su utilidad. | 5 |
| 3 | US-03 | Selección de plan en Landing Page | Como visitante, quiero seleccionar un plan y registrarme rápidamente para comenzar a usar el sistema. | 5 |
| 4 | US-04 | Visualización de creadores | Como visitante, quiero ver a los creadores del sistema para generar confianza en la plataforma. | 2 |
| 5 | US-05 | Cambio de idioma | Como visitante, quiero cambiar entre español e inglés para entender mejor la plataforma. | 2 |
| 6 | US-06 | Redes sociales | Como usuario, quiero acceder a las redes sociales de Ventix para conocer más sobre el proyecto. | 2 |
| 7 | US-07 | Formulario de contacto | Como usuario, quiero enviar consultas mediante un formulario para recibir soporte. | 3 |
| 8 | US-08 | Visualización de datos en tiempo real | Como usuario, quiero ver en tiempo real los niveles de CO₂, temperatura y humedad para monitorear mi ambiente. | 5 |
| 9 | US-09 | Historial de datos ambientales | Como usuario, quiero ver el historial de datos para analizar el comportamiento del ambiente. | 5 |
| 10 | US-10 | Activación automática por CO₂ alto | Como usuario, quiero que el ventilador se active automáticamente cuando el CO₂ sea alto. | 5 |
| 11 | US-11 | Activación automática por temperatura alta | Como usuario, quiero que el ventilador se active cuando la temperatura sea alta. | 5 |
| 12 | US-12 | Desactivación automática del ventilador | Como usuario, quiero que el ventilador se apague cuando el ambiente vuelva a niveles normales. | 5 |
| 13 | US-13 | Configuración de umbrales de humedad | Como usuario, quiero configurar el nivel de humedad para adaptar el sistema a mi entorno. | 4 |
| 14 | US-14 | Configuración de umbral de CO₂ | Como usuario, quiero definir el nivel de CO₂ para activar el sistema automáticamente. | 5 |
| 15 | US-15 | Configuración de temperatura | Como usuario, quiero definir la temperatura ideal para el control automático del sistema. | 5 |
| 16 | US-16 | Activación manual del ventilador | Como usuario, quiero encender el ventilador manualmente cuando lo necesite. | 3 |
| 17 | US-17 | Modo manual y automático | Como usuario, quiero alternar entre modo manual y automático para controlar el sistema. | 5 |
| 18 | US-18 | Modo ahorro energético | Como usuario, quiero activar un modo ahorro para reducir consumo energético. | 3 |
| 19 | US-19 | Monitoreo de múltiples espacios | Como usuario, quiero monitorear diferentes ambientes desde una sola plataforma. | 5 |
| 20 | US-20 | Modo optimizado | Como estudiante, quiero optimizar el ambiente automáticamente durante mis sesiones de estudio. | 4 |
| 21 | US-21 | Activación automática prioritaria | Como usuario, quiero que el sistema priorice la seguridad y active automáticamente el ventilador en casos críticos. | 5 |
| 22 | US-22 | Notificaciones de aire contaminado | Como usuario, quiero recibir alertas cuando el aire esté contaminado para actuar a tiempo. | 3 |
| 23 | US-23 | Monitoreo remoto de ambientes | Como usuario, quiero monitorear mi hogar desde cualquier lugar para asegurar condiciones saludables. | 5 |
| 24 | US-24 | Botón de pánico ambiental | Como usuario, quiero un acceso rápido a emergencias cuando detecte niveles peligrosos. | 4 |
| 25 | US-25 | Activación remota del ventilador | Como usuario, quiero activar el ventilador remotamente para mejorar el ambiente. | 4 |
| 26 | US-26 | Notificación de inactividad del sistema | Como usuario, quiero recibir alertas si el sistema deja de funcionar correctamente. | 3 |
| 27 | US-27 | Notificación de temperatura extrema | Como usuario, quiero recibir alertas cuando la temperatura sea peligrosa. | 3 |
| 28 | US-28 | Confirmación de acciones remotas | Como usuario, quiero confirmar que las acciones remotas se ejecutaron correctamente. | 2 |
| 29 | US-29 | Notificación de uso manual | Como usuario, quiero saber si alguien modifica el sistema manualmente en casa. | 3 |
| 30 | US-30 | Evaluación de estabilidad del entorno | Como usuario, quiero ver si el ambiente se mantiene estable durante el día. | 5 |
| 31 | US-31 | Registro de usuarios | Como usuario, quiero crear una cuenta para acceder al sistema Ventix. | 3 |
| 32 | US-32 | Recuperación de contraseña | Como usuario, quiero recuperar mi contraseña en caso de olvido. | 3 |
| 33 | US-33 | Vinculación de dispositivo | Como usuario, quiero vincular sensores o ventiladores a mi cuenta. | 5 |
| 34 | US-34 | Cierre de sesión global | Como usuario, quiero cerrar sesión en todos los dispositivos para proteger mi cuenta. | 3 |
| 35 | US-35 | Reporte mensual de calidad del aire | Como usuario, quiero recibir reportes mensuales del estado del aire en mi hogar. | 5 |
| 36 | US-36 | Validación de datos de registro | Como usuario, quiero que el sistema valide mis datos al registrarme. | 3 |
| 37 | US-37 | Recuperación de acceso simplificada | Como usuario, quiero recuperar mi acceso fácilmente si olvido mis credenciales. | 3 |
| 38 | US-38 | Persistencia de sesión | Como usuario, quiero mantener mi sesión activa para evitar iniciar sesión constantemente. | 2 |
| 39 | US-39 | Registro por tipo de usuario | Como usuario, quiero elegir mi tipo de perfil (estudiante o familiar) al registrarme. | 3 |
| 40 | US-40 | Visualización de perfil | Como usuario, quiero ver un resumen de mi perfil y configuración del sistema. | 2 |
