#8.1 VNC Server

**VNC server** está instalado de forma nativa en Raspbian, pero NO ESTA ACTIVO POR DEFECTO, hay que activarlo:

##8.1.1 Activarlo via SSH
Teclear



```
sudo raspi-config
```



Sale esta pantalla, entra en la opción 5 :

![](/assets/raspi-config.png)

Y entramos en VNC utilizando las flechas del teclado y tecla Intro:

![](/assets/vnc-activar.png)

Y le decimos que YES

![](/assets/activar-vnc-yes.png)

Finish

![](/assets/finish-raspi-config.png)

Pedirá reiniciar, le decimos que sí

##8.1.2 Activarlo con pantalla...
Entramos en **Preferencias- RaspberryPi configuration**

![](/assets/Selection_040.png)

Y en **Interfaces** lo activamos, de paso activa SSH

![](/assets/Selection_041.png)

