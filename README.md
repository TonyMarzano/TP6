# TP6
Repo para entregar del TP6, contiene un Dockerfile y archivos html,css,js que serán utilizados al momento de levantar un contenedor


-crea una imagen de Docker a partir de este Dockerfile ejecutando el siguiente comando en el directorio donde tengas los archivos mencionados:
  docker build -t santinotona/tp6:v3 .  (Link de la Imagen en DockerHub: https://hub.docker.com/repository/docker/santinotona/tp6/general)

-Una vez que la imagen esté construida, puedes ejecutar el siguiente comando para crear un contenedor basado en esa imagen:
  docker run -d -p 80:80 --name contenedor_v3 -v /mnt/c/Users/Marzano.S100/Desktop/BootCampDevops/TP6-BOOTCAMP:/var/www/html santinotona/tp6:v3

-Luego, puedes subir la imagen a DockerHub con el siguiente comando:
    docker push santinotona/tp6:v3
