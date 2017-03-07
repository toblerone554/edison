# edison
## Introducción

Hay 2 versiones: v1.0 y v2.0

(La 2 incluye encoder en las 2 ruedas y se resuelve la deriva)

### Sensores

* Deteccion de obstáculos derecho e izquierdo
* 1 Seguilínecesitamos
* Receptor de IR (38Khz)
* Siguelíneas (1 solo sensor)
* 2 fototransistores
* Sensor de sonido (piezoeléctrico)

Procesador de 8bits Freescale  8kb

### Programación

Se programa con un cable específico (EdComm) que se conecta a la salida de audio (del tablet, móvil Android, Raspberry, PC, ...) y que se coloca encima del sensor siguelíneas

#### Programación con código de barras

Podemos grabar un programa sencillo sin más que leer un código, lo que activa un programa: siguelíneas, esquivaobstáculos, control por sonido, sigueluz

Podemos usar código de barras para  hacer que responda con ciertos movimiento a ciertas teclas del mando a distancia

## [Descargas](https://meetedison.com/download/)

 [Descargas de software](https://meetedison.com/robot-programming-software/)

Hay aplicaciones (open https://github.com/Bdanilko/Edware) para Windows, Linux, MacOS, Android, iOS, web ([web bloques](http://edwareapp.com/?_ga=1.150026806.1695549331.1454041273#) [Web python](http://www.edpyapp.com/))

Se puede programar con bloques, python y código de bárras



## Libros

[10 Robotics lesson  plans](https://meetedison.com/wp-content/uploads/2015/04/Your-EdVenture-into-Robotics-10-Lesson-Plans.pdf?x20535)

¿Traducirlo al español?

[Edison robot activities: controller](https://meetedison.com/wp-content/uploads/2015/04/EdBook1-Your-EdVenture-into-Robotics-You-re-a-Controller.pdf?x20535)

[Edison robot activities: programmer](https://meetedison.com/wp-content/uploads/2015/04/EdBook2-Your-EdVenture-into-Robotics-You-re-a-Programmer.pdf?x20535)


## Instalación en Linux


Para ejecutar el software EdWare necesitamos instalar algunas dependencias. Para facilitar la instalación usaremos pyp. Lo instalamos con:

    sudo apt install pyp

Ahora instalamos los paquetes necesarios con:

    sudo pip install jsonpickle
    sudo pip install pygame


Ya podemos ejecutarlo con


  python edware.py
