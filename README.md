# Archivo River

Fotografías de River con sus versiones originales y restauradas. Proyecto independiente del launcher.

## Catálogo

`catalogo.json` es el punto de entrada para la web y el launcher. Las rutas de archivos son relativas al catálogo. Cada foto tiene un ID estable y versiones `original` y `restaurada`, con tamaño y SHA-256 para verificar descargas.

La categoría de hinchada se llama **LBDT**. Fecha, épocas y etiquetas son campos independientes. Los valores desconocidos quedan sin completar; no se atribuyen partidos ni autores sin evidencia.

La restauración con IA puede reconstruir detalles. Los originales se conservan sin modificaciones. Los pasos intermedios se mantienen fuera de este repositorio.

## Ver localmente

```sh
python3 -m http.server 8788
```

Abrir http://localhost:8788/. La misma web se puede publicar con GitHub Pages.

## Derechos y procedencia

No se atribuye una licencia general a las fotografías: los derechos corresponden a sus respectivos titulares. La fuente y autor se documentarán cuando se conozcan.
