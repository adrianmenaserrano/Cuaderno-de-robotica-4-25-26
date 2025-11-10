# INICIO
Primero hemos empezando creando el nombre de la pagina web con sus respetivos códigos despues hicimos una presentacion y pusimos una imagen de lo que representa robotica para nosotros.
despues hicimos carpetas.La primera seria imagenes donde van todas las imagenes, la segunda es pasos previos donde habia que crear un readme para escribir esto.Y por ultimo una subcarpeta de imagenes donde ponemos las fotos que hemos echo.
una de esas fotos es un codigo de luces intermitentes con su codigo y su forma.
# CODIGO DE TINKERCAD Y SU EXPLICACION
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
## Primera parte: Su conexiones
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
## CIRCUITO NUMERO 1
<img width="1366" height="510" alt="image" src="https://github.com/user-attachments/assets/f1cb3fb0-fb52-4d7b-8a56-6bda777b0720" />


