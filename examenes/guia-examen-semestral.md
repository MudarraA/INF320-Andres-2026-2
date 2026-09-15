# Guía de Estudio — Examen Semestral

**INF 320 Automatización de Procesos de Negocios · Semestre 2026-2**  
**Semana 15 · Cubre: los 5 módulos del curso**

---

## Formato del examen

| Sección | Peso | Tipo de preguntas |
|---------|------|------------------|
| Teoría conceptual (todos los módulos) | 30% | Opción múltiple, V/F, definiciones |
| Caso práctico integral (BPMN + automatización) | 35% | Caso extendido de negocio de e-commerce |
| Plataformas, herramientas y tendencias | 20% | Comparativas, identificación, selección |
| Seguridad, gobernanza y mejora continua | 15% | GDPR/Ley 81, Kaizen, Six Sigma, KPIs |

**Duración**: ~120 minutos · **Sin IA, sin dispositivos**

---

## Repaso de Módulos 1 y 2 (cubiertos en Parcial 1)

*(Para repasar preguntas específicas de estos módulos, revisa `guia-parcial-1.md`)*

**Conceptos clave a recordar**:
- Definición de BPA y sus beneficios en e-commerce
- Diferencia BPA vs. BPR (con ejemplo)
- Notación BPMN 2.0: eventos, tareas, compuertas, piscinas, carriles
- Técnicas de análisis de procesos: entrevistas, observación, datos operativos
- Criterios de priorización de oportunidades de automatización (volumen, repetitividad, reglas claras, valor)

---

## Repaso de Módulo 3 (cubierto en Parcial 2)

*(Para repasar preguntas específicas, revisa `guia-parcial-2.md`)*

**Conceptos clave**:
- BPM vs. RPA (definiciones, diferencias, complementariedad)
- Plataformas RPA: UiPath, Blue Prism, Automation Anywhere
- Plataformas no-code/IA: Zapier, Make, Power Automate, n8n
- Integración: API vs. webhook vs. conector nativo
- Criterios de selección de plataforma según caso de uso y perfil

---

## Módulo 4 — Chatbots, workflows y casos de uso en e-commerce

### Preguntas de práctica

1. ¿Cuáles son los 4 principios de diseño de procesos automatizados? ¿Cuál de ellos es más crítico para la operación en producción?

2. Explica la diferencia entre un **intent**, una **entidad** y una **utterance** en el contexto de un chatbot.

3. Para el siguiente escenario, diseña el flujo de diálogo de un chatbot:
   *"Un cliente escribe: '¿Cuándo llega mi pedido #4521?' El chatbot debe consultar el estado del pedido y responder con la fecha estimada de entrega."*
   
   Incluye:
   - Intent detectado
   - Entidad(es) extraída(s)
   - Respuesta del chatbot
   - Qué pasa si el número de pedido no existe

4. ¿Cuál es la diferencia entre Voiceflow y Dialogflow CX en términos de facilidad de uso y capacidades?

5. Nombra 3 casos de uso de chatbots en e-commerce y el tipo de intent que maneja cada uno.

### Gestión automatizada de pedidos e inventario

6. Diseña el flujo de automatización para la gestión de reposición de inventario:
   *"Cuando el stock de cualquier producto baje de 10 unidades, el sistema debe alertar al proveedor por email con el nombre del producto y la cantidad recomendada de reposición, y actualizar una hoja de seguimiento con la fecha de la alerta."*

---

## Módulo 5 — Seguridad, gobernanza y mejora continua

### Seguridad y normativa

7. ¿Qué establece la Ley 81 de 2019 de Panamá en materia de datos personales? Nombra al menos 3 derechos que otorga a los ciudadanos.

8. ¿Cuál es la diferencia entre el GDPR (UE) y la Ley 81 de 2019 (Panamá)? ¿A cuáles empresas panameñas aplica el GDPR?

9. Una tienda en línea panameña recopila: nombre, email, dirección, historial de compras y número de tarjeta de crédito. Para cada tipo de dato:
   - ¿Es dato personal? ¿Es dato sensible?
   - ¿Qué medida de seguridad mínima debes aplicar?

10. ¿Qué debe incluir un aviso de privacidad conforme a la Ley 81 de 2019?

### KPIs y monitoreo

11. Define 4 KPIs para el siguiente proceso automatizado: "chatbot de atención al cliente de una tienda en línea"
    Para cada KPI: nombre, fórmula, meta razonable, fuente de datos.

12. ¿Cuál es la diferencia entre una métrica y un KPI?

### Kaizen y Six Sigma

13. Describe el ciclo PDCA (Plan-Do-Check-Act) de Kaizen aplicado a la mejora de un flujo de automatización que tiene una tasa de error del 5%.

14. ¿Qué significa DMAIC en Six Sigma? Aplica brevemente cada fase al proceso de gestión de pedidos de una tienda en línea.

---

## Caso práctico integral (tipo Sección 2 del examen semestral)

15. **"TiendaPA — Automatización integral de una pyme de e-commerce"**

TiendaPA vende artesanías panameñas por internet. Actualmente sus procesos son completamente manuales:
- Los pedidos llegan por Instagram DM y WhatsApp
- Un empleado verifica el inventario en Excel
- Los pagos se reciben por Yappy, transferencia o efectivo
- Las confirmaciones y el tracking se envían manualmente por WhatsApp
- La atención al cliente es manual (el empleado responde preguntas durante horario de oficina)

**Tareas**:

a) **BPMN AS-IS**: describe (o dibuja) el proceso AS-IS de recepción y confirmación de pedido con los actores involucrados.

b) **BPMN TO-BE**: propone el proceso TO-BE automatizado. ¿Qué pasos se automatizan? ¿Cuáles quedan manuales y por qué?

c) **Herramienta de automatización**: ¿qué plataforma no-code usarías para el flujo de pedidos? Justifica la elección.

d) **Chatbot**: describe los 3 intents principales del chatbot de TiendaPA y cómo se articula con el flujo de automatización.

e) **KPIs**: define 3 KPIs que TiendaPA debería monitorear después de implementar la automatización.

f) **Seguridad**: ¿qué datos personales recopila TiendaPA? ¿Cómo debe manejarlos conforme a la Ley 81 de 2019?

---

## Tendencias emergentes (Módulo 5)

16. ¿Qué es la **minería de procesos asistida por IA** (*AI-augmented process mining*)? ¿Para qué sirve en el contexto de la optimización de procesos de negocio?

17. ¿Cuál es el impacto de la IA generativa (LLMs como Claude o GPT) en la automatización de procesos de negocios? Da 2 ejemplos concretos en e-commerce.
