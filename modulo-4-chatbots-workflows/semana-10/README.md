# Semana 10 — Principios de Diseño de Workflows Automatizados

**Módulo 4: Implementación de chatbots y asistentes virtuales en los procesos de negocios**

---

## Objetivos de aprendizaje

- Aplicar buenas prácticas de diseño: simplicidad, modularidad, trazabilidad, manejo de excepciones.
- Construir un workflow que incluya al menos una rama condicional para manejar errores o excepciones.

---

## Contenidos de la semana

### Teoría (martes)

1. Principios de diseño de procesos automatizados:
   - **Simplicidad**: que un flujo haga UNA cosa bien; evitar megaflujos imposibles de mantener
   - **Modularidad**: dividir en sub-flujos reutilizables
   - **Trazabilidad**: cada paso debe quedar registrado (logs, confirmaciones)
   - **Manejo de excepciones**: ¿qué pasa si el email falla? ¿si el pago es rechazado? ¿si el inventario está en cero?
2. Documentación de workflows: comentar los pasos, nombrar las rutas, etiquetar los filtros

### Práctica/Laboratorio (jueves)

**Lab 5**: construir un workflow con al menos una rama condicional de manejo de excepciones

Ejemplo: si el pago es aprobado → confirmar pedido; si el pago falla → notificar al cliente y marcar como pendiente.

---

## Entregable de la semana

**Laboratorio 5** — Workflow con manejo de excepciones

- Sube: captura del flujo completo con la rama condicional + descripción de cada rama
- Archivo: `modulo-4-chatbots-workflows/semana-10/lab05-workflow-excepciones/README.md`

---

## Patrón de manejo de excepciones en no-code

```
TRIGGER: Nuevo pedido recibido
    │
    ▼
[Verificar inventario]
    │
    ├── SI hay stock → [Reservar stock] → [Confirmar pedido] → [Notificar cliente ✅]
    │
    └── NO hay stock → [Notificar cliente ❌] → [Agregar a lista de espera]
                              │
                              ├── [Alerta al equipo de compras]
                              └── [Actualizar ETA en hoja de cálculo]
```

---

## Checklist de calidad de un workflow antes de entregarlo

- [ ] ¿Tiene nombre descriptivo cada paso?
- [ ] ¿Existe al menos una rama para el caso de error?
- [ ] ¿Los datos que pasan entre pasos están claramente definidos?
- [ ] ¿Si el workflow fallara, cómo sabrías en qué paso falló?
- [ ] ¿Hay algún paso que exponga datos personales innecesariamente?
