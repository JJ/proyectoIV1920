# Proyecto MyMedia

[![Build Status](https://travis-ci.com/MartaArM/proyectoIV1920.svg?branch=master)](https://github.com/MartaArM/proyectoIV1920)


# Descripción del proyecto
La idea es crear un sistema de gestión de elementos multimedia tales como libros electrónicos, música, películas, series... 

El microservicio permitirá eliminar, editar, o añadir estos elementos.

# Motivación

Permitirá el acceso y modificación fácilmente de elementos multimedia a distintos usuarios.

# Herramientas 

1. El lenguaje a utilizar será Ruby.
2. El gestor de base de datos será MariaDB, ya que es un gestor que he utilizado en otras asignaturas y me parece "sencillo".
3. Para hacer integración continua, utilizaré [Travis CI](https://travis-ci.com/), ya que viene "integrado" con GitHub y no es necesario crearse una cuenta ni descargar nada.
4. Para el despliegue en la nube, utilizaré [Heroku](https://www.heroku.com/), ya que es un servicio gratuito y fácil de utilizar.
5. Como framework, uso [Sinatra](http://sinatrarb.com/).

# Instalación y tests

Para instalarlo, simplemente hay que hacer un clone:

`git clone https://github.com/MartaArM/proyectoIV1920.git`.

Para ejecutar los test básicos, basta con hacer:

`rake test`

Para levantar y parar el servicio, se debe hacer:

`rake start`

y

`rake stop`

Para probar el servicio: 

`curl http://localhost:9292/status`

buildtool: rakefile