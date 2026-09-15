# Exámenes Parciales, Examen Semestral y Proyecto Integrador — INF 320

**Semestre 2026-2**

## 1. Examen Parcial 1

| Campo | Detalle |
|---|---|
| Semana | 6 |
| Ponderación | 15% de la nota final |
| Alcance temático | Módulo 1 completo (definición y beneficios de BPA; automatización en el comercio electrónico; diferencia entre automatización de procesos y reingeniería de procesos/BPR) y Módulo 2 completo (mapeo y modelado de procesos con diagramas de flujo y BPMN; herramientas y técnicas de análisis de procesos; identificación de oportunidades de automatización). |
| Duración sugerida | 90 minutos |

**Formato del examen**

| Sección | Peso | Descripción |
|---|---|---|
| Teoría conceptual (opción múltiple, verdadero/falso, definiciones cortas) | 40% | Conceptos de BPA, beneficios, diferencia con BPR, técnicas de análisis de procesos, criterios de priorización. |
| Caso práctico / BPMN | 45% | A partir de la descripción textual de un proceso de negocio de comercio electrónico, el estudiante debe: (a) elaborar o corregir un diagrama BPMN AS-IS, (b) identificar al menos dos oportunidades de automatización aplicando los criterios de priorización vistos en clase. |
| Preguntas de análisis/argumentación | 15% | Pregunta de desarrollo corto donde se argumenta si un caso dado constituye automatización de procesos o reingeniería (BPR), justificando la respuesta. |

**Modalidad**: examen presencial, individual, sin uso de dispositivos electrónicos ni asistentes de IA (ver política de IA en `05-Reglas-del-juego-politicas-aula.md`).

---

## 2. Examen Parcial 2

| Campo | Detalle |
|---|---|
| Semana | 11 |
| Ponderación | 15% de la nota final |
| Alcance temático | Módulo 3 completo (BPM vs. RPA: definiciones y diferencias; principales plataformas RPA y alternativas no-code/IA; integración de tecnologías de automatización con sistemas de comercio electrónico) y avance del Módulo 4 (principios de diseño de procesos automatizados; creación de workflows automatizados). |
| Duración sugerida | 90 minutos |

**Formato del examen**

| Sección | Peso | Descripción |
|---|---|---|
| Teoría conceptual | 30% | Definiciones y diferencias BPM/RPA, conceptos de API/webhook/conector, principios de diseño de workflows. |
| Preguntas sobre plataformas y herramientas | 30% | Identificación y comparación de plataformas: RPA clásico (UiPath, Blue Prism, Automation Anywhere) vs. no-code/IA (Zapier, Make, Power Automate, n8n); criterios de selección según caso de uso. |
| Caso práctico | 40% | A partir de un escenario de integración de sistemas de comercio electrónico (por ejemplo, tienda en línea + inventario + notificaciones), el estudiante diseña conceptualmente un workflow automatizado, indicando la herramienta más adecuada, los pasos del flujo y el manejo de al menos una excepción. |

**Modalidad**: examen presencial, individual, sin uso de dispositivos electrónicos ni asistentes de IA.

---

## 3. Examen Semestral

| Campo | Detalle |
|---|---|
| Semana | 15 |
| Ponderación | 35% de la nota final |
| Alcance temático | Integral: los cinco módulos del curso. |
| Duración sugerida | 120 minutos |

**Formato del examen**

| Sección | Peso | Descripción |
|---|---|---|
| Teoría conceptual (todos los módulos) | 30% | Preguntas de opción múltiple, verdadero/falso y definiciones cortas que abarcan los cinco módulos, con énfasis en los contenidos no cubiertos en los parciales (módulos 4 y 5: casos de uso de e-commerce, chatbots/asistentes virtuales, marketing automation, seguridad/gobernanza, Kaizen/Six Sigma/KPIs). |
| Caso práctico integral (BPMN + automatización) | 35% | Caso extendido de un negocio de comercio electrónico: el estudiante mapea o corrige un proceso BPMN, propone su automatización (herramienta y lógica del flujo) y plantea un componente de chatbot/IA aplicable. |
| Plataformas, herramientas y tendencias | 20% | Preguntas sobre plataformas RPA/no-code/BPMN/chatbot/marketing automation/monitoreo vistas en el curso, y sobre tendencias (IA, minería de procesos asistida por IA, automatización inteligente). |
| Seguridad, gobernanza y mejora continua | 15% | Preguntas sobre GDPR, CCPA, Ley 81 de 2019 (Panamá), Kaizen, Six Sigma y definición de KPIs de monitoreo. |

**Modalidad**: examen presencial, individual, sin uso de dispositivos electrónicos ni asistentes de IA.

---

## 4. Proyecto Integrador: "Automatización de un Proceso de Negocio de Comercio Electrónico"

### 4.1 Descripción general

El proyecto integrador articula, a lo largo de las 15 semanas, la aplicación práctica de todos los módulos del curso sobre un mismo caso. Los equipos (4-5 integrantes, conformados en la semana 3) eligen una **pyme real** (con anuencia del propietario para efectos de levantamiento de información, sin exponer datos sensibles reales) o un **negocio simulado de comercio electrónico** creado por el propio equipo con fines académicos.

Cada equipo debe:

1. Mapear un **proceso AS-IS** (tal como es hoy) del negocio elegido, usando diagramas de flujo/BPMN.
2. Rediseñar el proceso como **TO-BE** (cómo debería ser) aplicando principios de automatización.
3. Implementar una **automatización real y funcional** de al menos una parte significativa del proceso, utilizando al menos una herramienta RPA/no-code (UiPath, Blue Prism, Automation Anywhere, Zapier, Make, Power Automate o n8n).
4. Incorporar un **componente de IA o chatbot** (Dialogflow CX, Voiceflow, Landbot, o integración directa con la API de un LLM como Claude o GPT) aplicado a atención al cliente, recomendaciones o soporte del proceso automatizado.
5. Definir **KPIs de monitoreo** del proceso automatizado y presentarlos en un tablero (Looker Studio o Power BI).
6. Abordar explícitamente **consideraciones de seguridad y cumplimiento normativo** (protección de datos personales, anonimización de datos usados en los laboratorios, referencia a GDPR/CCPA/Ley 81 de 2019 según corresponda).

### 4.2 Cronograma de hitos

| Hito | Semana | Entregable | Ponderación sugerida sobre la nota del proyecto |
|---|---|---|---|
| Kickoff | 3 | Conformación de equipos, elección de negocio/proceso (ficha de 1 página) | No calificado formalmente / insumo de checkpoint 1 |
| **Checkpoint 1** | 5 | Mapeo BPMN AS-IS + oportunidades de automatización identificadas y priorizadas | 15% |
| **Checkpoint 2** | 9 | Prototipo de automatización funcional (al menos una integración real operando) | 25% |
| **Checkpoint 3** | 12 | Chatbot/asistente virtual básico funcional, articulado con el flujo de automatización | 25% |
| **Entrega y demo final** | 15 | Proyecto completo: TO-BE, automatización, chatbot/IA, tablero de KPIs, checklist de seguridad/cumplimiento, presentación/demo en vivo | 35% |
| **Total** | | | 100% de la nota del proyecto |

La nota del proyecto integrador se registra dentro del rubro de **Asignaciones grupales**, componente del **35% de Trabajo en Grupo** (ver `03-Sistema-evaluacion-rubricas.md`).

### 4.3 Entregable final (semana 15)

El entregable final debe incluir, como mínimo:

- Documento o presentación con el diagrama BPMN AS-IS y TO-BE del proceso.
- Evidencia funcional de la automatización implementada (acceso a la herramienta, video corto de respaldo o demo en vivo).
- Evidencia funcional del chatbot/componente de IA (demo en vivo o video corto de respaldo).
- Tablero de KPIs con al menos 4 indicadores relevantes al proceso.
- Checklist o sección de seguridad/cumplimiento normativo (datos personales anonimizados, referencia a la normativa aplicable).
- Presentación de máximo 10-12 minutos por equipo el día de la demo final, seguida de preguntas del profesor y del curso.

### 4.4 Rúbrica de evaluación del proyecto integrador (entrega final y demo)

Escala de 0 a 100 puntos, aplicada sobre el 35% correspondiente a la entrega y demo final (los checkpoints 1, 2 y 3 se evalúan con la rúbrica de asignaciones grupales de `03-Sistema-evaluacion-rubricas.md`, contextualizada a cada entregable específico).

| Criterio | Peso | Excelente (100-90%) | Bueno (89-75%) | Suficiente (74-60%) | Insuficiente (< 60%) |
|---|---|---|---|---|---|
| **Calidad del mapeo de procesos (AS-IS/TO-BE)** | 20% | Diagramas BPMN correctos, completos y bien justificados; el TO-BE resuelve claramente las oportunidades identificadas. | Diagramas correctos con imprecisiones menores de notación. | Diagramas incompletos o con errores de notación que dificultan su comprensión. | Diagramas ausentes, incorrectos o inconsistentes con el proceso descrito. |
| **Funcionalidad de la automatización implementada** | 20% | La automatización funciona de extremo a extremo, de forma robusta, con manejo de al menos una excepción. | Funciona en su mayoría, con fallas menores o manejo parcial de excepciones. | Funciona parcialmente o solo en un flujo muy acotado. | No funciona o es meramente conceptual/simulada sin evidencia real. |
| **Integración del componente de IA/chatbot** | 20% | El chatbot responde correctamente a los escenarios de prueba, está bien integrado (conceptual o técnicamente) al proceso automatizado y agrega valor real al negocio. | Chatbot funcional con respuestas adecuadas en la mayoría de los casos; integración parcial con el proceso. | Chatbot con funcionalidad muy limitada o poco relacionado con el proceso del proyecto. | Chatbot ausente, no funcional o irrelevante al caso. |
| **Definición de KPIs** | 15% | KPIs relevantes, medibles, bien definidos (fórmula, fuente de datos, meta) y visualizados en un tablero claro. | KPIs relevantes pero con definición incompleta (falta fórmula, meta o fuente). | KPIs genéricos o poco relacionados con el proceso específico. | KPIs ausentes o sin ninguna visualización. |
| **Consideraciones de seguridad y cumplimiento normativo** | 10% | Aborda explícitamente la protección de datos personales, anonimización y normativa aplicable (GDPR/CCPA/Ley 81 de 2019), con medidas concretas adoptadas en el proyecto. | Aborda el tema de forma general, con alguna medida concreta. | Menciona el tema superficialmente sin medidas concretas. | No aborda seguridad ni cumplimiento normativo. |
| **Trabajo en equipo** | 10% | Evidencia de reparto equitativo de tareas, coordinación efectiva y coevaluación de pares consistente con el desempeño observado. | Trabajo en equipo mayormente equitativo, con desbalances menores. | Desbalances notorios en la participación de los integrantes. | Evidencia de que el trabajo fue realizado por una minoría del equipo. |
| **Calidad de la presentación/demo** | 5% | Presentación clara, profesional, dentro del tiempo, con demo en vivo fluida y respuestas sólidas a las preguntas. | Presentación clara con demo funcional, con imprevistos menores resueltos adecuadamente. | Presentación desordenada o demo con fallas que afectan la comprensión. | Presentación deficiente, sin demo funcional o fuera de tiempo de forma significativa. |

### 4.5 Coevaluación de pares

En la semana 15, cada integrante completa un formulario individual de coevaluación de pares (criterios: cumplimiento de tareas asignadas, puntualidad, calidad del aporte, comunicación con el equipo). El profesor puede usar los resultados agregados para ajustar la nota individual dentro de la nota grupal del proyecto, conforme al procedimiento descrito en `05-Reglas-del-juego-politicas-aula.md`.
