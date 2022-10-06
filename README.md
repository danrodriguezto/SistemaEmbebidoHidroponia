# **Sistema Embebido para control de cultivo por hidroponia.** #

----
#### Daniel Esteban Rodriguez ####

#### Daniel Santiago Robayo ####

#### María Camila Muñoz Berrio ####

#### Sebastian Ruiz Torres ####


----

Se plantea optimizar el cultivo por hidroponia  con el objetivo de reducir perdidas por malas practicas, a la vez que se reduce el espacio necesario y se genera una interaccion educativa con el usuario.

Publico objetivo: Personas con la necesidad de cultivar en espacios reducidos sin la necesidad de dañar los suelos, personas con el deseo de tener un cultivo en el hogar como pasa tiempo 

Objeivo General:  Diseño, creacion y aplicacion  de un sistema de monitoreo que permita la optimizacion del cultivo y la interaccion educativa con el usuario.

![unknown](https://user-images.githubusercontent.com/88418156/186547927-50646758-781d-460b-a5ae-b2e2ee4a1a16.png)

Para el area urbana se plantea un rack de cultivo vertical (como el que se observa en la imagen anterior) con los sensores implementados dentro de si mismo, y previamente calibrados; todo conectado al esp32 de modo que el usuario solo deba conectar a la almientacion y  conectar a una fuente hidrica.
Se plantea que el usuario reciba notificaciones  por medio de su correo con la informacion del monitoreo y con informacion educativa sobre el cultivo en cuestion.

----
## **Diagrama de bloques del sistema.** ##

En el siguiente diagrama se muestran los diferentes componentes que se plantean implementar en el sistema, en este se pueden observar cada una de las entradas y salidas que se pretenden tener en el sistema. Como interacción principal con el usuario se va a construir un sistema que conecte con el telefono del usuario y lo alerte sobre las condiciones de la planta.

![Diagrama_en_blanco](https://user-images.githubusercontent.com/88418156/186547916-15719605-8ecb-488c-ab9b-c09ebaba3a6a.png)

## **Diagrama de caja negra con los modulos del ESP32.** ##
![Diagrama Bloque Embebidos](https://user-images.githubusercontent.com/88418156/187798153-f135e02f-7803-41c5-bae0-eb111757a825.png)


