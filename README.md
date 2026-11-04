# Mi Contenido

App web para planificar mi contenido de redes sociales: Instagram, TikTok, YouTube y Threads.

- Funciona en el navegador, sin instalar nada, sin cuentas y sin servidores.
- Los posts se guardan en el navegador (localStorage) y las fotos y videos en IndexedDB.
- Toda la app está en el archivo `index.html`.

## Archivos

| Archivo | Para qué sirve |
|---|---|
| `index.html` | La app completa |
| `FORMATO-IA.md` | Instrucciones para pedirle a una IA un plan semanal que la app pueda importar |
| `manifest.webmanifest`, `icon-*.png`, `sw.js` | Permiten agregarla a la pantalla de inicio del iPhone, con nombre e ícono, y abrirla sin internet |

## 1. Abrirla en tu computadora

1. En esta página de GitHub, toca el botón verde **Code** y luego **Download ZIP**.
2. Busca el ZIP en tu carpeta de **Descargas**, haz doble clic para descomprimirlo y entra a la carpeta `mi-contenido-main`.
3. Haz doble clic en **`index.html`**. Se abre en tu navegador. Te recomiendo Chrome, Edge o Safari.
4. Para no tener que buscarla, guárdala en favoritos (Ctrl + D en Windows, Cmd + D en Mac).

> Lo que guardes en la computadora vive **solo en ese navegador de esa computadora**. Para pasarlo a otro lado, usa **⋯ Más → Exportar respaldo**.

## 2. Activar GitHub Pages, para abrirla desde el celular con un link

1. En GitHub, entra a este repositorio (`mi-contenido`).
2. Toca **Settings** (⚙️, arriba a la derecha de la página del repositorio).
3. En el menú de la izquierda, toca **Pages**.
4. En **Build and deployment → Source**, elige **Deploy from a branch**.
5. En **Branch**, elige **main** y, al lado, **/ (root)**. Toca **Save**.
6. Espera 1 o 2 minutos y recarga la página. Arriba aparecerá: *"Your site is live at…"* con tu link. Será algo como `https://melidani86.github.io/mi-contenido/`.

> Si el repositorio es privado, GitHub Pages puede pedir un plan de pago. En ese caso cambia el repositorio a público: **Settings → General → Danger Zone → Change visibility**. Nadie puede ver tus posts por eso: tus datos viven en tu navegador, no en GitHub.

## 3. Agregarla a la pantalla de inicio del iPhone

Hazlo **antes** de empezar a cargar contenido en el celular.

1. Abre el link de GitHub Pages en **Safari**. Tiene que ser Safari.
2. Toca el botón **Compartir** (el cuadrado con la flecha hacia arriba ⬆️).
3. Baja y toca **Agregar a pantalla de inicio**.
4. Verás el nombre **Mi Contenido**. Toca **Agregar**.
5. Desde ahora, ábrela **siempre desde ese ícono**. Se abre a pantalla completa, sin la barra del navegador.

**Por qué es importante:** Safari puede borrar los datos de una página web que no visitas en varios días. Las apps que agregas a la pantalla de inicio no tienen ese límite. Además, la app le pide al navegador que proteja tus datos. En **⋯ Más** puedes ver si están protegidos.

**Ojo:** la app de la pantalla de inicio y Safari guardan sus datos por separado. Si ya cargaste cosas en Safari, pásalas así:

1. En Safari, toca **⋯ Más → Exportar respaldo**.
2. En la app de la pantalla de inicio, toca **⋯ Más → Importar respaldo**.

## Cómo se usa

- **Crear un post:** toca **＋** en un día, o **＋ Nuevo post** arriba.
- **Mover un post:** en la computadora, arrástralo con el mouse. En el celular, **mantenlo presionado un momento** y luego arrástralo. Si lo llevas hacia el borde de la pantalla, la página se desplaza sola.
- **Banco de ideas:** escribe una idea rápida y arrástrala a un día para programarla. Para devolver un post al banco, arrástralo a la zona "💡 Suelta aquí…" o usa el botón **💡 Al banco** dentro del post.
- **Copiar caption:** copia el caption, el CTA y los hashtags juntos.
- **Compartir:** en el iPhone abre el menú de compartir para mandar las fotos o el video a Instagram, y además copia el caption para que solo tengas que pegarlo. En la computadora descarga los archivos.
- **Borrar archivos:** cuando un post está en **Publicado**, puedes borrar sus fotos y videos para liberar espacio.
- **Plan con IA:**
  1. Toca **⋯ Más → Copiar instrucciones para la IA** y pégalas en Claude, ChatGPT o Gemini.
  2. Pídele tu plan de la semana.
  3. Copia la respuesta y pégala en **⋯ Más → Importar plan**.
- **Respaldo:** exporta un respaldo cada semana y guárdalo en iCloud Drive o Google Drive. Antes de descargar, la app te dice cuánto va a pesar.
