## Despliegue de apps Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido:

````
java.runtime.version=17
````

1. Crear cuenta en heroku.com
2. Tener configurado git en el ordenador
   1. 'git config --global user.name "username"'
   2. 'git config --global user.email email@email.com'
3. Subir el proyecto a GitHub desde Intellij IDEA desde la opción: VCS > Share project on GitHub
4. Desde Heroku, crear app y elegir método GitHub y buscar repositorio
5. Habilitar deploy automático y ejecutar el Deploy