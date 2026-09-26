# Publicar reparaciones

Guarda cada publicación como `TXT/art_1.txt`, `TXT/art_2.txt`, `TXT/art_3.txt` y así sucesivamente, sin saltar números. La página lee el catálogo al abrirse; después de agregar o cambiar publicaciones, actualiza la página para ver los cambios.

Escribe un campo por línea con este formato:

```text
Título: Cambio de pantalla
Categoría: Móviles
Imagen: fotos/art_1.jpg
Descripción: Se reemplazó la pantalla y se comprobó el funcionamiento.
```

Las categorías válidas son `Móviles`, `Tablet`, `PC`, `Corneta` y `Consolas`. La ruta de `Imagen` se indica desde la carpeta principal del sitio. Si se deja vacía, o la foto no se puede cargar, la galería muestra `assets/reparacion-ilustrativa.svg`.

Se pueden escribir descripciones en varias líneas. `Título`, `Categoría` y `Descripción` son obligatorios.