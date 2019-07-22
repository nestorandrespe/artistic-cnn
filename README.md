# artistic-cnn

![ejemplo del resultado obtenido](img-ejemplo.jpg?raw=true "Ejemplo resultado")

Adaptación del código publicado en [sub-subroutine](http://www.subsubroutine.com/sub-subroutine/2016/11/12/painting-like-van-gogh-with-convolutional-neural-networks) y [Garbled Notes](http://www.chioka.in/tensorflow-implementation-neural-algorithm-of-artistic-style). Modelo utilizado: [VGG19](http://www.vlfeat.org/matconvnet/pretrained/)

Esta implementación expande el código para aplicarlo a una carpeta y exportar un video con el estilo deseado.

## para ejecutar en una sola imagen

```bash
python neural-style.py -i [archivo de entrada] -s [archivo para el estilo] -m [ruta al modelo] -o [carpeta de destino]
```

TODO:

- [ ] agregar parámetros para los ciclos y los checkpoints

## para ejecutar en una carpeta con los frames del video

```bash
python neural-style-folder.py -i [carpeta de entrada] -s [archivo para el estilo] -m [ruta al modelo] -o [carpeta de destino]
```
