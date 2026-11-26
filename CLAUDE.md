# Fotos OurVision

Fotos de productos para Walmart (`walmart/`) y la tienda web (`tienda/`). Las URLs de estos archivos están
guardadas en la base de Supabase (tabla `imagenes`): **no renombrar ni borrar fotos** sin crear antes la
migración que actualiza esas URLs en `Ourvision-ventas`.

Responder siempre en español. Datos de productos: `atlas/` de `Reliquias-OurVision`.

## Trabajo en equipo (dos personas, cada una con su Claude)

Reglas completas: `colaboracion/TRABAJO-EN-EQUIPO.md` en `Ourvision-ventas`. Tablero: `colaboracion/EN-CURSO.md`.
- Al empezar y antes de editar `atlas/` o SQL: `git pull --rebase`. Al terminar cada tarea: commit chico y push en el momento.
- Tareas grandes (varios archivos, base de datos, Cloudflare): anotarlas en `EN-CURSO.md` y subirlo antes de empezar; borrarlas al terminar.
- SQL: reservar el número en `supabase/REGISTRO-SQL.md` (fila ⏳ + push) antes de escribir el archivo. No ejecutar un SQL ⏳ a nombre de la otra persona.
- Atlas: editar el original (`Reliquias-OurVision/atlas/`) y la copia de ventas, y subir los dos juntos. En un conflicto, conservar ambos datos y preguntar.
- Antes de `DROP`, `TRUNCATE`, `DELETE`/`UPDATE` sin `WHERE`, cambios de RLS, `push --force`, `reset --hard` o borrar ramas/proyectos:
  pedir confirmación a la persona de esta sesión (no a la otra). Quien está en la sesión decide.
- Nunca `git push --force` sobre `main` ni borrar trabajo ajeno.
