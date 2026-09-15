# Docker (opcional/avanzado) — n8n autoalojado para INF 320

**No es un requisito del curso.** Las cuentas cloud gratuitas de Zapier/Make/Power Automate (ver
`recursos/herramientas-setup.md`) son suficientes para aprobar todas las actividades y el proyecto
integrador. Esta opción existe para equipos con perfil técnico que:

- Quieran evitar los límites de los planes gratuitos (100 tareas/mes Zapier, 1,000 operaciones/mes Make), o
- Quieran experimentar con un flujo BPM/RPA "self-hosted" como lo haría una empresa real con datos sensibles
  que no puede enviar a un servicio cloud de terceros.

## Requisitos

- [Docker Desktop](https://www.docker.com/products/docker-desktop/) (Windows/macOS) o Docker Engine (Linux).

## Uso

```bash
docker compose -f docker/docker-compose.yml up -d
# abrir http://localhost:5678 y crear tu cuenta local de n8n (queda solo en tu máquina)

# apagar cuando termines:
docker compose -f docker/docker-compose.yml down
```

Los datos y workflows quedan en volúmenes Docker (`n8n_data`, `n8n_pg_data`) que persisten entre
reinicios. Se usa PostgreSQL en vez de la base SQLite por defecto de n8n porque SQLite no es apta
para persistencia confiable en contenedores.

## Contrapartidas frente al cloud

- Tu instancia solo corre mientras tu máquina/contenedor esté encendido — para la demo en vivo de la
  semana 15, ten el contenedor corriendo *antes* de tu turno de presentación.
- No hay integraciones nativas con SaaS de terceros preconfiguradas como en Zapier/Make: cada
  conexión se arma manualmente con nodos HTTP/Webhook.
- Sigue aplicando la política de manejo ético de datos del curso (`politicas/reglas-del-aula.md` §Manejo
  ético de datos): ningún dato real de clientes sin anonimizar, aunque el servidor sea local.
