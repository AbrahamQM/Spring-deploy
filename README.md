
## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:
...
java.runtime.version=17
...

1. Crear cuenta en heroku.com y github.com
2. Tener configurado el git en el ordenador (ejecutar únicamente la primera vez que instalamos git)
   1. 'git config --global user.name "Abraham Quintana"
   2. 'git config --global user.email abraha.....com'
3. Suit el proyecto a Github desde Intellij desde la opción: VCS >Share project on Github
4. Desde Heroku, crear app y elegir método Github, buscar el repositorio subido.
5. Habilitar deploy automático y ejecutar el Deploy

## Ejercicio 1

* Probar a empaquetar la app con maven package desde Intellij

* Desde terminal en Intellij verificar que se ejecuta correctamente con comando:

...
java -jar target/spring-deploy-1.0.jar
...

* Crear un perfil para dev y otro para test con una propiedad nueva que carguemos en el controlador.

## Ejercicio 2

Desplegar el api Rest de Laptop en Heroku y verificar funcionamiento desde Postman.

## Proveedores Cloud

*Heroku -- Java, Spring, PostgreSQL
*Netlify -- Frontend (React, Angular, ...)
*Vercel -- Frontend (React, Angular, ...)