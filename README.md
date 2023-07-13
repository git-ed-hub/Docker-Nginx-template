# Docker-Nginx-template
Dockerfile para migrar un sitio web en un servidor Nginx

#Se crea una imagen que nos muestra nuestra plantilla
docker build .

#Para ejecutar la imagen
docker run -p 8080:80 <nombre de la imagen docker>

#Para visualizar el template en Nginx
localhost:8080
