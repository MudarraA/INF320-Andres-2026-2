Laboratorio 2 — Análisis del proceso: devolución de pedido en BIXO

Negocio: BIXO, tienda e-commerce de pixel art (negocio simulado, basado en mi propio proyecto).
Proceso analizado: devolución de un pedido (el mismo que modelé en el diagrama AS-IS del Lab 1).
Técnicas aplicadas: entrevista simulada al dueño del proceso y observación directa (walkthrough), más una estimación de datos operativos.

1. Entrevista al dueño del proceso (simulada)

Como BIXO es un proyecto mío, hice la entrevista poniéndome en el lugar del dueño, siguiendo la guía de preguntas del curso.

Sobre el proceso

1.Descripción paso a paso. El cliente escribe pidiendo la devolución. Atención recibe el mensaje, verifica el pedido y el plazo, y si cumple la política le manda instrucciones. El cliente envía el producto, bodega lo recibe y lo inspecciona, y si está en buen estado finanzas hace el reembolso y se avisa al cliente. Si no cumple la política o el producto llega dañado, se rechaza.
2.Quiénes intervienen. Cliente, atención al cliente, bodega y finanzas. En un negocio chico varios de esos roles los hace la misma persona, pero el proceso los separa.
3.Frecuencia. Ocurre por pedido, unas pocas veces al mes.
4.Tiempo total. Entre 5 y 8 días hábiles, de principio a fin.

Sobre los problemas

5.Pasos que más tiempo consumen. El envío del producto por parte del cliente y el reembolso, porque dependen de terceros y de que alguien lo haga a mano.
6.Dónde se cometen más errores. Al verificar pedido y plazo, y al calcular el monto a reembolsar, porque se hace revisando datos a mano.
7.Pasos manuales que podrían automatizarse. La recepción de la solicitud, la verificación del plazo, el envío de instrucciones y la notificación al cliente.
8.Dónde se atasca. Al inicio, cuando la solicitud queda sin respuesta hasta que alguien la ve, y en el reembolso, cuando falta confirmar el pago.

Sobre los datos

9.Información que se genera. Mensajes del cliente, datos del pedido, un registro de la inspección y el comprobante del reembolso.
10.Cómo se comunican los actores. Por WhatsApp y correo, sin un sistema que lleve el seguimiento.

2. Registro de observación directa

Observador: Andrés Mudarra
Negocio / Proceso: BIXO, devolución de pedido

| Paso | Actor | Tiempo aproximado | Sistema/Herramienta | Observaciones |
|------|-------|-------------------|---------------------|---------------|
| 1. Solicitar devolución | Cliente | 5 min | WhatsApp / correo | No hay formulario, cada cliente lo explica a su manera |
| 2. Recibir solicitud | Atención | Hasta 24 h de espera | WhatsApp / correo | Depende de que alguien vea el mensaje |
| 3. Verificar pedido y plazo | Atención | 15–20 min | Hoja de cálculo | Se busca el pedido a mano y se compara la fecha |
| 4. Enviar instrucciones | Atención | 10 min | WhatsApp | Se escribe el mensaje cada vez |
| 5. Enviar producto | Cliente | 2–3 días | Mensajería externa | Fuera del control de BIXO |
| 6. Recibir producto | Bodega | Hasta 1 día | Registro manual | No hay aviso automático de que llegó |
| 7. Inspeccionar estado | Bodega | 20 min | Revisión visual | Criterio de "buen estado" sin lista definida |
| 8. Procesar reembolso | Finanzas | 2–3 días | Yappy / transferencia manual | Se calcula y se paga a mano |
| 9. Notificar al cliente | Finanzas | 10 min | WhatsApp | Depende de acordarse |

3. Hallazgos

- Todo el proceso corre sobre mensajes sueltos de WhatsApp y correo, así que no hay un lugar donde ver en qué etapa va cada devolución.
- Muchas tareas son repetitivas y se escriben o se buscan a mano cada vez (instrucciones, verificación, avisos).
- Hay dos puntos de decisión (política de devolución y estado del producto) que hoy dependen del criterio de una persona.

4. Cuellos de botella detectados

1.Espera para atender la solicitud: la devolución puede quedar parada hasta 24 horas solo porque nadie vio el mensaje.
2.Verificación manual del pedido y el plazo: lenta y con riesgo de error.
3.Reembolso manual:** es el paso más largo después del envío y depende de que finanzas lo haga y avise.
4.Falta de seguimiento: sin un sistema, nadie sabe en qué paso está cada devolución.

5. Datos operativos estimados

Son aproximaciones hechas para este ejercicio, no mediciones reales.

-Frecuencia del proceso: unas 8 devoluciones al mes.
-Tiempo total promedio: 5 a 8 días hábiles.
-Tiempo de trabajo activo: cerca de 1 hora por devolución (el resto es espera).
Tasa de error aproximada: alrededor del 15 %, sobre todo en verificación y en el monto del reembolso.

6. Oportunidades iniciales

Por ahora solo las dejo señaladas para el Checkpoint: un formulario de devolución que genere la solicitud, verificación automática del plazo contra la fecha del pedido, mensajes automáticos de instrucciones y de avance, y un reembolso con registro. No las desarrollo todavía, porque este documento es de análisis del proceso tal como es hoy.

Declaración de uso de IA

Para este entregable usé Claude (Anthropic) como apoyo para estructurar el documento y redactar el borrador a partir del diagrama del Lab 1 y de mi proyecto BIXO, y Google NotebookLM como herramienta de apoyo para estudiar el material. La entrevista es simulada y los datos operativos son estimaciones. El contenido final fue revisado por mí.
