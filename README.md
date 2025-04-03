# ParticionadoDiscos
Particionaremos dos discos con una maquina ubuntu atendiendo a las siguientes directrices.

El primer disco de 50Gib 
Particionado en Gdisk
Dos particiones primarias de 20GiB y 15GiB.
Crearemos un archivo de texto en cada partición con el texto "Soy la partición X GPT y tengo un tamaño de XGiB".
Las particiones se han de cargar en /media/sdX.

El segundo disco sera de 100GiB
Particionado con fdisk 
Tres particiones primarias de 20 GiB, 10 GiB y 15 GiB.
Una partición extendida que ocupe el resto del espacio.
Dos particiones lógicas de 10GiB y 15 GiB.
Crearemos un archivo de texto en cada partición con el texto "Soy la partición X MBR y tengo un tamaño de XGiB".

Realizaremos las modificaciones necesarias del /etc/fstab para poder montarlas en el arranque del sistema.
