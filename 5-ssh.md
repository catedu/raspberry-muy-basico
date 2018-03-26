#5 SSH
Controlar Raspberry pi de forma remota y de forma textual es muy rápido y eficaz, sobre todo para la robótica con AlphaBot.

SSH (Secure Shell) es el nombre de un protocolo y del programa que lo implementa, y sirve para acceder servidores privados a través de una puerta trasera. [Wikipedia](https://es.wikipedia.org/wiki/Secure_Shell).
Recuerda que lo que hemos hecho [en la sección 4](/4-primera-comunicacion.md) es:
* Hemos activado el protocolo SSH en la raspberry
* Hemos fijado una IP para poder acceder a él.

Con estas dos cosas ya podemos trabajar por SSH.

**YA PODEMOS ENCENDER LA RASPBERRY** si has elegidos las opciones A de [3Rasbian](/3-raspbian.md) y [4Conectando](/4-primera-comunicacion.md) aún no lo habías encendido.

##5.1 Linux
Linux trabaja tiene de forma nativa el protocolo SSH, lo activamos en el icono en negro que es el **Terminal**:

![](/assets/terminal-where.jpg)

Supongamos que la IP fija que le hemos asignado a la Rasbperry en el [punto 4](/4-primera-comunicacion.md) es 192.168.1.131 Tecleamos
```
ssh pi@192.168.1.131

```
Te pide la contraseña, por defecto es _raspberry_, la tecleas **_no la puedes ver_**, te tiene que salir algo así en la pantalla:

**Cuando te sale pi@raspberrypi: es que ya está preparado para recibir órdenes**


```
cat@cat-Aspire-E5-571 ~ $ ssh pi@192.168.1.131
pi@192.168.1.131's password: 
Linux raspberrypi 4.9.80-v7+ #1098 SMP Fri Mar 9 19:11:42 GMT 2018 armv7l

The programs included with the Debian GNU/Linux system are free software;
the exact distribution terms for each program are described in the
individual files in /usr/share/doc/*/copyright.

Debian GNU/Linux comes with ABSOLUTELY NO WARRANTY, to the extent
permitted by applicable law.
Last login: Fri Mar 23 18:03:09 2018 from 192.168.1.131
pi@raspberrypi:~ $ 

```
##5.2 Windows
No lo tiene nativo, tenemos que instalar [Putty](https://www.putty.org/)

Y rellenamos los campos de la IP, puerto y el protocolo SSH, es recomendable grabar la sesión para tenerlo en futuras entradas.

![](/assets/Selection_043.png)

Se abre una ventana pidiendo el usuario **_pi_** y contraseña por defecto **_rasbperry_**


