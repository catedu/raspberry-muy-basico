#2 GPIO ¿qué es eso?

Pues es importante para la robótica pues **General Purpose Input Output (GPIO)** es el sistema que tiene la Raspberry para usarlo como entradas y salidas de uso general, los marcados como naranjas: 

![](https://docs.microsoft.com/en-us/windows/iot-core/media/pinmappingsrpi/rp2_pinout.png)

Su gran ventaja con respecto al Arduino es la cantidad de pines GPIO que están disponibles junto con la posibilidad de programar diréctamente en la raspberry,  pero su desventaja es que no pueden leer entradas analógicas, para ello hay que usar un componente exterior o un Arduino.

##Tensiones
Están diseñados para 3.3V **NO conectes componentes de 5V o de lo contrario ESTROPEARÁS LA RASPBERRY DE FORMA IRREVERSIBLE** debido a que todos los pines están **sin protección** de buffer.

<iframe src="https://giphy.com/embed/wWT7Clw42FKXC" width="480" height="198" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/short-circuit-movie-ouch-wWT7Clw42FKXC">via GIPHY</a></p>

##Corrientes
Los GPIO están diseñados para ofrecer 3mA por cada pin, suficiente para encender LEDs pero no pidas más o **te cargarás la RASPBERRY**:

<iframe src="https://giphy.com/embed/2TzxBMRKMcYF2" width="480" height="413" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/analog-2TzxBMRKMcYF2">via GIPHY</a></p>

