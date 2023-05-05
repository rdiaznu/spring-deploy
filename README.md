## Despliegue de apps en Spring Boot en Heroku

Crear archivo 'system.properties' en el proyecto con el contenido:

```
java.runtime.version=17
```



1. Crear cuenta en Heroku
2. Tener configuración git en el ordenador
   1. `git config --global user.name "Rommel Díaz"`
   2. `git config --global user.email rodinur27@gmail.com`
3. Subir el proyecto a GitHub desde Intellij Idea desde la opció: VCS > Share projecti con GitHub
4. Desde Heroku, crear app y elegir método GitHUb y buscar el repositorio subido
5. Habilitar deploy automático y ejecutar el Deploy