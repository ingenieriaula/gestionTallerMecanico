## Trabajo de Gestión de calidad de software
sistema de gestion de talleres mecanicos
####comandos git mas usados
### iniciar repositorio
~~~
git init
~~~
### clonar repositorio
~~~
git clone https://github.com/ingenieriaula/gestionTallerMecanico.git
~~~
### ver información de status
~~~
git status
~~~
### agregar documentos no guardados 
~~~
git add .
~~~
### crear un commit (captura de pantalla)
~~~
git commit -m "mensaje del commit"
~~~
### enviar commit al repositorio en github
~~~
git push origin master
~~~
### descargar datos desde el repositorio de github
~~~
git pull origin master
~~~
### actualizar repositorio local desde el repositorio de github
~~~
git fetch origin master
~~~
***
### crear una rama nueva
~~~
git branch prueba
~~~
en "prueba" se debe de indicar el nombre de la rama que queramos crear
### cambiar de rama de trabajo
~~~
git checkout pruebas
~~~
### subir nueva rama a repositorio de github
~~~
git push origin pruebas
~~~
### eliminar una rama del repositorio local
~~~
git branch -d pruebas
~~~
