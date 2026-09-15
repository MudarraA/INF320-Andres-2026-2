# Semana 7 — Plataformas RPA y Alternativas No-code/IA

**Módulo 3: Automatización de marketing y ventas en la cadena de suministro y logística**

---

## Objetivos de aprendizaje

- Describir las principales plataformas RPA (UiPath, Blue Prism, Automation Anywhere) y sus diferencias.
- Describir las alternativas no-code/IA (Zapier, Make, Power Automate, n8n) y cuándo son preferibles.
- Construir un primer flujo automatizado simple en una plataforma no-code.

---

## Contenidos de la semana

### Teoría (martes)

1. Comparativa de plataformas RPA clásicas:
   - **UiPath**: líder de mercado, entorno visual (Studio), Community Edition gratuita
   - **Blue Prism**: orientado a enterprise, alta seguridad
   - **Automation Anywhere**: Cloud-native, IQ Bot para IA
2. Alternativas no-code/low-code con IA:
   - **Zapier**: la más accesible, conector entre apps SaaS
   - **Make (Integromat)**: más potente y visual, bueno para lógica compleja
   - **Power Automate**: integrado con el ecosistema Microsoft
   - **n8n**: open source, autoalojable
3. Criterios de selección: perfil del usuario (técnico vs. negocio), costo, ecosistema de conectores, complejidad del proceso

### Práctica/Laboratorio (jueves)

**Lab 3**: construir el primer flujo automatizado simple en Zapier o Make

Ejemplo: "Cuando llega un email con el asunto 'Nuevo pedido', crear una fila en Google Sheets y enviar una notificación por email/Slack"

---

## Entregable de la semana

**Laboratorio 3** — Primer flujo no-code funcional

- Sube capturas de pantalla del flujo configurado + descripción de la lógica
- Archivo: `modulo-3-herramientas-bpm-rpa/semana-07/lab03-primer-flujo/README.md`

**Quiz** (en clase) — plataformas BPM/RPA/no-code

---

## Comparativa de plataformas no-code

| Plataforma | Facilidad | Conectores | Plan gratuito | Mejor para |
|-----------|-----------|-----------|--------------|-----------|
| Zapier | ★★★★★ | 6,000+ | 100 tareas/mes | Principiantes, integraciones simples |
| Make | ★★★★ | 1,000+ | 1,000 ops/mes | Flujos visuales complejos |
| Power Automate | ★★★ | 900+ (Microsoft) | Con M365 educativo | Ecosistema Microsoft |
| n8n | ★★★ | 400+ | Unlimited (self-hosted) | Usuarios técnicos, control total |

---

## Cómo documentar tu flujo (formato de entrega)

```markdown
## Flujo: [nombre del flujo]

**Herramienta**: Zapier / Make / Power Automate / n8n

**Disparador (Trigger)**:
- Aplicación: Gmail
- Evento: "Nuevo email recibido" con asunto que contiene "Nuevo pedido"

**Pasos del flujo**:
1. ACCIÓN: Google Sheets → Agregar fila
   - Columna "Fecha": {{ timestamp }}
   - Columna "Asunto": {{ email.subject }}
2. ACCIÓN: Gmail → Enviar email
   - Para: angel.avila@up.ac.pa
   - Asunto: "Procesado: {{ email.subject }}"

**[Captura de pantalla del flujo en la herramienta]**

**Declaración de uso de IA**: (si aplica)
```
