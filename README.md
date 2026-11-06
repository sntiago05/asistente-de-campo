# Asistente de Campo

Aplicación web **instalable (PWA)** pensada para un operador de campo: permite diagnosticar una falla o seguir una guía paso a paso desde el móvil.

## Tecnologías
- HTML, CSS (Tailwind-style utilities) y JavaScript vanilla
- `manifest.json` e icono para instalarla en pantalla de inicio
- `sw.js` (Service Worker) para funcionamiento sin conexión

## Cómo ejecutar
Sirve la carpeta con cualquier servidor estático, por ejemplo:
```bash
npx serve .
```
Luego abre la URL que indique. Los Service Workers requieren `localhost` o HTTPS.

## Estado
Prototipo de front-end, sin backend.
