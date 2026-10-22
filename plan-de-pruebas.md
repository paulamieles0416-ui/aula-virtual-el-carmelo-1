# Plan de pruebas

La columna de resultado está pendiente: se completa al ejecutar cada prueba (aprobó / no aprobó, fecha y observaciones).

| ID | Caso de prueba | Requisito | Resultado esperado |
|---|---|---|---|
| PF-01 | Inicio de sesión con credenciales válidas e inválidas | RF01 | Acceso concedido solo con credenciales correctas |
| PF-02 | Verificación de permisos por rol | RF03 | Cada rol accede solo a sus funciones |
| PF-03 | Carga masiva de usuarios y matrícula | RF04, RF05 | Los usuarios quedan creados y matriculados sin errores |
| PF-04 | Creación de un curso y publicación de recursos | RF06, RF07 | El curso y los recursos son visibles para los estudiantes |
| PF-05 | Descarga y consulta de contenidos sin conexión | RF09 | Los contenidos se abren sin red desde la aplicación móvil |
| PF-06 | Resolución de un cuestionario con retroalimentación | RF10, RF11 | Calificación automática y retroalimentación correcta |
| PF-07 | Entrega de una tarea desde el celular | RF12 | Entrega registrada y confirmación al estudiante |
| PF-08 | Calificación con rúbrica y consulta del resultado | RF13, RF16 | El estudiante visualiza nota y comentarios |
| PF-09 | Participación en un foro y aviso en el foro de novedades | RF14 | Mensajes publicados y visibles según el rol |
| PF-10 | Generación de informes de participación y uso | RF19, RF20 | Los informes muestran datos coherentes |
| PR-01 | Carga de páginas con conexión de referencia de 1 Mbps | RNF01 | Tiempo de carga de 5 s o menos |
| PS-01 | Intento de acceso a un curso sin matrícula | RNF09 | Acceso denegado |
| PS-02 | Restauración de una copia de respaldo | RF21, RNF08 | La información se recupera completa |
| PU-01 | Prueba de usabilidad con usuarios y escala SUS | RNF03, RNF04 | Puntaje SUS de 68 o más |
| PA-01 | Lista de verificación de accesibilidad | RNF05 | Cumple los criterios de contraste y texto alternativo |

**Resultados:** _pendiente de registrar_
