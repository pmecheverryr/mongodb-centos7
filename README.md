# MongoDB en CentOS 7
Imagen Docker con Base de datos MongoDB con Centos 7

* Descargar imagen
docker pull mecheverry/mongodb-centos7

* Crear contenedor
docker run -d --name mongodb-test -p 27017:27017 mecheverry/mongodb-centos7
