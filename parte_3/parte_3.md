1. Analiza
git status : Nos muestra el estado en el que se encuentran nuestros archivos antes de hacer un commit
git add README.md : Sube el archivo para que se pueda hacer un commit
git commit -m "Actualiza documentación" : Crea un commit a nuestro  git
git push Sube el commit a la nube en GitHub 

Explica qué ocurre en cada instrucción.


2. Identifica qué falta

Caso A
Modificar archivo
↓
git add .
↓
¿?
↓
git push

Indica qué operación falta y explica su función.

Falta el git commit : que nos permite subir un commit a nuestro repositorio.


Caso B
Repositorio GitHub
↓
¿?
↓
Repositorio local

Indica qué operación utilizarías y explica por qué.

git clone nos permite tener un repositorio que se le iso un fork en nuestra cuenta para asi poder tenerlo en local.

Caso C
Repositorio remoto actualizado
↓
¿?
↓
Repositorio local actualizado

Indica qué operación utilizarías y explica por qué.

git pull lo que hace es actualisar nuestro repositorio local con la nueva informacion que se le alla agregado al proyecto.