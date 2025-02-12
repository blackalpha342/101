¿Qué hacen los siguientes comandos?

pwd : Muestra la ruta del directorio en el que se encuentra el usuario.
ls : Muestra la lista de archivos y directorios en la ubicación actual dentro del directorio. 
cd: Cambia a un directorio especificado.
mkdir: Se encarga de crear un nuevo directorio
touch: Actualiza la marca de tiempo de un archivo existente o crea uno vacío.
cd projects

Cambia al directorio projects. (Debe existir previamente, si no, dará error).
mkdir new-project

Crea un directorio llamado new-project dentro de projects.
touch new-project/newfile.md

Crea un archivo vacío llamado newfile.md dentro de new-project.
cd ..

Regresa al directorio padre de projects.
ls projects/new-project

Lista los archivos dentro de projects/new-project.
Como ya creamos newfile.md, este será mostrado en la terminal.
Lista los archivos dentro de new-project. Aquí verás newfile.md.
ls projects/new-project:
¿Qué comando usarías en la terminal para listar todos los archivos, incluidos los archivos ocultos, en un directorio de Linux o macOS? Explica qué significan los parámetros utilizados en el comando.

-l → Muestra los archivos en formato detallado (permisos, propietario, tamaño, fecha de modificación).
-a → Muestra todos los archivos, incluidos los ocultos (los archivos ocultos comienzan con . en Unix).

ls -la
