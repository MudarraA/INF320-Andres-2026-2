# INF 320 — Automatización de Procesos de Negocios · Semestre 2026-2

**Universidad de Panamá — Facultad de Informática, Electrónica y Comunicación**  
**Licenciatura en Comercio Electrónico**  
**Docente:** Angel R. Avila G. · angel.avila@up.ac.pa

---

## Bienvenida

Este repositorio es la **plantilla** del curso, privada. En la semana 1 el docente crea tu propia
copia privada y te agrega como colaborador (instrucciones abajo, en "Herramientas del curso") — ahí
trabajas todo el semestre: laboratorios, avances del proyecto integrador, diagramas BPMN y
documentación asociada.

> **Regla de oro**: ninguna entrega se acepta por correo electrónico. Todo va en este repositorio, organizado en la carpeta correcta, antes de la fecha límite.

---

## Estructura del repositorio

```
INF320-Automatizacion-Procesos-Negocios-2026-2/   (plantilla — 1 copia por estudiante, ver "Herramientas del curso")
├── syllabus/               → Syllabus oficial del curso (créditos, evaluación, bibliografía)
├── politicas/              → Reglas del aula, política de IA, integridad académica
├── recursos/               → Guía de herramientas (Zapier, Make, Bizagi…) y referencias
├── docker/                 → n8n autoalojado, opcional/avanzado
├── docente/                → Material de planificación del docente (syllabus fuente, plan de 15 semanas,
│                              rúbricas, guion de clase semana a semana, guía de entregas por GitHub)
├── .github/workflows/      → Checklist automático de entregas (informativo)
├── modulo-1-introduccion-bpa/
│   ├── semana-01/          → Presentación + panorama BPA 2026
│   └── semana-02/          → BPA en e-commerce y diferencia con BPR
├── modulo-2-mapeo-procesos/
│   ├── semana-03/          → BPMN + Kickoff del proyecto integrador
│   ├── semana-04/          → Técnicas de análisis de procesos
│   └── semana-05/          → Oportunidades de automatización + CHECKPOINT 1
├── modulo-3-herramientas-bpm-rpa/
│   ├── semana-06/          → BPM vs. RPA + PARCIAL 1
│   ├── semana-07/          → Plataformas RPA y alternativas no-code/IA
│   ├── semana-08/          → Integración con sistemas de comercio electrónico
│   └── semana-09/          → Taller integrador + CHECKPOINT 2
├── modulo-4-chatbots-workflows/
│   ├── semana-10/          → Principios de diseño de workflows automatizados
│   ├── semana-11/          → Casos de uso en e-commerce + PARCIAL 2
│   └── semana-12/          → Pedidos/inventario + Chatbot + CHECKPOINT 3
├── modulo-5-seguridad-monitoreo/
│   ├── semana-13/          → Marketing automation y CRM
│   ├── semana-14/          → Chatbots avanzados + Seguridad + KPIs
│   └── semana-15/          → EXAMEN SEMESTRAL + Demo final
└── examenes/               → Guías de estudio para parciales y examen semestral
```

> **El proyecto integrador vive en un repositorio aparte:** [`INF320-Proyecto-Integrador-2026-2`](../INF320-Proyecto-Integrador-2026-2/) — trabajo individual (este repo, una copia por estudiante) y trabajo en equipo (el proyecto, una copia por equipo de 4-5) se mantienen separados a propósito. El equipo crea su copia del repo de proyecto en la semana 3, tras el kickoff. Ver `docente/GUIA-ENTREGAS-GITHUB.md` para el paso a paso.

---

## Calendario de hitos y evaluaciones

| Semana | Fecha aprox. | Evento principal | Rubro |
|--------|-------------|-----------------|-------|
| 1  | ago 2026 | Reporte caso real BPA | Asignación/participación |
| 2  | ago 2026 | Quiz 1 + taller de casos | Quiz + participación |
| 3  | ago 2026 | Lab 1: BPMN AS-IS · **Kickoff proyecto integrador** | Lab / Proyecto |
| 4  | ago 2026 | Lab 2: análisis del proceso · Quiz | Lab / Quiz |
| **5**  | sep 2026 | **Checkpoint 1 del proyecto** | Proyecto integrador |
| **6**  | sep 2026 | **Examen Parcial 1** (Módulos 1 y 2) | 15% |
| 7  | sep 2026 | Lab 3: primer flujo no-code · Quiz | Lab / Quiz |
| 8  | sep 2026 | Lab 4: integración de servicios | Lab |
| **9**  | oct 2026 | **Checkpoint 2 del proyecto** | Proyecto integrador |
| 10 | oct 2026 | Lab 5: workflow con excepciones | Lab |
| **11** | oct 2026 | **Examen Parcial 2** (Módulo 3 + avance M4) | 15% |
| **12** | oct 2026 | **Checkpoint 3 del proyecto** (chatbot) | Proyecto integrador |
| 13 | nov 2026 | Lab 6: marketing automation · Quiz | Lab / Quiz |
| 14 | nov 2026 | Lab 7: KPIs y seguridad · Quiz | Lab / Quiz |
| **15** | nov 2026 | **Examen Semestral** · **Demo final** · Coevaluación | 35% / Proyecto |

---

## Sistema de evaluación

| Rubro | Porcentaje |
|-------|-----------|
| Trabajo en Grupo (Asignaciones, Labs, Quices) | 35% |
| Exámenes Parciales (2 × 15%) | 30% |
| Examen Semestral | 35% |
| **Total** | **100%** |

**Nota mínima de aprobación: 71%**

El proyecto integrador se califica dentro del rubro "Trabajo en Grupo" como asignación grupal. Ver detalle de pesos por checkpoint en `../INF320-Proyecto-Integrador-2026-2/README.md`.

---

## Proyecto integrador — resumen rápido

El proyecto integrador corre todo el semestre y tiene **4 entregables evaluados**:

| Entregable | Semana | Peso en el proyecto |
|-----------|--------|-------------------|
| Checkpoint 1: BPMN AS-IS + oportunidades | 5 | 15% |
| Checkpoint 2: prototipo de automatización funcional | 9 | 25% |
| Checkpoint 3: chatbot/asistente virtual básico | 12 | 25% |
| Demo final: proyecto completo + presentación | 15 | 35% |

Equipos de 4-5 integrantes. Elección de negocio (real o simulado) en la semana 3. Especificación completa en `../INF320-Proyecto-Integrador-2026-2/README.md`.

---

## Reglas para usar este repositorio

1. **Commits frecuentes y descriptivos.** Registra tu progreso real, no solo subas en el último minuto.
2. **Organiza tus archivos en la carpeta correcta.** Cada entregable tiene su carpeta asignada.
3. **Declara el uso de IA en todo entregable.** Lee la política en `politicas/politica-ia.md`.
4. **En el proyecto grupal, todos los integrantes deben hacer commits.** El historial de Git es evidencia de participación.
5. **Nombra tus diagramas con el formato:** `semanaXX-bpmn-as-is-v1.png` (descriptivo + versión).

---

## Horario de clases

| Sesión | Día | Hora |
|--------|-----|------|
| Teoría | Martes | 6:55 p.m. – 8:40 p.m. |
| Laboratorio / Práctica | Jueves | 5:05 p.m. – 6:50 p.m. |

---

## Herramientas del curso (crea tus cuentas en la semana 1)

| Categoría | Herramienta | Plan |
|-----------|------------|------|
| Modelado BPMN | Bizagi Modeler / draw.io | Gratuito |
| Automatización no-code | Zapier / Make / n8n | Gratuito / Community |
| Automatización no-code | Microsoft Power Automate | Educativo |
| RPA clásico (referencia) | UiPath Community Edition | Gratuito |
| Chatbots | Voiceflow / Landbot / Dialogflow CX | Gratuito |
| Marketing automation | HubSpot / Mailchimp | Gratuito |
| Dashboards KPI | Looker Studio / Power BI | Gratuito |
| Control de versiones | Git + GitHub | — |

Guía de configuración de cuentas: [`recursos/herramientas-setup.md`](recursos/herramientas-setup.md)

### Cómo obtienes tu copia del repositorio

Este repositorio es la **plantilla del docente** — es privada, así que no puedes verla ni copiarla tú
mismo. En la semana 1, después de que respondas con tu usuario de GitHub en Google Classroom, el
docente crea **tu propia copia privada** y te agrega como colaborador. GitHub te manda un correo de
invitación automáticamente — acéptala, clona tu copia (nunca la plantilla del docente) y trabaja como
siempre: `git clone`, `git add`, `git commit`, `git push`.

**Alternativa opcional/avanzada:** si prefieres un n8n local sin límite de ejecuciones en vez del plan cloud gratuito, el repo incluye un stack Docker listo en [`docker/`](docker/) (n8n + PostgreSQL). No es obligatorio — ver [`docker/README.md`](docker/README.md).

---

## Contacto

- **Correo:** angel.avila@up.ac.pa
- **Horario de atención:** (ver aula virtual)
- **Plataforma oficial:** Aula virtual institucional de la FIEC-UP
