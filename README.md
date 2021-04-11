 API REST
URL : https://api-dev-backend.herokuapp.com/
-----------------------------------------------
 
 versiones:
  - Spring boot Version: 3.9.13.RELEASE
  - Java version 1.8
  - Apache Maven 3.6.3
  
 
 --> LEVANTAR PROYECTO:
 	
 	
Clonar repositorio:
	git clone https://github.com/RogerBariles/api.git
	
Actualizar librerias:
	mvn clean package
	
	
DOCUMENTACIÓN SWAGGER:
	https://api-dev-backend.herokuapp.com/swagger-ui.html#/
	
----------------------------------------------------

DESCRIPCIÓN PROYECTO:
- Se utilizo el framework Sprin boot para realizar dicha Api Rest, en lo cual el proyecto se desglosa en dos directorios:
 	 com.apiRest.config: Donde se utilizo para realizar la implementación de el framework Swagger 						para documentar la api realizada.
 	 com.apiRest.Controllers: Donde se realiza en si el metodo para la api rest, se basa en una
 	 					clase e implementando decoradores tipo Controllers.
 	 					La api creada es por un metodo Put , que recibe 2 parametros Dato1 (horario 						a convertir), dato2 (desplazamiento).
 	 					
 	 					
 Para dar por finalizada esta parte, teniendo en cuenta que dicho proyecto no consta de desarrollo complejo se opto por utilizar el servidor virtual web de Heroku por su accesible creación y despliegue por medio de git.
 

 	 					
 	 				