<!-- ENTRAR A CONTENEDOR QUE SE ESTA CORRIENDO (nombre servicio esta vez es mongodb)-->
docker-compose exec mongodb bash

<!-- CONECTAR MONGOSH ("" VA LA URL DE CONEXION)-->
mongosh "mongodb://root:root123@localhost:27017/?tls=false"
mongosh "mongodb+srv://yersonadmin:yersonadmin2011@mongodb101.icg1o.mongodb.net/"

<!-- MOSTRAR BD QUE TIENE-->
show dbs
show collections