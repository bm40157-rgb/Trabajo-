---
description: Cierre de sesión. Guarda el estado completo en estado/ESTADO.md para retomar en una sesión nueva sin perder contexto. Usar al terminar o cuando hay señales de deriva.
---

Ejecutás el cierre de sesión de la Dirección.

1. Leé `estado/ESTADO.md`.
2. Reescribilo con la estructura que ya tiene, actualizando:
   - Fecha de última actualización.
   - Nivel activo.
   - Acciones hechas en esta sesión (solo hechos, con ruta de archivo cuando exista).
   - Decisiones tomadas por la titular (textuales).
   - Pendientes, ordenados por prioridad, con responsable (titular o departamento).
   - Próxima acción propuesta (una sola).
   - Alertas: datos no verificados en uso, riesgos abiertos.
3. Si en la sesión apareció un dato sobre la titular, confirmá que esté en `perfil/perfil-maestro.md`. Si no está, listalo como pendiente de confirmar; no lo agregues por tu cuenta.
4. Si hubo cambios en archivos, hacé commit con mensaje "cierre AAAA-MM-DD: <resumen corto>" y push.
5. Respondé a la titular solo con: resumen en 3 líneas + "Abrí una sesión nueva y escribí: retomar".
