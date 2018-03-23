# 1 Un vistazo rápido
##De donde viene ...

En 2011 se desarrolló la Raspberry Pi como ordenador de bajo coste para facilitar la enseñanza de la informática en los colegios, pero hasta 2012 no comenzó a fabricarse. La fundación recibe apoyos del laboratorio de informática de la Universidad de Cambridge y de Broadcom.

No hay ningún secreto en su precio, ya que fue diseñada con el fin de ser lo más barato posible, libre y llegar al máximo número de usuarios. Te puedes encontrar un PI3 con carcasa, alimentación y tarjeta clase 10 de 16 GB [por 50 € aprox](https://es.aliexpress.com/).

## Modelos

**RASPBERRY PI 1** ya empezó con 8 puertos GPIO en 26 pines, un HDMI y 2xUSB con un microprocesador ARM de 700MHz y SDRAM 256M ¿no estaba nada mal para empezar en el 2012?. 

**RASPBERRY PI 2** En 2015 se aumentaba la potencia a 900MHz y SDRAM de 1G con lo que las aplicaciones cargadas lo agradecían. Los puertos USB se amplian a 4, los núcleos también y los GPIO a 17 !! (con 40 pines y los primeros 26 son los mismos que la versión anterior para mantener la compatibilidad).

**RASPBERRY PI 3** Un año después, los que se compraron la PI2 se arrepintieron pues este modelo incopora Bluetooth y Wifi y el micro es de 64 bits.

**Modelos micros**, para robots que requieran espacios reducidos, es el **RASPBERRY PI ZERO** equivalente al PI 1 pero sin Ethernet y el **RASPBERRY PI ZERO W** que se le añade Bluetooth y Wifi.

>[+Info aquí](https://www.luisllamas.es/modelos-de-raspberry-pi/), y para complicarlo más hay diferentes versiones de cada A, A+ B+ Rev1 Rev2.. [ver](https://www.raspberryshop.es/guia-completa-raspberry-pi.php#a27)

## ¿Cual usamos?

La pregunta es ¿para qué lo vas a usar?

* Aplicaciones que no requieren uso abusivo de recursos, como la robótica, [un servidor de Torrents](https://raspberryparatorpes.net/proyectos/instalar-y-configurar-un-descargador-de-torrents/), [streaming](http://www.devlopez.com/es/camara-remota-super-simple-en-raspeberry-con-modulo-camera-pi-o-noir/), [videovigilancia](https://programarfacil.com/podcast/87-video-con-raspberry-pi/)...todo son buenos, pero que tenga Wifi incorporado como el PI3 facilita las cosas.

<iframe src="https://giphy.com/embed/MH680xjlXjtII" width="480" height="366" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/raspberry-MH680xjlXjtII">via GIPHY</a></p>

* Aplicaciones con alto uso de recursos como video juegos, [recalbox](https://raspberryparatorpes.net/proyectos/recalbox-emulacion-y-retro-gaming-para-torpes/), [retropie](https://www.programoergosum.com/cursos-online/raspberry-pi/239-consola-arcade-basada-en-raspberry-pi-con-retropie/introduccion)... mejor la última versión.

<iframe src="https://giphy.com/embed/WiGLW6zGIPUyY" width="480" height="226" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/raspberry-WiGLW6zGIPUyY">via GIPHY</a></p>

En este curso usaremos el modelo PI3 por sus ventajas de conectividad Wifi, no obstante si se tiene otro modelo anterior, habría que conectar un pincho wifi.




