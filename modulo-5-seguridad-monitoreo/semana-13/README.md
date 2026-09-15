# Semana 13 — Marketing Automation y CRM

**Módulo 5: Seguridad, monitoreo y optimización continua de los procesos de negocios**

---

## Objetivos de aprendizaje

- Utilizar herramientas de marketing automation (HubSpot, Mailchimp) para configurar una campaña automatizada con segmentación.
- Aplicar conceptos de CRM, captación de leads, personalización y segmentación de audiencias.

---

## Contenidos de la semana

### Teoría (martes)

1. Automatización de marketing:
   - Embudo de conversión: conciencia → interés → decisión → acción
   - **Lead nurturing**: nutrición de leads con contenido automatizado en el momento correcto
   - **Segmentación**: agrupar contactos por comportamiento, demografía o etapa del embudo
   - **Personalización**: usar el nombre, historial de compras, preferencias en el email
2. CRM (Customer Relationship Management):
   - Centralización de información de contactos y clientes
   - Seguimiento de interacciones y pipeline de ventas

### Práctica/Laboratorio (jueves)

**Lab 6**: cada equipo configura una campaña de email automatizada en HubSpot o Mailchimp

Requisitos mínimos de la campaña:
- Al menos **un criterio de segmentación** (ej. clientes que han comprado en los últimos 30 días)
- Al menos **un trigger** (ej. formulario enviado, link clickeado)
- Email automatizado con al menos un campo personalizado (`{{first_name}}`)

---

## Entregable de la semana

**Laboratorio 6** — Campaña de marketing automatizada

- Sube: capturas de la segmentación, el trigger y el email configurado + justificación de negocio
- Archivo: `modulo-5-seguridad-monitoreo/semana-13/lab06-marketing-automation/README.md`

**Quiz** (en clase) — automatización de marketing y CRM

---

## Elementos clave de un email automatizado efectivo

```
ASUNTO: "{{first_name}}, tu carrito te espera 🛒"
         ↑ personalización  ↑ urgencia + emoji (si aplica a la marca)

ESTRUCTURA DEL EMAIL:
1. Saludo personalizado: "Hola {{first_name}},"
2. Contenido relevante: mostrar los productos del carrito abandonado
3. Prueba social: "3,000 personas compraron esto este mes"
4. CTA claro: botón "Completa tu compra" → URL del carrito
5. Pie de página: opción de cancelar suscripción (requerida por ley)

SEGMENTACIÓN SUGERIDA:
- Contactos con carrito abandonado en las últimas 24 horas
- SIN compra completada en ese período
- Excluir: ya compraron, cancelaron suscripción, compras > $500 (segmento VIP separado)
```
