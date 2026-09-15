# Guía de Estudio — Parcial 1

**INF 320 Automatización de Procesos de Negocios · Semestre 2026-2**  
**Semana 6 · Cubre: Módulos 1 y 2 completos**

---

## Formato del examen

| Sección | Peso | Tipo de preguntas |
|---------|------|------------------|
| Teoría conceptual | 40% | Opción múltiple, V/F, definiciones cortas |
| Caso práctico / BPMN | 45% | Elaborar o corregir un diagrama BPMN AS-IS + identificar oportunidades |
| Argumentación | 15% | Justificar si un caso es automatización o BPR |

**Duración**: ~90 minutos · **Sin IA, sin dispositivos**

---

## Módulo 1 — Introducción a BPA

### Preguntas de práctica — teoría

1. ¿Cuál es la diferencia entre la automatización de procesos (BPA) y la reingeniería de procesos de negocio (BPR)? Da un ejemplo de cada una en el contexto de una tienda en línea.

2. Enumera 4 beneficios de la automatización de procesos en el comercio electrónico.

3. ¿Qué es el panorama no-code/IA en automatización 2026? Nombra al menos 3 herramientas.

4. Clasifica cada ejemplo como BPA (automatización) o BPR (reingeniería):
   - a) Una tienda que antes confirmaba pedidos por teléfono y ahora envía un email automático.
   - b) Un banco que elimina sus sucursales físicas y migra 100% a banca digital con chatbot de IA.
   - c) Un almacén que automatiza el envío de alertas cuando el stock baja de 10 unidades.
   - d) Una empresa que rediseña su cadena de suministro para trabajar sin inventario propio (dropshipping puro).

5. ¿Por qué la automatización es estratégica para la competitividad en e-commerce en 2026?

---

## Módulo 2 — Mapeo y modelado de procesos

### Notación BPMN — preguntas de práctica

6. Identifica los elementos BPMN:
   - ¿Qué representa un círculo delgado en BPMN?
   - ¿Qué representa un rombo con una X?
   - ¿Cuál es la diferencia entre una piscina (pool) y un carril (lane)?

7. Dado este proceso textual, elabora el diagrama BPMN AS-IS:
   
   *"Cuando un cliente hace un pedido en la tienda en línea, un empleado lo revisa manualmente. Si el pago está aprobado, el empleado actualiza el inventario en una hoja de cálculo y envía un email de confirmación al cliente. Si el pago está rechazado, el empleado notifica al cliente por email para que reintente el pago."*

8. El siguiente diagrama BPMN tiene 3 errores de notación. Identifícalos:
   *(El docente incluirá un diagrama con errores en el examen real)*

### Técnicas de análisis de procesos

9. ¿Cuál es el propósito de la observación directa (walkthrough) de un proceso? ¿En qué se diferencia de una entrevista?

10. Diseña 5 preguntas que harías en una entrevista para levantar el proceso de atención de reclamos de una tienda en línea.

11. ¿Qué son los indicadores operativos de un proceso? Nombra 3 indicadores relevantes para el proceso de gestión de pedidos de una tienda en línea.

### Identificación de oportunidades de automatización

12. Aplica la matriz de priorización a los siguientes 3 pasos de un proceso de gestión de pedidos. Asigna puntaje del 1 al 5 y justifica:
    - a) Enviar email de confirmación de pedido
    - b) Negociar descuentos con proveedores por teléfono
    - c) Actualizar el estado del pedido en el sistema de inventario

13. ¿Qué criterios determinan si un proceso es un buen candidato para automatización? Menciona los 4 criterios principales y explica por qué importa cada uno.

---

## Ejercicio integrador de argumentación (tipo Sección 3 del examen)

14. Una cadena de supermercados panameña tiene el siguiente proceso: sus cajeros ingresan manualmente el nombre, cantidad y precio de cada producto vendido en una hoja de Excel al final de cada día para actualizar el inventario. Los errores son frecuentes y el proceso toma 2 horas diarias por tienda.

    La empresa está considerando dos opciones:
    - **Opción A**: Automatizar el proceso conectando las cajas registradoras directamente al sistema de inventario mediante una integración.
    - **Opción B**: Rediseñar completamente la cadena de suministro para implementar RFID en todos los productos y actualización de inventario en tiempo real.

    a) ¿Cuál es una automatización incremental y cuál es una reingeniería (BPR)? Justifica.
    b) ¿Cuál recomendarías para implementar en los próximos 3 meses? ¿Por qué?
