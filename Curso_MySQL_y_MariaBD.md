
# Curso MySQL y Maria BD
## 1. ¿Cuál es el RDBMS que creó originalmente Monty y que ahora pertenece a Oracle?
> MySQL
## 2. ¿Cuál tipo de diagrama ER me permite describir detalladamente mis bases de datos?
> Diagrama físico
## 3. ¿Cuál tipo de diagrama ER me permite expresar la idea general de mi base de datos?
> Diagrama conceptual

## 4. Cuando tengo una relación muchos a muchos, ¿cómo debería relacionar mis tablas?
> Creando una tabla pivot que relacione una fila de una tabla con una fila de otra tabla.
## 5. ¿Cuál sentencia SQL me permite crear una nueva base de datos?
> CREATE DATABASE

## 6. ¿Cómo puedo crear un nuevo usuario en mi base de datos?
> CREATE USER 'nombre_usuario'@'localhost' IDENTIFIED BY 'password';

## 7. ¿Cómo puedo darle ciertos privilegios a un usuario de mi base de datos?
> GRANT privileges ON database.table TO 'username'@'localhost';

## 8. ¿Es posible insertar múltiples filas con un único INSERT INTO?
>Verdadero, simplemente pongo cada nueva fila encerrada en paréntesis después del VALUES.
## 9. Si dentro de mi tabla "usuarios" tengo un usuario con el id 4 cuyo "username" está
escrito como "RtaxMatser". ¿Qué sentencia SQL me ayudaría a corregir dicho nombre
de usuario?

> UPDATE username = "RetaxMaster" FROM `usuarios` WHERE id = 4; 
## 10. Si necesito borrar una tabla ¿cuál sentencia SQL debería utilizar?

> DROP TABLE
## 11. ¿Cuál es esa frase que debes repetir ANTES DE BORRAR registros de una tabla?
> Nunca hacer un DELETE FROM sin un WHERE.

## 12. ¿Es posible renombrar una columna usanto la sentencia SELECT?
>Verdadero

## 13. ¿Es posible calcular distancias geográficas con un RDBMS?
>Verdadero. Muchos RDBMS actuales incluyen una serie de Spatial Functions.

## 14¿Cuál es el tipo de dato que me permite guardar una coordenada terrestre en mi base de datos?
> POINT

## 15.¿Cuál de los siguientes sería un ejemplo en el que puedes aplicar las funciones espaciales?
> Cuando necesito obtener la lista de restaurantes que estén a menos de 3 kilómetros de distancia de un usuario.

## 16. ¿En qué casos es más recomendable usar procedimientos almacenados?
> Cuando tenemos una consulta SQL muy larga que estaremos ocupando muchas veces a lo largo de nuestra aplicación.

## 17. ¿Es posible concatenar código SQL dentro de un procedimiento almacenado?
> Verdadero. Gracias a los prepared statements y a la función CONCAT es posible hacer esto.

## 18.¿Cuál característica de un RDBMS debería usar para desencadenar una acción después de que yo ejecute alguna otra acción en mi base de datos?
>Triggers

## 19. ¿Debería usar al usuario root siempre que quiera trabajar con mis bases de datos?
> Falso. Es una mala práctica usar al usuario root, ya que tiene muchos privilegios. Es mejor crear un usuario aparte con permisos específicos.

## 20. ¿Qué es una llave foránea?
> Es una columna que nos permite relacionar los registros de una tabla con los registros de otra tabla
