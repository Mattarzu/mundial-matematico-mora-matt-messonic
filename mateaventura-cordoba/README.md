# MateAventura Córdoba (v18)

Juego de matemática para 5.º grado de la Escuela Dalmacio Vélez Sarsfield, Córdoba. Tiene 3 mundos × 4 niveles, más la **Isla de los Exploradores** (modo adaptado, en MAYÚSCULAS), un mapa de isla fantástica con lugares de Córdoba y devoluciones pedagógicas.

Está publicado como aplicación web de Google Apps Script:

https://script.google.com/macros/s/AKfycby6MjHtjDW5oh3NnsMRH3_9OzJ0FbqjSUlYjXy22Yi4wPf6Il8yqBtEPewM4OryYMmw1g/exec

## Cómo desplegar

1. Creá un proyecto de Apps Script.
2. Pegá `Code.gs` y un archivo HTML llamado `Index` (el contenido de `Index.html`).
3. En Propiedades del script configurá `SHEET_ID`, `TEACHER_SECRET` y `MAIL_TO`. Nunca subas esos valores al repositorio.
4. Implementá como aplicación web: **Ejecutar como yo** y acceso **Cualquier usuario**.

Las plantillas SVG de `Index.html` no deben incluir `xmlns`.
