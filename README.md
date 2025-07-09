# tv4you
free tv from around the  world  , ready for you.
# 📺 Mi TV Station - Multisección M3U Viewer

Visualiza listas de canales `.m3u` organizadas por secciones temáticas o regionales (Colombia, USA, Deportes, etc.) con un diseño moderno tipo carrusel.

---

## 🚀 Características

- 🎞️ Carga múltiples archivos `.m3u` en paralelo
- 🖼️ Muestra los logos de cada canal (`tvg-logo`) o los genera automáticamente
- ▶️ Botón de reproducción directa para cada canal
- 🎨 Interfaz oscura, minimalista y responsive
- 💾 Compatible con GitHub Pages

---

## 🧩 Estructura esperada

Este proyecto espera que subas los siguientes archivos `.m3u` junto al `index.html`:

- `update.m3u` → Lista principal
- `colombia.m3u` → Canales de Colombia 🇨🇴
- `usa.m3u` → Canales de USA 🇺🇸
- `deportes.m3u` → Canales deportivos ⚽

Puedes cambiar los nombres de los archivos o agregar más secciones editando el bloque en `index.html`:

```js
document.addEventListener("DOMContentLoaded", () => {
  cargarSeccion("update.m3u", "📦 Lista Principal");
  cargarSeccion("colombia.m3u", "🇨🇴 Colombia");
  cargarSeccion("usa.m3u", "🇺🇸 USA");
  cargarSeccion("deportes.m3u", "⚽ Deportes");
});
