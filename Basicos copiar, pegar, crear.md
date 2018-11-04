### Touch

Touch crea un archivo vacío, si el archivo existe actualiza la hora de modificación. Para crear el archivo prueba1.txt en /home, seria:

$ touch /home/prueba1.txt

</br>

### Mkdir

Mkdir (de make directory o crear directorio), crea un directorio nuevo tomando en cuenta la ubicación actual. Por ejemplo, si estas en /home y deseas crear el directorio ejercicios, sería:

$ mkdir /home/ejercicios


Mkdir tiene una opción bastante útil que permite crear un árbol de directorios completo que no existe. Para eso usamos la opción -p:

$ mkdir -p /home/ejercicios/prueba/uno/dos/tres

</br>

### Mv

mv para mover archivos
