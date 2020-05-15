# Página de mi perfil.

Este proyecto es de mi perfil y sigue en proceso.

Hola a todos en el b40 de blanca! :D

## Git vs Github

https://git-scm.com/

https://github.com/


## Configuramos nuestra terminal:

Aprendimos comandos

### Comandos Unix

cd
cd ..
ls
pwd
mkdir
touch

rm ¡¡cuidado!!

### Commando de git

• Desde consola, se puede acceder a la configuración de Git con el comando:

git config

• Se recomienda establecer una identidad en Git, para ello se usan los comandos:

git config user.name
git config user.email

• Usando el flag “--global” podemos establecer la configuración de forma global y realizarla una sola vez.

git config --global user.name “devf”
git config --global user.email “devf@gmail.com”

git init -> Inicializamos repositorio

git clone (url) -> Clonar repositorio existente

git status -> Nos muestra un desglose los archivos agregados y modificados

git add (nombre archivo) -> Agregamos archivos al staging area

git commit -m “Comentario” -> Agregamos comentario sobre el cambio hecho

git push -> Enviamos cambios a repositorio remoto

git checkout -b (nombre) -> Salimos de la rama actual creando una nueva

git checkout (nombre) -> Salimos de la rama actual a una existente

git merge (rama) -> Unimos cambios de una rama

git pull -> Obtenemos cambios más recientes de la rama


## Flujo de git.

- crear repo

### Cuando ya tengo archivos

- git init
- git  git status
On branch master
Untracked files:
  (use "git add <file>..." to include in what will be committed)

	about.html
	contact.html
- git add .
- git status
On branch master
Changes to be committed:
  (use "git reset HEAD <file>..." to unstage)

	new file:   about.html
	new file:   contact.html

- git commit -m "primer versión de mi página de perfil"

Hasta aquí ya estaban los cambios en mi repo local

la primera vez 
- git push -u origin master

Ya estaban los cambios en mi repo remoto.

- git add .
- git commit -m 
- git push origin nombreDeLaRama

Crear nuevas ramas

- git checkout -b nombreRamaNueva

Entrar a rama que ya existía

- git checkout ramaExistente

Para unir ramas, hacemos un pull request
en la sección de github

https://github.com/nombreUsuario/nombreRepo/pulls



## Recursos extra

https://learngitbranching.js.org/?locale=es_AR

http://git-school.github.io/visualizing-git/

