# bitbunkerhq.github.io

# BitBunkerHQ – Estructura

- `index.html`: home con Overview de Monitoring + Indexación + BI.
- `experiments/`: una página por prueba/caso (case study).
- `images/YYYY-MM/<slug>/`: capturas por prueba (prefijo 01-, 02-…).
- `assets/og/`: imágenes Open Graph (index y cada experimento).
- `assets/favicons/`: favicons y manifest.

## Flujo para nueva prueba
1. Crear slug (ej. `loadtest-v2`).
2. Capturas → `/images/AAAA-MM/loadtest-v2/`.
3. Duplicar una página en `/experiments/` → `loadtest-v2.html` y actualizar `<head>`.
4. Crear OG → `/assets/og/experiments/loadtest-v2-og.png` (1200×630).
5. Añadir enlace en “Todas las pruebas” (en `index.html`, arriba del listado).
6. (Opcional) actualizar Overview para destacar la nueva.
