# ig-assets

Imágenes de las publicaciones de [@ricardoguerrero.cl](https://instagram.com/ricardoguerrero.cl).

La API de Instagram no acepta archivos: hay que pasarle una URL pública y ella
va a buscar la imagen. Este repositorio es ese hosting.

Cada carrusel vive en su propia carpeta con fecha:

```
carruseles/AAAA-MM-DD-nombre/1.jpg
```

Y se referencia así:

```
https://raw.githubusercontent.com/ricardoestebanguerrero-bit/ig-assets/main/carruseles/AAAA-MM-DD-nombre/1.jpg
```

Los archivos fuente (HTML y el generador) están aparte, en `INSTAGRAM_RICARDO/carrusel/`.
