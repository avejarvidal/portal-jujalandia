# Portal Oficial de Jujalandia 🍅

Sitio web humorístico de la "República de Jujalandia", una micronación familiar fundada por los Abuelos tras el hallazgo de la Caja Dorada y el Tomate Gigante.

## Ver el sitio

Abrí `index.html` en un navegador, o serví la carpeta con cualquier servidor estático (por ejemplo `npx serve` o GitHub Pages). No requiere build ni instalación: React, ReactDOM y Babel se cargan desde CDN en tiempo de ejecución.

## Contenido

- **Inicio** — bienvenida, bandera nacional, estadísticas, símbolos patrios y un skyline 3D animado de Nueva Juja.
- **Historia**, **Gobierno**, **Cultura**, **Naturaleza**, **Relaciones Exteriores**, **Turismo** y **Leyes** — los "capítulos" del país.
- **Inmigración** — formulario de ciudadanía que genera un pasaporte oficial descargable (foto por cámara o archivo + `<canvas>`).

## Estructura

```
index.html       Página completa (todas las secciones viven en un solo archivo)
support.js       Runtime que interpreta el template y monta React (generado, no editar a mano)
uploads/         Imágenes usadas en el sitio
```

## Créditos

Ilustración "Anatomía de un Estado Surrealista" generada con Gemini Notebook.
