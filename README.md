# docker_php
Ejercicio de creación de Mini-página web con PHP en un Contenedor de Docker y montado en Render

# Docker-PHP
"Hola Mundo" Creado con PHP y montado en contenedor Docker

## GIT Commands
git add .
git commit -m "CREATED "
git push -u origin main

## Docker Commands
### 1. Build an image from a File:
```bash
docker build -t [name:tag] "dockerfile path"
```

### 2. Delete an image:
```bash
docker rmi [name:tag/id]
```

### 3. Create the docker container:
```bash
docker run -p 8080:8080 [name:tag]
```

### 3. Visualize docker containers: 
```bash
docker ps # Actives
docker ps -a # All
```

#
docker start nice_albattani
docker start -i nice_albattani
docker kill nice_albattani


#
docker tag isma:v2 sengokusama/prueba:latest

#
docker push sengokusama/prueba:latest

docker pull salvadorhm/ml4d:0.79
docker run -it -p 8080:8080 salvadorhm/ml4d:0.79
