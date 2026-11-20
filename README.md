# Radlands Bot Híbrido (PWA Offline para GitHub Pages)

Bot táctico 100% offline de **Radlands** (edición base en español, Maldito Games) para jugar con tus cartas físicas contra un oponente virtual con mazo compartido fiel, voz y tablero interactivo.

## Cómo publicarlo en GitHub Pages en 1 minuto (sin consola)

1. Creá un repositorio nuevo en [github.com/new](https://github.com/new) (por ejemplo `radlands-bot`, en modo **Public** para que funcione GitHub Pages gratis).
2. Tocá **uploading an existing file** y arrastrá todos los archivos de esta carpeta (`index.html`, `manifest.webmanifest`, `sw.js`, `icon.svg`, `icon-192.png`, `icon-512.png`, `.nojekyll`, `README.md`). Confirmá con **Commit changes**.
3. Andá a **Settings → Pages → Build and deployment**:
   - **Source:** `Deploy from a branch`
   - **Branch:** `main` / `/ (root)` → **Save**.
4. Esperá ~30 segundos y abrí `https://<tu-usuario>.github.io/radlands-bot/`.

## Qué funciona en ese enlace

- **Botón rojo 🎙️ y modo Manos libres:** al estar en HTTPS real sin sandbox, Chrome y Edge habilitan el micrófono con un clic en tu Chromebook, PC y Android (en iPhone funciona el dictado del teclado con **⚡ Auto-dictado ON**).
- **Instalable como app (PWA):** tocá **📲 Instalar app** en la barra superior (o **Agregar a pantalla de inicio** en iPhone/Android). Después de abrirla una vez, corre **100% offline** incluso en modo avión.
