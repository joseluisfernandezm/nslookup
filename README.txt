Nombre del proyecto: P2_3261_P02
Autor: José Luis Fernández Moreno <joseluis.fernandezm@estudiante.uam.es>
Fecha:29/11/2020

Descripción: El programa hace la función de un cliente DNS, obtiene 
direcciones IP a partir de un dominio proporcionado (de forma similar al
comando nslookup de linux).

Como ponerlo en marcha: 

Tras haber descomprimido el archivo .zip hallará
una carpeta en la que tendremos el programa minslookup.c y archivo makefile
necesario para compilarlo. Para ejecutarlo se necesitarán dos argumentos,
el ejecutable y el dominio del que se quiere obtener la direccion; si no
se proporcionan ambos el programa no funcionará.

Anotación:

Según las pruebas que he realizado al programa en ocasiones no 
se recibirá respuesta por parte del server DNS y saltará el timeout.
Si se vuelve ejecutar el problema se debería de solucionar (a veces habrá que
hacerlo más de dos veces), imagino que este problema ocurre debido a que la
respuesta no es capaz de llegar a nuestro cliente desde el servidor.

