# Requisitos del proyecto

## Historias de usuario

| ID | Historia de usuario | Prioridad | Criterios de aceptación |
|---|---|---|---|
| HU01 | Como estudiante o docente, quiero ingresar con mi usuario y contraseña desde el celular o el computador, para acceder a mis cursos. | Debe | Ingreso exitoso en menos de 10 s con conexión limitada; mensaje claro ante credenciales erróneas |
| HU02 | Como estudiante, quiero ver mis cursos, mis fechas de entrega y mi progreso, para saber qué debo hacer. | Debe | El tablero muestra cursos, actividades pendientes y porcentaje de avance |
| HU03 | Como estudiante, quiero descargar guías y recursos, para estudiar sin conexión continua. | Debe | Los recursos marcados como descargables se abren sin conexión desde la aplicación móvil |
| HU04 | Como estudiante, quiero resolver cuestionarios y ver mi resultado de inmediato, para recibir retroalimentación oportuna. | Debe | El cuestionario califica automáticamente y muestra la retroalimentación configurada |
| HU05 | Como estudiante, quiero entregar tareas desde el celular, para no depender del cuaderno ni de la presencialidad. | Debe | Se pueden adjuntar archivos o escribir texto y se confirma la recepción |
| HU06 | Como estudiante, quiero participar en foros y recibir avisos, para comunicarme con mis compañeros y mi docente. | Debería | Se pueden publicar y responder mensajes; los avisos llegan al foro de novedades |
| HU07 | Como estudiante, quiero consultar mis calificaciones y la retroalimentación del docente, para mejorar mi aprendizaje. | Debe | El libro de calificaciones muestra solo las notas propias, con comentarios |
| HU08 | Como docente, quiero crear y organizar cursos por unidades, para estructurar mis clases. | Debe | Se crea un curso desde la plantilla con unidades y actividades |
| HU09 | Como docente, quiero publicar recursos (PDF, video, H5P y enlaces), para enriquecer mis clases. | Debe | Los recursos se publican, se ocultan o se muestran por unidad |
| HU10 | Como docente, quiero crear cuestionarios con un banco de preguntas, para evaluar a mis estudiantes de forma ágil. | Debe | Se crean preguntas por categoría y se reutilizan en varios cuestionarios |
| HU11 | Como docente, quiero calificar con rúbricas y retroalimentar, para valorar los productos de manera objetiva. | Debería | La rúbrica genera la nota y el estudiante visualiza los criterios |
| HU12 | Como docente, quiero ver reportes de participación y desempeño, para hacer seguimiento a cada estudiante. | Debería | El informe muestra accesos, entregas y calificaciones por estudiante |
| HU13 | Como administrador, quiero gestionar usuarios, roles y matrículas, incluso de forma masiva, para organizar la plataforma. | Debe | Se cargan usuarios desde un archivo y se asignan roles y cursos |
| HU14 | Como administrador, quiero contar con copias de respaldo automáticas y poder restaurarlas, para proteger la información. | Debe | Existe copia diaria de la base de datos y una restauración verificada |
| HU15 | Como directivo, quiero consultar reportes de uso de la plataforma, para tomar decisiones institucionales. | Debería | Existe un informe de uso por curso y por periodo |

## Requisitos funcionales

| ID | Requisito | Historia | Prioridad |
|---|---|---|---|
| RF01 | Autenticar a los usuarios con usuario y contraseña | HU01 | Debe |
| RF02 | Permitir la recuperación de contraseña por correo o por el administrador | HU01 | Debería |
| RF03 | Gestionar roles (administrador, docente, estudiante y directivo) con permisos diferenciados | HU13 | Debe |
| RF04 | Registrar usuarios individualmente y mediante carga masiva desde un archivo | HU13 | Debe |
| RF05 | Matricular a los usuarios en los cursos según su rol | HU13 | Debe |
| RF06 | Crear y editar cursos organizados por unidades, a partir de una plantilla | HU08 | Debe |
| RF07 | Publicar recursos: archivos, enlaces, videos y páginas | HU09 | Debe |
| RF08 | Incorporar contenidos interactivos H5P | HU09 | Debería |
| RF09 | Permitir la descarga de recursos y el acceso desde la aplicación móvil | HU03 | Debe |
| RF10 | Administrar un banco de preguntas por categorías | HU10 | Debe |
| RF11 | Crear cuestionarios con calificación y retroalimentación automáticas | HU04, HU10 | Debe |
| RF12 | Recibir tareas en archivo o texto en línea con confirmación de entrega | HU05 | Debe |
| RF13 | Calificar con rúbricas y emitir retroalimentación | HU11 | Debería |
| RF14 | Ofrecer foros del curso y un foro de novedades | HU06 | Debería |
| RF15 | Ofrecer talleres de evaluación entre pares | HU11 | Podría |
| RF16 | Mostrar al estudiante su libro de calificaciones | HU07 | Debe |
| RF17 | Registrar el progreso por actividad completada | HU02 | Debe |
| RF18 | Mostrar un tablero personal con cursos y fechas de entrega | HU02 | Debe |
| RF19 | Generar informes de participación y calificaciones por curso | HU12 | Debería |
| RF20 | Generar informes de uso institucional para los directivos | HU15 | Debería |
| RF21 | Realizar copias de respaldo automáticas y permitir su restauración | HU14 | Debe |
| RF22 | Ofrecer mensajería interna y notificaciones | HU06 | Podría |
| RF23 | Aplicar las encuestas SUS y TAM dentro de la plataforma | Evaluación (OE3) | Debe |

## Requisitos no funcionales

| ID | Característica | Requisito | Verificación |
|---|---|---|---|
| RNF01 | Eficiencia de desempeño | Las páginas principales deben cargar en 5 segundos o menos con una conexión de referencia de 1 Mbps | Prueba de carga PR-01 |
| RNF02 | Eficiencia de desempeño | Los recursos deben ser livianos: videos de 10 MB o menos y documentos PDF de 5 MB o menos por recurso | Revisión de contenidos por sprint |
| RNF03 | Usabilidad | El puntaje SUS promedio debe ser igual o superior a 68 | Escala SUS al final del piloto |
| RNF04 | Usabilidad | La interfaz debe estar en español y permitir llegar a cualquier actividad en tres clics o menos | Prueba de usabilidad PU-01 |
| RNF05 | Accesibilidad | El contenido debe cumplir los criterios de contraste, texto alternativo y navegación de WCAG 2.1 en lo aplicable | Lista de verificación PA-01 |
| RNF06 | Compatibilidad | La plataforma debe funcionar en los navegadores actuales y en celulares Android con diseño adaptable | Pruebas en dispositivos |
| RNF07 | Fiabilidad | La disponibilidad debe ser de 95 % o más en el horario escolar durante el piloto | Monitoreo del servidor |
| RNF08 | Fiabilidad | Debe existir copia diaria de la base de datos y una restauración verificada al final de cada sprint | Prueba PS-02 |
| RNF09 | Seguridad | Debe usarse HTTPS, contraseñas robustas y roles con el mínimo privilegio necesario | Prueba PS-01 |
| RNF10 | Seguridad y legalidad | Se tratarán solo los datos personales necesarios, con consentimiento, conforme a la Ley 1581 de 2012 | Revisión de formatos y de configuración |
| RNF11 | Mantenibilidad | La configuración debe estar documentada y versionada, de modo que un tercero pueda reproducirla | Revisión de la guía de configuración |
| RNF12 | Portabilidad y sostenibilidad | Solo se usarán componentes de licencia libre y se entregará una guía para replicar la solución | Revisión de licencias y de la guía |

## Casos de uso

| ID | Caso de uso | Actor | Descripción |
|---|---|---|---|
| CU01 | Autenticarse | Todos | El usuario ingresa sus credenciales y el sistema valida su identidad y muestra su tablero |
| CU02 | Gestionar usuarios, roles y matrículas | Administrador | Crea cuentas (individual o masiva), asigna roles y matricula en cursos |
| CU03 | Crear y organizar cursos | Docente | Crea un curso desde la plantilla y organiza las unidades |
| CU04 | Publicar recursos y actividades | Docente | Agrega recursos y actividades a cada unidad y define su visibilidad y disponibilidad |
| CU05 | Crear cuestionarios y banco de preguntas | Docente | Registra preguntas por categoría y configura cuestionarios con retroalimentación |
| CU06 | Calificar y retroalimentar | Docente | Revisa entregas, califica con rúbricas y escribe comentarios |
| CU07 | Consultar contenidos | Estudiante | Navega por los cursos y accede a los recursos de cada unidad |
| CU08 | Descargar recursos para uso sin conexión | Estudiante | Descarga contenidos desde la aplicación móvil para consultarlos sin red |
| CU09 | Resolver actividades y cuestionarios | Estudiante | Responde las actividades y recibe el resultado y la retroalimentación |
| CU10 | Participar en foros y entregar tareas | Estudiante | Publica mensajes en foros y envía sus tareas dentro del plazo |
| CU11 | Consultar calificaciones y progreso | Estudiante | Visualiza sus notas, comentarios y avance en cada curso |
| CU12 | Generar reportes de uso y desempeño | Docente y directivo | Obtiene informes de participación, calificaciones y uso |
| CU13 | Realizar copias de respaldo | Administrador | Programa, verifica y restaura las copias de la base de datos y de los archivos |
| CU14 | Administrar y configurar la plataforma | Administrador | Configura el tema, los plugins, la seguridad y las políticas de uso |

## Trazabilidad

| Objetivo | Necesidad | Historias | Requisitos | Casos de uso | Pruebas |
|---|---|---|---|---|---|
| OE1 | Conocer el contexto y definir requisitos | — | RNF01, RNF02, RNF05, RNF06 | — | Instrumentos y diagnóstico |
| OE2 | Acceso y autenticación | HU01, HU02 | RF01, RF02, RF17, RF18 | CU01, CU07 | PF-01, PF-02 |
| OE2 | Administración de usuarios y seguridad | HU13, HU14 | RF03 a RF05, RF21; RNF07 a RNF10 | CU02, CU13, CU14 | PF-03, PS-01, PS-02 |
| OE2 | Creación y publicación de contenidos | HU08, HU09 | RF06 a RF08 | CU03, CU04 | PF-04 |
| OE2 | Acceso sin conexión continua | HU03 | RF09; RNF01, RNF02 | CU08 | PF-05, PR-01 |
| OE2 | Evaluación y seguimiento | HU04 a HU07, HU10 a HU12 | RF10 a RF16 | CU05, CU06, CU09 a CU11 | PF-06 a PF-09 |
| OE3 | Reportes, usabilidad y aceptación | HU12, HU15 | RF19, RF20, RF23; RNF03, RNF04 | CU12 | PF-10, PU-01 |
