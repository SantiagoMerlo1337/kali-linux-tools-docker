Fichero Dockerfile con instrucciones para instalar algunas herramientas de kali linux dentro de Docker (ejecutable en cualquier sistema operativo).

Comandos:

cd kali-linux-tools-docker/

sudo docker build --no-cache --tag kali .

sudo docker run -it --privileged --network=host kali bash
