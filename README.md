# Safety

[![Docker Image Size (latest by date)](https://img.shields.io/docker/image-size/dued/safety)](https://hub.docker.com/r/dued/safety/)
![MicroBadger Layers](https://img.shields.io/microbadger/layers/dued/safety)
![GitHub](https://img.shields.io/github/license/dued/safety)

## ¿Que es safety?

Es una imagen para crear un servicio de copia de seguridad multipropósito basado en Cron

## ¿Por qué?

Por que siempre necesitamos respaldar cosas, y pretendemos hacer de Safety es una de las
mejores herramientas disponibles para ese fin.

## ¿Cómo?

Creamos una imagen basada en las dependencias [Duplicity][] para admitir todos sus
backends dentro de un sistema [Alpine][] muy liviano por si mismo, y añadimos un script
Python de Job Runner que se encarga de convertir algunas variables de entorno en
trabajos cron flexibles y enviar un informe por correo electrónico de forma automática.

## ¿Donde?

Safety se encuentra en:

- [Código de origen](https://github.com/dued/safety).
- [Imagen preconstruida en el registry de GitHub package](https://github.com/dued/safety/packages/212851).
- [Imagen preconstruida en el registry de Docker Hub](https://hub.docker.com/r/dued/safety).

[alpine]: https://alpinelinux.org/
[duplicity]: http://duplicity.nongnu.org/
