En este archivo incluiremos las diferencias que hemos encontrado sobre GIT y SVN.
<<<<<<< HEAD
Pablo Jose Cerero Mateos

Subversion (SVN) es un sistema centralizado y Git es un sistema distribuido, ese es la gran diferencia.

En Git utilizar ramas es muy común y fácil, mientras que en SVN es algo mas complicado y no habitual.
=======
-----------------------------------------------------------------------------------------------------------
Pablo Jose Cerero Mateos

 Subversion (SVN) es un sistema centralizado y Git es un sistema distribuido, ese es la gran diferencia.
 
 En Git utilizar ramas es muy común y fácil, mientras que en SVN es algo mas complicado y no habitual.
 
------------------------------------------------------------------------------------------------------------

>>>>>>> 6a3b28d9b9d59a5b6d39b4bc07a8ac427d0f7a4d

Enrique Rapela Castej�n

En SVN solamente nos permite tener un �nico repositorio, en Git tenemos repositorios distribuidos, por lo cual es m�s dificil en Git saber donde est�n los archivos ubicados.

En los comandos git en sencillez est� muy por delante, dado que para crear un repositorio en SVN tendriamos que poner estas lineas de comandos:

<<<<<<< HEAD
svnadmin create /ruta/del/repositorio svn import /ruta/del/repositorio "http://ejemplo.com/svn" -m "Iniciando repositorio"

Y en Git es mucho m�s f�cil e intuitivo: Primero nos vamos al directorio donde vamos a crear el repositorio.

git init

O para a�adir un repositorio que tenemos en Git Hub: Nos vamos al directorio:

git clone http:/github.com/repositorioPruebas

José Antonio Reina Montes En SVN los cambios realizados no se pueden fusionar entre sí, además se pueden registrar directorios vacíos, renombrados y mudados de sitio sin pérdidas de su historia. En Git los cambios se transfieren rápidamente al repositorio central,además registra los contenidos de los directorios, por eso los vacíos se eliminan automáticamente.

Adrian Haba: 
1- En SVN los ficheros se encuentran alojados en un repositorio central, y en GIT cada uno es su propio servidor.
2- En GIT un commit no es m�s que una secuencia de cambios aplicados sobre una versi�n anterior, una fecha, un autor y un identificador, y en SVN son ficheros completos que luego se comparan para ver diferencias
=======
svnadmin create /ruta/del/repositorio
svn import /ruta/del/repositorio "http://ejemplo.com/svn" -m "Iniciando repositorio"

Y en Git es mucho m�s f�cil e intuitivo:
Primero nos vamos al directorio donde vamos a crear el repositorio.

git init

O para a�adir un repositorio que tenemos en Git Hub:
Nos vamos al directorio:

git clone http:/github.com/repositorioPruebas


--------------------------------------------------------------------------------------------------------------------------------

José Antonio Reina Montes 
En SVN los cambios realizados no se pueden fusionar entre sí, además se pueden registrar directorios vacíos, renombrados y mudados de sitio sin pérdidas de su historia. 
En Git  los cambios se transfieren rápidamente al repositorio central,además registra los contenidos de los directorios, por eso los vacíos se eliminan automáticamente.
>>>>>>> 6a3b28d9b9d59a5b6d39b4bc07a8ac427d0f7a4d
