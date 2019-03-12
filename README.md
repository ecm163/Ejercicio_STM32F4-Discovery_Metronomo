# Ejercicio_STM32F4-Discovery_Metronomo

En éste ejercicio práctico se ha desarrollado software en C para implementarlo en el micro STM32F407VGt6 de la placa de desarrollo 
STM32F4-Discovery, de forma que al pulsar el botón de usuario de la placa se va disminuyendo la frecuencia de parpadeo de un LED. 

· ¿Qué hace éste programa cuando se carga en la placa?.

Una vez cargado el programa en la placa, si pulsamos el botón azul una primera vez, de la placa (el botón ‘user’), el led naranja de dicha 
placa empezará a parpadear de manera que se mantiene encendido un segundo y luego se apaga un segundo, se vuelve a encender un segundo y 
apagar un segundo, y así sucesivamente.

Si volvemos a pulsar el botón azul o ‘user’ de la placa por segunda vez, ahora el parpadeo disminuye a la mitad su frecuencia, esto es, se
enciende medio segundo, se paga medio segundo, se enciende medio segundo, se apaga medio segundo … y así sucesivamente.

Si volvemos a pulsar el botón azul o ‘user’ una tercera vez el parpadeo se detiene y se inicializa el sistema para que la próxima vez que 
se pulse el botón tengamos el parpadeo de un segundo encendido, un segundo apagado, un segundo encendido, un segundo apagado (el mismo caso
que la primera vez que se pulsa el botón).

El led verde se mantendrá en todo momento encendido para mostrar que el programa se está ejecutando.

En la documentación de éste repositorio hay un documento PDF dónde se explica con más detalle cómo ejecutarlo en la placa y 
el funcionamiento que implementa su software. 

Un saludo. 

