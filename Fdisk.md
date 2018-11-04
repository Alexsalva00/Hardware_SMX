# Fdisk

Fdisk es un software que está disponible para varios sistemas operativos, el cual permite dividir en forma lógica un disco duro, siendo denominado este nuevo espacio como partición.

# Comandos 

1. Ver todas las particiones.

Para listar todas las particiones existentes en nuestro sistema pasaremos el argumento “-l”, que hará que se listen ordenadas por el nombre del dispositivo.

fdisk –l

2. Ver un disco específico. 

Para ver todas las particiones de un único disco, al comando anterior añadiremos el nombre de dicho disco, expresado de la forma en la que se mostraba en la captura anterior, es decir, algo así:

fdisk –l /dev/sdb

3. Ver todos los comandos disponibles.

Si queremos ver todas las opciones que nos ofrece fdisk, únicamente deberemos pasar el comando seguido de una unidad de disco (para darle algo sobre lo que trabajar).

Ya en el menú de fdisk, pulsaremos ‘m’ para entrar en la ayuda y ver todas las opciones que podríamos aplicar al disco seleccionado.

4. Mostrar toda la tabla de particiones del Sistema.

Para mostrar al completo la lista de particiones de nuestro sistema, al igual que antes deberemos pasar una unidad con la que conseguir acceso al menú de fdisk, tras lo cual, una vez en el mismo, pulsaremos en esta ocasión ‘p’, para obtener el listado que buscamos.

