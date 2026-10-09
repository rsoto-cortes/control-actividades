1. Flujo colaborativo
Supón que quieres colaborar con el repositorio de otro desarrollador. Ordena y explica los siguientes elementos:
Push, Fork, Pull Request, Clone, Merge, Commit, Review, Branch y Modificar archivos. Agrega cualquier
operación que consideres necesaria.

    1-Fork: Este se utiliza para poder hacer una copia de un proyecto en nuestra cuenta.
    2-Clone: ESte se pone en la terminal con la direccion URL que nos da la copia del repositorio que esta en nuestra cuenta. Esta nos permite poder tener el poryecto en local en nuestra maquina.
    3-Modificar archivos: Aqui se editan o agregan archivos al proyecto como parte de nuestra colaboracion con el proyecto.
    4-Commit: Aqui se suben los archivo que se editaron o que se desean agregar al repositorio (aun no se sube a GitHub).
    5-Branch: SE crea una nueva rama en la terminal con el comando git switch -c "nombre de la rama" en el proyecto para evitar causar algun problema en el proyecto asi si ocurre algun error aun se tiene el proyecto de la rama principal.
    6-Push: Aqui ya se suben todos los archivos nuevos y ediciones que se se realizaron en el proyecto a Github en una rama que se creo anteriormente.
    7-Pull request: en esta parte es como si le preguntaramos al autor del proyecto que si las cosas que agregamos o editamos estan bien o si necesitan algun cambio.
    8-Review: Aqui el autor del proyecto checa el pull request para ver si las cosas que se realizaron por parte de un colaborador estan bien o si necesitan hacer cambios
    9-Merge: Aqui ya se aceptaron los cambios que realizo el colaborador por lo que se procede a juntar los cambios con el proyecto original



2. Fork y Clone
Analiza la afirmación: “Clone crea una copia del proyecto dentro de mi cuenta de GitHub”. Indica si es correcta
y explica la diferencia entre Fork y Clone.

    Si es correcta, la diferencia es que el fork solo crea una copia en la nube y el clone necita del fork para poder obtener el URL para asi poder tener el proyecto en local 

3. Pull Request
Supón que realizaste Fork, Clone, Branch, Modificar, Commit y Push. Responde: ¿los cambios ya forman parte
del repositorio original? ¿Qué debe ocurrir para incorporarlos?

    Se primero se sincronisan los dos repositorios y luego se utiliza un "git pull" en la terminal para que asi la copia del proyecto que tenemos se actualise con los cambios que se realizaron en el archivo principal 

4. Request Changes
El propietario revisa tu Pull Request y selecciona Request Changes. Explica qué debes hacer, si necesitas crear
otro Pull Request y qué ocurre cuando realizas nuevamente push.

    Se tienen que realizar cambios en el codigo que subimos y luego se debe de crear otro pull request.

5. Merge y repositorio local
Un Pull Request fue aceptado y se realizó Merge en GitHub. Sin embargo, el repositorio local del propietario no
contiene los cambios. Explica por qué sucede y qué operación debe realizarse.

    Esto sucede porque su proyecto que tiene en local aun no se actualisa con la nueva rama que se creo por lo que debe de poner un git pull en la terminal para que este reciba la nueva informacion que se agrego en el proyecto que esta en la nube.

6. Sync Fork
Tu Fork fue creado varios días atrás y el repositorio original recibió nuevos commits. Explica qué herramienta
utilizarías, qué repositorio se actualiza y qué diferencia existe entre Sync Fork y git pull.
Registra este cambio en un cuarto commit con un mensaje descriptivo y súbelo a github.

    primero se debe de utilizar un sync fork para que asi el fork que nosotros tenemos se sincronise con el original luego se debe de poner un git pull en la terminal paraque asi se actualise nuestro proyecto con toda la nueva informacion que se incorporo en el proyecto.