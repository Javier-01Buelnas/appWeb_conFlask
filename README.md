# Flask_appWeb

This is a project web where is working whit Flask, Html, and mongo Data Bases 

# Clonar el repositorio
 git clone https://github.com/Javier-01Buelnas/Flask_appWeb
 
 
 Compilar el contenedor dentro de la terminal

 -cd basic_flaskapp_container
 
# 1.Iniciar el servidor Docker en la terminal 
  $ docker-compose up -d 
  
  Ctrl + C -> Para detener Docker
# 2. Ver registros en Mongo 
$ sudo docker ps -> Para ver un enlistado en el cual aparece mongo(copiar ID)

$ sudo docker exec -it bash -> Iniciar mongo 

mongo -> Ejecutar mongo 

########################################################

# Dentro de mongo
show dbs ->para ver las BD disponibles 

use testdb -> usar testdb 

show collections -> Mostrar tablas 

db.users.find() -> ver registros de users 

db.posts.find() -> ver registros de posts 

db.post.drop() -> eliminar regiatros

# 3.Iniciar Docker Copiar url en el navegador para realizar un registro http://localhost:8181/signup
