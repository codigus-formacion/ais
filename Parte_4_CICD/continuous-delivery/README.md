# Entrega Continua

Este proyecto consta de un servidor WEB sencillo para la gestión de posts (anuncios).

## Construir la aplicación (en local)

Para construir la imagen Docke del proyecto (y lanzar los test):

```
    mvn spring-boot:build-image
```

## Lanzar la aplicación (en local)

Para lanzar la aplicación el local:

```
    docker run -p 8080:8080 posts:0.1.0-SNAPSHOT
```

## Construimos y subimos la imagen a DockerHub

```
    docker login
    docker tag posts:0.1.0-SNAPSHOT <dockerhub-user>/posts:0.1.0-SNAPSHOT
    docker push <dockerhub-user>/posts:0.1.0-SNAPSHOT
```

## Lanzamos la imagen

```
    docker run -p 8080:8080 <dockerhub-user>/posts:0.1.0-SNAPSHOT
```

