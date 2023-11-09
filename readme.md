# Servidor Jenkins con Blueocean y Docker in Docker

Este proyecto tiene como objetivo mantener la configuracion de Jenkins con blueocean para implementar distintas automatizaciones para los pipelines CI/CD, construccion de imagenes de docker, backups, etc.

Se despliega usando docker-compose y una imagen que debe ser construida a partir del dockerfile que esta en la carpeta 
/docker

## Construcción de la imagen

Ver docker/dockerfile:

/docker $ docker build -t uololo/jenkins-blueocean-dind .

## Documentación

Este repo fue configurado siguiendo la siguiente documentación

- https://www.jenkins.io/doc/book/installing/docker/#setup-wizard
- https://akarshseggemu.medium.com/ci-docker-compose-to-containerize-jenkins-and-docker-in-docker-dind-agent-ad68bac9e1d8

## Plugins instalados

- Folders Plugin 
- OWASP Markup Formatter 
- Build Timeout 
- Credentials Binding Plugin 
- Timestamper 
- Workspace Cleanup 
- Ant 
- Gradle 
- Pipeline 
- GitHub Branch Source Plugin 
- Pipeline: GitHub Groovy Libraries 
- Pipeline: Stage View Git plugin 
- SSH Build Agents 
- Matrix Authorization Strategy 
- PAM Authentication 
- LDAP 
- Email Extension 
- Mailer Plugin 
- Dashboard View 
- Configuration as Code 
- NodeJS 
- Conditional BuildStep 
- Parameterized Trigger 
- Copy Artifact 
- Git Parameter 
- GitHub plugin 
- Role-based Authorization Strategy 
- Locale

## Replicación en Local

Para replicar en local ver documentación

https://docs.google.com/document/d/1-WfYXPjHHSdq9lBGJ_ZzYz10UweZw7bLTP2FTOHr844
