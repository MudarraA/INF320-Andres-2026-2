# Guía de Herramientas y Configuración de Cuentas — INF 320

**Crea todas las cuentas en la primera semana. Muchas requieren verificación de email.**

---

## 1. Control de versiones (obligatorio)

### Git y GitHub

- Descarga Git desde git-scm.com
- Crea cuenta en github.com (usa un nombre profesional)
- Responde la pregunta de Google Classroom de la semana 1 con tu **usuario de GitHub**. El docente te creará tu propia copia privada del repositorio y te agregará como colaborador — recibirás un correo de invitación de GitHub. Acéptala.

```bash
git config --global user.name "Tu Nombre"
git config --global user.email "tu-email@up.ac.pa"
```

---

## 2. Modelado de procesos BPMN

### Opción A: Bizagi Modeler (recomendado, descarga local)

1. Descarga desde bizagi.com/es/products/bpmn-modeler
2. Instala (Windows/Mac)
3. Crea cuenta gratuita para guardar en la nube

### Opción B: draw.io / diagrams.net (en línea, sin instalación)

- URL: app.diagrams.net
- Crea diagrama → selecciona plantilla BPMN 2.0
- Guarda en Google Drive o descarga como XML

### Opción C: Lucidchart

- URL: lucidchart.com
- Plan educativo gratuito: regístrate con tu correo @up.ac.pa o @estudiante.up.ac.pa
- Forma de guardar archivos BPMN: exporta como PNG + guarda el link compartible

---

## 3. Plataformas de automatización no-code/IA

### Zapier (recomendado para primeros laboratorios)

1. Crea cuenta gratuita en zapier.com
2. El plan gratuito permite 100 tareas/mes y 5 Zaps activos — suficiente para el curso
3. Verifica el email y completa el perfil

### Make (antes Integromat)

1. Regístrate en make.com
2. Plan gratuito: 1,000 operaciones/mes
3. Explora la biblioteca de conectores

### n8n (open source, autoalojado o cloud)

1. Opción cloud: crea cuenta en app.n8n.io
2. Opción local con Docker (más técnica, sin límite de ejecuciones): el repositorio incluye un stack listo en `docker/` (n8n + PostgreSQL). Ejecuta `docker compose -f docker/docker-compose.yml up -d` y abre `http://localhost:5678`. Ver `docker/README.md` para el detalle y las contrapartidas frente al cloud. Es opcional — el plan cloud gratuito alcanza para el curso.

### Microsoft Power Automate

1. Si tienes cuenta Microsoft 365 educativa, Power Automate ya está incluido
2. URL: powerautomate.microsoft.com
3. Inicio de sesión con tu cuenta universitaria si está disponible

---

## 4. RPA clásico (referencia del contenido oficial)

### UiPath Community Edition

1. Descarga desde uipath.com/developers/community-edition-download
2. Requiere Windows (para el Studio completo); UiPath StudioX es más accesible
3. Crea cuenta gratuita para acceder al programa educativo

---

## 5. Chatbots y asistentes virtuales

### Voiceflow (recomendado — sin código)

1. Crea cuenta en voiceflow.com
2. Plan gratuito: proyectos ilimitados
3. Permite crear flujos de conversación visualmente y probarlos en el navegador

### Landbot

1. Crea cuenta en landbot.io
2. Plan gratuito: 100 conversaciones/mes

### Dialogflow CX (Google)

1. Necesitas cuenta de Google
2. URL: dialogflow.cloud.google.com
3. Activa el proyecto en Google Cloud Console (requiere tarjeta, pero tiene capa gratuita generosa)

---

## 6. Marketing automation

### HubSpot CRM + Marketing Hub (gratuito)

1. Crea cuenta en hubspot.com/products/crm
2. El CRM gratuito incluye email marketing básico, formularios y seguimiento de contactos
3. Programa educativo HubSpot for Startups/Education puede dar acceso a funciones premium

### Mailchimp

1. Crea cuenta en mailchimp.com
2. Plan gratuito: hasta 500 contactos y 1,000 emails/mes
3. Suficiente para el laboratorio de campañas automatizadas

---

## 7. Dashboards y KPIs

### Looker Studio (Google Data Studio)

1. URL: lookerstudio.google.com
2. Completamente gratuito
3. Conecta con Google Sheets (perfecto para el proyecto integrador)
4. Necesitas cuenta de Google

### Power BI Desktop

1. Descarga gratuita: powerbi.microsoft.com/en-us/desktop/
2. Solo Windows; para Mac usa Power BI en la web con cuenta educativa Microsoft

---

## 8. Verificación de cuentas

Antes del tercer laboratorio, verifica que tienes acceso a:

| Herramienta | ¿Cuenta creada? | ¿Login verificado? |
|------------|----------------|-------------------|
| Tu copia del repo en GitHub | ☐ | ☐ |
| Bizagi o draw.io | ☐ | ☐ |
| Zapier o Make | ☐ | ☐ |
| Voiceflow o Landbot | ☐ | ☐ |
| HubSpot o Mailchimp | ☐ | ☐ |
| Looker Studio | ☐ | ☐ |

Si tienes problemas con alguna herramienta, publica en el foro del aula virtual con captura de pantalla del error.
