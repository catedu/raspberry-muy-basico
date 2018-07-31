#9 Transferencia de ficheros

Para hacer una transferencia de ficheros, necesitamos un lugar común entre nuestro Raspberry y nuestro PC.

Podemos hacer una carpeta compartida en el Linux de Raspbian instalando un servidor Samba para que nuestro PC lo vea ... o también podemos compartir una carpeta compartida en nuestro PC, añadir usuarios y permisos apropiados y depende si nuestro ordenador es Windows7, Windows10, Linux, Mac... todas estas opciones son muy interesantes, en Internet puedes encontrar tutoriales muy buenos y .... siempre hay fallos.

O dejarnos de ser tan tecnológicos y utilizar el adaptador y la micro tarjeta de la Raspberry: Es decir insertas, salen las particiones **boot **y **rootfs **(sólo **boot **si utilizas windows) y pones y sacas los ficheros que quieras.

![](/assets/2018-07-31 10_35_14-3 Raspbian · Raspberry muy básico.png)
>Esto me recuerda a una historia en la carrera espacial: Hay un problema a la hora de usar los bolígrafos en gravedad 0 pues sólo funcionan por la caída de la tinta. La NASA gastó bastante dinero en desarrollar un bolígrafo capaz de escribir en el espacio pero el proyecto fue cancelado por sobrecoste, aunque luego [alguna empresa acabó inventanto un bolígrafo que funciona con gravedad 0](https://es.wikipedia.org/wiki/Space_Pen).

>... los rusos usan un lápiz. :DD

#Consejo
Utilizar la misma micro tarjeta SD para transferir archivos desde vuestro PC a vuestra Raspberry y viceversa, evidentemente necesitas un adaptador.
###En mi PC tengo LINUX
Pues mejor, ves las dos particiones de la micro tarjeta SD:
* boot
* rootfs
Create una carpeta en **rootfs** en la carpeta /**home/pi** y ahí guarda tus proyectos.

![](/assets/rootfs.jpg)

###En mi PC tengo Windows
Pues sólo ves una de las dos particiones, almacena todo en la **boot** y luego en Rasbian por VNC pasa los archivos a la otra partición **rootfs** en la carpeta /**home/pi**:

![](/assets/boot.jpg)
