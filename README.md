# redes-imagenes

Imágenes públicas de los posts de Zootropic (Instagram, Facebook y Google Business).

Este repositorio es público a propósito: las APIs de Meta y de Google Business recuperan la foto haciendo una petición HTTP a una URL abierta. No hay secretos, tokens ni datos de clientes.

## Cómo se usa

El script `/workspace/redes/alojar-imagen.py` sube el JPEG y devuelve la URL estable:

`https://raw.githubusercontent.com/zootropic/redes-imagenes/main/posts/<fecha>/<archivo>.jpg`

Los ficheros van en `posts/AAAA-MM-DD/`. Solo JPEG de los posts (normalmente 1080×1350).
