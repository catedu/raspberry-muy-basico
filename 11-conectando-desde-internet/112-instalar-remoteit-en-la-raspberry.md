# 11.2 Instalar remote.it en la Raspberry y añadir servicios

Tienes dos opciones:

## OPCIÓN A Instalar ya una imagen RASBIAN con todos los servicios (recomendado)

Para instalar la imagen la descargas en [esta página](https://remote.it/downloads/#raspberrypi) y ya sabes cómo instalar la imagen [ver instalar Raspbian](https://catedu.github.io/raspberry-muy-basico/3-raspbian.html)

{% youtube %}https://www.youtube.com/watch?v=j9EsCvBF-cA{% endyoutube %}

## OPCIÓN B Instalar remote.it en tu raspbian

Si optas por querer instalar remote.it en tu Raspbian sin utilizar la imagen, hay que seguir las instrucciones de esta página https://support.remote.it/hc/en-us/articles/360047542051-Installing-remoteit-on-a-Raspberry-Pi-running-Raspbian-or-Raspberry-Pi-OS

Que en definitiva los pasos importantes son :

1. sudo apt update //Actualizar raspbian
1. sudo apt install remoteit //instala servicio remoteit
1. sudo remoteit add //añade el servicio que quieras tener SSH, VNC ...
