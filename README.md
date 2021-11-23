
## Despliegue de apps Spring Boot en Heroku

Crear archivo `system.properties` en el proyecto con el contenido:
...
java.runtime.version=17
...

1. Crear cuenta en heroku.com y github.com
2. Tener configurado el git en el ordenador
   1. 'git config --global user.name "Abraham Quintana"
   2. 'git config --global user.email abraha.....com'
3. Suit el proyecto a Github desde Intellij desde la opción: VCS >Share project on Github
4. Desde Heroku, crear app y elegir método Github, buscar el repositorio subido.
5. Habilitar deploy automático y ejecutar el Deploy