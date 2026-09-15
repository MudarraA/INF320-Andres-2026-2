# Material de Clase y Banco de Actividades

**Automatización de Procesos de Negocios (INF 320) — Semestre 2026-2**
**Docente: Angel R. Avila G. — angel.avila@up.ac.pa**

Este documento complementa a `02-Plan-trabajo-15-semanas.md`. Mientras aquel describe **qué** se hace cada semana, este desarrolla **el contenido listo para usar en clase**: guiones breves de mini-clase, casos resueltos, técnicas de aprendizaje activo específicas por sesión, preguntas de cierre y un banco adicional de ejercicios/casos con solución guiada por módulo. El objetivo es maximizar el aprendizaje dentro de las 4 horas semanales (2 teóricas + 2 prácticas) frente a un curso orientado a analistas de negocio, no necesariamente programadores.

**Horario real del curso**: Teoría, martes 6:55 p.m. – 8:40 p.m. Laboratorio, jueves 5:05 p.m. – 6:50 p.m.

---

## 0. Rutina de clase recomendada (aplicar cada sesión teórica de 1h45)

| Bloque | Duración sugerida | Propósito |
|---|---|---|
| **Warm-up / pregunta detonante** | 5-10 min | Conectar el tema con la experiencia cotidiana del estudiante como consumidor o futuro analista de negocio. |
| **Mini-clase dialogada** | 30-35 min | Exponer el concepto nuevo apoyado en ejemplos reales de comercio electrónico, con preguntas intercaladas. |
| **Caso o mini-demo resuelto** | 25-30 min | Analizar un caso corto o mostrar una demo en vivo de la herramienta correspondiente. |
| **Técnica de aprendizaje activo** | 20-25 min | Ver técnica sugerida por semana (sección 2). |
| **Exit ticket** | 5 min | Pregunta de cierre individual que conecta el tema con el proyecto integrador del equipo. |

---

## 1. Banco de técnicas de aprendizaje activo (usar de forma rotativa)

| Técnica | Cómo aplicarla | Cuándo funciona mejor |
|---|---|---|
| **Piensa-Compara-Comparte** | Respuesta individual, luego en pareja, luego a la clase. | Preguntas conceptuales (BPA vs. BPR, BPM vs. RPA). |
| **Estudio de mini-caso en equipo** | Se entrega un caso de 1 párrafo; el equipo responde 2-3 preguntas guía en 10 minutos y sustenta ante la clase. | Casos de e-commerce, priorización de oportunidades. |
| **Demo en vivo con predicción** | Antes de ejecutar un flujo en Zapier/Make, la clase predice qué pasará con cada paso. | Cualquier demostración de herramienta no-code. |
| **Rol de "dueño del proceso"** | Un estudiante asume el rol de gerente de un área (logística, marketing, atención al cliente) y el resto le hace preguntas de levantamiento de información. | Técnicas de análisis de procesos (semana 4), entrevistas. |
| **Debate estructurado** | La clase se divide en dos posturas (ej. "RPA clásico" vs. "no-code/IA") y defiende su posición con argumentos técnicos. | Comparación de plataformas, selección de herramientas. |
| **Galería de diagramas** (Gallery Walk) | Cada equipo pega/proyecta su diagrama BPMN; el resto circula y deja retroalimentación en notas adhesivas o comentarios. | Revisión de diagramas BPMN AS-IS/TO-BE. |
| **Uno verdadero, uno falso** | Dos afirmaciones sobre el tema; la clase vota cuál es falsa y por qué. | Repaso rápido antes de examen. |
| **Simulación de pitch** | Cada equipo presenta en 2 minutos el avance de su proyecto como si fuera ante un inversionista/gerente. | Cierre de checkpoints del proyecto integrador. |

---

## 2. Guion de clase por semana

### MÓDULO 1 — Introducción a la automatización

**Semana 1 — Presentación del curso y panorama de la BPA**
- *Warm-up*: "Mencionen 3 procesos que hacen como consumidores hoy en día que hace 15 años requerían una persona (ej. rastrear un pedido, pedir una cita, pagar una factura)."
- *Mini-clase*: definición de BPA, beneficios (eficiencia, reducción de errores, escalabilidad, experiencia de cliente), panorama 2026 (RPA clásico + no-code/IA + LLM).
- *Caso resuelto*: comparar el proceso de compra en una tienda física de los años 90 vs. una tienda en línea actual, identificando qué pasos se automatizaron.
- *Técnica activa*: **Piensa-Compara-Comparte** sobre "¿qué proceso de su vida diaria les gustaría que estuviera automatizado y no lo está? ¿Por qué creen que no lo está?"
- *Exit ticket*: "En una oración, ¿qué es BPA y por qué le importa a un negocio de comercio electrónico?"

**Semana 2 — Automatización en e-commerce y diferencia con BPR**
- *Warm-up*: mostrar dos titulares ficticios: uno de una empresa que "mejoró su proceso de envíos" y otro que "rediseñó por completo su modelo de atención al cliente". Preguntar cuál creen que es automatización y cuál BPR.
- *Mini-clase*: automatización incremental vs. reingeniería radical (BPR), con ejemplos de e-commerce (confirmaciones automáticas, seguimiento de envíos, recomendaciones personalizadas).
- *Caso resuelto*: analizar el caso guiado de un negocio ficticio que pasó de recibir pedidos por WhatsApp manualmente a un sistema de carrito de compras automatizado — clasificar si es automatización o BPR y justificar.
- *Técnica activa*: **estudio de mini-caso en equipo** con los 4 mini-casos (logística, atención al cliente, marketing, pagos) del laboratorio de la semana.
- *Exit ticket*: "Den un ejemplo propio (no visto en clase) de automatización incremental y uno de BPR."

### MÓDULO 2 — Mapeo, análisis e identificación de oportunidades

**Semana 3 — Mapeo y modelado BPMN**
- *Warm-up*: dibujar en la pizarra, sin notación formal, los pasos de "pedir comida a domicilio" tal como los estudiantes los describan en voz alta.
- *Mini-clase*: elementos básicos de BPMN 2.0 (eventos, tareas, compuertas exclusivas/paralelas, piscinas/carriles), traduciendo el diagrama informal de la pizarra a notación BPMN.
- *Caso resuelto*: modelar en vivo, proyectando la herramienta (Bizagi/draw.io), el proceso de "checkout de una tienda en línea" paso a paso, pidiendo a la clase que indique el siguiente elemento BPMN antes de dibujarlo.
- *Técnica activa*: **demo en vivo con predicción** aplicada al modelado BPMN mismo (la clase predice si el siguiente paso requiere una compuerta exclusiva o paralela).
- *Exit ticket*: "¿Cuándo usarían una compuerta exclusiva y cuándo una paralela? Den un ejemplo de cada una en un proceso de e-commerce."

**Semana 4 — Técnicas de análisis de procesos**
- *Warm-up*: preguntar "si tuvieran que entender cómo funciona realmente el proceso de devoluciones de una tienda, ¿a quién le preguntarían primero y qué le preguntarían?"
- *Mini-clase*: entrevistas estructuradas/semiestructuradas, observación directa (walkthroughs), análisis de datos operativos (tiempo de ciclo, volumen, tasa de error).
- *Caso resuelto*: modelar en vivo una entrevista simulada breve (el docente hace de "dueño del proceso" y un estudiante voluntario aplica un guion de entrevista) para mostrar buenas y malas preguntas.
- *Técnica activa*: **rol de "dueño del proceso"** — un estudiante por equipo asume el rol y el resto de equipos rota para entrevistarlo sobre un proceso ficticio asignado.
- *Exit ticket*: "Escriban dos preguntas de entrevista que usarían para detectar un cuello de botella en el proceso de su proyecto."

**Semana 5 — Identificación de oportunidades — Checkpoint 1**
- *Warm-up*: presentar dos oportunidades de automatización ficticias (una de bajo esfuerzo/alto impacto, otra de alto esfuerzo/bajo impacto) y preguntar cuál priorizarían primero.
- *Mini-clase*: matriz de priorización esfuerzo vs. impacto; concepto de "quick win".
- *Caso resuelto*: ubicar en vivo, con participación de la clase, 5-6 oportunidades de automatización de un negocio ficticio en la matriz esfuerzo/impacto proyectada.
- *Técnica activa*: **galería de diagramas** con los diagramas BPMN AS-IS de cada equipo, retroalimentación cruzada antes de la entrega del checkpoint.
- *Exit ticket*: no aplica (se sustituye por la entrega del Checkpoint 1).

### MÓDULO 3 — BPM, RPA e integración

**Semana 6 — BPM vs. RPA — Parcial 1**
- *Warm-up*: "Uno verdadero, uno falso" con dos afirmaciones sobre BPM y RPA.
- *Mini-clase*: repaso general de módulos 1 y 2 dirigido por preguntas guía, como preparación directa al parcial.
- *Técnica activa*: **debate estructurado** breve (10 min) sobre "¿BPM y RPA compiten o se complementan?" antes del examen, como calentamiento conceptual.
- *Exit ticket*: no aplica (se sustituye por el Parcial 1).

**Semana 7 — Plataformas RPA y alternativas no-code/IA**
- *Warm-up*: mostrar los logos de UiPath, Zapier y Dialogflow y preguntar "¿cuál de estas herramientas usaría alguien sin conocimientos de programación?"
- *Mini-clase*: comparación de arquitectura, curva de aprendizaje, costo y casos de uso típicos entre RPA clásico y no-code/IA.
- *Caso resuelto*: demo en vivo de un flujo simple en Zapier o Make (ej. "al recibir un correo con cierto asunto, crear una fila en una hoja de cálculo"), la clase predice cada paso antes de ejecutarlo.
- *Técnica activa*: **demo en vivo con predicción**, seguida de **debate estructurado**: "RPA clásico" vs. "no-code/IA" para el caso de una pyme con presupuesto limitado.
- *Exit ticket*: "¿Qué herramienta recomendarían a una pyme sin personal técnico: UiPath o Zapier? Justifiquen en 2 líneas."

**Semana 8 — Integración con sistemas de comercio electrónico**
- *Warm-up*: preguntar "cuando llenan un formulario en línea y reciben un correo de confirmación segundos después, ¿qué creen que ocurre 'por detrás'?"
- *Mini-clase*: conceptos de API, webhook y conector explicados con analogías no técnicas (API como "mesero" que lleva pedidos entre sistemas; webhook como "timbre" que avisa cuando algo pasa).
- *Caso resuelto*: demo en vivo conectando un formulario en línea a una hoja de cálculo y a una notificación por correo, usando Zapier/Make/Power Automate.
- *Técnica activa*: **estudio de mini-caso en equipo**: cada equipo diseña conceptualmente (en papel, sin implementar aún) una integración de 3 pasos para su propio proyecto y la presenta en 1 minuto.
- *Exit ticket*: "Dibujen con flechas los 3 sistemas que conectarían en la integración de su proyecto y qué dato viaja entre ellos."

**Semana 9 — Taller integrador — Checkpoint 2**
- *Warm-up*: repaso relámpago con "Uno verdadero, uno falso" de BPM/RPA/no-code/integración.
- *Mini-clase*: breve, enfocada en cómo aplicar lo visto a escenarios de cadena de suministro y logística (notificaciones de stock, seguimiento de pedidos, alertas a proveedores).
- *Técnica activa*: **simulación de pitch**: cada equipo presenta en 2 minutos su prototipo funcional antes de entregarlo, recibiendo una pregunta rápida de un compañero de otro equipo.
- *Exit ticket*: no aplica (se sustituye por la entrega del Checkpoint 2).

### MÓDULO 4 — Diseño de workflows y chatbots

**Semana 10 — Principios de diseño de workflows automatizados**
- *Warm-up*: preguntar "¿qué pasa si un cliente paga con una tarjeta rechazada y el sistema no tiene previsto ese caso?"
- *Mini-clase*: principios de simplicidad, modularidad y trazabilidad; manejo de excepciones y casos borde.
- *Caso resuelto*: construir en vivo un workflow con una rama condicional (ej. "si el pago falla, notificar al cliente y al equipo de soporte"), mostrando cómo se ve una excepción no manejada vs. manejada.
- *Técnica activa*: **estudio de mini-caso en equipo**: se entrega un workflow sin manejo de excepciones; cada equipo debe identificar 2 casos borde no contemplados y proponer cómo manejarlos.
- *Exit ticket*: "Mencionen un caso borde de su propio proceso que su workflow todavía no maneja."

**Semana 11 — Casos de uso en e-commerce — Parcial 2**
- *Warm-up*: "Uno verdadero, uno falso" integrando módulo 3 y avance del módulo 4.
- *Mini-clase*: casos de uso reales en gestión de pedidos, procesamiento de pagos y gestión de inventarios, como repaso aplicado antes del examen.
- *Técnica activa*: **debate estructurado** breve sobre cuál de los tres casos de uso (pedidos, pagos, inventario) es más crítico de automatizar primero en una pyme típica.
- *Exit ticket*: no aplica (se sustituye por el Parcial 2).

**Semana 12 — Automatización de pedidos/inventario y chatbot — Checkpoint 3**
- *Warm-up*: mostrar una conversación simple de chatbot (capturas de pantalla) y preguntar qué preguntas del cliente identifican como "intent" distintos.
- *Mini-clase*: fundamentos de diseño conversacional (intents, entidades, flujos de diálogo).
- *Caso resuelto*: demo en vivo de construcción de un intent básico en Voiceflow/Landbot/Dialogflow CX para responder "¿cuál es el estado de mi pedido?".
- *Técnica activa*: **estudio de mini-caso en equipo**: cada equipo lista las 5 preguntas más frecuentes que su chatbot debería responder y las clasifica por intent.
- *Exit ticket*: "Escriban 2 preguntas que un cliente le haría a su chatbot y cómo debería responder cada una."

### MÓDULO 5 — Marketing, seguridad y mejora continua

**Semana 13 — Automatización de marketing y ventas**
- *Warm-up*: preguntar "¿por qué reciben correos distintos de la misma tienda según lo que compraron o dejaron en el carrito?"
- *Mini-clase*: embudo de conversión, lead nurturing, segmentación de audiencias.
- *Caso resuelto*: demo en vivo de configuración de una campaña simple en HubSpot/Mailchimp con un criterio de segmentación.
- *Técnica activa*: **estudio de mini-caso en equipo**: diseñar 2 segmentos de audiencia y un disparador de campaña para el negocio del proyecto.
- *Exit ticket*: "¿Qué segmento de clientes definirían para su proyecto y qué mensaje les enviarían?"

**Semana 14 — Chatbots avanzados, tendencias, seguridad y mejora continua**
- *Warm-up*: preguntar "¿qué datos personales de un cliente estarían dispuestos a compartir con un chatbot y cuáles no?"
- *Mini-clase*: tendencias de IA en BPA (minería de procesos asistida por IA); marco legal (GDPR, CCPA, Ley 81 de 2019 de Panamá); Kaizen, Six Sigma y diseño de KPIs.
- *Caso resuelto*: construir en vivo, con participación de la clase, un tablero mínimo de 4 KPIs para un proceso de e-commerce ficticio (ej. tasa de abandono de carrito, tiempo de respuesta, tasa de conversión, NPS).
- *Técnica activa*: **debate estructurado**: "¿qué dato personal es razonable pedir a un cliente y cuál sería excesivo?" conectando con la checklist de seguridad del proyecto.
- *Exit ticket*: "Mencionen un riesgo de privacidad de datos en el proceso de su proyecto y una medida concreta para mitigarlo."

**Semana 15 — Examen semestral y demo final**
- *Warm-up*: "Uno verdadero, uno falso" integrando los cinco módulos como repaso final.
- *Mini-clase*: no aplica (sesión dedicada al examen semestral y a las demos finales).
- *Técnica activa*: **simulación de pitch** aplicada a la demo final real de cada equipo, con preguntas del docente y coevaluación de pares.
- *Exit ticket*: encuesta de cierre de semestre (ver `02-Plan-trabajo-15-semanas.md`, semana 15).

---

## 3. Banco de mini-casos adicionales por módulo (con guía de solución)

Uso sugerido: repaso previo a exámenes, actividad comodín, o insumo para debates en clase.

### Módulo 1-2 (BPA, BPR, mapeo y análisis)

1. **Caso**: Una pyme de ropa recibe pedidos por Instagram y los anota en un cuaderno; luego el dueño llama a cada cliente para confirmar talla y pago. ¿Automatización o BPR si se implementa un catálogo con carrito de compras y pago en línea?
   **Guía de solución**: Es BPR, porque cambia radicalmente la forma en que se capta y procesa el pedido (no es una mejora del cuaderno, es un modelo distinto).

2. **Caso**: Un negocio que ya recibe pedidos en línea decide agregar una confirmación automática por correo en lugar de que un empleado la envíe manualmente. ¿Automatización o BPR?
   **Guía de solución**: Automatización incremental — el proceso central (pedido en línea) no cambia, solo se automatiza un paso puntual.

3. **Caso**: Un equipo levanta información de un proceso de devoluciones únicamente revisando los registros del sistema, sin entrevistar a nadie. ¿Qué riesgo tiene este enfoque?
   **Guía de solución**: Se pierde información cualitativa sobre por qué ocurren las devoluciones y cómo el personal realmente maneja excepciones no registradas en el sistema; se recomienda combinar con entrevista u observación directa.

### Módulo 3 (BPM/RPA, plataformas, integración)

4. **Caso**: Una empresa grande con procesos muy estables (facturación masiva) evalúa entre UiPath (RPA clásico) y Zapier (no-code). ¿Cuál recomendarían y por qué?
   **Guía de solución**: RPA clásico (UiPath) suele ser más apropiado para procesos de alto volumen, estables y que interactúan con sistemas legacy sin API, mientras que Zapier es más ágil para integraciones entre servicios modernos con API disponible.

5. **Caso**: Un equipo conecta su formulario de pedidos a una hoja de cálculo mediante un webhook, pero el flujo falla silenciosamente cuando el formulario tiene un campo vacío. ¿Qué principio de diseño de workflows se violó?
   **Guía de solución**: Manejo de excepciones/casos borde: el flujo debería validar campos obligatorios y notificar el error en lugar de fallar sin aviso.

### Módulo 4-5 (chatbots, marketing, seguridad, KPIs)

6. **Caso**: El chatbot de una tienda responde bien preguntas sobre horario y ubicación, pero cuando le preguntan "¿dónde está mi pedido #4521?" no sabe responder. ¿Qué le falta al diseño del chatbot?
   **Guía de solución**: Falta un intent específico de "estado de pedido" integrado con el sistema de pedidos (vía API/integración), no solo respuestas genéricas preprogramadas.

7. **Caso**: Una campaña de marketing automatizada envía el mismo correo promocional a todos los clientes, incluyendo a quienes ya compraron ese producto la semana pasada. ¿Qué falta aplicar?
   **Guía de solución**: Segmentación de audiencia (excluir compradores recientes del mismo producto) y personalización básica.

8. **Caso**: Un proyecto estudiantil usa datos reales de clientes de una pyme (nombres y números de teléfono) en las capturas de pantalla del proyecto entregado sin anonimizar. ¿Qué política del curso se está incumpliendo?
   **Guía de solución**: La prohibición de usar datos reales de clientes/terceros sin anonimizar (ver `05-Reglas-del-juego-politicas-aula.md`), con implicaciones de cumplimiento normativo (Ley 81 de 2019).

9. **Caso**: Un equipo define como único KPI de su proyecto "número de automatizaciones creadas". ¿Es un buen KPI de negocio?
   **Guía de solución**: No necesariamente — un buen KPI debe medir impacto de negocio (ej. tiempo de respuesta, tasa de conversión, reducción de errores), no solo el esfuerzo técnico invertido.

---

## 4. Plantillas rápidas de "ticket de salida" (exit ticket) genéricas

1. "Explica el concepto de hoy en una sola oración, como si se lo explicaras al dueño de una pyme sin conocimientos técnicos."
2. "¿Qué fue lo más confuso de la sesión de hoy?"
3. "¿Cómo aplicarían lo visto hoy al proceso de negocio de su proyecto integrador?"

---

*Documento elaborado para el semestre 2026-2. Complementa el conjunto de documentos del Plan 2026-2 de Automatización de Procesos de Negocios (INF 320). Docente: Angel R. Avila G. — angel.avila@up.ac.pa.*
