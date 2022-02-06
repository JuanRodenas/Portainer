# Portainer
Proyecto para crear un contenedor portainer en Docker.

![alt text](https://github.com/JuanRodenas/Portainer/blob/main/portainer.png)

### INSTALAR DOCKER-COMPOSE.YML DE PORTAINER
Edite las siguientes variables:

Descargar docker compose [docker-compose.yml](https://github.com/JuanRodenas/Portainer/blob/main/docker-compose.yml)

### Variables del docker-compose
- Cambiar el valor de la variable

### Lanzar el contenedor
Edite el volumen y cambiar la ruta deseada:
~~~
  volumes:
    - /patch/to/data/portainer/config:/config
~~~

### Lanzar el contenedor
~~~
docker-compose up -d
~~~

### Ver el log para ver los códigos QR para los usuarios
~~~
docker logs portainer
~~~

### Supervisar el tráfico de un cliente conectado
- Acceder al contenedor:
~~~
docker exec -it portainer bash
~~~

### Acceso al portal web
Accedemos al portal web de gestión de los contenedores.
~~~
domain.example.com
~~~

## Ready!
