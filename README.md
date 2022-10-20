# ComandosGit
Desde los comandos básicos de git hasta comandos de cómo colaborar en equipo.

> Tomar notas en mardown [Guia](https://colab.research.google.com/notebooks/markdown_guide.ipynb#scrollTo=Lhfnlq1Surtk)

## Inicializar un repositorio

`git init`

## Añadir un cambio al repositorio
`git add <namedelarchivo>`<br><br>
>Si se desean agragar todos los cambios<br>`git add .`

## Hacer una confirmación de cambio
`git commit -m "comentario de cambio realizado"`

## Configurar el autor y gmail del repositirio
`git config --global user.email "correodeGitGub"`<br> `git config --global usar.name "nombredeGitHUb"`
## Configurar el repositirio remoto 
1. Ver los link remotos de `fetch` y `push`
   `git remote -v`
   *ejemplo modo remoto **ssh***
   ![](ejemplo_remote_ssh.png)<br>
   *ejemplo modo remoto **https***
   ![](ejemplo_remote_https.png)
2. Agregar el repositirio remoto 
   `git remote -add origin "link_https"`
## Subir cambios al repositorio
<br>

`git push origin "name_de_rama"`

## Actualizar el repositorio con los cambios nuevos o nomas por que sí
<br>

`git pull origin "name_de_rama"`




Saludos Angel!!...

