# Curso de Introducción a la Terminal y Línea de Comandos

1. La shell o línea de comandos es:

   Un programa que nos ayuda a comunicarnos con nuestro sistema operativo.

2. ¿Qué hace el comando pwd?

   Imprime la ruta del directorio actual de trabajo.

3. Para crear un archivo usamos el comando:

   ```console
   touch mi_archivo
   ```

4. ¿Con cuál comando copiamos un directorio y su contenido? (Esto hace parte de uno de los retos que te dejé)

   ```console
   cp -r mi_directorio ruta_destino
   ```

5. Para leer el manual de usuario de un comando usamos:

   ```console
   man
   ```

6. Las wildcards son caracteres que nos permiten definir patrones avanzados de búsqueda en la línea de comandos, esto es:
   Verdadero

7. Si queremos listar todos los archivos que sean extensión txt podemos usar el comando:

   ```console
   ls *.txt
   ```

8. El file descriptor correspondiente al stderr es:

   2

9. ¿Qué operador nos ayuda a concatenar la salida de un comando a un archivo de texto?

   ```console
   >>
   ```

10. El pipe operator redirecciona la salida de un comando a la entrada de otro comando, esto es:

    Verdadero

11. Si queremos explorar las primeras 100 líneas de un documento de texto lo podemos hacer con:

    ```console
    head -n 100 mi_texto | less
    ```

12. Si queremos correr una serie de comandos de manera asíncrona lo hacemos con el operador:

    ```console
    &
    ```

13. El comando `chmod u=rwx,go=r mi_archivo` ¿qué permisos otorga?

    Otorga permisos de lectura, escritura y ejecución al usuario. Solo otorga permiso de lectura a los grupos y a otros.

14. Es una mala práctica de seguridad asignar la siguiente configuración de permisos en modo octal a cualquier archivo o directorio.

    ```console
    777
    ```

15. Para guardar todas nuestras variables de entorno en un archivo de texto podemos ejecutar el comando:

    ```console
    env > environment.txt
    ```

16. Es un comando que nos ayuda a buscar la ruta de binarios o ejecutables en nuestro sistema.

    ```console
    which
    ```

17. Para buscar todas las imágenes png dentro de nuestra computadora podemos ejecutar:

    ```console
    find / -name *.png
    ```

18. Para usar grep sin distinción de mayúsculas o minúsculas usamos:

    ```console
    -i
    ```

19. ¿Qué comando nos ayuda consultar la disponibilidad de un equipo en una red?

    ```console
    ping
    ```

20. ¿Qué comando muestra los procesos que consumen más recursos en nuestro sistema?

    ```console
    top
    ```
