# Curso de Docker

## 1. ¿Cuál de los siguientes no es uno de los grandes problemas del desarrollo de software profesional?
    Depurar

## 2. ¿Cuál es el principal problema que intenta resolver la virtualización?
    Desacoplar el entorno de ejecucción de la máquina real que ejecuta nuestras aplicaciones.

## 3. ¿En qué se parecen las máquinas virtuales y los contenedores?
    Son una unidad autocontenida preparada para ejecutar nuestras aplicacones correctamente.

## 4. ¿Cuál de las siguientes afirmaciones es falsa?
    Docker es una aplicación que ejecuta máquinas virtuales.

## 5. ¿Cuál de las siguientes afirmaciones es verdadera?
    Cuando hacemos docker run se crea y ejecuta un nuevo contenedor.

## 6. ¿Cual de las siguientes no es una caractarística de un contenedor?
    Siempre puede acceder al filesystem completo de la máquina anfitriona.

## 7. Indica el comando correcto para ver todos los contenedores por el docker daemon.
    docker ps -a

## 8. ¿Cuál es el comando correcto para correr un contenedor de Ubuntu en modo interactivo?
    docker run -it ubuntu

## 9. ¿Cuál es la causa para que un contenedor se detenga?
    El proceso principal termina su ejecución.

## 10. ¿Qué ocurre si en la terminal escribes dicker run -p 8080:80 nginx?
    Se crea y ejecuta un contenedor que corre nginx, vinculando el puerto 8080 de la máquina anfitriona al puerto 80 del contenedor.

## 11. Indica qué afirmación es verdadera luego de ejecutar docker run -v /home/data:/files mongo
    Los cambios que hagamos en /home/data en la máquina anfitriona se verán reflejados en /files dentro del contenedor de mongo, y viceversa.

## 12. Indica la principal diferencia entre un volume mount y un bind mount.
    El sistema de archivos de la máquina anfitriona donde se escriben los datos de un volume mount manejado enteramente por Docker.

## 13. ¿Cuál es el comando correcto para copiar un archivo "file.txt" desde tu directorio actual al directorio "/home" del contenedor "prueba" basado en Ubuntu?
    docker cp file.txt prueba:/home

## 14. ¿Cuál de las siguientes afirmaciones es falsa?
    Una imagen de Docker es un contenedor con procesos configurados para ejecutarse de forma independiente.

## 15. ¿Cuál es el comando indicado para construir una imagen llamada "mi/imagen" a partir de un Dockerfile llamado "mi.Dockerfile" utilizando el directorio actual como contexto de build?
    docker build -t mi/imagen -f mi.Dockerfile

## 16. ¿Cuál de las siguientes afirmaciones es verdadera?
    

## 17. Cuando construimos una imagen, la cantidad total de sus capas es...
    La cantidad de capas de la imagen base y la cantidad de instrucciones en el Dockerfile.

## 18. Para construir una imagen que contenga código presente en el disco de la máquina anfitriona es necesario, en el Dockerfile, usar la instrucción...
    COPY

## 19. ¿Cuál de las siguientes afirmaciones es verdadera?
    El caché de build es afectado por tanto el orden de las instrucciones en el Dockerfile como también por los archivos que son utilizados o generados en cada instrucción del mismo.
    
## 20. Para que un contenedor A pueda comunicarse con un contenedor B es necesario que...
    Ambos estén conectados a la misma red.
    
## 21. ¿Cuál de las siguientes afirmaciones es verdadera?
    

## 22. ¿Qué comando debe ejecutarse para ver, a medida que se generan, únicamente los logs del servicio "app" de un compose file con 3 servicios?
    docker-compose logs -f app

## 23. ¿Cuál es el efecto de usar el comando docker-compose build?
    Construye imágenes solo para aquellos servicios que especifican el atributo build.

## 24. ¿Cuál es el principal objetivo de un archivo docker-compose.override.yml?
    Permitir modificar la configuración de un ambiente de docker-compose sin necesidad de alterar el compose file original.

## 25. ¿Cuál de los siguientes comandos no es válido?
    docker daemon prune

## 26. ¿Cuál es la principal diferencia entre SHELL y EXEC form en el CMD de un Dockerfile?
    Al usar SHELL, el proceso principal del contenedor es un shell y el que nosotros escribimos en CMD es un proceso hijo del mismo.

## 27. Dado un contenedor creado a partir de una imagen con ENTRYPOINT y CMD, ¿Cuál de las siguientes afirmaciones es verdadera?
    El proceso principal es el definido en ENTRYPOINT y sus parámetros son los definidos en CMD.

## 28. ¿Cuál de las siguientes afirmaciones sobre el contrxto de build es falsa?
    Siempre tiene acceso al sistema de archivos completo de la máquina anfitriona.

## 29. ¿Cuántas imágenes son generadas a partir de un Dockerfile con múltiples etapas?
    Solo una, la definida por la última etapa del Dockerfile
    
## 30. Dado un contenedor que tenga montado (mounted) el socket y el cliente de Docker de la máquina anfitriona, ¿qué sucedería si ejecuto comandos de Docker en la Shell del contenedor?
    Crea contenedores, imágenes, etc. en la máquina anfitriona.
    

