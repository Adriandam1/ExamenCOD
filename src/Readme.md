# Tienes la responsabilidad de realizar la release v1.0 de un proyecto.
La URL del proyecto es: https://github.com/damiancastelao/ExamenCOD
## [] Para trabajar en él tendrás, antes de nada, que hacer un fork
Voy a la URL y le doi a fork para forkear creando mi repositorio

## [] En una rama diferente llamada readme, crea un Readme.md vas a ir anotando los pasos que vayas dando, comandos y la justificación de las desiciones
git branch readme

## [] Debes juntar todo el código en la main (menos la rama readme).
git checkout datos
git pull origin datos
git checkout interface
git pull origin interface

## [] hacer un undo del ultimo commit de interface
en el menu intelliG voy a la rama interface clico el ultimo commit y le doi a undo y añado un comentario explicandolo


## [] Realizas la fusión (merge)
Nos situamos en la rama main y:
click derecho en datos "merge datos into main"
click derecho en interface "merge interface into main"

## [] Una vez finalizada la fusión etiqueta el último commit con v1.0 para poder hacer el push y la release
git tag -a v1.0 -m 'my version 1.0'
uso git tag y compruebo que me sale la v1.0 correctamente

## [] Pero vaya!!! te das cuenta sorprendido que el gitignore no está incluido y está incompleto. Entonces lo completas y lo añades al commit etiquetado con v1.0.
hago un gitadd .gitignore
hago el commit ya con la interfaz grafica
en la propia intergaz uso el amend para incluir el archivo al ultimo commit

## []Ahora si ya puedes hacer el push y crear la release.
edito el readme para mostrar esto y hago el push









