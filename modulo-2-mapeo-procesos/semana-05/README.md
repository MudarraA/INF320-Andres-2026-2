# Semana 5 — Identificación de Oportunidades de Automatización · CHECKPOINT 1

**Módulo 2: Herramientas, diseño e implementación de procesos automatizados — Cierre**

---

## Objetivos de aprendizaje

- Aplicar criterios de priorización (volumen, repetitividad, reglas claras, valor) para identificar oportunidades de automatización.
- Consolidar el mapeo BPMN AS-IS y las oportunidades identificadas.

---

## Contenidos de la semana

### Teoría (martes)

1. Criterios de priorización de oportunidades de automatización:
   - **Volumen**: ¿cuántas veces ocurre este paso por día/mes?
   - **Repetitividad**: ¿es siempre el mismo procedimiento?
   - **Reglas claras**: ¿puede describirse con lógica if-then sin ambigüedad?
   - **Valor generado**: ¿cuánto tiempo/dinero se ahorraría?
2. Matriz de priorización: esfuerzo de implementación vs. impacto esperado
3. "Quick wins" (automatización rápida, alto impacto) vs. automatizaciones complejas

### Práctica/Laboratorio (jueves)

1. Cada equipo aplica la matriz de priorización a los hallazgos del análisis de la semana 4
2. Selección de la(s) oportunidad(es) de automatización para el proyecto
3. Finalización y depuración del diagrama BPMN AS-IS

---

## CHECKPOINT 1 — Entregable evaluado

**Fecha**: fin de la semana 5 (ver fecha exacta en el aula virtual)

**Qué entregar**: `proyecto-integrador/checkpoint-1/checkpoint-1.md` (completar la plantilla)

**Qué debe incluir**:
- Diagrama BPMN AS-IS finalizado (imagen PNG + archivo fuente)
- Análisis de oportunidades de automatización con la matriz de priorización
- Oportunidad seleccionada y justificación

**Peso**: 15% de la nota del proyecto integrador (ver `../INF320-Proyecto-Integrador-2026-2/README.md`)

---

## Matriz de priorización de oportunidades

| Oportunidad de automatización | Volumen (1-5) | Repetitividad (1-5) | Reglas claras (1-5) | Valor (1-5) | Esfuerzo estimado | Total |
|-------------------------------|--------------|--------------------|--------------------|------------|------------------|-------|
| Ej: Enviar email de confirmación de pedido | 5 | 5 | 5 | 4 | Bajo | **19** |
| Ej: Negociar precio con proveedor | 1 | 1 | 2 | 5 | Alto | **9** |
| (Proceso 1 del equipo) | | | | | | |
| (Proceso 2 del equipo) | | | | | | |

**Criterio de selección**: prioriza las filas con mayor total Y menor esfuerzo estimado.

---

## Diagrama AS-IS → TO-BE: la dirección del proyecto

```
AHORA (AS-IS):
  Cliente hace pedido
      ↓
  Empleado revisa manualmente el stock (30 min)
      ↓
  Empleado envía email manual de confirmación (15 min)
      ↓
  Empleado actualiza hoja de cálculo de inventario (10 min)

META (TO-BE) — lo que construirá el equipo:
  Cliente hace pedido
      ↓
  Sistema verifica stock AUTOMÁTICAMENTE (segundos)
      ↓
  Sistema envía email de confirmación AUTOMÁTICAMENTE (segundos)
      ↓
  Sistema actualiza inventario AUTOMÁTICAMENTE (segundos)
```
