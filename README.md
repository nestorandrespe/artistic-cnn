# artistic-cnn

Adaptación del código publicado en [sub-subroutine](http://www.subsubroutine.com/sub-subroutine/2016/11/12/painting-like-van-gogh-with-convolutional-neural-networks) y [Garbled Notes](http://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style).

Esta implementación expande el código para aplicarlo a una carpeta y exportar un video con el estilo deseado.

## para ejecutar en una sola imagen

```bash
python neura-style.py -i [archivo de entrada] -s [archivo para el estilo] -m [ruta al modelo] -o [carpeta de destino]
```

TODO:

- [ ] agregar parámetros para los ciclos y los checkpoints

## para ejecutar en una carpeta con los frames del video

TODO:

- [ ] adaptar el script de arriba para importar las imágenes de una carpeta
- [ ] exportar las imágenes como video mp4
