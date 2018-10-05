#2 GPIO 
##2.1 ¿Qué es eso?¿Es importante?

Pues sí que es importante para la robótica. GPIO significa **General Purpose Input Output (GPIO)** es el sistema que tiene la Raspberry de entradas y salidas de uso general. En la figura lo tienes marcados como naranjas: 

![](https://docs.microsoft.com/en-us/windows/iot-core/media/pinmappingsrpi/rp2_pinout.png)

Su gran ventaja con respecto al Arduino es la cantidad de pines GPIO que están disponibles junto con la posibilidad de programar diréctamente en la Raspberry,  pero su desventaja es que **no pueden leer entradas analógicas**, para ello hay que usar un componente exterior o un Arduino.

##2.2 Tensiones
Otra desventaja con respecto al Arduino: Están diseñados para 3.3V **NO conectes componentes de 5V o de lo contrario ESTROPEARÁS LA RASPBERRY DE FORMA IRREVERSIBLE** debido a que todos los pines están **sin protección** de buffer.

<iframe src="https://giphy.com/embed/wWT7Clw42FKXC" width="480" height="198" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/short-circuit-movie-ouch-wWT7Clw42FKXC">via GIPHY</a></p>

##2.3 Corrientes
Los GPIO están diseñados para ofrecer 3mA por cada pin, suficiente para encender LEDs pero **no pidas más** o **te cargarás la RASPBERRY**:

Y por supuesto los leds no a lo bruto, sino a través de una resistencia ¿de qué valor?

Voltios máximos 3.3V Intensidad máxima 3mA luego:

R = V/I = 3.3/3 = 1.1 kOhm COMO **MAXIMO**

<iframe src="https://giphy.com/embed/2TzxBMRKMcYF2" width="480" height="413" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/analog-2TzxBMRKMcYF2">via GIPHY</a></p>

##2.4 ¿QUE PUEDO CONECTAR PUES DIRÉCTAMENTE?
**PRACTICAMENTE NADA** sólo un led o un interruptor/pulsador con una resistencia de como mínimo 1.1K 

##2.5 QUE PUEDO CONECTAR INDIRECTAMENTE
**Casi de todo** a través de alguna Shield o interface, por ejemplo:
* Shield Pibrella muy, muy básico
* Shield GrovePi+ ya permite todo tipo de sensores
* AlphaBot un robot ya en movimiento.

###2.5.1 Pibrella

[Esta shield ](http://pibrella.com/)es muy, muy básica que tiene 3 leds, un pulsador, un buzzer y dos conectores de extensión.

![](http://pibrella.com/assets/pibrella-board.png)

###2.5.2 GrovePi+
[Esta shield](https://www.seeedstudio.com/GrovePi%2B-p-2241.html) tiene un buen precio y muchas posibilidades y [muy buena página web de proyectos](http://wiki.seeedstudio.com/Grove_System/):

![](https://www.seeedstudio.com/upload/image/20161021/1477039769923791.jpg)

![](https://www.seeedstudio.com/upload/image/20161021/1477039791590132.jpg)

###2.5.3 Alphabot
* [CURSO EN AULARAGON](https://catedu.gitbooks.io/alphabot/content/) Programación con Python de este [AlphaBot](https://www.waveshare.com/wiki/AlphaBot) con webcam
    
![](/assets/alphabot.png)


