# Curso de Administración de Servidores Linux

1. ¿Cuál es la distribución más utilizada de Linux en servidores según w3techs?

   Ubuntu Server

2. ¿Cuáles proveedores de nube me permiten lanzar instancias de Ubuntu server y CentOS como base?

   Todas las mencionadas

3. ¿Por qué debo elegir versiones LTS en Ubuntu?

   Mayor tiempo de soporte en actualizaciones de seguridad y en software.

4. ¿Cuál es el mecanismo recomendado para validar la integridad de la imagen ISO descargada?

   sha256

5. Comando utilizado para concatenar y leer archivos:

```console
cat
```

8. Comando para listar los archivos en formato largo, por orden de modificación y en orden reverso:

```console
ls -ltr
```

9. Número de líneas por defecto que leemos con head y tail en un archivo:

   10

10. Modificador del comando tail que me permite hacer seguimiento del archivo en tiempo real:

```console
-f
```

11. Como mínimo se requiere una partición para:

```console
/
```

12. ¿Qué comando debo utilizar para usar comandos que requieren privilegios de root?

```console
sudo
```

13. Archivo que contiene los usuarios del sistema:

```console
/etc/passwd
```

14. ¿Qué comando debo ejecutar para usar el usuario nodejs?

```console
su - nodejs
```

15. ¿Cuál es el grupo en Linux que tiene permisos de administrador?

```console
sudo
```

16. Comando que permite cambiar los permisos de un archivo:

```console
chmod
```

17. Sistema numérico utilizado para cambiar permisos de forma numérica en Linux:

    octal

18. Si un archivo tiene el valor de permisos 400 quiere decir que:

    Solo el usuario propietario puede leer el archivo.

19. Para poder ejecutar un script en bash, necesitamos el permiso de:

    Ejecución para el usuario que lo quiere correr.

20. ¿Qué comando se puede utilizar para mostrar la información de la conexión de red actual (Dirección IP y MAC) en Ubuntu y CentOS sin instalar paquetes adicionales?

```console
ip a
```

21. ¿Cuál es el protocolo que me permite conectar a otras máquinas Linux de forma segura y ejecutar comandos en un servidor remoto?

```console
ssh
```

22. ¿Con qué comando puedo ver los paquetes instalados en una máquina Ubuntu?

```console
dpkg -l
```

23. ¿Dónde se encuentra almacenada la base de datos de rpm?

```console
/var/lib/rpm
```

24. ¿Qué comando me permite ver los procesos corriendo en el servidor?

```console
ps
```

26. ¿Cuál es el comando que me permite editar el archivo crontab?

```console
crontab -e
```

27. Al realizar la configuración de una base de datos, ¿cuál comando puedo utilizar para proporcionar seguridad básica en una base de datos MySQL o MariaDB?

```console
mysql_secure_installation
```

28. ¿Cuál es el nombre del proceso que controla Apache y que se maneja con systemctl?

```console
apache2
```

29. Este parámetro en NGINX depende directamente de la cantidad de CPU que tengamos en nuestro servidor:

```console
worker_processes
```

30. Después de almacenar información en una variable, ¿cuál símbolo debemos incluir para poder obtener su contenido?

```console
$
```

31. ¿Cuál operador redirige la salida de pantalla a un archivo y lo concatena al final?

```console
>>
```

32. ¿Cuál es el Firewall instalado por defecto en distribuciones Ubuntu?

```console
ufw
```

33. Comando para verificar los puertos en escucha de nuestro servidor:

```console
netstat
```

34. Parámetro en nmap que hace uso de los scripts:

```console
-sC
```

35. El reporte CVE-2017-18017 corresponde a:

    Vulnerabilidad en el kernel de Linux antes de la versión 4.11, 4.9.x y antes de la versión 4.9.36
