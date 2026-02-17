# MiniLearn Web

Landing page estática para MiniLearn (HTML/CSS/JS) con selector de idioma ES/EN.

## Estructura
- `docs/` sitio para GitHub Pages
- `docs/index.html` contenido y estructura
- `docs/styles.css` estilos
- `docs/main.js` interacciones e i18n
- `docs/assets/` imágenes y favicon

## Desarrollo local
Abre `docs/index.html` en el navegador.

## Deploy
Cloudflare Pages sirve el contenido estático desde `docs/`.

## Notas
- Cambios de texto deben hacerse en `docs/main.js` (objeto `translations`).
- Para actualizar el cache en producción, incrementa el querystring de `styles.css` y `main.js` en `docs/index.html`.
- El idioma por defecto se ajusta automáticamente por dominio:
  - `minilearn.cl` (y subdominios): español (`es`).
  - `minilearn.app` (y subdominios): inglés (`en`).
