#### Trabajando como un pro 

## Setup the tools
* Lo primero que debes hacer es instalar Anaconda -> https://docs.anaconda.com/anaconda/install/
1. Recuerda agregar las variables de entorno de anaconda al path -> en el buscador del equipo abres el anaconda prompt y pones "where conda"
si instalaste anaconda correctamente, entonces saldran 3 rutas. Deberás agregar estas rutas al path buscando en el buscador del equipo "Variables de entorno de esta cuenta"
y agregas las 3 rutas dentro de la variable path. Para que esto tenga efecto hay que reiniciar el computador.
* VS -> https://code.visualstudio.com/download
2. Recuerda instalar el tool de python para que interprete correctamente el environment. Esto lo puedes hacer buscando en el panel izquierdo de VS opcion "Extensions" alli dentro escribes python y le das instalar.
3. Para cambiar la terminal y que esta se ejecute con el cmd en vez del power shell dentro de VS ve a file, preferences, settings-> escribe terminal y busca el apartado terminal>integrated>defaultprofile -> Cambia power shell por cmd.
* git bash -> https://git-scm.com/downloads (Este aplicativo te permitira interactuar con github en tu computador local)
4. Clonar el repositorio de la clase, para ello crearás una carpeta en tu escritorio que se llame github y alli dentro harás clic derecho "open git bash here" y en la ventana
que salga tienes que escribir "git clone ruta_al_Repo_clase" es el repo que esta en el email que te pasamos ej: git clone https://github.com/mateocivil10/pj_sa_202601
5. Ahora dentro de VS debes ir a file, open folder y seleccionar la carpeta del repo que te acabas de clonar.

## Install environment :rocket:
----------------------
6. Ahora deberás instalar los paquetes que necesitaras para trabajar a lo largo del curso, haciendo lo siguiente:
* conda env create -p .\venv -f .\bin\local\environment.yml :relaxed: 
* Para activar el environment indefinidamente -> ctrl+shift+p ->"Terminal: Select Default Profile" o bien vas a la carpeta venv que se creo (La cual contiene todo los paquetes)
y escribes en la terminal conda activate "ruta a venv" 

## Github: Algunos comandos clave para trabajar con github
----------------------
* git checkout name_rama_interes_remoto **Cambia de rama en el repo local**
* git merge name_rama_remoto  **Fusiona la rama remota con la rama local actual**
* git push origin name_rama_actual_local:name_rama_remota **Hace push de la rama local a la rama remota**
* git add file_name **Agregar un fichero específico antes de un commit**
* git add . **Agrega todos los cambios ante de un commit**
* git commit -m "Mensaje descriptivo del commit" **Crea un commit con ese mensaje**
* git fetch origin **Actualiza el repositorio local, pero no actualiza los ficheros automaticamente**
* git pull origin name_rama_remota **Actualiza inmediatamente el repo local con la rama especificada**

*** Importante, recuerda moverte a tu rama de github (Previamente en el primer bullet point explicamos como hacerlo), y cualquier cambio, proyecto 
entrega debes subirlo allí, haciendo git add . , seguido de git commit -m "Mensaje descriptivo del commit", y finalmente envias al repositorio web con git push origin name_rama_actual_local:name_rama_remota

**Gestión de issues y pull request:**

1. Generar un issue en la página web de github
2. Trabajar los cambios sobre la rama que gestionará el issue
3. Agregar los ficheros modificados con el comando git add
4. Hacer commit pero es muy importante incluir en el comentario el número del issue EX: "Resuleve #10" si el issue es el 10
5. Hacer push sobre tu rama (la rama encargada del issue)
6. Crear la pull request (base: Main) (compare : rama encargada del issue)
7. El revisor se encargará de validar que los cambios propuestos estan ok y entonces aceptará cambio y guardara la pull request.

Si tienes dudas pregunta a chatgpt, te ayudara seguro :)

#### Trabajando como la mayoria

Si bien la mayoria de los proyectos profesionales actualmente se gestionan de la forma que te explicamos previamente, bien puedes hacer uso de google colab y subir los notebooks al repo tal cual lo vayamos sugiriendo, es más sencillo, pero no tan profesional, igualmente podrás aprender los conceptos del curso y no hay implicación alguna en la nota asignada.

## Developers
----------------------
The developers responsible for the development and maintaining of this project.

* **Julian Mateo Caro** - *Author/Maintainer* - [mateocivil10@gmail.com]

C:\Users\Z079355\Allianz\Pricing Varios - Z079355\workspace_github\tch-prc-mlops-comunidades

venv\Scripts\activate

C:\github\pj_sa_202601

