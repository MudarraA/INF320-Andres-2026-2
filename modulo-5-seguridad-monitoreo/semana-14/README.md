# Semana 14 — Seguridad, Gobernanza, Tendencias y KPIs

**Módulo 5: Seguridad, monitoreo y optimización continua — continuación**

---

## Objetivos de aprendizaje

- Aplicar principios de seguridad, gobernanza y cumplimiento normativo (GDPR, CCPA, Ley 81 de 2019 de Panamá).
- Definir KPIs relevantes al proceso automatizado y construir un tablero de visualización básico.
- Reconocer tendencias: IA generativa en BPA, minería de procesos asistida por IA.

---

## Contenidos de la semana

### Teoría (martes)

1. Seguridad y gobernanza en automatización:
   - **GDPR** (UE) y **CCPA** (California): principios de protección de datos personales
   - **Ley 81 de 2019 (Panamá)**: protección de datos personales en el contexto local
   - Principios clave: consentimiento, minimización de datos, derecho al olvido, notificación de brechas
   - Aplicación práctica: ¿tu proyecto usa datos personales? ¿cómo los proteges?
2. Monitoreo y optimización continua:
   - **Kaizen**: mejora continua incremental
   - **Six Sigma**: reducción de variabilidad y defectos (DMAIC: Define, Measure, Analyze, Improve, Control)
   - **KPIs**: indicadores clave de desempeño — deben ser medibles, relevantes y monitoreables
3. Tendencias emergentes:
   - IA generativa en BPA: automatización de tareas cognitivas, redacción, análisis
   - Minería de procesos asistida por IA: descubrimiento automático de procesos desde event logs

### Práctica/Laboratorio (jueves)

**Lab 7** (en equipos):
1. Definir el tablero de KPIs del proyecto integrador (mínimo 4 indicadores)
2. Construir la visualización en Looker Studio o Power BI
3. Revisar la checklist de seguridad/cumplimiento del proyecto

---

## Entregable de la semana

**Laboratorio 7** — Tablero de KPIs y checklist de seguridad

- Sube: captura del tablero + link público (si aplica) + checklist completada
- Archivo: `modulo-5-seguridad-monitoreo/semana-14/lab07-kpis-seguridad/README.md`

**Quiz** (en clase) — seguridad, gobernanza y mejora continua

---

## Marco de KPIs para el proyecto integrador

Define al menos 4 KPIs usando este formato:

| KPI | Fórmula | Fuente de datos | Meta | Frecuencia |
|-----|---------|----------------|------|-----------|
| Tiempo de procesamiento de pedido | (Hora de envío - Hora de pedido) en horas | Sistema de pedidos | < 2 horas | Por pedido |
| Tasa de error en automatización | (Ejecuciones fallidas / Total) × 100 | Logs de Zapier/Make | < 1% | Semanal |
| Satisfacción del cliente | Promedio de respuestas CSAT | Encuesta post-compra | > 4/5 | Mensual |
| (Tu KPI 4) | | | | |

---

## Checklist de seguridad del proyecto (completar en el checkpoint final)

```
DATOS PERSONALES
☐ ¿El proyecto recopila datos personales (nombre, email, teléfono, dirección)?
☐ ¿Se cuenta con el consentimiento explícito de los usuarios?
☐ ¿Los datos están anonimizados en el entorno de pruebas/demo?

ALMACENAMIENTO
☐ ¿Dónde se almacenan los datos? (Google Sheets, base de datos, plataforma no-code)
☐ ¿Esa plataforma tiene acceso protegido (no es pública)?
☐ ¿Se eliminan los datos de prueba al finalizar el proyecto?

NORMATIVA
☐ ¿El proyecto cumple con la Ley 81 de 2019 de Panamá?
☐ Si hay usuarios en la UE/California: ¿se consideró GDPR/CCPA?
☐ ¿Existe una política de privacidad (aunque sea básica) para el negocio simulado?
```
