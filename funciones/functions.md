# Documentación técnica de mi tarjeta personal

## Decisiones semánticas

- **`<!DOCTYPE html>`**: le dice al navegador que el documento sigue las reglas modernas de la web.
- **`<html lang="es">`**: se usa para indicar que la página está en español.
- **`<head>`**: actúa como contenedor de los metadatos y la configuración técnica del sitio.
- **`<meta charset="UTF-8">`**: permite visualizar las tildes y la ñ.
- **`<meta name="viewport">`**: permite que la pagina sea responsivo.
- **`<header>`**: define el bloque superior para el encabezado.
- **`<main>`**: encapsula el cuerpo de contenido único y más relevante del documento.
- **`<section>`**: para organizar la informacion por fragmentos.
- **`<h1>`**: El encabezado principal.
- **`<h2>`**: los subtitulos del encabezado.
- **`<p>`**: se usa para escribir los párrafos.
- **`<time>`**: permite que las fechas sean interpretadas por navegadores.
- **`<strong>`**: resalta fragmentos importantes.
- **`<em>`**: sirve para colocar la letra a cursiva.
- **`<footer>`**: el pie de página.
- **`<address>`**: proporcionar datos de contacto.
- **`<a>`**: lo utlice para que cuando le de click al correo, me lleve directamente allí.

## Árbol DOM (visual)

```text
html
├── head
│   ├── meta
│   ├── meta
│   └── title
└── body
    ├── header
    │   ├── h1
    │   └── p
    ├── main
    │   ├── section
    │   │   ├── h2
    │   │   ├── p
    │   │   └── time
    │   └── section
    │       ├── h2
    │       ├── p
    │       ├── strong
    │       └── em
    └── footer
        └── address