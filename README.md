# **Sistema Embebido para control de cultivo por hidroponia.** #

----
#### Daniel Esteban Rodriguez ####

#### Daniel Santiago Robayo ####

#### María Camila Muñoz Berrio ####

#### Sebastian Ruiz Torres ####


----
## **Descripción del problema** ## 

En la actualidad obtener alimentos vegetales con los nutrientes necesario y sin tanto procesamiento quimico a un valor moderado no es sencillo por lo que la idea de cultivar autonomamente los alimentos en una huerta casera se hace una mejor opción. Ahora, cultivar en la ciudad trae multiples desafios como los son el espacio, el tiempo que es posible dedicarle a esta labor y la falta de conocimiento en esto. De alli nacen vaias alternativas que pretenden reeemplazar las huertas en suelo convencionales por formas más eficientes de cutivar en el mismo espacio y por un valor menor.

Las principales alternativas son: Acuaponía, aeroponía e hidroponía. Esta ultima fue la elegida para desarrollar el proyecto debido a que esta se desarrolla en el agua, esto quiere decir que la raíz se desarrolla en un sustrato o en la misma solución liquida nutritiva utilizada.
 

## **Propuesta** ##
Se plantea construir un cultivo vertical de hidroponia que reduzca el espacio utilizado para un cultivo y que cuente con un sistema de monitoreo que cuente con sensores previamente calibrados que midan variables importantes para el sostenimiento del cultivo, estos sensores enviaran información que sera procesada y a partir de esto se enviaran alertas al telefono movil del usuario haciendo así interactivo el proceso de producir su alimento. También se pretende que esta dispositivo pueda ser usado por cualquier persona incluso si no conoce sobre hidroponia por medio de avisos informativos-educativos. 

**Publico objetivo** Personas con interesadas en cultivar en espacios reducidos sin la necesidad de dañar los suelos y aprender sobre cultivos hidroponicos.

**Objetivo General**  Diseño, creacion y aplicacion  de un sistema de monitoreo que permita la optimizacion del cultivo y la interaccion educativa con el usuario.

![unknown](https://user-images.githubusercontent.com/88418156/186547927-50646758-781d-460b-a5ae-b2e2ee4a1a16.png)



----
## **Requerimientos** ##
* Medir la temperatura de agua
* Medir el nivel del agua
* Ser ergonomico
* Recirculamiento del agua eficiente

## **Diagrama de bloques del sistema.** ##

En el siguiente diagrama se muestran los diferentes componentes que se plantean implementar en el sistema, en este se pueden observar cada una de las entradas y salidas que se pretenden tener en el sistema. Como interacción principal con el usuario se va a construir un sistema que conecte con el telefono del usuario y lo alerte sobre las condiciones de la planta.

![Diagrama_en_blanco](https://user-images.githubusercontent.com/88418156/186547916-15719605-8ecb-488c-ab9b-c09ebaba3a6a.png)

## **Diagrama de caja negra con los modulos del ESP32.** ##
![Diagrama Bloque Embebidos](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/DiagramaBloqueEmbebidosActualizado1.png)

## **Diseño de la placa** ##

El diseño de la PCB fue hecho en el programa KiCad y se presentan los esquematicos a continuación,

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/ESP32.jpeg)

Se puede observar la distribución de los pines en el ESP32, la conexión de los sensores y la alimentación para este. Aqui se puede observar la conexión del interruptor de flash para subir el programa. 


![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/ubicacionpines.jpeg)

Se puede detallar la distribución de los pines para cada sensor, con la respectiva alimentación y tierra.


![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Regulación.jpeg)

Aquí se presenta la configuración de la alimentación, el regulador(LT1963a5T-3.3), el octoacoplador(SFH617A-1Z01B) y los Mosfet utilizados (IRF4905).


![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/updown.jpeg)

Esta fue la configuración para los led's utilizados, uno de iniciación y otro de boot. También se encuentran el  interruptor de reset.


De la misma manera se crea el diseño de la PCB de dos caras con medidas de 10cm X 10cm.

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_16.png)

Y a continuación se presentan ambas caras de la PCB.
Teniendo la cara frontal:

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_17.png)

Y la cara trasera:

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_18.png)

Por lo tanto las imagenes de la PCB con sus componentes en 3D.

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_19.png)

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_20.png)

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_21.png)

## **Ensamble** ##

En primera instancia se recibio la PCB, fabricada en JLCPCB Hong Kong.

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Images_Project/Image_10.jpeg)

## **Resultados** ##

Este esquematico se puede ver en la placa ya con los sensores en la siguiente imágen,

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Montaje%20PCB.jpeg)


## **Brochure** ##

![unknown](https://github.com/danrodriguezto/SistemaEmbebidoHidroponia/blob/main/Image/Brochure%20Hidro.png)
