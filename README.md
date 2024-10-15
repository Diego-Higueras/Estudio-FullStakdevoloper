# Introduccion a Git y GitHub

## Comandos Basicos

-"cd" : Navega al directorio principal
-"cd ruta" : Navega al directorio indicado
-"cd .." : Vuelve un directorio atrás

-"ls" : Lisda todas las carpetas o archivos en el directorio
-"ls -a": Lista todas las carpetas o archivos al directorio incluyendo los archivos ocultos

-"pwd" : Muestra la ruta completa del directorio

-"mkdir nombrecarpeta" : Crea una nueva carpeta

-"touch nombreArchivo" : Crea un nuevo archivo

> Tiene que incluir siempre el tipo de archivo, por ejemplo ,css, .html, .md

## Configurar Git por primera vez

1. Configurar nombre de usuario de GitHub

```Bash
git config --global user.name "Diego-Higueras"
```
2. Configurar tu correo electronico

```Bash
git config --global user.email "diego.lucianobonnassiolle@gmail.com"
```
Para verificar que todo este correcto:

-`Git config --list`

> Ete comando devuelve una lista de configuracion de usuario

`Git config user.name`

> Este comando verifica su nombre de usuario

## Inicializar un nuevo Proyecto con comandos que da GitHub

```
bash
echo "#DesafioLata_G87" >> README.md
```
`git init`
`git add README.md`
`git commit -m "first commit"`
`it branch -M main`
`git remote add origin https://github.com/Diego-Higueras`
`git push -u origin main`

> ↑↑↑ Serie de comando que da github a la hora de crear un nuevo repositorio

1. `echo "#Desafiolatam_G87"` >> README-md (opcioal)

- Crea un archivo README.md con el contenido dek titulo indicado

2. `git init` (se usa **una sola vez, _obligatorio**)

- inicializa un nuevo repositorio de Git en el directorio actual

3. `git add README.md o Git add` .(se va a utilizar en mas de 1 ocacion)

4. `git commit -m "first commit"` (se va a utilizar en mas de 1 ocacion)

- Registra todos los comentarios que se agregaron en el comndo anterior "first commit". Lo que esta entre comillas
va a variar depenndiendo del cambio relizado

5. `git branch -M main` (se usa **una sola vez, _obligatorio**)

- Crea y cambia a la rama "main", que sera la rama principal

6. `git remote add origin` https://github.com/Diego-Higueras (se usa **una sola vez, _obligatorio**)

- Enlaza su repositorio local con el repositorio remoto de GitHub

7. `git push -u origin main` (se va a utilizar en mas de 1 ocacion sin el "-u")

- Sube todos los cambios realizados y registras al repositorio remoto

## Inicializar un nuevo repositorio

1. `git init` (se usa **una sola vez, _obligatorio**)

2. `git branch -M main` (se usa **una sola vez, _obligatorio**)

3. `git remote add origin` https://github.com/Diego-Higueras (se usa **una sola vez, _obligatorio**)

## Guardar cambios y subirlos al repositorio

Cada vez que realicesun cambio importante en tu proyecto se realizan los siguientes cambios

1. `git add`. `# Estudio-FullStakdevoloper
# Estudio-FullStakdevoloper
