# Tieneunperro

Landing page del proyecto musical Tieneunperro.

**🌐 Página en vivo: https://soundfalya.github.io/Tieneunperro/**

Un orbe hermético que flota sobre un fondo índigo, verde musgo y rojo ladrillo, con símbolos de alquimia y astrología:

- Cada planeta toca una nota de la serie armónica (Saturno es la fundamental, la Luna el 7º armónico).
- El ojo del centro toca un arpegio.
- Hay 7 brillos ocultos para descubrir; el contador está bajo el sello del perro.
- Arriba están las redes como cuadrados, al estilo Linktree.
- El sello del perro (kamon con 無, "vacío") guarda su propio secreto.

Es HTML, CSS y JavaScript estático, sin build.

## Editar

- `index.html`: la página principal, el orbe interactivo. Todo va en este archivo (estilos, sonido y el logo del perro incrustado), así que se abre bien aunque se copie solo. Los links de redes están en `<nav class="socials">`.
- `portadas.html` + `styles.css`: la primera versión, inspirada en las portadas.
- `assets/`: portadas, foto del artista y el logo del perro en `assets/perro/` (SVG y PNG grande).

## Publicar con GitHub Pages

Settings → Pages → Source: "Deploy from a branch" → rama `main`, carpeta `/ (root)`.
Cada cambio que entra a `main` se publica solo en un par de minutos.
