# Colpensiones en cifras

App ciudadana (PWA) de **Vibras Positivas HM**: cuánto le gira la Nación a Colpensiones de 2012 a 2027, datos de población del DANE, lo que pasa en septiembre de 2026 y las dos posturas del debate.

Dirección: https://haroldco45.github.io/colpensiones-en-cifras/

## Publicar en GitHub Pages
1. Cree el repositorio público `colpensiones-en-cifras` en la cuenta `haroldco45`.
2. Suba todos los archivos de esta carpeta a la raíz del repositorio (incluido `.nojekyll`).
3. Settings → Pages → Source: *Deploy from a branch* → rama `main`, carpeta `/ (root)` → Save.
4. Espere 1 o 2 minutos y abra la dirección de arriba.

## Actualizar
- Edite `index.html` y súbalo.
- En `sw.js` cambie `colpensiones-v1` por `colpensiones-v2` (y así sucesivamente) para que los celulares carguen la versión nueva.
- Si cambia `og-image.png`, suba el número en `?v=1` dentro de `index.html` para que WhatsApp muestre la imagen nueva.

## Archivos
- `index.html` — la app completa
- `manifest.webmanifest`, `sw.js` — instalación en el celular y uso sin señal
- `icon-*.png`, `apple-touch-icon.png` — íconos
- `og-image.png` — vista previa al compartir por WhatsApp (1200×630)

Fuentes de datos: PGN (gráfica de @soyjerome_), DANE Estadísticas Vitales, Ministerio del Trabajo. Corte: 26 de septiembre de 2026, hora de Colombia.
