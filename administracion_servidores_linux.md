# Curso de Administración de Servidores Linux

## 1. ¿Cuál es la distribución más utilizada de Linux en servidores según w3techs?
    Ubuntu Server

## 2. ¿Cuáles proveedores de nube me permiten lanzar instancias de Ubuntu server y CentOS como base?
    Todas las mencionadas

## 3. ¿Cuánto tiempo de soporte tengo con las versiones LTS de Ubuntu?
    5 años

## 4. ¿Por qué debe elegir versiones LTS en Ubuntu?
    Mayor tiempo de soporte en actualizaciones de seguridad y en software

## 5. ¿Cuál es el mecanismo recomentado para validar la integridas de la imagen ISO descargada?
    sha256

## 6. ¿Cuántos tipos de descargas puedo hacer desde la página de CentOS? ¿Cuáles son?
    2: DVD y Minimal

## 7. Comando utilizado para concatenar y leer archivos:
    cat

## 8. Comando para listar los archivos en formato largo, por orden de modificación y en orden reverso:
    ls -ltr

## 9. Número de líneas por defecto que leemos con head y tail en un archivo:
    10

## 10. Modificador del comando tail que me permite hacer seguimiento del archivo en tiempo real:
    -f

## 11. Como mínimo se requiere una partición para:
    /

## 12. ¿Qué comando debo utilizar para usar comandos que requieren privilegios de root?
    sudo

## 13. Archivo que contiene los usuarios del sistema:
    /etc/passwd

## 14. ¿Qué comando debo ejecutar para usar el usuario nodejs?
    su - nodejs

## 15. ¿Cuál es el grupo en Linux que tiene permisos de administrador?
    sudo

## 16. Comando que permite cambiar los permisos de un archivo:
    chmod

## 17. Sistema numérico utilizado para cambiar permisos de forma numperica en Linux:
    octal

## 18. Si un archivo tiene el valor de permisos 400 quiere decir que:
    Solo el usuario propietario puede leer el archivo.

## 19. Para poder ejecutar un script en bash, necesitamos el permiso de:
    Ejecución para el usuario que lo quiere correr.
    
## 20. Qué comando se puede utilizar para mostrar la información de conexión de red actual (Dirección IP y MAC) en Ubuntu y CentOS sin instalar paquetes adicionales?
    ip a
    
## 21. ¿Cuál es el protocolo que me permite conectar a otras máquinas Linux de forma segura y ejecutar comandos en un servidor remoto?
    ssh
    
## 22. ¿Con qué comando puedo ver los paquetes instalados en una máquina Ubuntu?
    dpkg -l

## 23. ¿Dónde se encuentra almacenada la base de datos de rpm?
    /var/lib/rpm

## 24. ¿Qué comando me permite ver los procesos corriendo en el servidor?
    ps

## 25. ¿Qué comando me muestra la lista de procesos en background?
    jobs

## 26. ¿Cuál es el comando que me permite editar el archivo crontab?
    crontab -e

## 27. Al realizar la configuracón de una base de datos, ¿cuál comando puedo utilizar para proporcionar seguridad básica en una base de datos MySQL o MariaDB?
    mysql_secure_installation

## 28. ¿Cuál es el nombre del proceso que controla Apache y que se maneja con systemctl?
    apache2

## 29. Este parámetro en NGINX depende directamente de la cantidad de CPU que tengamos en nuestro servidor:
    worker_processes

## 30. Después de almacenar información en una variable. ¿cuál símbolo debemos incluir para poder obtener su contenido?
    $

## 31. ¿Cuál operador redirige la salida de pantalla a un archivo y lo concatena al final?
    >>

## 32. ¿Cuál es el Firewall instalado por defecto en distribuciones Ubuntu?
    ufw

## 33. Comando para verificar los puertos en escucha de nuestro servidor:
    netstat

## 34. Parámetro en nmap que hace uso de los scripts:
    -sC

## 35. El reporte CVE-2017-18017 corresponde a:
    Vulnerabilidad en el kernel de Linux antes de la versión 4.11, 4.9.x y antes de la versión 4.9.36

