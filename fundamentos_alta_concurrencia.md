1. ¿DevOps y SRE son lo mismo?

```
Falso, SRE es el puesto y DevOps es la cultura.
```

2. ¿Cuándo se debe empezar a pensar en implementar arquitecturas de alta concurrencia?

```
Cuando un solo servidor no puede manejar la cantidad de usuarios que son recibidos.
```

3. ¿Qué son los buckets u object stores?

```
Un servicio/arquitectura en la nube donde podemos guardar información de forma indefinida para escalar.
```

4. ¿Qué es el escalamiento vertical?

```
Es agrandar el tamaño de la instancia/servidor en CPU y RAM.
```

5. ¿Qué es el escalamiento horizontal?

```
Es cuando aumentamos la cantidad de servidores.
```

6. ¿Cuándo preferimos crear un servidor stateless?

```
Cuando queremos escalar muy fácilmente: no queremos copiar información de un servidor a otro al copiarlo/reemplazarlo.
```

7. ¿Para qué sirve hacer stress testing de nuestra aplicación?

```
Para probar la capacidad de tráfico de un sistema simulando su uso por muchos usuarios a la vez.
```

8. ¿Qué es más común hacer en bases de datos? ¿Lecturas o escrituras?

```
Lecturas, por ello creamos réplicas de lectura de la base de datos.
```

9. ¿Cuál es una función importante de las CDN cuando hablamos de tráfico por regiones/países?

```
Replicar servidores en muchos países para que la aplicación funcione rápido en todo el mundo.
```

10. ¿Por qué la mayoría de los servidores usan Linux?

```
Es más accesible económicamente e históricamente ha sido más estable.
```

11. Las contraseñas deben quedar registradas en los logs de nuestro sistema. Estos es:

```
Falso, la información sensible no debe quedar disponible para que cualquier persona pueda verla.
```

12. ¿Qué hace un orquestador de contenedores? Por ejemplo, Kubernetes.

```
Orquesta contenedores ubicándolos en diferentes servidores y crea nuevos contenedores en caso de que alguno deje de funcionar.
```

13. ¿Qué tipo de base de datos es más sencillo escalar?

```
MongoDB
```

14. ¿Cuál es el principal uso de CDN?

```
Cachear archivos estáticos.
```

15. ¿Qué es un ataque DDoS?

```
Un ataque donde se intenta hacer muchos request desde miles servidores a una aplicación para sobrecargarla.
```

16. ¿Cuál es el lenguaje de definición más usado para el protocolo de API REST?

```
JSON
```

17. ¿Siempre se deben considerar las mismas características para cualquier aplicación?

```
Falso, depende del tipo de negocio y aplicación.
```
