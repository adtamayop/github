git init 

git status

git add nombre_archivo

git add -A   (agrega todo los archivos)

git commit -m "mensaje del commit"

git log      (ver los commit)

git checkout codigo_largo_del_commit  (para poder cambiar )

git checkout master (nos mueve al último commit que tenemos)

git help

git help nombre_comando

head es el commit donde nos econtramos en este momento (actualmente)

git branch (muestra las ramas)

git branch nombre_rama    (crea la rama)

git branch -d nombre rama (borrar la rama)


para hacer un merge, me paro en la rama con la que voy a fusionar por ejm la master

git merge nombre_rama



Para clonar un proyecto, entonces voy al directorio y le doy

git clone link_github

los repositorios remotos son los que están en github y los locales son los que están en mi pc

git remote --> vincula nuestro proyecto local, con nuestro git remoto

entonces 

git remote add origin https://github.com/adtamayop/Repaso-Parcial-Dise-o-.git (vincula el proyecto con github)

git remote -v  (comprobar)

git remote remove origin (desvincula)

git push origin nombre_rama_a_pasar