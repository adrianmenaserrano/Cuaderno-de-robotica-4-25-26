# INICIO
Primero hemos empezando creando el nombre de la pagina web con sus respetivos códigos despues hicimos una presentacion y pusimos una imagen de lo que representa robotica para nosotros.
despues hicimos carpetas.La primera seria imagenes donde van todas las imagenes, la segunda es pasos previos donde habia que crear un readme para escribir esto.Y por ultimo una subcarpeta de imagenes donde ponemos las fotos que hemos echo.
una de esas fotos es un codigo de luces intermitentes con su codigo y su forma.
# Doble intermitente.
<img width="568" height="457" alt="image" src="https://github.com/user-attachments/assets/5281ac29-472b-4d43-8ba1-a327870bf450" />

Para esto hemos tenido que hacer un codigo que es el siguiente

<img width="332" height="383" alt="image" src="https://github.com/user-attachments/assets/30ae8b77-d8ad-4919-b8d4-71a6325249ac" />

Lo que hace este codigo es generar un bucle entre dos diodo led que se van intercambiando entre encendido y apagado provocando un efecto de luces intermitentes.
## El funcionamiento del codigo
1 El void set up: su función es ejecutar código de configuración una sola vez al inicio del programa.

2 El void loop: lo que hace es generar un bucle en el comando.

3 El int: es una variable de una variable que almacena números enteros

4 El pingmode: es la seleccion de numeros que has elejido en una placa Arduino

5 El digitalwrite: es  una escritura digital :)

6 Los botones HIGH y LOW: En la programacion HIGH es encendido y LOW apagado

7 Delay: es el tiempo de espera que le pones a un comando 

8 Serial begin: es un indicador de velocidad 

9 El if: Es una condicional que indica a un bloque la funcion que tiene que hacer.
## Pulsador.
<img width="638" height="491" alt="image" src="https://github.com/user-attachments/assets/d973f853-685a-48c2-afc5-de1669b71147" />

Esta es la imagen de lo que tendria que tener la placa arduino para que funcionase el pulsador que esta compuesto por un. Cables,diodos LED, resistencias y un pulsador.
## Segunda parte: su codigo y como funciona
<img width="293" height="450" alt="image" src="https://github.com/user-attachments/assets/c8bb4e9f-ecfd-4634-b285-cc2f242560da" />

## El codigo funciona de la siguiente manera:
1 Se inicia el codigo y una LED se enciende gracias los pines 3 y 6 que estan en OUTPUT

2 Al encenderse el primer LED el segundo permanece apagado. Eso gracias a que mientras uno esta en HIGH el otro permanecera en LOW

3 Activas/pulsas el pulsador 

4 Al pulsar el pulsador el primer LED se enciende y el otro se apaga probocando que se conviertan en luces intermitentes. Eso pasa por que mientras uno esta en HIGH(ON) el otro va estar en LOW(OFF) provocando que uno este encendido y otro apagado.

5 Que es el if: Es el que indica un bloque la funcion que tiene que hacer.

# Mapeado de los circuitos
##  Potenciómetro. Monitor serie.
<img width="678" height="481" alt="image" src="https://github.com/user-attachments/assets/2d8a59c6-3f11-4b60-ba9e-3abe0eb3f62d" />

Lo que hace este circuito es al encenderse se encinde un potenciometro que mientrasestes girando su ruedecita sube o baja la intensidad de la luz del diodo led

## Su codigo:
<img width="242" height="288" alt="image" src="https://github.com/user-attachments/assets/1f359632-80a2-4811-ae53-3d6f6154245c" />

lo que hace es crear un bucle que mientras más gires la ruedecita para un lado o para el otro mas sube su intensidad o se disminuye

## Foto de la prueba
![Imagen de WhatsApp 2025-11-10 a las 13 00 57_f36aacb7](https://github.com/user-attachments/assets/6c0329a7-2b43-4706-8064-9d5566f1e79b)

# Fotos del nuevo robot de ultrasonido.
![Imagen de WhatsApp 2025-11-10 a las 13 39 46_1a110128](https://github.com/user-attachments/assets/40f0e03c-364a-40f4-96d0-877acc1529ba)

![Imagen de WhatsApp 2025-11-10 a las 13 39 47_25341bec](https://github.com/user-attachments/assets/5a12fe5c-4ea7-4bde-b406-cf954ceabdfe)

![Imagen de WhatsApp 2025-11-10 a las 13 39 47_9e56d25e](https://github.com/user-attachments/assets/ebc767fb-10dc-4ff9-8df1-b0ca925ea88f)





