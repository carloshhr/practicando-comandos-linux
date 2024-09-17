# Practicando Comandos Linux

Lista de comandos Linux y Estructura de Directorios para practicar

- ls:

    Este comando se utiliza para listar los archivos y directorios en un directorio específico. Cuando se ejecuta sin argumentos, muestra los archivos y directorios en el directorio actual. Se pueden usar diferentes opciones con este comando para cambiar su comportamiento, como mostrar detalles de los archivos (con -l), mostrar archivos ocultos (con -a), ordenar por tamaño (con -S), entre otros.

- cd:

    El comando cd se utiliza para cambiar el directorio actual. Se puede usar para navegar entre los directorios del sistema de archivos. Por ejemplo, cd directorio cambiará al directorio llamado "directorio". Si se utiliza sin argumentos, cd cambiará al directorio de inicio del usuario.

- clear:

    Este comando se utiliza para limpiar la pantalla de la terminal, eliminando todo el texto anterior. Es útil cuando se desea limpiar la pantalla para una mejor visualización o para ocultar información sensible.

- pwd:

   El comando pwd (Print Working Directory) muestra el directorio de trabajo actual, es decir, la ruta completa desde la raíz del sistema hasta el directorio actual en el que te encuentras. Es útil para saber en qué parte del sistema de archivos te encuentras en un momento dado.

- tree:

    El comando tree muestra de forma jerárquica la estructura de directorios y archivos a partir del directorio especificado. Es útil para visualizar la estructura de directorios de manera organizada y detallada.

- mkdir:

    Este comando se utiliza para crear nuevos directorios. Por ejemplo, mkdir directorio creará un directorio llamado "directorio" en el directorio actual.

- touch:

    touch se utiliza para crear nuevos archivos vacíos o actualizar las marcas de tiempo de los archivos existentes. Por ejemplo, touch archivo.txt creará un archivo llamado "archivo.txt" si no existe, o bien actualizará su marca de tiempo si ya existe.

- cp:

   El comando cp se utiliza para copiar archivos y directorios de un lugar a otro. Por ejemplo, cp archivo.txt /directorio/destino copiará el archivo "archivo.txt" al directorio "destino".

- mv:

   mv se utiliza para mover archivos y directorios de un lugar a otro o para cambiar su nombre. Por ejemplo, mv archivo.txt /directorio/destino moverá el archivo "archivo.txt" al directorio "destino".

- rm:

   Este comando se utiliza para eliminar archivos y directorios. Por ejemplo, rm archivo.txt eliminará el archivo "archivo.txt". Para eliminar directorios y su contenido de manera recursiva, se puede utilizar la opción -r (por ejemplo, rm -r directorio). Este comando debe ser utilizado con cuidado ya que puedes borrar archivos o directorios que son importantes.

- head:

   El comando head se utiliza para mostrar las primeras líneas de un archivo de texto. Por defecto, muestra las primeras 10 líneas, pero se puede especificar un número diferente de líneas utilizando la opción -n. Por ejemplo, head -n 5 archivo.txt mostrará las primeras 5 líneas del archivo "archivo.txt".

- tail:

   tail se utiliza para mostrar las últimas líneas de un archivo de texto. Por defecto, muestra las últimas 10 líneas, pero al igual que con head, se puede especificar un número diferente de líneas utilizando la opción -n. Por ejemplo, tail -n 3 archivo.txt mostrará las últimas 3 líneas del archivo "archivo.txt".

- less:

   El comando less se utiliza para visualizar el contenido de un archivo de texto de forma interactiva. A diferencia de head y tail, que solo muestran una parte específica del archivo, less permite desplazarse hacia arriba y hacia abajo por todo el contenido del archivo. Es especialmente útil para visualizar archivos largos. Se puede utilizar simplemente escribiendo less archivo.txt. Una vez dentro de less, se pueden usar las teclas de flecha, la barra espaciadora y otras teclas para navegar y buscar en el archivo.

### Ejercicios

1.  cd (Cambiar directorio):

    -   Navega al directorio `principal`.
    -   Navega hacia atras (directorio padre).
    -   Desde el directorio `espacio-de-trabajo` navega a otro-directorio
2.  pwd (Mostrar directorio actual):

    -   Muestra el directorio actual.
3.  ls (Listar contenido de directorio):
    -   Ir al directorio principal
    -   Lista todos los archivos y directorios en el directorio actual.
    -   Utiliza opciones para mostrar archivos ocultos.
    -   Lista solo archivos o solo directorios en el directorio actual.
4.  head (Mostrar las primeras líneas de un archivo):

    -   Ve al directorio `principal` y muestra las primeras 5 líneas del archivo `pruebas2.txt`.
5.  tail (Mostrar las últimas líneas de un archivo):
    -   Muestra las últimas 3 líneas del archivo `prueba2.txt`.

6.  tree (Mostrar estructura de directorios):

    -   Muestra la estructura de directorios a partir del directorio `espacio-de-trabajo`.
7.  mv (Mover archivos o directorios):

    -   Mueve el archivo `prueba3.txt` al directorio `/segundo-directorio`.
    -   Cambia el nombre del archivo `prueba3.txt` a `d.txt`.
    -   Utiliza opciones para mover múltiples archivos a la vez.
8.  cp (Copiar archivos o directorios):

    -   Copia el archivo `c.txt` al directorio `/backup`.
9.  touch (Crear archivos vacíos o actualizar tiempo de modificación):

    -  Ve al directorio `principal` y crea un archivo llamado `newfile.txt`.
    -  Actualiza el tiempo de modificación de `prueba.txt` (si existe).
