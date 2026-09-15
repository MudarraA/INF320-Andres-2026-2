# Semana 8 — Integración con Sistemas de Comercio Electrónico

**Módulo 3: Automatización de marketing y ventas en la cadena de suministro y logística**

---

## Objetivos de aprendizaje

- Explicar los conceptos de **API**, **webhook** y **conector** en el contexto de integración de sistemas.
- Conectar dos o más servicios digitales mediante una plataforma de automatización.

---

## Contenidos de la semana

### Teoría (martes)

1. Conceptos de integración:
   - **API (Application Programming Interface)**: contrato que permite que dos sistemas se "hablen" mediante solicitudes HTTP
   - **Webhook**: "callback" que un sistema envía automáticamente a otro cuando ocurre un evento ("avisa cuando algo pasa")
   - **Conector nativo**: integración preconfigurada en plataformas no-code (no requiere programar la API)
2. Diferencia API vs. Webhook:
   - API: tú preguntas → el sistema responde (polling)
   - Webhook: el sistema te avisa cuando ocurre algo (event-driven, más eficiente)
3. Casos de integración típicos en e-commerce:
   - Tienda (Shopify/WooCommerce) → hoja de cálculo → email/SMS de seguimiento
   - Formulario de contacto → CRM → asignación de vendedor
   - Pago aprobado → actualizar inventario → notificar al proveedor

### Práctica/Laboratorio (jueves)

**Lab 4**: conectar dos servicios reales

Ejemplo: formulario de Google Forms → Google Sheets → notificación por email

Aplicar al proceso del proyecto integrador si es posible.

---

## Entregable de la semana

**Laboratorio 4** — Integración funcional de dos servicios

- Sube: captura de la integración + reflexión sobre cómo aplica al proyecto integrador
- Archivo: `modulo-3-herramientas-bpm-rpa/semana-08/lab04-integracion/README.md`

---

## API vs. Webhook — analogía

```
API (polling):
  Tú llamas cada 5 minutos: "¿Hay pedido nuevo?"
  El sistema responde: "No." / "No." / "¡Sí! Pedido #1234"
  → Ineficiente: muchas llamadas innecesarias

Webhook (event-driven):
  Le dices al sistema: "Cuando haya un pedido nuevo, envíame un aviso a esta URL"
  El sistema te avisa SOLO cuando hay un pedido nuevo
  → Eficiente: cero llamadas desperdiciadas

En Zapier/Make, los triggers tipo "instant" usan webhooks;
los triggers tipo "polling" hacen verificaciones periódicas.
```

---

## Ejemplo de flujo de integración para documentar

```
TRIGGER:   Formulario Google Forms → "Nuevo envío de formulario"
PASO 1:    Google Sheets → "Crear fila" con los datos del formulario
PASO 2:    Gmail → "Enviar email al cliente" con resumen del pedido
PASO 3:    Gmail → "Enviar email al equipo" notificando nuevo pedido

Diagrama de datos:
  Formulario → [nombre, email, producto, cantidad]
       ↓
  Sheets      → [fecha, nombre, email, producto, cantidad, estado="Nuevo"]
       ↓
  Email cliente → "Gracias {{nombre}}, recibimos tu pedido de {{producto}}"
  Email equipo  → "Nuevo pedido de {{nombre}}: {{producto}} × {{cantidad}}"
```
