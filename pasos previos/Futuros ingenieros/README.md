# FOTO DE COMO QUEDARIA MI ROBOT DEL PROYECTO.
<img width="1260" height="642" alt="Brilliant Bigery-Curcan (3)" src="https://github.com/user-attachments/assets/178e95f0-ee44-48ed-a031-e6b4355e0c90" />


## EXPLICACION DEL PROYECTO EN CUESTION.
Lo que vamos ha hacer en este poyecto es hacer un vehiculo impreso en 3D. El objetivo principal es gracias a la placa arduino meterlo codigo para que el vehiculo pueda escapar de un laberinto que día a día sera distinto haciendo que el robot pueda salir dando igual de que forma este hecha el laberinto.

## ¿QUE MATERIALES USA?
Los materiales que usa son los siguientes:

-2 motores de corriente continua con reductora

-1 placa arduino

-1 ultrasonidos

-1 pollito

-1 escudo L298N

-2 baterias 3,7V 18650

-1 chasis

# RESULTADO DE COMO QUEDARIA EL ROBOT CON SUS PIEZAS.
|           PARTE UNO DEL DISEÑO DEL ROBOT DES EL ENFRENTE    |        PARTE DOS DEL DISEÑO DEL ROBOT DESDE ARRIBA            |      
|--------------------------------------------------------------|--------------------------------------------------------------|
|<img src= "Imagenes/IMG_1179.jpeg" width="500" height="500" />|<img src= "Imagenes/IMG_1272.jpeg" width="500" height="500" />|

## ¿COMO LO HEMOS HECHO?
## Para hacer el robot lo hemos echo en varios pasos:

## 1. Atornillar las placas a la base del robot

Para ello, lo que hemos hecho ha sido medir cuánto mide, por ejemplo, la placa Arduino y luego medir la base para saber dónde colocarla y cómo hacerlo. De esta manera, a la hora de atornillarla no tendremos problemas con las demás piezas que también hay que fijar, como el escudo y los motores.

## 2. El cableado

Esta es la parte más estresante, sin ninguna duda, por la cantidad de cables que hay en un espacio tan reducido. Pero bueno, lo primero es saber qué cables necesitamos. Para ello, solo necesitamos cables macho-macho y macho-hembra. Aproximadamente, usamos unos 9 cables macho-hembra y 6 macho-macho.
Una vez que tengamos los cables, habría que unirlos con las partes correspondientes. Lo primero que hay que hacer es conectar los 6 cables macho-macho al escudo, de forma que queden bien fijados (los ponemos en el escudo para poder controlar y programar los motores más tarde). Después, conectamos los cables macho-hembra que quedan entre el escudo y la placa Arduino que atornillamos antes.

## 3. La programación

Es un proceso que aún no hemos hecho, pero estamos en ello. La idea que tenemos es que el robot, utilizando un solo sensor ultrasónico (aunque en un principio pensábamos usar 3), pueda, con la ayuda de un servomotor, hacer que el sensor gire 180 grados. Así, el robot podrá detectar obstáculos e intentar recorrer un laberinto sin chocar.

(corregido por chatGPT)
## ¿CUAL ES EL FIN DE TODO ESTO?
El fin de todo esto es construir programar y hacer que aprenda ha hacer  que el robot pueda pasar or un laberito que cambia y se hace más dificil cada día que pase y lo que tiene que hacer el robot es conseguir que pase el laberinto sin chocarse ninguna vez.
## ¿QUE OBJETOS HEMOS UTILIZADO?
-2 Motor: esto lo que hace es darle la movlidad al robot que para ello hemos tenido que atornillar a la base no sin antes medir el espacio que tiene  para que ocupe el minimo espacio posible antes de colocarlo y atornillarlo.
-1 Escudo: esto lo que hace es que la programacion que le demos al robot se la pase al escudo y del escudo al motor para darle movilidad.
-1 Placa arduino:esto sirve para que se pueda programar para que haga todas las funciones que he mencionado arriba que luego pasara una vez terminado la programacion pase al escudo y del escudo a los motores

## FOTO DEL ROBOT.
|        PARTE DOS DEL DISEÑO DEL ROBOT DESDE ARRIBA           |                
|--------------------------------------------------------------|
|<img src= "Imagenes/vvvvv.jpg" width="500" height="500" />    |                                                              

# RETOS
## 1 el giro del servomotor
[![](https://img.youtube.com/vi/qjQLPe0YbU4/0.jpg)](https://www.youtube.com/watch?v=qjQLPe0YbU4)

El reto uno consiste en hacer que el servo motor haga que el ultrasonido gire en 0 90 y 180 grados.

## 2 Marcar la distancia del ultrasonido
[![](https://img.youtube.com/vi/m6MNIqrkrx4/0.jpg)](https://www.youtube.com/watch?v=m6MNIqrkrx4)

El reto dos consiste en con el codigo marcar datos que vaya haciendo en el monitorSeries.

## 3 Qué pueda ir hacia adelante y hacia atras
[![](https://img.youtube.com/vi/ZSjYsuk3554/0.jpg)](https://www.youtube.com/watch?v=ZSjYsuk3554)

El reto tres consiste en el que el robot con ayuda de los motores pueda ir hacia adelante y hacia atras

## 4 marcar la distancia y quedarse quieto.
[![](https://img.youtube.com/vi/UCqJFzujzTE/0.jpg)](https://www.youtube.com/watch?v=UCqJFzujzTE)

El cuarto ejercicio consiste en que con la ayuda del ultrasonido lo que va ha hacer es que si se encuentra una estructura en el momento que marque en el monitorSeries menos de 20 cm el robot se quedara quieto.

## 5 Detectar la pared más lejana
[![](https://img.youtube.com/vi/uuJXEzctWdo/0.jpg)](https://www.youtube.com/watch?v=uuJXEzctWdo)

El quinto lo que hace es detectar la pared que más lejos este y dependiendo si la pared más lejana esta a la izquierda o ha la derecha se ira para un lado o para el otro.

## 6 EL ROBOT GIRA HACIA LA PARED MÁS LEJANA.
(No tengo el video)

Lo que hace este reto es que el robot lo vamos a poner en un situacion donde haya una pared que este muy cerca del robot y otra pared que este muy lejos entonces lo que tiene que hacer el robot es que si la pared más lejana es la de la derecha el robot con el ultrasonido detectara las dos paaredes y decidira cual de las dos paredes este más lejos si la pared de la derecha est más lejos el robot dara un giro asta ponerse en direccion a esa pared y avanzara hacia la pared más lejana.
# PROGRAMACION DE LOS RETOS
## RETO 1
<img width="318" height="481" alt="image" src="https://github.com/user-attachments/assets/4603c2ad-fad5-42d0-89d5-2a47e04917ed" />

## RETO 2 
<img width="318" height="481" alt="image" src="https://github.com/user-attachments/assets/1cb0b72c-8cd1-488d-b698-651223fa4c45" />

## RETO 3
<img width="267" height="455" alt="image" src="https://github.com/user-attachments/assets/4a838249-021c-460c-9387-e54baa83c041" />

## RETO 4
<img width="261" height="409" alt="image" src="https://github.com/user-attachments/assets/ec8e3d20-57d5-41eb-a3b2-889005a25f34" />

## RETO 5
<img width="221" height="475" alt="image" src="https://github.com/user-attachments/assets/a114e55c-0f49-4a05-941a-c98db534a9f9" />

# PROGRAMACION DEL RETO FINAL
## PARTE 1
<img width="533" height="857" alt="codigo parte 2" src="https://github.com/user-attachments/assets/c129b80d-851f-4e0a-ba69-36b9141392fb" />

## PARTE 2
<img width="612" height="803" alt="codigo parte tres" src="https://github.com/user-attachments/assets/87df4aba-3972-4b35-a550-ca0fcb0afc91" />

## PARTE 3
<img width="407" height="787" alt="image" src="https://github.com/user-attachments/assets/0987cb9b-c533-4920-a655-127d6b0ba394" />

## PARTE 4
<img width="407" height="157" alt="codigo final" src="https://github.com/user-attachments/assets/f39db7e1-ceb7-4256-b14f-eb055e47a74a" />

# DIADRAMA DE FLUJO
<img width="290" height="293" alt="image" src="https://github.com/user-attachments/assets/2e541686-f03d-4477-8c17-f8f87e19671c" />
