#11.2 Instalar remote.it en la Raspberry y añadir servicios
Seguimos los pasos de su [documentación](https://remot3it.zendesk.com/hc/en-us/articles/115000264832-Add-your-Pi-and-all-your-Weaved-services-to-remot3-it-today), necesitamos acceder a la Raspberry de forma local con un terminal y la Raspberry conectado a Internet:
##11.2.1 Instalar remote.it en la Raspberry
Entramos en nuestra RASPBERRY por SSH ([ya sabes cómo hacerlo](/5-ssh.md)) y tecleamos
1.- Actualizamos la Raspberry
>sudo apt-get update

2.-Instalamos el programa weavedconnectd que está apoyado por Remote.it :
>sudo apt-get install weavedconnectd   

3.- Ejecutamos weavedinstaller

>sudo weavedinstaller

4.- Nos aparecerá un menú, elegiremos **la opción 1** (aunque las otras también podrían valer pero lo más fácil es registrarse online tal y como hemos visto en [11.1 Remote.it](/11-conectando-desde-internet/111-remoteit.md) y utilizar ese **usuario **y **contraseña **con la opción 1):

![](http://forum.weaved.com/uploads/default/original/1X/415af66ac614261c254f11b540f0dd34297998f3.png)

**OJO cuando tecleas la contraseña NO SE VE** piensas que el teclado no funciona, ¡no te engañes! el teclado funciona perfectamente, teclea tu contraseña y pulsa enter.
## 11.2.2 Añadir un servicio SSH
Una vez que ya está instalado y logueado weavedinstaller podemos añadir el servicio SSH 

Si te has salido vuelve a ejecutar **sudo weavedinstaller**

Te aparecerá una vez logueado este menú:
![](/assets/pi@raspberrypi_ ~.jpg)

Elegimos la **opción 1 de añadir un servicio** y nos aparecerá otro menú:
![](/assets/otromenu.jpg)

Elegimos la opción 1 SSH nos pedirá si queremos mantener el puerto 22 como defecto, o si queremos poner otro puerto, podemos dejar el puerto 22

Luego nos pedirá que le asignemos un nombre, podemos poner **el que queremos** por ejemplo **ssh-picam** 

Después de unos minutos el servicio queda registrado en remote.it

##11.2.3 Añadir un servicio VNC
Totalmente análogo al anterior, pero simplemente elegimos la opción 3 de este menú:
![](/assets/otromenu.jpg)
Nos preguntará si queremos el puerto 5900 o si queremos otro, podemos dejar 5900, luego nos pregunta por un nombre arbritario, por ejemplo **vnc-micam** y luego después de unos minutos nuestro servicio queda registrado en remote.it


 