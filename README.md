# El archivo docker-compose.yml tiene la configuración para la ejecucion del proyecto Springboot para la deteccion de ADN mutante.

Ejecucion.

Clonar el repositorio
git clone https://github.com/rantezPeperino/mutante-docker-compose.git


Luego ejecutar el docker-compose para crear los contenedores de springboot y mysql

docker-compose up -d

End point

http://localhost:8080/mutante/mutante/

http://localhost:8080/mutante/stats/
