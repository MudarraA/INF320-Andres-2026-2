# Syllabus Actualizado — INF 320 Automatización de Procesos de Negocios

**Universidad de Panamá — Facultad de Informática, Electrónica y Comunicación**
**Semestre 2026-2**

## 1. Datos generales

| Campo | Detalle |
|---|---|
| Denominación de la asignatura | AUTOMATIZACIÓN DE PROCESOS DE NEGOCIOS |
| Código | INF 320 |
| Carrera | Licenciatura en Comercio Electrónico |
| Ubicación en el plan | II Semestre del III año |
| Créditos | 3 |
| Horas totales | 4 horas semanales (2 teóricas + 2 prácticas) — 60 horas en 15 semanas |
| Horario de clases | Teoría: martes, 6:55 p.m. – 8:40 p.m. · Laboratorio: jueves, 5:05 p.m. – 6:50 p.m. |
| Prerrequisitos | INF 221, INF 312 |
| Período académico | Semestre 2026-2 (15 semanas) |
| Modalidad | Presencial, con apoyo de plataformas digitales y herramientas de IA generativa |

## 2. Justificación de la asignatura

La automatización de procesos de negocios (BPA, por sus siglas en inglés) se ha convertido en una competencia central para cualquier profesional del comercio electrónico. Entre 2018 y 2024 el mercado consolidó plataformas de RPA (Robotic Process Automation) como UiPath, Blue Prism y Automation Anywhere; sin embargo, el panorama de 2026 exige ir más allá: la convergencia entre automatización no-code/low-code (Zapier, Make/Integromat, Microsoft Power Automate, n8n) y la inteligencia artificial generativa ha reducido drásticamente la barrera técnica para diseñar, implementar y mantener procesos automatizados, permitiendo que analistas de negocio —no solo programadores— construyan soluciones robustas.

Para un egresado de Comercio Electrónico, dominar estas herramientas ya no es opcional: la demanda laboral en Panamá y la región muestra un crecimiento sostenido de puestos relacionados con automatización de marketing, atención al cliente asistida por chatbots/LLMs, integración de sistemas de venta en línea y análisis de KPIs en tiempo real. Asimismo, la irrupción de modelos de lenguaje de gran escala (LLM) como motor de chatbots y asistentes virtuales obliga a actualizar los contenidos clásicos de BPM/RPA con un enfoque híbrido: procesos bien mapeados (BPMN), automatizados con la herramienta adecuada (RPA clásico o no-code/IA) y potenciados con componentes de IA conversacional, sin descuidar la seguridad, la gobernanza de datos y el cumplimiento normativo (GDPR, CCPA y, en el contexto panameño, la Ley 81 de 2019 de Protección de Datos Personales).

Este curso conserva íntegramente la síntesis modular y los contenidos oficiales del programa aprobado, y actualiza el instrumental tecnológico y los ejemplos de aplicación al panorama 2026, manteniendo la coherencia con el perfil de egreso de la Licenciatura en Comercio Electrónico.

## 3. Competencias

### 3.1 Competencias genéricas

- Capacidad de análisis y síntesis para comprender procesos de negocio complejos.
- Capacidad de trabajo en equipo y gestión de proyectos con entregables por hitos.
- Habilidad para aprender de forma autónoma y adaptarse a nuevas herramientas tecnológicas.
- Comunicación oral y escrita efectiva para presentar soluciones técnicas a audiencias no técnicas.
- Compromiso ético y responsabilidad en el manejo de datos e información de terceros.
- Pensamiento crítico frente a la adopción de inteligencia artificial en procesos de negocio.

### 3.2 Competencias específicas

- Analizar y modelar procesos de negocio de comercio electrónico utilizando diagramas de flujo y notación BPMN.
- Identificar oportunidades de automatización con criterios de priorización (volumen, repetitividad, reglas claras, valor generado).
- Distinguir y aplicar conceptos de BPM y RPA, seleccionando la plataforma adecuada (clásica o no-code/IA) según el caso de uso.
- Diseñar e implementar workflows automatizados funcionales que integren sistemas de comercio electrónico mediante APIs, webhooks y conectores.
- Implementar chatbots y asistentes virtuales básicos con herramientas de IA conversacional aplicados a atención al cliente y recomendaciones.
- Aplicar herramientas de automatización de marketing y ventas (CRM, captación y segmentación de leads).
- Definir indicadores clave de desempeño (KPI) y aplicar principios de mejora continua (Kaizen, Six Sigma) al monitoreo de procesos automatizados.
- Incorporar consideraciones de seguridad, gobernanza y cumplimiento normativo en el diseño de soluciones automatizadas.

## 4. Actualización 2026: decisión de modernización del instrumental tecnológico

El programa sintético oficial referencia herramientas consolidadas entre 2018 y 2024 (UiPath, Blue Prism, Automation Anywhere, HubSpot, Marketo, Mailchimp, Dialogflow, Microsoft Bot Framework). Sin alterar el contenido oficial, este syllabus incorpora el panorama tecnológico 2026 como material didáctico complementario y como stack recomendado para las prácticas de laboratorio, dado que ofrece planes gratuitos o educativos, menor curva de aprendizaje y mayor pertinencia para el perfil de un analista de comercio electrónico (no necesariamente programador):

- **RPA clásico** (contenido oficial, se mantiene): UiPath, Blue Prism, Automation Anywhere.
- **No-code/low-code de automatización con IA** (incorporación 2026): Zapier, Make (antes Integromat), Microsoft Power Automate, n8n.
- **Modelado BPMN accesible** (incorporación 2026): Bizagi Modeler, Lucidchart, draw.io/diagrams.net, Miro.
- **Chatbots y asistentes virtuales con LLM** (actualización del contenido oficial de Dialogflow/Bot Framework): Voiceflow, Landbot, Dialogflow CX, e integraciones directas con APIs de modelos de lenguaje (Claude, GPT).
- **Automatización de marketing** (contenido oficial, con foco en planes gratuitos/educativos): HubSpot, Mailchimp, ActiveCampaign.
- **Monitoreo y KPI**: Looker Studio, Power BI.
- **Tendencia emergente**: minería de procesos asistida por IA (*AI-augmented process mining*) para el descubrimiento automático de procesos a partir de registros de eventos (*event logs*), mencionada como panorama de futuro dentro del Módulo 5.

Esta actualización se limita al instrumental tecnológico y a los ejemplos de aplicación; la síntesis modular, los contenidos oficiales y el sistema de evaluación se mantienen conforme al programa aprobado.

## 5. Síntesis modular oficial

| Módulo | Título | Horas | Semanas |
|---|---|---|---|
| 1 | Introducción a la automatización y análisis de procesos de negocios | 8 | 2 |
| 2 | Herramientas, diseño e implementación de procesos automatizados de negocios | 12 | 3 |
| 3 | Automatización de marketing y ventas en la cadena de suministro y logística | 15 | 4 |
| 4 | Implementación de chatbots y asistentes virtuales en los procesos de negocios | 15 | 3 |
| 5 | Seguridad, monitoreo y optimización continua de los procesos de negocios | 10 | 3 |
| **Total** | | **60** | **15** |

## 6. Contenidos oficiales por módulo

### Módulo 1 — Introducción a la automatización y análisis de procesos de negocios
- Definición y beneficios de la automatización de procesos de negocios (BPA).
- Importancia de la automatización en el comercio electrónico: competitividad y satisfacción del cliente.
- Diferencia entre automatización de procesos y reingeniería de procesos de negocio (BPR).

### Módulo 2 — Herramientas, diseño e implementación de procesos automatizados de negocios
- Mapeo y modelado de procesos de negocio: diagramas de flujo y BPMN.
- Herramientas y técnicas de análisis de procesos.
- Identificación de oportunidades de automatización.

### Módulo 3 — Automatización de marketing y ventas en la cadena de suministro y logística
> *Nota:* el título de este módulo se conserva tal cual aparece en el programa sintético oficial. En el plan de trabajo de 15 semanas (`02-Plan-trabajo-15-semanas.md`) y en el repositorio del curso, el contenido de BPM/RPA se dicta en las semanas 6-9, y el contenido específico de automatización de marketing se dicta en el Módulo 5 (semana 13), para alinear la secuencia pedagógica con la del Módulo 4 (chatbots).
- Introducción a herramientas BPM y RPA: definición y diferencias.
- Principales plataformas de RPA (UiPath, Blue Prism, Automation Anywhere) y su panorama ampliado no-code/IA.
- Integración de tecnologías de automatización con sistemas de comercio electrónico.

### Módulo 4 — Implementación de chatbots y asistentes virtuales en los procesos de negocios
- Principios de diseño de procesos automatizados.
- Creación de workflows automatizados.
- Casos de uso en comercio electrónico: gestión de pedidos, procesamiento de pagos, gestión de inventarios.

### Módulo 5 — Seguridad, monitoreo y optimización continua de los procesos de negocios
- Automatización de marketing y ventas (HubSpot, Marketo, Mailchimp); CRM y captación de leads; personalización y segmentación.
- Implementación de chatbots y asistentes virtuales (Dialogflow, Microsoft Bot Framework); atención al cliente y recomendaciones.
- Tendencias y futuro: inteligencia artificial, aprendizaje automático, automatización inteligente y minería de procesos asistida por IA.
- Seguridad y gobernanza: GDPR, CCPA y normativa panameña de protección de datos (Ley 81 de 2019).
- Monitoreo y optimización continua: Kaizen, Six Sigma, indicadores clave de desempeño (KPI).

## 7. Metodología

El curso se desarrolla bajo un enfoque **andragógico, activo y basado en proyectos reales de comercio electrónico** (Project-Based Learning), articulado alrededor de un **proyecto integrador** que atraviesa todo el semestre (ver `04-Examenes-parciales-y-proyecto-final.md`). Se combinan:

- **Clases teóricas** (2 horas/semana): exposición dialogada, estudio de casos, discusión guiada y análisis de lecturas.
- **Laboratorios prácticos** (2 horas/semana): trabajo directo con herramientas BPMN, RPA, no-code/IA, chatbots y marketing automation, en equipos.
- **Aprendizaje basado en proyectos**: equipos de trabajo eligen una pyme o negocio simulado de comercio electrónico y aplican, de forma incremental, cada módulo del curso al mismo proceso de negocio, con checkpoints evaluables en las semanas 5, 9 y 12, y demo final en la semana 15.
- **Uso responsable de IA generativa**: se fomenta el uso de asistentes de IA como apoyo al aprendizaje y al desarrollo del proyecto, con declaración explícita de uso (ver política de IA en `05-Reglas-del-juego-politicas-aula.md`).
- **Evaluación auténtica**: quices, laboratorios, asignaciones grupales, parciales y examen semestral, complementados con coevaluación entre pares en el proyecto final.

## 8. Recursos

### 8.1 Recursos tecnológicos (actualizados a 2026)

RPA: UiPath, Blue Prism, Automation Anywhere. No-code/IA: Zapier, Make, Microsoft Power Automate, n8n. Modelado BPMN: Bizagi Modeler, Lucidchart, draw.io/diagrams.net, Miro. Chatbots/LLM: Voiceflow, Landbot, Dialogflow CX, APIs de Claude/GPT. Marketing automation: HubSpot, Mailchimp, ActiveCampaign. Monitoreo/KPI: Looker Studio, Power BI. (Detalle completo con uso pedagógico en `06-Herramientas-recursos-IA.md`.)

### 8.2 Recursos institucionales

Aula de clase con proyector y conexión a internet, laboratorio de cómputo de la Facultad de Informática, Electrónica y Comunicación, plataforma virtual institucional para materiales y entregas, cuentas educativas/gratuitas de las herramientas listadas en la sección 8.1.

### 8.3 Bibliografía

**Textos base**

- Aladro, E. & Díaz-Chao, Á. (2022). *Automatización de procesos de negocio: Guía práctica para la implementación de soluciones BPM*. Esic Editorial.
- Artola, R. & Martínez, S. (2021). *Automatización de procesos de negocio con BPMN 2.0*. Bubok Publishing.
- Everest, G. & Van der Aalst, W. (2023). *Business Process Management: A theory and practice perspective*. Springer Nature.
- Jeston, J. & Nellore, R. (2024). *Business Process Management: A practical guide to improving efficiency and effectiveness*. Pearson.
- Vom Brocke, J. & Rosemann, M. (2023). *Handbook of Process Modeling*. Springer Nature.

**Artículos académicos**

- Abeysekera, A. & Dwivedi, Y. (2023).
- Al-Dawaileh, A. et al. (2022).
- Hagemann, S. & Fettke, P. (2024).
- La Rosa, M. & Rago, A. (2022).
- Papathanasiou, K. & Van der Aalst, W. (2023).

**Recursos en línea**

- ProcessMaker (blog oficial sobre BPM/automatización).
- BPM Institute.
- IDC.
- McKinsey & Company.

(Ver bibliografía completa y recursos complementarios actualizados en `06-Herramientas-recursos-IA.md`.)

## 9. Sistema de evaluación (oficial)

| Componente | Ponderación |
|---|---|
| Trabajo en Grupo (Asignaciones, Laboratorios, Quices) | 35% |
| Exámenes Parciales (2, 15% cada uno) | 30% |
| Examen Semestral | 35% |
| **Total** | **100%** |

**Nota mínima de aprobación**: conforme a los artículos 280-283 del Estatuto de la Universidad de Panamá, se toma como referencia institucional estándar una calificación mínima de **71%** para aprobar la asignatura. Esta cifra se indica como referencia general del Estatuto, ya que el documento fuente del programa no la repite explícitamente para este curso en particular; el profesor debe verificar la vigencia de este umbral con la Secretaría Académica de la Facultad al inicio del semestre.

Detalle completo de rúbricas en `03-Sistema-evaluacion-rubricas.md`. Especificación de parciales, examen semestral y proyecto integrador en `04-Examenes-parciales-y-proyecto-final.md`.

## 10. Datos del docente

| Campo | Detalle |
|---|---|
| Docente | Angel R. Avila G. |
| Correo institucional | angel.avila@up.ac.pa |
| Horario de atención | (completar) |
| Sección / grupo | (completar) |

## 11. Vigencia

Syllabus elaborado para el semestre **2026-2** (15 semanas), sobre la base del programa sintético oficial de INF 320 de la Licenciatura en Comercio Electrónico, Facultad de Informática, Electrónica y Comunicación, Universidad de Panamá.
