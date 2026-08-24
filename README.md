# Portal Oficial de Jujalandia 🍅

Sitio web humorístico de la "República de Jujalandia", una micronación familiar fundada por los Abuelos tras el hallazgo de la Caja Dorada y el Tomate Gigante.

## Ver el sitio

Abrí `index.html` en un navegador, o serví la carpeta con cualquier servidor estático (por ejemplo `npx serve` o GitHub Pages). No requiere build ni instalación: React, ReactDOM y Babel se cargan desde CDN en tiempo de ejecución.

## Contenido

- **Inicio** — bienvenida, bandera nacional, estadísticas, símbolos patrios y un skyline 3D animado de Nueva Juja.
- **Historia**, **Gobierno**, **Cultura**, **Naturaleza**, **Relaciones Exteriores**, **Turismo** y **Leyes** — los "capítulos" del país.
- **Inmigración** — elegís un avatar y generás un apodo oficial (sin fotos ni nombres reales) para descargar un pasaporte generado en `<canvas>`. El pasaporte lleva el número de ciudadano embebido en el propio PNG (metadato `tEXt`), sin servidor.
- **Cómics** — biblioteca de historietas con lector de páginas (parte del "Centro Cultural" de la Plaza).
- **Juegos** — "Atrapá el Tomate" y "Memoria de Jujalandia". Requieren subir el archivo del pasaporte: el sitio lee el número de ciudadano del PNG y guarda el mejor puntaje por ciudadano en el navegador.
- **La Plaza de Jujalandia** (dentro de Turismo) — recorrido 3D inspirado en ["La Plaza"](https://es.wikipedia.org/wiki/Enlaces_(Chile)) (Proyecto Enlaces, Mineduc Chile, años 90): un Kiosco, un Centro Cultural, un Correo y un Museo que llevan a distintas secciones del sitio. También pide el pasaporte.

## Administrar contenido (ticker y cómics)

Abrí `admin/index.html` (en el sitio publicado: `/admin/`). Ahí podés editar las noticias del zócalo y los cómics, y descargar los archivos `ticker.json` / `comics.json` actualizados. Para publicarlos: subilos a la carpeta `content/` del repositorio en GitHub (editar el archivo o "Add file → Upload files" reemplazando el existente) y hacer commit. El panel no publica solo — es un editor local que genera el archivo para subir a mano.

## Estructura

```
index.html       Página completa (todas las secciones viven en un solo archivo)
support.js       Runtime que interpreta el template y monta React (generado, no editar a mano)
uploads/         Imágenes usadas en el sitio
content/         ticker.json y comics.json — contenido editable desde admin/
admin/           Panel de administración simple (sin login, edita en el navegador)
```

## Créditos

Ilustración "Anatomía de un Estado Surrealista" generada con Gemini Notebook.
