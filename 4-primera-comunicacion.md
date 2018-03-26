#4 Conectamos nuestra Rasbperry
Lo que tenemos que hacer es conectar la Raspberry con la WIFI, hay dos opciones, con trastos (pantalla, teclado y ratón) o sin trastos:

##Opción A Conectar la Raspberry sin necesidad de pantalla, teclado y ratón
Con esta opción no tienes que encender la Rasbperry.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSuE389RRI67Vi1LGxySj5rWjhfNMjV9t27FbO80BOqMqDJyKcH7hFZWdOXubwsuO8NtnwXtaTQfg4p/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>

**Texto que hay que poner en interfaces** (para copiar y pegar)

```
auto wlan0
iface wlan0 inet static
address 192.168.1.xxx
gateway 192.168.1.1
netmask 255.255.255.0
wpa-ssid el_nombre_tu_red_wifi
wpa-psk la_contraseña_de_tu_wifi
dns-nameservers 8.8.8.8 188.244.82.1
```
##Opción B Conectar la Raspberry con pantalla, teclado y ratón
Aquí sí que tienes que encender la raspberry
<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQShQenHWgn0_axlCmlKpIX6kqQOHHzaIHhy7SxTtXjLOXZip40JO5B-UB7KRx6g1Z8M1LsUg2N8fi8/embed?start=false&loop=false&delayms=3000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>



