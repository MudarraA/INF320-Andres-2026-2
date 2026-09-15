# Guía de Estudio — Parcial 2

**INF 320 Automatización de Procesos de Negocios · Semestre 2026-2**  
**Semana 11 · Cubre: Módulo 3 completo + avance Módulo 4**

---

## Formato del examen

| Sección | Peso | Tipo de preguntas |
|---------|------|------------------|
| Teoría conceptual | 30% | Definiciones, diferencias, conceptos de integración |
| Plataformas y herramientas | 30% | Comparar RPA vs. no-code, criterios de selección |
| Caso práctico | 40% | Diseñar conceptualmente un workflow con integración y manejo de excepciones |

**Duración**: ~90 minutos · **Sin IA, sin dispositivos**

---

## Módulo 3 — Herramientas BPM, RPA y no-code

### BPM vs. RPA

1. Define BPM y RPA. ¿En qué se diferencian fundamentalmente?

2. Completa la tabla:
   | Aspecto | BPM | RPA |
   |---------|-----|-----|
   | ¿Es una disciplina o una tecnología? | | |
   | ¿Requiere modificar los sistemas existentes? | | |
   | Herramientas ejemplo | | |
   | Ciclo de vida que gestiona | | |

3. ¿Son BPM y RPA excluyentes o complementarios? Da un ejemplo donde se usen juntos.

### Plataformas RPA clásicas

4. Nombra los 3 principales proveedores de RPA clásico y una característica diferenciadora de cada uno.

5. ¿Cuándo es preferible usar RPA clásico en lugar de una herramienta no-code? Da un caso concreto de e-commerce donde RPA clásico sea la mejor opción.

### Plataformas no-code/IA

6. Explica la diferencia entre Zapier, Make y n8n en términos de: facilidad de uso, número de conectores, y plan gratuito.

7. Un equipo de ventas de una tienda en línea quiere automatizar: "cuando alguien llena el formulario de contacto de nuestro sitio, agregar el contacto al CRM y enviar un email de bienvenida automático". ¿Qué herramienta elegirías? ¿Por qué?

### Integración de sistemas (API, webhook, conector)

8. Explica la diferencia entre una API y un webhook con una analogía de la vida cotidiana.

9. En Zapier, ¿cuál es la diferencia entre un trigger por polling y un trigger instantáneo (webhook)?

10. Diseña el flujo de datos de la siguiente integración:
    *"Cuando un cliente hace un pedido en la tienda, se debe actualizar el inventario en Google Sheets y notificar al proveedor por email si el stock queda por debajo de 10 unidades."*
    Indica: trigger, pasos, datos que fluyen entre cada paso.

---

## Módulo 4 — Avance: Principios de diseño de workflows

11. ¿Qué significa que un workflow sea "trazable"? ¿Por qué es importante para la auditoría?

12. Dibuja o describe un workflow que incluya:
    - Un trigger (qué lo inicia)
    - Al menos una condición (if-then)
    - Al menos un manejo de excepción (qué pasa si algo falla)
    - Al menos una acción final

13. ¿Cuáles son los 4 principios de diseño de procesos automatizados? Define brevemente cada uno.

---

## Caso práctico integrador (tipo Sección 3 del examen)

14. Una pyme panameña de venta de ropa en línea tiene el siguiente proceso manual: 
    - El cliente hace un pedido por WhatsApp
    - Un empleado verifica el inventario en una hoja de cálculo
    - Si hay stock: el empleado responde al cliente confirmando y actualiza la hoja
    - Si no hay stock: el empleado responde disculpándose
    - El empleado registra la venta en otra hoja de cálculo

    **Tarea**: Diseña un workflow automatizado que reemplace este proceso manual:
    a) Indica qué plataforma no-code usarías y por qué.
    b) Describe el trigger del flujo.
    c) Describe todos los pasos del flujo, incluyendo la rama para "sin stock" (excepción).
    d) ¿Qué servicios estarían integrados (conectados)?
    e) ¿Qué datos fluyen entre los pasos?
