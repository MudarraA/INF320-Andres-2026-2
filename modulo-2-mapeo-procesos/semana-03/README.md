# Semana 3 — Mapeo y Modelado BPMN · Kickoff del Proyecto Integrador

**Módulo 2: Herramientas, diseño e implementación de procesos automatizados**

---

## Objetivos de aprendizaje

- Elaborar diagramas de flujo y diagramas **BPMN básicos** de un proceso de negocio.
- Aplicar la notación BPMN 2.0 estándar: eventos, tareas, compuertas, piscinas y carriles.
- Conformar el equipo de trabajo del proyecto integrador y seleccionar el proceso a intervenir.

---

## Contenidos de la semana

### Teoría (martes)

1. Diagramas de flujo tradicionales — ventajas y limitaciones
2. BPMN 2.0 — elementos básicos:
   - **Eventos**: inicio (círculo delgado), intermedio (círculo doble), fin (círculo grueso)
   - **Tareas**: rectángulos con nombre del proceso
   - **Compuertas**: exclusiva (X — solo uno de los caminos), paralela (+), basada en evento
   - **Flujos de secuencia**: flechas continuas entre elementos
   - **Piscinas** (pools) y **carriles** (lanes): separan actores/sistemas
3. Buenas prácticas de modelado: nombrar las tareas con verbo+objeto ("Verificar pago")

### Práctica/Laboratorio (jueves)

1. **Lab 1**: modelar en equipos un proceso AS-IS usando Bizagi Modeler o draw.io (caso guiado: proceso de devolución de pedido)
2. **Kickoff del proyecto integrador**:
   - Formación de equipos (4-5 integrantes)
   - Elección de pyme real o negocio simulado de e-commerce
   - Selección del proceso de negocio a intervenir durante el semestre

---

## Entregable de la semana

**Laboratorio 1** — Diagrama BPMN AS-IS (evaluado con rúbrica)

- Archivo: `proyecto-integrador/kickoff/diagrama-as-is-practica.png` (imagen exportada) + archivo fuente `.bpmn`

**Ficha de equipo** — completar `proyecto-integrador/kickoff/PLANTILLA-ficha-equipo.md`

---

## Notación BPMN — referencia rápida

```
Eventos:
  ○  → Inicio        ⊙ → Intermedio        ● → Fin

Tareas:
  [__Verificar pago__]   [__Enviar confirmación__]

Compuertas:
  ◇X  → Exclusiva (solo una rama)
  ◇+  → Paralela (todas las ramas al mismo tiempo)

Piscinas y Carriles:
  ┌─────────────────────────────────┐
  │ SISTEMA DE PEDIDOS              │
  │  ┌──────────────────────────┐   │
  │  │ Proceso automático       │   │
  │  └──────────────────────────┘   │
  │  ┌──────────────────────────┐   │
  │  │ Verificación manual      │   │
  │  └──────────────────────────┘   │
  └─────────────────────────────────┘
```

---

## Recursos de la semana

| Recurso | Propósito |
|---------|-----------|
| Bizagi Modeler | Herramienta principal para los diagramas BPMN |
| draw.io / app.diagrams.net | Alternativa en línea (Template BPMN 2.0) |
| Artola & Martínez (2021) | Cap. 3: introducción a BPMN 2.0 |
| bpmn.io | Editor web de BPMN 2.0 de referencia (muestra la notación estándar) |
