# manual-trabajo

_Comandos_ 


  Dentro de los comandos visto de Git son:  
CD "nombrerepositorio": Para ingresar de manera remota a repositorios de Git es necesario este comando. Esto elaborado desde el CMD.

Git status: Usado para ver cambios hechos que no han sido implementados, nos nombrará el estado general de fichero correspondiente. A su vez, nos mostrará que archivos han sido modificados y no han sido implementados. 

Commit: Para aplicar los cambios hechos para el Git local, el cual procederá abrir los archivos en el editor predeterminado; una vez que queramos aplicar cambios se nos pedirá proporcionar "nombre" al cambio y opcionalmente agregar "descrpción", esto si no deseamos hacerlo desde la consola.
Los cambios en la consola se ejecutan con "git commit README.md -m "nombre para los cambios"" (Guion m "-m" usado para agregar mensaje.) Lo que ejecutará dentro de la consola el cambio predicho y cuantas fueron los cambios hechos(Insersiones.)
 
git init: este se encarga de crear un .git dentro de la rama de trabajo actual. es la rama principal  
git clone: se usa para crear una copia o clonar un repositorio remoto.  
git add --all: con este comando se guardan todos los cambios a la rama principal. Utilizando la setencia "." puede agregar todos los ficheros necesarios para el repositorio. Si nosotros volvemos a introducicr "Git Status" podemos encontrar si los archivos fueron agregados de manera correcto, y/o cuales fueron agregados.   
git Config: Es capaz de agregar configuraciones predestinadas para inicio o cambios globales. 
git push: esta guarda una copia antes de realizar un cambio


_Pull request_

El pull request funciona como peticiones al repositorio original para otorgar cambios adversos al commit original. Son observados la englobación de todos los cambios al que se ha hecho originalmente, como un salvaguarda para no modificar directamente el original. 

![Pull request](https://raw.githubusercontent.com/Sof1aSinaloa/manual-trabajo/blob/main/Pullrequest.PNG)

_Issues_

Estan hechos a partir de querer mejorar fallas o caracteristicas dentro de algun archivo del repositorio. Los issues se prestan como solicitudes a modificaciones a diferentes tipos de doc., los equipos de desarrollo esta encargado de solucionar esos "Issues" nombrando a colaboradores que a partir de los pull request realizaran cambios solicitados o nombrados dentro de los "Issues" estos ayudaran como un filtro para tareas. 
Existen distintos tipos de Issues, pero una vez que ellos estan solucionados, o en ciertos casos, ese Issue puede proceder a ser cerrados. 


![Issues](https://raw.githubusercontent.com/Sof1aSinaloa/manual-trabajo/blob/main/Issues.PNG)


