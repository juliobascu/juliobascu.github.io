# 🌐 Portafolio web — Julio Bascuñán

Página pública que muestra la evolución de mis proyectos desde 2015 hasta hoy.

Al entrar se ve **mi habitación de los 90 en 3D** (three.js). Tiene el PC con un escritorio estilo Windows 95 donde están los proyectos por carpetas. También hay una tele con consola para los juegos, mis consolas, el Atari 800XL (mi primer computador), los sistemas operativos que he usado, mis instrumentos, la mesa de Calabozos y Dragones y mi manga.

**Tecnología:** un solo archivo `index.html` (HTML + CSS + JavaScript + three.js desde CDN). Funciona en PC y celular.

## Cómo verla
Abre https://juliobascu.github.io. Para verla en tu PC necesitas un servidor local, porque los modelos 3D se cargan aparte. Por ejemplo: `python -m http.server` en esta carpeta y luego abre http://localhost:8000.
Atajos: `#pc` va directo al escritorio y `#juegos` va directo a los juegos.

## Cómo editar
- **Proyectos:** en `index.html`, busca `const P = [` . Cada línea es un proyecto: `[id, etapa, nombre, descripción, categoría, tecnologías, extras]`.
  - Extras: `star:1` = aparece en Destacados · `live:"https://..."` = botón «En línea» · `priv:1` = etiqueta «Uso interno».
- **Capturas:** guarda la imagen en `capturas/<id>.png` (o `.jpg`), por ejemplo `capturas/pixelito.png`. Si no existe, se ve un recuadro de color.
- **Modelos 3D:** la lista está en `modelos/lista.txt`. Al cambiarla, la acción `modelos` de GitHub los descarga de Poly Haven, los optimiza y los guarda en `modelos/` y `texturas/`.

## Créditos
- Modelos 3D y texturas: [Poly Haven](https://polyhaven.com) (licencia CC0).
- Consolas, Atari, instrumentos, pósters y mesa de rol: modelados y dibujados a mano en el código (diseños propios, sin logos oficiales).

## Publicado
En línea en **https://juliobascu.github.io** (GitHub Pages, repo público `juliobascu/juliobascu.github.io`, rama `main`). Cada cambio que se sube a `main` se publica solo en 1–2 minutos.
