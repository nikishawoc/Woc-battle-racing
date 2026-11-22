# WOC Battle Racing Web

Proyecto de juego multijugador por turnos para Chrome en Android.

## Publicación en Render

1. Subir **el contenido descomprimido** del ZIP `WOC_Battle_Racing_WEB_0_73_0_Chrome_Internet.zip` a la raíz de este repositorio (no subir solamente el ZIP).
2. Confirmar que `server.js`, `package.json`, `render.yaml` y la carpeta `public/` estén en la raíz.
3. En Render, crear un servicio web desde este repositorio (o Blueprint usando `render.yaml`).
4. Build: `npm install --omit=dev`; Start: `npm start`; Health: `/healthz`.
5. Abrir el enlace HTTPS del servicio en Chrome. Render debe admitir WebSockets.

**Importante:** el repositorio aún no contiene el juego completo hasta subir el ZIP descomprimido. Este README es solo la preparación para desplegarlo.
