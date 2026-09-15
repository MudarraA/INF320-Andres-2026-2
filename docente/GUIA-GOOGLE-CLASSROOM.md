# Guía docente — Google Classroom para INF 320 (Automatización de Procesos de Negocios)

Google Classroom es el LMS del curso: agenda, materiales, recolección del usuario de GitHub de cada
estudiante, y libro de calificaciones. El código/documentación viven en GitHub (ver
`GUIA-ENTREGAS-GITHUB.md`) — Classroom no aloja las entregas, solo organiza el curso alrededor de esos
repositorios.

Todo esto se hace a mano en classroom.google.com (no tiene una CLI equivalente a `gh`; si quieres
automatizar la creación de las tareas semanales más adelante, se puede con un script de Google Apps
Script que llama a la API de Classroom — pregúntame si lo quieres y te lo escribo).

---

## 1. Crear la clase

1. classroom.google.com → **+** → **Crear clase**.
2. Nombre: `INF 320 — Automatización de Procesos de Negocios (2026-2)`.
3. Asignatura: `Automatización de Procesos de Negocios`. Aula: el horario de teoría/laboratorio.
4. Classroom genera un **código de clase** — compártelo en la primera sesión, o invita por correo institucional desde **Personas → Invitar estudiantes**.

## 2. Crear los Temas (uno por semana, igual que el repositorio)

**Trabajo de clase → Crear → Tema**. Crea 15 temas con el mismo nombre que las carpetas del repo:

```
Semana 01 · Semana 02 · Semana 03 · Semana 04 · Semana 05 · Semana 06 · Semana 07 ·
Semana 08 · Semana 09 · Semana 10 · Semana 11 · Semana 12 · Semana 13 · Semana 14 · Semana 15
```

## 3. Recolectar el usuario de GitHub de cada estudiante (semana 1)

**Trabajo de clase → Crear → Pregunta**:

- Título: `Tu usuario de GitHub`
- Tema: `Semana 01`
- Tipo: **Respuesta corta**
- Instrucciones: *"Crea una cuenta en github.com si no tienes una. Muchos en este curso lo harán por primera vez — está bien, lo repasamos juntos en clase. Escribe aquí tu usuario exacto: lo voy a usar para darte acceso a tu repositorio privado del curso."*
- Fecha límite: antes de tu primera sesión de laboratorio.

Entra a la pregunta → **Ver todas las respuestas** para obtener el roster (nombre real + usuario de
GitHub). Dame esa lista o úsala tú con `scripts/crear-repos-estudiantes.sh` (ver `GUIA-ENTREGAS-GITHUB.md`).

Repite esta pregunta en la **semana 3** pidiendo el **nombre del equipo** del proyecto integrador, para
`scripts/crear-repos-equipos.sh`.

## 4. Publicar el material de bienvenida

**Trabajo de clase → Crear → Material** (tema: `Semana 01`):

- Syllabus (`docente/01-Syllabus-actualizado.md`), enlace de la presentación de clase, y el
  [Panel del semestre](https://claude.ai/code/artifact/653b3e29-08d9-4336-aed3-2a46b717fd4f).
- Un párrafo: *"Tu trabajo se entrega en un repositorio privado de GitHub que te crearé después de que respondas la pregunta de esta semana. No se aceptan entregas por correo."*

## 5. Configurar las categorías de calificación

**Ajustes (⚙️) → Calificación → Categorías de calificación ponderadas**:

> Si tu cuenta no muestra esta opción (es de Google Workspace for Education), asigna los puntos de
> cada tarea para que ya sumen proporcionalmente en vez de depender de la ponderación automática.

Agrega 3 categorías, con el mismo peso que `docente/03-Sistema-evaluacion-rubricas.md`:

- **Trabajo en Grupo** (asignaciones + laboratorios + quices + proyecto integrador) — 35%
- **Exámenes Parciales** (2, 15% cada uno) — 30%
- **Examen Semestral** — 35%

## 6. Crear una Tarea por cada semana

**Trabajo de clase → Crear → Tarea**, una por semana (copia objetivos/entregable de
`docente/02-Plan-trabajo-15-semanas.md` o el `semana-XX/README.md` correspondiente):

| Campo | Qué poner |
|---|---|
| Título | `Semana XX — <título de la semana>` |
| Tema | El tema `Semana XX` |
| Instrucciones | Objetivos + entregable, copiados del README de esa semana |
| Categoría | `Trabajo en Grupo` (semanas normales, checkpoints), `Exámenes Parciales` (semanas 6, 11), `Examen Semestral` (semana 15) |
| Puntos | Según la rúbrica de esa semana |
| Adjuntos | Ninguno — el repo es privado y personal. En las instrucciones basta con: "Tu entregable está en tu propio repositorio (revisa tu correo de invitación de GitHub)." |

**Semanas con evento especial**:

- **Semana 3**: Kickoff del proyecto integrador (formación de equipos).
- **Semana 5**: Checkpoint 1 del proyecto (15%).
- **Semana 6**: Examen Parcial 1 (15% de la nota final).
- **Semana 9**: Checkpoint 2 del proyecto (25%).
- **Semana 11**: Examen Parcial 2 (15% de la nota final).
- **Semana 12**: Checkpoint 3 del proyecto — chatbot (25%).
- **Semana 15**: Examen Semestral (35%) + Demo final (35% del proyecto) + Coevaluación.

## 7. Ritmo semanal sugerido

Antes de cada sesión de teoría: **Trabajo de clase → Crear → Anuncio** con el tema, la actividad
práctica y la fecha límite. 2 minutos, mantiene a la clase orientada.

## 8. Automatizar esto (opcional)

Igual que en INF 222: es posible automatizar la creación de temas y tareas con un script de **Google
Apps Script** (script.google.com, servicio avanzado Classroom) que corre en tu propia cuenta de
Google sin compartirme ninguna credencial — solo lo autorizas una vez desde el navegador. Dímelo si lo
quieres y te lo escribo con los datos exactos de las 15 semanas.
