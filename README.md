# SugarCombat — Política de Privacidad

Página pública de política de privacidad del juego **SugarCombat** (match-3 de caramelos, Godot), desarrollada por **Gerica Herrera**. Contacto: iasincodigo32@gmail.com.

Esta página es la URL de privacidad que se declara en Google Play Console al publicar el juego.

## Archivos

| Archivo | Qué es |
|---|---|
| `index.html` | La política de privacidad completa. HTML autocontenido (CSS en `<style>`, sin imágenes externas ni JavaScript). |
| `README.md` | Este archivo: instrucciones de publicación y notas para Play Console. |

## Cómo publicarlo con GitHub Pages

1. Crea un repositorio público en GitHub llamado **`sugarcombat-privacy`** (usuario `iasincodigo32-cmyk`).
2. Sube `index.html` y `README.md` a la raíz del repositorio, en la rama **`main`**.
3. En el repositorio, ve a **Settings → Pages**.
4. En "Build and deployment", elige **Deploy from a branch**, rama **`main`** y carpeta **`/ (root)`**. Guarda.
5. Espera 1–2 minutos a que GitHub Pages despliegue el sitio.

La URL resultante será:

**https://iasincodigo32-cmyk.github.io/sugarcombat-privacy/**

## Notas para Google Play Console

- Pega esa URL en Play Console, en la ficha del juego: **Política de privacidad** (sección de presencia en Google Play / información de la app).
- La sección **«Seguridad de los datos»** de Play debe coincidir con lo que dice la página:
  - **Datos que se comparten:** el nombre de usuario (apodo dentro del juego), el nivel, el avatar y el banner elegidos, la puntuación y las acciones de juego se comparten **con el otro jugador** durante las partidas online, a través del relay de Cloudflare. Es el propio rival quien los recibe en su dispositivo.
  - **Datos que se recopilan:** ninguno en servidores propios. El progreso (diamantes, nivel, estadísticas, mazo, preferencias) se guarda **solo en el dispositivo** del jugador.
  - **Sin** anuncios, **sin** SDK de analíticas de terceros, **sin** compras con dinero real (los diamantes son virtuales y se ganan jugando), **sin** ubicación, contactos, cámara, micrófono ni fotos.
  - El servidor online (Cloudflare Workers / Durable Objects) solo retransmite la partida: no crea cuentas, no usa base de datos de jugadores y no conserva el estado al terminar.
- Si en el futuro el juego cambia (por ejemplo, si se añadieran anuncios o cuentas), hay que actualizar **a la vez** esta página y la sección de Seguridad de los datos de Play.

## Actualizaciones

Última actualización de la política: **8 de noviembre de 2026**. Al cambiar la política, actualiza la fecha en `index.html` (arriba y en el pie) y en este README.
