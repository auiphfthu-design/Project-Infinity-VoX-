# Infinity VoX

Navegador / app web instalable (PWA). Todo en `index.html`, sin servidor.

## Subirlo a GitHub y que se pueda instalar
1. Creá un repositorio nuevo en github.com y subí **todos** los archivos de esta carpeta (no el zip).
2. Settings → Pages → Source: `Deploy from a branch` → Branch: `main` / `(root)` → Save.
3. En 1–2 minutos queda en `https://TU-USUARIO.github.io/NOMBRE-DEL-REPO/`.
4. Abrí ese link en Chrome (Android) → ⋮ → **Instalar app** (o "Agregar a pantalla de inicio").

Se instala con su ícono, abre a pantalla completa y funciona sin internet (las búsquedas sí necesitan internet).

## Archivos
- `index.html` — la app
- `manifest.webmanifest` + `icon-*.png` — datos e íconos para instalar
- `sw.js` — service worker (modo sin conexión)
- `.nojekyll` — para que GitHub Pages sirva todo tal cual

Para actualizar: reemplazá `index.html` en GitHub. Si cambiás archivos, subí la versión `V` en `sw.js` (`ivx-v2`, …).
