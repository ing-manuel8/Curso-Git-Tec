1. Configuración Inicial

    Configurar el nombre de usuario:

        git config --global user.name "Tu Nombre"
        
    Configurar el correo electrónico:

        it config --global user.email "tuemail@ejemplo.com"

2. Crear y Clonar Repositorios

    Inicializar un repositorio nuevo:

        git init

3. Estado del Repositorio

    Verificar el estado actual del repositorio:

        it status

    Ver historial de commits:

        git log

4. Seguimiento de Archivos

    Agregar un archivo al área de preparación:

        git add <archivo>
    
    Agregar todos los archivos al área de preparación:

        git add .

    Hacer un commit con mensaje: 

        git commit -m "Descripción del cambio"

5. Modificaciones y Revisión

    Quitar un archivo del área de preparación:

        git restore --staged <archivo>

    Revertir cambios no confirmados en un archivo:

        git restore <archivo>

6. Volver a Commits Anteriores

    Volver temporalmente a un commit (estado "detached HEAD"):

        it checkout <id_commit>

    Volver permanentemente a un commit (soft reset):

        git reset --soft <id_commit>

    Eliminar cambios posteriores (hard reset):

        git reset --hard <id_commit>

7. Ramas

    Ver las ramas disponibles:

        git branch

    Crear una nueva rama:

        git branch <nombre_rama>

    Cambiar a otra rama:

        git checkout <nombre_rama>

    Crear una nueva rama y cambiar a ella:

        git checkout -b <nombre_rama>

    Fusionar una rama con la actual:

        git merge <nombre_rama>

    Eliminar una rama:

        git branch -d <nombre_rama>
  