# Aula Virtual · I.E. El Carmelo

**Autor:** Eucarlos Gámez Cuello
**Programa:** Ingeniería de Sistemas · Universidad Nacional Abierta y a Distancia (UNAD), ECBTI
**Curso:** Proyecto de grado (202016907) · Fase 4, componente práctico
**Institución beneficiada:** Institución Educativa El Carmelo, San Juan del Cesar (La Guajira)

## ¿Qué es esta página?

El Aula Virtual es una plataforma digital de aprendizaje: un sitio web donde la institución puede organizar sus cursos y apoyar la clase presencial con herramientas digitales. En una sola página, los estudiantes consultan contenidos, resuelven cuestionarios, entregan tareas y participan en foros; los docentes publican actividades, califican y hacen seguimiento; y la rectoría consulta reportes de uso y desempeño.

Fue diseñada para el contexto de la institución, donde la conectividad es limitada. Por eso funciona desde el celular o el computador, usa recursos livianos y permite descargar contenidos para estudiar sin conexión continua. No reemplaza la clase presencial: la complementa y facilita una transición gradual de lo tradicional a lo digital.

Este repositorio contiene el prototipo funcional de la plataforma y la documentación del proyecto.

## Misión

En los próximos años la institución educativa «El Carmelo» será reconocida debido a su mejor nivel académico y social por:

* Fortalecer su modelo pedagógico
* Hacer convenios para el desarrollo de competencias laborales
* Mejorar sus resultados en las pruebas externas
* Crear espacios para interrelacionarse con la comunidad
* Fortalecer valores éticos, cívicos y sociales
* Formular y desarrollar proyectos para la atención de poblaciones especiales.

## Visión

“Somos una institución educativa formadora de seres humanos competentes académicamente, capaces de adquirir nuevos conocimientos a través de la investigación; críticos, reflexivos, respetuosos, responsables tolerantes y solidarios que buscan solución a los problemas de su localidad, de su región y de su país”.

## Demo

https://TU-USUARIO.github.io/aula-virtual-el-carmelo/

También se puede abrir el archivo `index.html` directamente en el navegador. No requiere instalación ni servidor.

## Cuentas de demostración

La contraseña de todas es `1234`.

| Rol | Correo |
|---|---|
| Administrador | admin@elcarmelo.edu.co |
| Docente | docente@elcarmelo.edu.co |
| Estudiante | estudiante1@elcarmelo.edu.co |
| Directivo | directivo@elcarmelo.edu.co |

## Recorrido sugerido (5 minutos)

1. Ingresa como **estudiante** y abre el curso de Matemáticas. Resuelve el cuestionario de repaso y mira la calificación y la retroalimentación automáticas.
2. Pulsa **Descargar** en una lección, apaga el interruptor **En línea** (arriba a la derecha) y comprueba que solo se abren los recursos descargados. Entrega una tarea sin conexión y vuelve a encender el interruptor: el envío se sincroniza.
3. Responde la **Encuesta SUS y TAM** desde el menú.
4. Ingresa como **docente**: agrega una actividad, califica la tarea del estudiante y revisa los **Reportes**.
5. Ingresa como **administrador**: cambia un rol, prueba la carga masiva y descarga una copia de respaldo.
6. Ingresa como **directivo** y consulta los reportes de uso, con el puntaje SUS y la aceptación TAM.

## Qué contiene la página

**Para todos los roles**
- Ingreso con correo y contraseña, y menú según el rol.
- Interruptor de conexión para simular un entorno de baja conectividad.
- Diseño adaptable al celular, con modo claro y oscuro.
- Identidad visual con el escudo de la institución.

**Estudiante**
- Tablero con sus cursos y el porcentaje de avance.
- Cursos organizados por unidades; cada actividad indica su nivel de la Taxonomía de Bloom (recordar, comprender, aplicar, analizar, evaluar y crear).
- Lecciones, cuestionarios con calificación y retroalimentación automáticas, tareas y foros.
- Descarga de recursos para usarlos sin conexión; los envíos hechos sin conexión quedan pendientes y se sincronizan al reconectarse.
- Libro de calificaciones con las notas y los comentarios del docente.
- Encuesta de usabilidad (SUS, 10 ítems) y de aceptación tecnológica (TAM, 12 ítems).

**Docente**
- Agregar actividades (lección, cuestionario, tarea o foro) con su nivel de Bloom.
- Crear cuestionarios escribiendo las preguntas en un formato simple.
- Calificar tareas con nota de 0 a 5 y retroalimentación.
- Reportes del curso: estudiantes activos, actividades completadas y promedio de notas.

**Administrador**
- Gestión de usuarios y cambio de roles.
- Carga masiva de usuarios (nombre, correo y rol).
- Copias de respaldo: descargar y restaurar los datos, o restablecer la demostración.

**Directivo**
- Reportes de uso y desempeño por curso.
- Puntaje SUS promedio (meta: 68 o más) y aceptación TAM favorable (meta: 70 % o más).

## Contenido del repositorio

- `index.html`: el prototipo (página única, sin dependencias).
- `docs/documento-maestro-fase3.docx`: documento maestro con el planteamiento, los marcos de referencia, la metodología, los requisitos y el diseño.
- `docs/requisitos.md`: historias de usuario, requisitos funcionales y no funcionales, casos de uso y trazabilidad.
- `docs/backlog-sprints.md`: plan de los 12 sprints.
- `docs/plan-de-pruebas.md`: casos de prueba y su resultado.
- `docs/manual-de-usuario.md`: guía para docentes y estudiantes.
- `docs/riesgos.md` y `docs/capacitacion.md`: registro de riesgos y plan de capacitación docente.
- `docs/img/`: figuras del proyecto (arquitectura, casos de uso, mockups, cronograma y otras).
- `CHANGELOG.md`: registro de versiones.

## Metodología

- **Investigación:** enfoque mixto con diseño de ciencias del diseño; evaluación de usabilidad y aceptación con SUS y TAM.
- **Desarrollo:** Scrum en 12 sprints de dos semanas, combinado con el modelo de diseño instruccional ADDIE.
- **Meta tecnológica:** nivel de madurez TRL 5 (validación en un entorno relevante).

## Alcance y limitaciones

- Es un prototipo: los datos se guardan en el navegador (localStorage) y no hay servidor ni base de datos.
- Los cursos son de ejemplo (Matemáticas, Ciencias naturales y Tecnología e informática de 9.º) y se ajustarán a las áreas que priorice la institución.
- La solución definitiva propuesta en el documento maestro se basa en Moodle, software libre; este prototipo valida el diseño, los flujos y la experiencia de uso.
- Los datos personales se tratan solo con fines académicos, conforme a la Ley 1581 de 2012.

## Licencia

MIT. Ver el archivo `LICENSE`.
