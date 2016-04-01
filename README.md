# gitutils
Comandos y opciones de git de uso común
# Los comandos a continuación se puede usar para crear un repositorio local y vincularlo a uno remoto y subir esos cambios a una nueva rama del repositorio remoto.
#Inicializar el repositorio
git init
#Vincular repositorio local con remoto "se usa la url del repositorio a vincular"
git remote add origin https://chuckcruz@github.com/hubcodice/postensa.git
# agregar una nueva rama simbolica
# git symbolic-ref HEAD refs/heads/<rama_creada_por_referencia_simbolica>
git symbolic-ref HEAD refs/heads/postensa2_
#Agregar todos los archivos en el repositorio local
git add .
git status
#Borrar algún archivo de la lista de archivos por hacer commit
git rm --cached sitio_postensa_050215.zip
git status
git rm --cached error_log
git commit -m "Archivos de proyectosphp/postensa3 a git master"
#Hacer el push al repositorio Origen (Remoto) "master" seria la nueva rama que queremos crear al hacer el push
#git push -u origin <rama_creada_por_referencia_simbolica>
git push -u origin postensa2_

#comandos completos
git init
<br>
git remote add origin https://chuckcruz@github.com/hubcodice/postensa.git
<br>
git symbolic-ref HEAD refs/heads/postensa2_
<br>
git add .
<br>
git status
<br>
git rm --cached sitio_postensa_050215.zip
<br>
git status
<br>
git rm --cached error_log
<br>
git commit -m "Archivos de proyectosphp/postensa3 a git rama nueva"
<br>
git push -u origin postensa2_

#cambio nuevo
