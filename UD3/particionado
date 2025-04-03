# Particionado

Primero añadiremos los discos necesarios para la práctica, en este caso uno de 50GB para particionar en GPT y uno de 100GB para particionar en MBR.
![Imagen1](./Imagenes/1.png)


## Verificación de los discos

Comprobamos que los discos se añadieron adecuadamente y comprobamos el estado de partida.
![Imagen2](./Imagenes/2.png)
## Particionado con Gdisk

Empezamos por el disco más pequeño que particionaremos con **Gdisk**.
![Imagen3](./Imagenes/3.png)

### Creación de particiones

A continuación, haremos las particiones.
![Imagen4](./Imagenes/4.png)
![Imagen5](./Imagenes/5.png)

Guardamos y salimos.
![Imagen6](./Imagenes/6.png)
### Formateo y montaje

Formateamos en **ext4**.
![Imagen7](./Imagenes/7.png)
![Imagen8](./Imagenes/8.png)
Montaje en `/media/sdb`.
![Imagen9](./Imagenes/9.png)
Añadimos los ficheros de texto.
![Imagen10](./Imagenes/10.png)
### Configuración del `fstab`

Configuramos el `fstab`.
![Imagen11](./Imagenes/11.png)
![Imagen12](./Imagenes/12.png)
Aplicamos los cambios.
![Imagen13](./Imagenes/13.png)
---

## Particionado con fdisk

A continuación, el disco de 100GB con la herramienta **fdisk** e iremos creando las distintas particiones primarias.
![Imagen14](./Imagenes/14.png)
![Imagen15](./Imagenes/15.png)
![Imagen16](./Imagenes/16.png)

### Creación de particiones

Ahora la extendida.
![Imagen17](./Imagenes/17.png)

Ahora haremos las lógicas, siguiendo el mismo proceso con las dos.
![Imagen18](./Imagenes/18.png)
![Imagen19](./Imagenes/19.png)

Guardamos con `W`.
![Imagen20](./Imagenes/20.png)
### Formateo y montaje

Formateamos las particiones, repitiendo el proceso con cada número de partición.
![Imagen21](./Imagenes/21.png)

Montamos las particiones.
![Imagen22](./Imagenes/22.png)

Añadimos el fichero de texto correspondiente a cada partición.
![Imagen23](./Imagenes/23.png)
Editamos el fichero `fstab`.
![Imagen23](./Imagenes/ultima.png)
---

Y con esto estaría completa la práctica.