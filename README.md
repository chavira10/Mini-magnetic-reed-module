## Mini-magnetic-reed-module




El Módulo interruptor de láminas magnético Arduino Keyes KY-021. Un interruptor de lengüeta es un sensor magnético que normalmente está abierto y se cierra cuando se expone a un campo magnético.


![ScreenShot](1.png)
![](2.jpg)



*Especificaciones*

El mini módulo de interruptor de lengüeta magnético KY-021 consta de una resistencia de 10 kΩ y un pequeño interruptor de lengüeta accionado por un campo magnético, comúnmente utilizado en sistemas mecánicos como sensores de proximidad. Compatible con plataformas electrónicas populares como Arduino, Teensy y ESP8266.





| Tension de funcionamiento | 3.3V hasta 5V |
|---------------------------|---------------|
| Tipo de salida            | Digital       |




Diagrama de conexión KY-021
Conecte la línea de alimentación (medio) y la tierra (-) del módulo a +5 y GND respectivamente. Conecte la señal (S) al pin 2 en el Arduino.

KY-021	Arduino
S	2
medio	+ 5V
-	GND
Diagrama de conexión KY-021 ArduinoClick para agrandar
Código de ejemplo KY-021 Arduino
El siguiente boceto encenderá el LED del pin 13 en el Arduino cuando el módulo detecte un campo magnético. Coloque un imán cerca del KY-021 para activar el interruptor del carrete.
