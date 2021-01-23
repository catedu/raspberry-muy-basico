# 11.2 Instalar remote.it en la Raspberry y añadir servicios

Tienes dos opciones:

## OPCIÓN A Instalar ya una imagen RASBIAN con todos los servicios (recomendado)

Es el método más sencillo:

1. Desgarcar la imagen del Raspbian con los servicios Remote.it ya preinstalados desde [esta página](https://remote.it/downloads/#raspberrypi)
1. Instalar la imágen en la Raspberry [ver instalar Raspbian](https://catedu.github.io/raspberry-muy-basico/3-raspbian.html)
1. Arrancar la Raspberry en modo gráfico, utilizando un monitor, teclado y ratón.
1. Aparece los diálogos típicos que pongas contraseña al usuario pi y configuración de teclado, idiomas...
1. Importante, configura la Raspberry para que esté en Internet (doble click en el icono Wifi arriba a la derecha)
1. Hay un nuevo diálogo que abre remote.it y te pide loguearte, entra con tu usuario y contraseña (OJO estamos hablando del navegador de la Raspberry no de tu ordenador) y te pide un nombre para el dispositivo y ... ya está!!
1. Entra ahora desde tu ordenador a https://remote.it/ te logueas, y automáticamente aparece tu raspberry con el botón verde si está conectado a Internet y con la opción de activar VNC y SSH

{% youtube %}https://www.youtube.com/watch?v=j9EsCvBF-cA{% endyoutube %}

## OPCIÓN B Instalar remote.it en tu raspbian

Si optas por querer instalar remote.it en tu Raspbian sin utilizar la imagen, hay que seguir las instrucciones de esta página https://support.remote.it/hc/en-us/articles/360047542051-Installing-remoteit-on-a-Raspberry-Pi-running-Raspbian-or-Raspberry-Pi-OS

Que en definitiva los pasos importantes son :

1. sudo apt update //Actualizar raspbian
1. sudo apt install remoteit //instala servicio remoteit
1. sudo remoteit add //añade el servicio que quieras tener SSH, VNC ...
