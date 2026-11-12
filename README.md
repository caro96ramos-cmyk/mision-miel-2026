# MISIÓN MIEL · Museo virtual 2026

Sitio web estático para la Muestra Pedagógica 2026 de 5.º grado, Instituto Privado Rivadavia.

## Abrir el sitio

Abrí `index.html` en Chrome o Edge. No necesita instalación ni servidor para ver las páginas, fotografías, videos y audios locales. Las tipografías externas requieren conexión a internet; sin conexión se utilizan fuentes del sistema.

## Publicar en GitHub Pages

1. Creá un repositorio **público** llamado `mision-miel` en GitHub (solo después de verificar las autorizaciones de publicación de fotos, voces y videos).
2. Subí **todo el contenido** de esta carpeta, manteniendo `index.html` en la raíz y conservando las carpetas `assets`, `css` y `js`.
3. En Settings → Pages → Build and deployment elegí **Deploy from a branch**, rama `main`, carpeta `/(root)` y guardá.
4. Abrí `https://TU-USUARIO.github.io/mision-miel/` después del despliegue.
5. GitHub no permite subir por la interfaz web archivos de más de 25 MiB. Los videos de esta entrega son inferiores a ese límite, pero el conjunto puede tardar en cargarse. Para videos más grandes, usá Git LFS con precaución (no siempre apto para Pages) o alojá videos en un servicio externo e insertá un reproductor autorizado.

## Editar y agregar contenido

- Fotografías: guardá los JPG en `assets/fotos/`.
- Videos: guardá los MP4 y sus miniaturas en `assets/videos/`.
- Audios: guardá OGG/MP3 en `assets/audios/`.
- Documentos: guardá PDF/DOCX en `assets/documentos/`.
- Para que aparezcan en las galerías, agregá un objeto correspondiente al arreglo `photos`, `videos`, `audios` o `docs` en `js/contenido.js` (el sitio usa ese archivo). `js/contenido.json` es una copia legible para referencia; no se carga directamente.
- Para modificar textos educativos o títulos, editá `index.html`.
- Para modificar estilos y colores, editá `css/estilos.css`.

## Contenidos y transparencia

- Se incluyeron siete fotografías únicas, siete videos únicos (se descartaron cuatro copias exactas), dos audios y nueve documentos PDF/DOCX.
- Los videos se identifican como «Registro audiovisual 01…07» porque no se verificó individualmente su contenido semántico. Cambiá los títulos cuando confirmes cada tema.
- Los objetivos pedagógicos son texto complementario propuesto, no una transcripción de una planificación institucional.
- La información sobre anatomía, polinización, historia y miel se basa en documentos proporcionados, con aclaraciones de seguridad. Los documentos originales se conservan sin modificar en Biblioteca.
- El logo institucional no fue identificado de forma inequívoca en los materiales disponibles; el encabezado usa una identidad tipográfica temporal. Reemplazala por el logo oficial cuando lo confirmes.

## Privacidad

**Antes de publicar:** comprobá que la institución y las familias hayan autorizado la difusión pública de imágenes, videos y voces de menores. GitHub Pages con repositorio público no ofrece acceso privado a los medios. Para materiales no autorizados, no los subas: eliminá sus archivos y entradas del catálogo o utilizá un sistema de acceso restringido.


## Actualización noviembre 2026
- 20 fotografías nuevas con filtros por temática (27 fotografías en total).
- Tercer audio: «La miel a través del tiempo: tradición, historia y tecnología».
- Los nombres y descripciones se editan en `js/contenido.json` y deben sincronizarse con `js/contenido.js` para que se reflejen en la página.
- Antes de publicar fotografías o voces de estudiantes en un sitio público, verificá las autorizaciones correspondientes.
