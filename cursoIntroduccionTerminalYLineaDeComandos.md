# Curso de Introducción a la Terminal y Línea de Comandos

## La shell o línea de comandos es:
    Un programa que nos ayuda a comunicarnos con nuestro sistema operativo.
## ¿Qué hace el comando pwd?
    Imprime la ruta del directorio actual de trabajo.
## Para crear un archivo usamos el comando:
    ```console
    touch mi_archivo
    ```
## ¿Con cuál comando copiamos un directorio y su contenido? (Esto hace parte de uno de los retos que te dejé)
    ```console
    cp -r mi_directorio ruta_destino
   ```
## Para leer el manual de usuario de un comando usamos:
    ```console
    man
    ```
## Las wildcards son caracteres que nos permiten definir patrones avanzados de búsqueda en la línea de comandos, esto es:
    Verdadero
## Si queremos listar todos los archivos que sean extensión txt podemos usar el comando:
    ```console
    ls *.txt
    ```
## El file descriptor correspondiente al stderr es:
    2
## ¿Qué operador nos ayuda a concatenar la salida de un comando a un archivo de texto?
    ```console
    >>
    ```
## El pipe operator redirecciona la salida de un comando a la entrada de otro comando, esto es:
    Verdadero
## Si queremos explorar las primeras 100 líneas de un documento de texto lo podemos hacer con:
    ```console
    head -n 100 mi_texto | less
    ```
## Si queremos correr una serie de comandos de manera asíncrona lo hacemos con el operador:
    ```console
    &
    ```
## El comando `chmod u=rwx,go=r mi_archivo` ¿qué permisos otorga?
    Otorga permisos de lectura, escritura y ejecución al usuario. Solo otorga permiso de lectura a los grupos y a otros.
## Es una mala práctica de seguridad asignar la siguiente configuración de permisos en modo octal a cualquier archivo o directorio.
    ```console
    777
    ```
## Para guardar todas nuestras variables de entorno en un archivo de texto podemos ejecutar el comando:
    ```console
    env > environment.txt
    ```
## Es un comando que nos ayuda a buscar la ruta de binarios o ejecutables en nuestro sistema.
    ```console
    which
    ```
## Para buscar todas las imágenes png dentro de nuestra computadora podemos ejecutar:
    ```console
    find / -name *.png
    ```
## Para usar grep sin distinción de mayúsculas o minúsculas usamos:
    ```console
    -i
    ```
## ¿Qué comando nos ayuda consultar la disponibilidad de un equipo en una red?
    ```console
    ping
    ```
## ¿Qué comando muestra los procesos que consumen más recursos en nuestro sistema?
    ```console
    top
    ```