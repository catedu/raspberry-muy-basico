#11.3 SSH y VNC de mi Raspberry desde Internet

Nos vamos a la página de [Remote.it](https://remote.it/) y al logearnos nos aparecerá nuestro dispositivo si hemos hecho los pasos anteriores correctamente

![](/assets/remoteit1.jpg)

Pinchamos en el dispositivo y nos aparece los servicios que tenemos instalados:

![](/assets/remoteit2.jpg)

Vemos que tenenemos SSH, VNC y HTTP que eso lo verás si haces el curso de [Alphabot](https://catedu.github.io/alphabot/)

##11.3.1 Conexión SSH
Pinchamos en la anterior imagen en SSH y nos aparece los valores que tenemos que necesitamos para nuestra conexión SSH

![](/assets/remoteit-ssh.jpg)

Entramos en nuestra aplicación SSH por ejemplo en Windows con [PUTTY](https://www.putty.org/)

![](/assets/remoteit-ssh-1.jpg)

Y ya nos sale la terminal SSH, ponemos nuestro usuario y contraseña, [¿no la sabes?](/6-cambiar-usuario-y-contrasena.md) y ya estamos conectados:

![](/assets/remoteit-ssh-2.jpg)

##11.3.2 Conexión por VNC

En los servicios de nuestro dispositivo, pinchamos en VNC

![](/assets/remoteit2.jpg)

>Nots, puedes observar que antes remote.it ofrecía servicio HTTP que venía muy bien para manejar la [cámara de Alphabot](https://catedu.github.io/alphabot/8-camara.html), ahora no lo ofrece

Salta una nueva página web que nos da un enlace web para conectar por VNC

![](/assets/remote-it-vnc2.jpg)

  o nos da la configuración que tenemos que añadir a VNC Viewer en el campo VNC Server:

![](/assets/remote-it-vnc.jpg)

evidentemente nos preguntará por nuestro usuario y nuestra contraseña en la raspberry, [¿no la sabes?](/6-cambiar-usuario-y-contrasena.md).

![](/assets/remote-it-vnc3.jpg)
