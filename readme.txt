Fichero Dockerfile cono instrucciones para instalar algunas herramientas de kali linux dentro de Docker, ejecutable en cualquier sistema operativo.

comandos:

cd repo/

docker build --tag hacking .

docker run -it --network=host hacking bash