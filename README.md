# Linux-AM
- `root`:  Permite cambiar todo.
- `htop`: Muestra la lista de los procesos.
- `pstree`: Ver los procesos de nuestro sistema operativo(no es interactivo).
- `top`: Ver los procesos de nuestro sistema operativo( es interactivo). 
- `sudo`: Ejecutar los comandos.
- `apt`: Instalar aplicaciones.
- `ping`: Revisar si esta conectado a internet.
`Comando 1`
  for file in /proc/*/status ; do awk '/VmSwap|Name/{printf $2 " " $3}END{ print ""}' $file; done | sort -k 2 -n -r | less

`Comando 2`: free -h

`Comando 3`
  swapon

`Comando 4 Swampiness`
  cat /proc/sys/vm/swappiness

`Montar un RAM Disk`
  sudo mkdir /mnt/ram_disk
  sudo mount -t tmpfs -o size=1024m new_ram_disk /mnt/ram_disk
`sudo pacman -Syuu` : Sirve actualizar los paquetes disponibles del sistema operativo:  
`sudo pacman -S unrar zip unzip p7zip gzip bzip2` : Sirve para instalar nuevos paquetes se utiliza el comando pacman: 
`sudo pacman -S yay` :Este repositorio permite tener acceso a otros paquetes de software que no están disponibles (EN MAJARO)
`sudo useradd -m nombredeusuario -G wheel -p passworddelusuario` : Este es un comando para agregar un nuevo usuario
`uname -a`: 
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
``
