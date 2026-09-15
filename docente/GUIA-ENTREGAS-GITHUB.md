# Guía docente — Entregas por GitHub (repos privados, sin GitHub Classroom)

GitHub Classroom está en transición hacia soluciones de terceros y no está disponible para configurar
asignaciones nuevas. Los repos del curso se mantienen **privados** (incluyen guías de examen), así que
el autoservicio con "Use this template" no funciona: un estudiante sin acceso no puede ni ver la
plantilla. En su lugar, **el docente (o Claude, con `gh` ya autenticado) crea una copia privada por
estudiante** a partir de la plantilla y lo agrega como colaborador de su propia copia — el estudiante
nunca necesita acceso a la plantilla en sí.

| Repositorio (plantilla, privado) | Tipo | URL |
|---|---|---|
| Asignaciones/laboratorios (individual) | 1 copia privada por estudiante | `https://github.com/avila-fiec-up/INF320-Automatizacion-Procesos-Negocios-2026-2` |
| Proyecto integrador (equipo) | 1 copia privada por equipo de 4-5 | `https://github.com/avila-fiec-up/INF320-Proyecto-Integrador-2026-2` |

---

## 1. Recolectar el roster (nombre + usuario de GitHub)

La forma más simple: en Google Classroom, publica en la semana 1 una **Pregunta** de respuesta corta
("¿Cuál es tu usuario de GitHub? Créalo antes de responder si no tienes uno"). Muchos estudiantes de
Comercio Electrónico usarán Git por primera vez — dedica los primeros 20-30 minutos de la semana 1 a
crear la cuenta juntos en vivo antes de pedirles el usuario. Detalle en `GUIA-GOOGLE-CLASSROOM.md`.

Para el proyecto integrador (equipos de 4-5), necesitas además el nombre del equipo y sus integrantes
— puede ser la misma pregunta reformulada en la semana 3, después del kickoff.

## 2. Crear un repo privado por estudiante (individual)

Con el roster en mano, esto se hace con `gh` — pégamelo en el chat y lo corro, o hazlo tú mismo con
`scripts/crear-repos-estudiantes.sh` de este repositorio (un usuario de GitHub por línea en un
archivo de texto):

```bash
export PATH="$HOME/.local/bin:$PATH"
./scripts/crear-repos-estudiantes.sh roster.txt
```

GitHub le manda automáticamente al estudiante una **invitación por correo** a su propio repo en cuanto
lo agregas como colaborador — no hace falta que tú le pases el link a mano.

## 3. Crear un repo privado por equipo (proyecto integrador)

Con `INF320-Proyecto-Integrador-2026-2/scripts/crear-repos-equipos.sh` y un CSV
`nombre-equipo,usuario1,usuario2,usuario3,usuario4`:

```bash
./scripts/crear-repos-equipos.sh equipos.csv
```

## 4. Cómo el docente ve y sigue todas las entregas

```bash
gh repo list avila-fiec-up --limit 200 --json name,pushedAt,isPrivate --jq '.[] | select(.name | test("(?i)inf320"))'
```

## 5. Checklist automático (no calificador)

Cada copia hereda `.github/workflows/checklist-entregas.yml`: al hacer `git push`, confirma en la
pestaña **Actions** si los archivos esperados de la semana ya existen en la ruta correcta. Es
informativo, no reemplaza tu revisión con la rúbrica.

## 6. Si más adelante GitHub Classroom vuelve a estar disponible

Los dos repos plantilla ya cumplen los requisitos (marcados como plantilla, en una organización). Si
retomas Classroom, solo faltaría vincular la organización `avila-fiec-up` y crear las asignaciones —
el resto del curso no cambia.
