# Checkpoint 1: oportunidades de automatización en la devolución de pedidos de BIXO

**Negocio:** BIXO, una tienda e-commerce de pixel art. Es un negocio simulado que parte de mi propio proyecto.
**Proceso:** devolución de pedido.
**Autor:** Andrés Mudarra (trabajo individual).

---

## 1. Diagrama BPMN AS-IS finalizado

El diagrama muestra cómo funciona hoy el proceso de devolución, sin mejoras todavía. Está en estos dos archivos:

- Imagen: `diagrama-as-is-practica.png`
- Archivo fuente: `diagrama-as-is-practica.bpmn`

Tiene cuatro carriles (Cliente, Atención al cliente, Bodega y Finanzas) y dos decisiones: si la solicitud cumple la política de devolución y si el producto llegó en buen estado. El proceso puede terminar de tres formas: solicitud rechazada, reembolso rechazado o devolución completada.

## 2. Matriz de priorización

Para armarla me basé en los cuellos de botella que encontré en el análisis de la semana 4. Los datos de volumen son estimaciones mías (unas 8 devoluciones al mes), no mediciones reales.

| Oportunidad de automatización | Volumen (1-5) | Repetitividad (1-5) | Reglas claras (1-5) | Valor (1-5) | Esfuerzo estimado | Total |
|---|---|---|---|---|---|---|
| Verificar el plazo de devolución automáticamente con la fecha del pedido | 2 | 5 | 5 | 4 | Bajo | 16 |
| Recibir la solicitud con un formulario y enviar las instrucciones de forma automática | 2 | 5 | 5 | 3 | Bajo | 15 |
| Avisar al cliente del avance y del reembolso con mensajes automáticos | 2 | 5 | 5 | 3 | Bajo | 15 |
| Procesar el reembolso con cálculo y registro automático | 2 | 4 | 4 | 4 | Medio | 14 |
| Decidir el estado del producto en la inspección | 2 | 3 | 2 | 2 | Alto | 9 |

El volumen me quedó bajo en todas las filas porque BIXO recibe pocas devoluciones al mes. Por eso el beneficio de automatizar está más en ganar velocidad y evitar errores que en ahorrar muchas horas de trabajo.

## 3. Oportunidad seleccionada y justificación

**Seleccionada:** un formulario de devolución que verifique el plazo automáticamente y envíe las instrucciones al cliente sin que nadie lo haga a mano. Junta las dos primeras filas de la matriz.

**Por qué la elegí:**
- Tiene el total más alto y el esfuerzo es bajo, así que es un *quick win* según el criterio de selección del curso.
- Las reglas son claras y se pueden escribir como un if-then: si la solicitud llega dentro del plazo, se mandan las instrucciones; si no, se rechaza.
- Ataca los dos primeros cuellos de botella del análisis: la espera de hasta 24 horas para que alguien atienda la solicitud y la verificación manual del pedido, que es lenta y donde se cometen errores.

**Cómo cambia el proceso (de AS-IS a TO-BE):** hoy el cliente escribe por WhatsApp y alguien revisa el pedido a mano. Con la automatización, el cliente llena un formulario, el sistema comprueba el plazo en segundos y le responde con las instrucciones o con el rechazo.

**Lo que dejo para después:** los avisos de avance y el reembolso automático quedan para una siguiente etapa, porque dependen de que el primer paso ya esté funcionando.

---

## Declaración de uso de IA

Para este checkpoint usé dos herramientas de IA: Claude y Google NotebookLM.

Con Claude me ayudé a armar la estructura del documento y a redactar un primer borrador, partiendo del diagrama del Lab 1 y del análisis que hice en la semana 4 sobre las devoluciones de BIXO. También lo usé para ordenar la matriz de priorización y para explicar mejor por qué elegí esa oportunidad.

NotebookLM lo usé para estudiar y repasar el material del curso mientras preparaba el trabajo.

Los puntajes de la matriz y los datos de volumen son estimaciones que puse para el ejercicio, no mediciones reales. Cuando tuve el borrador lo revisé y lo ajusté, y me hago responsable de lo que entrego.
