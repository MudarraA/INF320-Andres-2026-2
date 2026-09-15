# Semana 12 — Automatización de Pedidos/Inventario + Chatbot · CHECKPOINT 3

**Módulo 4: Implementación de chatbots y asistentes virtuales — Cierre**

---

## Objetivos de aprendizaje

- Automatizar de extremo a extremo un flujo de gestión de pedidos o inventario.
- Implementar un **chatbot o asistente virtual básico** usando una herramienta de IA conversacional.

---

## Contenidos de la semana

### Teoría (martes)

1. Fundamentos del diseño conversacional:
   - **Intents**: la intención del usuario ("quiero rastrear mi pedido")
   - **Entidades**: los datos clave dentro del intent ("número de pedido: #1234")
   - **Flujos de diálogo**: secuencia de pasos para resolver el intent
   - **Utterances**: ejemplos de cómo un usuario puede expresar el mismo intent
2. Integración del chatbot con el proceso automatizado:
   - El chatbot como "frontend conversacional" del flujo de automatización
   - Ejemplo: chatbot recibe "¿dónde está mi pedido?" → consulta el workflow → responde con el estado

### Práctica/Laboratorio (jueves)

**Taller práctico** (en equipos):
1. Automatización end-to-end de un flujo de pedidos/inventario del proyecto
2. Construcción de un **chatbot básico** usando Voiceflow, Landbot, Dialogflow CX, o API de Claude/GPT

---

## CHECKPOINT 3 — Entregable evaluado

**Fecha**: fin de la semana 12

**Qué entregar**: `proyecto-integrador/checkpoint-3/checkpoint-3.md`

**Qué debe incluir**:
- Chatbot/asistente virtual básico funcional (demo en vivo o video corto)
- Al menos 3 intents implementados relevantes al negocio
- Cómo el chatbot se articula con el flujo de automatización del proyecto
- Pruebas: guion de preguntas que el chatbot debe responder correctamente

**Peso**: 25% de la nota del proyecto integrador

---

## Herramientas para el chatbot del proyecto

| Herramienta | Sin código | Integración con API | Plan gratuito |
|------------|-----------|---------------------|--------------|
| **Voiceflow** | ✅ | ✅ (Claude, GPT) | ✅ |
| **Landbot** | ✅ | ✅ parcial | ✅ (100 conv/mes) |
| **Dialogflow CX** | 🔄 bajo código | ✅ | ✅ (capa gratuita) |
| **API de Claude/GPT** | ❌ (código) | ✅ nativa | 🔄 (créditos) |

---

## Guion de pruebas mínimo del chatbot (incluir en el checkpoint)

El chatbot de tu negocio debe responder correctamente a al menos estas 3 categorías:

1. **Consulta de estado de pedido**: "¿Dónde está mi pedido #1234?"
2. **Solicitud de información de producto**: "¿Tienen el producto X disponible?"
3. **Escalado a humano**: "Quiero hablar con un agente"

Para cada pregunta, documenta:
- La utterance probada (cómo lo preguntó el usuario)
- El intent detectado
- La respuesta del chatbot
- ¿Fue correcta? Sí / No / Parcialmente
