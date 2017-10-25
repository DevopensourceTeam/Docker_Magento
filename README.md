# Docker_Devostack

Nuestro stack de desarrollo contendrá diferentes herramientas para la utilización en el desarrollo general de la empresa
donde abarcamos diferentes plataformas y servicios:

**Contenedores principales:**

- Nginx proxy = jwilder/nginx-proxy
- Apache2 + PHP7.0.12-fpm + Unison (performance Mac only)= magento/magento2devbox-web:latest
- Mysql 5.6 = mysql:5.6
- Portainer

**Servicios adicionales**

- Portainer = portainer/portainer
  - Interfaz web de Docker

# Commands

Documentación de comandos

- http://devdocs.magento.com/guides/v2.1/install-gde/docker/docker-commands.html

# Links de interes

- Como optimizar el tamaño de cada capa en contenedores Docker https://developers.redhat.com/blog/2016/03/09/more-about-docker-images-size/
- Validar un Dockerfile https://www.fromlatest.io
