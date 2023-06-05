# Cheatsheet de Comandos Git

# Luis Miguel Vasquez Alvarez

A continuación se muestra una lista de los comandos Git más utilizados hasta el momento, junto con una explicación de su sintaxis y funcionalidad.

## Comandos para crear y configurar repositorios

git init # Crea un nuevo repositorio local Git.
git clone [url] # Crea una copia local de un repositorio remoto.
git fetch [remote-name] # Descarga todos los objetos y referencias de un repositorio remoto.

## Comandos para trabajar con ramas

git branch [branch-name] # Crea una nueva rama.
git branch -a # Lista todas las ramas locales y remotas en el repositorio actual.
git checkout [branch] # Cambia a una rama existente y actualiza el directorio de trabajo.
git checkout -b [branch] # Crea una nueva rama y cambia a ella.

## Flujo de trabajo común [Local] (init, add, commit)

git add # Agrega los cambios realizados en archivos al área de preparación (Staging Area).
git commit # Crea un nuevo commit con los cambios agregados al área de preparación.
git commit -m "Mensaje del commit" # Crea un nuevo commit con un mensaje descriptivo.
git commit --amend -m "Nuevo mensaje del commit" # Cambia el mensaje del último commit.
git commit -am "Mensaje" # Agrega y crea un nuevo commit con los archivos modificados.

## Flujo de trabajo común [Remoto]

git pull # Descarga los cambios del repositorio remoto y los fusiona con la rama actual.
git push # Envía los commits locales al repositorio remoto.
git fetch # Trae las actualizaciones del repositorio remoto y las guarda en el repositorio local.
git merge # Combina los cambios del repositorio remoto con el directorio de trabajo local.

## Otros comandos útiles

git status # Muestra el estado de los archivos y carpetas del repositorio.
git show # Muestra los cambios históricos realizados.
git log # Muestra el historial de commits.
git config # Configura opciones de Git, como el nombre de usuario y correo electrónico.
git tag # Crea y maneja etiquetas para marcar puntos específicos en la historia del repositorio.
git checkout # Cambia entre ramas o versiones anteriores de archivos.
git merge # Combina ramas o commits en el historial del repositorio.
git remote # Administra conexiones con repositorios remotos.
git grep # Busca texto dentro de los archivos del proyecto.
git clean # Elimina archivos no rastreados y no deseados del directorio de trabajo.

Recuerda consultar la documentación oficial de Git para obtener más detalles sobre cada comando y sus opciones.
