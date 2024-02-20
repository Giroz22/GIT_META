# Configuracion

Comando para conocer la version de github

- git --version

Comandos para configurar git por primera vez:

- Configural nombre de usuario:
  git config --global user.name "Your name"

- Configurar correo de usuario:
  git config --global user.email "your@correo.com"

Comando para ver las configuraciones de git:

- git config --global user.name
- git config --global user.email
- git config --list

Comando para eliminar la configuracion de git

- rm ~/.gitconfig

Comando para inicializar git en un directorio

- git init

Comando para ver el estado de los archivos

- git status

Comando para ver todas las versiones de mi proyecto

- git log //Detallado
- git log --online //Info base

Comando para cambiar entre versiones

- git checkout "Nombre de la rama o del identificador de la version"
- git checkout --. //Ir a la version anterior

Pasos para crear una version de mi codigo

1. Agregar los cambios

   - git add . //Agrega todos
   - git add \*.js //Agregar todos los archivos .js
   - git add index.html //Agregar un solo archivo

2. Comprometer los archivos
   -git commit -m "Descripcion del commit"
