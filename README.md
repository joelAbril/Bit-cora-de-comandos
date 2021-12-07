# Bit-cora-de-comandos
Comandos que se ven en las clases del curso de Sistemas Operativos 
Comando  | Descripción  |    Ejemplo    |
-------- | ------------ | ------------- |
ip addr | ver el network | dirrección ip(inet 192.168.003)|
ping 8.8.8.8 | acceso a internet | 64 bytes from 8.8.8.8: icmp_seq=2 ttl=113 time=59.8 ms |
clear | limpia la pantalla | deja la terminal limpia |
sudo apt update | Muestra las actualizaciones que hay | Se pueden actualizar 4 paquetes. Ejecute «apt list --upgradable» para verlos |
sudo apt upgrade| actualizar todo en el sistema | Creando árbol de dependencias |
pwd| Donde estoy en el sistema | /home/joel |
whoami| quien soy, nombre de usuario | joel |
echo | imprimir un mensaje con Bash | echo "hola mundo" |
cd /| Entrar a un sector en especifico del file explorer en linux | cd Downloads/ |
sudo apt install| instalar paquetes | sudo apt install docker |
nano script| crear un nuevo script | nano Script hola |
bash nombreScript| correr un script | bash Script0.1 |
mkdir nombre| crear una carpeta | mkdir joel |
cp | agregar texto | cp joel |
ls| ver el contenido de algo | ls Desktop |
rm| borrar | rm joel |
grep| buscar cadena de texto | grep "literal_string" filename |
touch| crear archivo | touch joel |
-R| remover algo recursivamente | joel -R |
-f| remover algo forzado | joel -f |
rm -rf/| borrar todo | no hay ejemplo |
scp| hacer copia atravez de la red | scp joel |
wget| extraer archivos páginas web | wget https://cdn.kernel.org/pub/linux/kernel/v4.x/linux-4.17.2.tar.xz |
git clone | clonar github | no hay ejemplo |
Curl -x Get -L | enviar a una página web | Curl -x Get -L https://cdn.kernel.org/pub/linux/kernel/v4.x/linux-4.17.2.tar.xz |
wc | conteo de palabras | wc joel.txt |
history | historial de comandos | no hay | 
find | buscar cadena de texto | find . -name tecmint.txt | 
-mc | conteo de caracteres | -mc joel.txt |
-lc | conteo de lineas | -lc joel.txt |
reboot | reinicia el sistema | no hay ejemplo |
tail | muestra las ultimas lineas de un archivo de texto | tail -n joel.txt |
head | muestra las primeras lineas de un archivo de textos | head -n joel.txt |
du | ver cuánto espacio ocupa un archivo o un directorio | du -h joel.txt |
diff | compara el contenido de dos archivos | diff archivo1.ext archivo2.ext |
tar | guardar archivos en un tarball | no hay ejemplo | 
chmod | cambair los permisos de lectura | chmod +rwx filename to add permissions. | 
chown | cambiar o transferir la propiedad de un archivo | chown linuxize file1 |
jobs | muestra todos los trabajos actualez | jobs | 
kill | cerrar un programa manualmente | kill -1 PID_NUMBER | 
sudo apt-get install apt-transport-https ca-certificates curl gnupg-agent software-properties-common | Instalar paquetes necesarios de docker | sin ejemplo |
curl -fsSL https://download.docker.com/linux/debian/gpg | sudo apt-keyadd - |  Agregar la clave GPG oficial de Docker | sin ejemplo |
sudo add-apt-repository "deb [arch=amd64] https://download.docker.com/linux/ubuntu bionic stabl |  Agregar el repositorio oficial de Docker | sin ejemplo |
sudo apt-get install docker-ce docker-ce-cli containerd.io docker-compose | Instalar docker | sin ejemplo |
sudo usermod -aG docker $USER | usar docker sin necesidad del sudo | sin ejemplo |
docker search ubuntu | para buscar imagenes | sin ejemplo |
sudo docker images | para ver todas las imagenes instaladas | sin ejemplo |
sudo docker ps -a | para ver como están las imagenes instaladas | sin ejemplo |
docker start container-id| para iniciar un contenedor | sin ejemplo |
docker stop container-id | para detener un contenedor | sin ejemplo |
sudo docker login -u USUARIODOCKERHUB | iniciar sesión en docker | sudo docker login -u jabrilm16 | 
sudo docker commit b7dc036f2c99 | hacer un push a la cuenta de docker | sin ejemplo |
docker rmi Image Image | eliminar imagenes en docker | docker rmi Image Image15 |
docker rm ID ID | eliminar contenedores en docker | docker rm ID 4bd76e08b07f |
docker run --rm image_name | eliminar contenedores en docker después de cerrado| docker run --rm wordpress |
sudo docker rm $(sudo docker ps -a -f status=exited -q) |  Eliminar todos los contenedores con estado Exited (0) | sin ejemplo |
finger usuario | Muestra información general sobre un usuario en la red | finger jabrlim467@ulacit.ed.cr |
passwd | para cambiar la contraseña | sin ejemplo |
ps -ux | para mostrar información sobre los procesos que se están ejecutando en el sistema | sin ejemplo | 
Date | mustra la hora y la fecha actual | sin ejemplo |
cmatrix | pEntrar a Matrix | sin ejemplo |
telnet towel.blinkenlights.nl | Star Wars, A New Hope | Solo ver |
