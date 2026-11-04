# Las Misiones de Mora, Matt y Messonic — Mundial Matemático

Sitio interactivo para Matemática de 5.º grado de Córdoba, Argentina. **La aplicación está íntegramente en `index.html`**: HTML, CSS, JavaScript, gráficos SVG y sonidos Web Audio API, sin dependencias ni compilación.

Incluye 4 mundos, 20 microtutoriales, 48 desafíos autocorregibles, hasta 3 intentos por consigna, pistas e intento guiado, registro de desempeño, informes curriculares y opción **Guardar como PDF / Imprimir**.

## Publicación en GitHub Pages

1. Abrí **Settings → Pages** en este repositorio.
2. En **Build and deployment**, elegí **Deploy from a branch**.
3. Seleccioná la rama **main** y el directorio **/(root)**, luego **Save**.
4. Una vez desplegado, el enlace público será `https://mattarzu.github.io/mundial-matematico-mora-matt-messonic/` (comprobar que GitHub Pages confirme la URL antes de distribuir).

## Envío automático del informe al docente

Antes de usar con estudiantes, creá un formulario en https://formspree.io/ y verificá que envíe correos al destinatario docente correcto (`messiaprende@gmail.com`). En `index.html`, editá `CONFIG.formspreeEndpoint` y poné la URL pública del formulario, por ejemplo `https://formspree.io/f/xxxxxxxx`. Publicá la actualización.

**Sin ese endpoint, el sitio no envía correos:** informa claramente que falta la configuración; siempre permite imprimir/guardar PDF desde el navegador. Jamás incluyas secretos, contraseñas ni claves privadas en `index.html`.

## Privacidad y evaluación

Los nombres y los resultados no están alojados en este repositorio: se guardan localmente en el navegador del alumno y solo se envían mediante Formspree si existe endpoint configurado y autorización. En equipos compartidos, borrar la partida después de guardar el informe. La persistencia entre computadoras no está implementada.

Las categorías de logro son una **rúbrica formativa construida para el juego**, no criterios de acreditación oficiales. Referencias: *Progresiones de Aprendizaje para Matemática* (Córdoba, 2025), 5.º grado, pp. 43–49; cuadernillo *Las misiones de Mora, Matt y Messonic*, pp. 1–49.
