#  — Rediseño de interfaz

Rediseño de una historia clínica electrónica (HCE) para consulta externa ambulatoria, desarrollado como prototipo de alta fidelidad para el curso de **Interacción Humano-Computador**.

El proyecto parte del sistema SISME existente y propone una reorganización completa de su interfaz, priorizando la eficiencia clínica, la seguridad del paciente y la claridad visual.

## Ver el prototipo

**[→ Abrir SISME](https://TU-USUARIO.github.io/TU-REPOSITORIO/)**

*(Reemplaza el enlace por la URL de tu GitHub Pages una vez publicado.)*

No requiere instalación: es un único archivo HTML que corre en cualquier navegador moderno, en computadora o teléfono.

## Qué incluye

El prototipo integra diez pantallas conectadas entre sí, navegables desde una barra lateral persistente:

- **Inicio** — panel con indicadores del día y citas de la jornada.
- **Citas** — consulta de citas con filtros por estado y búsqueda.
- **Calendario** — vista mensual con carga de trabajo por día (consultas nuevas, reconsultas y procedimientos) y panorama clínico al tocar cada día.
- **Mis pacientes** — registro de pacientes atendidos, con marca de control vencido.
- **Registrar paciente** — formulario de datos filiatorios reorganizado por relevancia clínica.
- **Historia clínica** — anamnesis completa estructurada en formato SOAP, con antecedentes por excepción, cálculo automático de IMC e índice paquete-año, récipe con buscador y diagnósticos CIE-10.
- **Interrogatorio funcional** — entrada rápida por sistemas con narrativa autogenerada.
- **Verificación de reconsulta** — confirmación de datos sin recaptura.
- **Emergencias** — registro mínimo para atender primero y completar después.
- **Encuesta** — evaluación de usabilidad con System Usability Scale (SUS) y cálculo automático del puntaje.

## Principios de diseño

- **El color significa algo.** Los tonos fuertes se reservan para información que afecta la seguridad del paciente (alergias, valores críticos). Lo rutinario se codifica con forma y tipografía, no con color.
- **Entrada por excepción.** En interrogatorio y antecedentes, lo normal es negar; el médico solo detalla lo positivo, ahorrando tiempo sin perder constancia de lo explorado.
- **Verificar, no recapturar.** Los datos que no cambian se muestran como lectura; solo se actualiza lo que varía entre visitas.
- **Datos estructurados desde el origen.** Diagnósticos con CIE-10, procedencia del dato en valores sensibles (tipo de sangre referido vs. confirmado), pensados para análisis posterior e interoperabilidad.
- **Cada registro se adapta a su contexto.** Una emergencia pide lo mínimo; una primera consulta, la anamnesis completa; una reconsulta, solo verificación.

## Tecnología

Prototipo de front-end en HTML, CSS y JavaScript puro (sin dependencias ni framework). Tipografía Inter y Source Serif 4. Todo el comportamiento interactivo (filtros, búsquedas, cálculos clínicos, navegación) funciona en el navegador. No hay base de datos: los datos mostrados son de ejemplo y no se almacenan.

## Evaluación

El prototipo incluye una encuesta basada en el **System Usability Scale (SUS)**, instrumento validado internacionalmente, complementado con preguntas de satisfacción, recomendación (NPS) y feedback clínico abierto. El objetivo es recoger retroalimentación medible de médicos, estudiantes y docentes.

## Estado del proyecto

Prototipo en desarrollo iterativo. El diseño se ajusta a partir de la retroalimentación de profesionales de salud que interactúan con el sistema.

## Autor

Desarrollado por Nelson Merentes — médico cirujano (UCV) y estudiante de Maestría en Ciencias de la Computación (UCV), en el marco del curso de Interacción Humano-Computador.

## Licencia

Proyecto académico. Uso educativo.
