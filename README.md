# electo-legal

Páginas legales públicas de la aplicación **Electo**. Actualmente: política de privacidad (`index.html`).

- Página estática, sin cookies, sin analítica, sin fuentes remotas y sin dependencias.
- Estado: datos del responsable y del correo de contacto completados (Javier García Martínez, `electo.privacidad@gmail.com`). Pendiente de publicación.
- URL prevista: `https://reelswapai.github.io/electo-legal/`.

## Archivos

| Archivo | Uso |
|---|---|
| `index.html` | Política de privacidad (HTML + CSS en un solo archivo). |
| `.nojekyll` | Evita que GitHub Pages procese el sitio con Jekyll. |
| `README.md` | Este documento. |

## Antes de publicar

1. Comprobar que no quedan marcas `[PENDIENTE: …]` (`node scripts/legal/verify-legal-page.js --publish`, desde el repositorio principal de Electo).
2. Actualizar la fecha de «Última actualización» si cambia el texto.

## Publicar en GitHub Pages (cuando se autorice)

1. Crear en GitHub un repositorio **público** llamado `electo-legal`.
2. Subir el contenido de esta carpeta a la raíz del repositorio (rama `main`).
3. En el repositorio: **Settings → Pages → Build and deployment → Source: Deploy from a branch → Branch: `main` / `(root)` → Save**.
4. Esperar uno o dos minutos. La URL pública será `https://reelswapai.github.io/electo-legal/`.
5. Abrir la URL en el móvil y comprobar que se ve el texto completo y que no quedan marcas `[PENDIENTE: …]`.
6. Usar esa URL como «URL de la política de privacidad» en App Store Connect y, después, enlazarla desde la aplicación.
