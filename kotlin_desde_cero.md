# Curso de Kotlin desde Cero

#### Kotlin es un lenguaje fuertemente tipado.
		 Verdadero
------------
#### Kotlin solo sirve para crear aplicaciones Android.
 		 Falso
------------
#### La función main es...
		 El punto de entrada de tu programa.
------------
#### El tipo de variable val es de lectura y escritura.
		 Falso
------------
#### ¿Cuántos valores puede tener la siguiente variable? val a : Boolean
		 Tres
------------
#### Las variables de tipo var son de lectura y escritura.
		 Verdadero

------------
#### En Kotlin un tipo de dato entero se define como:
		 Int
------------
#### Al escribir código en Kotlin debes evitar la mutabilidad y utilizar más la inmutabilidad.
		 Verdadero
------------
#### En Kotlin es posible asignar un valor utilizando un if
		 Verdadero
------------
#### ¿Cuántas ramas puede tener un when?
		 Dependiendo del tipo de dato que se utilice puede tener desde 2 ramas hasta n cantidad.
------------
#### Con el when siempre tengo que incluir una rama else.
		 Sí, es una buena práctica tener un when exhaustivo.
------------
#### Cuando quiero iterar sobre una lista para modificar elementos y devolver elementos modificados debe utilizarse la función:
		 map 
------------
#### ¿Por qué debo utilizar la función map en lugar de un for normal?
		 Porque al utilizar la función map evito estar creando una lista mutable y estar agregando elementos a dicha lista.
----------- 
#### Si quiero filtrar los elementos de una lista por una condición, debo utilizar la función:
		 filter
------------
#### Los nullables son:
		 Como toda herramienta, pueden ser buenas o malas dependiendo de su uso.
------------
#### El operador double bang !! es...
		 Considerado una mala práctica y debemos evitar utilizarlo lo más posible.
------------
#### Este operador ?: es llamado el operador:
		 Elvis
------------
#### En Kotlin el operador ternario no existe porque:
		 Con un If podemos replicar el comportamiento.
------------
#### Dada la siguiente lista: val lista = listOf(1,2,3,4) si quisiera eliminar el primer elemento de la lista ¿que tendría que hacer?
		 No podría porque la lista es inmutable.
------------
#### Si tengo un MutableMap con un elemento que tiene como clave "RazaDePerro" y el valor es "Corgi". Al intentar asignar un nuevo elemento con la clave "RazaDePerro" y el valor "Pitbull" ¿Cuál sería el resultado?
		 El primer valor será sobreescrito por el segundo valor.
		 ###### Razón: Los maps son elementos de clave,valor, y solo puede haber una clave.
------------
#### Si tenemos: val set = setOf("a","b","c") y ejecutamos la función set.remove(0) ¿Qué ocurrirá?
		 No ocurre nada porque no se pueden eliminar elementos de un set.
------------
#### Las funciones en Kotlin siempre devuelven un tipo.
		 Sí, siempre devuelven un valor aunque sea implícito.
------------
#### La palabra reservada para crear una función en Kotlin es:
		 fun
------------
#### ¿Cuál es el resultado de la siguiente función? fun miFuncion(val nombre: String, val apellido: String) = nombre + apellido
		 Si utilizamos los parámetros Andrea Gómez el resultado sería: AndreaGómez
------------
#### Las high order functions son llamadas así porque:
		 Son funciones que reciben como parámetro otras funciones.
------------
#### Las funciones de extensión nos permiten:
		 Extender del lenguaje y añadir funcionalidades a objetos, creando un código entendible y conciso.
------------
#### El siguiente código miVariableNullable?.let{ it -> it.length } nos ayuda a:
		 Ejecutar el código dentro de las llaves solamente cuando miVariableNullable no sea nulo.
------------
#### Las lambdas se pueden crear y pasar como parámetros a otras funciones, pero no se pueden almacenar en variables.
 		 Falso, las lambdas se pueden crear y almacenar en variables así como también se pueden pasar como parámetros a otras funciones.
------------
#### La función apply nos permite:
		 Realizar modificaciones a una variable y devolver la misma variable con las propiedades modificadas.

------------
#### Cuando quiero iterar sobre una lista sin necesariamente modificar sus elementos puedo usar la función:
		 forEach