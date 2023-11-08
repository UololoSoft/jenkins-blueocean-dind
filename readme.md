# Servidor Jenkins con Blueocean y Docker in Docker

Este proyecto tiene como objetivo mantener la configuracion de Jenkins con blueocean para implementar distintas automatizaciones para los pipelines CI/CD, construccion de imagenes de docker, backups, etc.

Se despliega usando docker-compose y una imagen que debe ser construida a partir del dockerfile que esta en la carpeta 
/docker

## Construcción de la imagen

/docker $ docker build -t uololo/jenkins-blueocean-dind .

