# Fundamentos de JavaScript 2018

## Si tengo el siguiente código:
```
let nombre = 'Pepe'

    const persona = {
      nombre: 'Sacha',
      apellido: 'Lifszyc',
      edad: 28,
      saludar: function () {
        console.log(`Hola, me llamo ${this.nombre}`)
      },
      decirAdios: function () {
        console.log('Chau, me voy!')
      }
    }

    const otraPersona = {
      ...persona,
      nombre: 'Eric',
      edad: 24
    }

    nombre = 'Lucas'
    otraPersona.saludar()
```
## Se imprimirá por consola:

    Hola, me llamo Eric

##  Tengo el siguiente HTML:
```
<form>
	<input type="text" name="username">
	<input type="password" name="password">
	<button type="submit" id=”btnSubmit”>Login</button>
</form>
```
## Si quiero obtener el botón con id “btnSubmit” puedo hacer:

    document.getElementById(‘btnSubmit’)

## Si tenemos un array de números y queremos un nuevo array con el triple de cada número, ¿qué función de los arrays deberíamos utilizar?

    map

##  Estos dos códigos hacen lo mismo:
```
// 1
total = total + 10
//2
total += 10
```
    Verdadero

##  Si tenemos un array de equipos de fútbol de un torneo y cada equipo tiene una propiedad que indica cuántos goles hizo en lo que va del torneo. Si queremos saber la cantidad de goles totales que hicieron en el torneo, ¿qué función de arrays podríamos utilizar?

    reduce

##  Si comparamos los siguientes objetos de esta manera, da true:
```
const persona = { nombre: 'Sacha' }
persona === { nombre: 'Sacha' } 
```
    Falso: para que dos objetos sean idénticamente iguales (triple igual) deben hacer referencia a la misma posición de memoria

##  Si tengo el siguiente código:
```
obtenerPersonaje('https://swapi.co/api/people/1')
        .then(luke => console.log(luke.name))

      console.log('Sacha')
```
## En consola sale primero el nombre de Luke Skywalker antes que el de Sacha:

    Falso


## Siempre da lo mismo usar var, let o const. Son tres formas de declarar variables que tienen el mismo efecto:

    Falso

##  Para incrementar una variable i en 1 podemos hacer:

    Cualquiera de las anteriores

##  Las promesas son una forma de ejecutar código asíncrono evitando que se produzca un callback hell en nuestro código:

    Verdadero

##  Si tengo el siguiente código de JavaScript
```
var nombre = 'Sacha'
var apellido = 'Lifszyc'

function pasarAMayusculas(nombre){
	return nombre.toUpperCase()
}

pasarAMayusculas(nombre + ' ' + apellido)
pasarAMayusculas('Lucía')
pasarAMayusculas('') 
```
    No da error en ninguna línea

## La siguiente sentencia es true:
```
“1” == 1
```
    Verdadero

## Si queremos repetir cierto código hasta que se cumpla una condición debemos usar un ciclo:

    while

## Si tengo el siguiente código:
```
 const luke = await obtenerPersonaje('https://swapi.co/api/people/1')
      console.log(luke.name)
      console.log('Sacha')
```
## En consola sale primero el nombre de Luke:

    Verdadero

## El primer código es equivalente al segundo:
```
 // 1
      const nombre = persona.nombre
      const apellido = persona.apellido
      const edad = persona.edad
 // 2
      const { nombre, apellido, edad } = persona
```
    Verdadero

## Si sabemos precisamente cuántas veces queremos ejecutar cierto código, nos conviene usar un ciclo:

    for

## Para pasar un string a mayúsculas debemos ejecutar:

    str.toUpperCase()

## Si estamos usando las clases de JavaScript y queremos que una clase “herede” de otra, utilizamos la palabra clave:

    extends

## Si tenemos estas dos llamadas a funciones para obtener datos:
```
  $.get('https://swapi.co/api/people/1', function (luke) {
        console.log(luke.name)
      })

      $.get('https://swapi.co/api/people/4', function (vader) {
        console.log(vader.name)
      })
```
    No podemos saber cuál de los dos aparecerá primero

## Las “clases” en JavaScript no son más que una forma linda de escribir prototipos:

    Verdadero

## Cuando declaro una variable en JavaScript tengo que especificar su tipo:

    Falso

## La siguiente sentencia es true:
```
“1” === 1
```
    Falso

##  Si tengo el siguiente código:
```
$.get('https://swapi.co/api/people/1', function (err, luke) {
        console.log(luke.name)
      })

      console.log('Sacha')
En consola sale primero el nombre de Sacha:
```
    Verdadero

## Si tenemos un array de nombres y queremos excluir aquellos que empiecen con ‘S’, ¿qué función de los arrays deberíamos utilizar?

    filter

## Si queremos ejecutar distintos códigos de acuerdo a múltiples valores (más de 3) que puede tener una variable, nos conviene usar un:

    switch

## En JavaScript para declarar una variable llamada edad y asignarle el valor 27 escribo:

    var edad = 27

##  Al correr este programa en el navegador ¿Qué número se imprime primero en la pantalla?
```
  setTimeout(() => console.log(1), 1000)
     setTimeout(() => console.log(2), 300)
     setTimeout(() => console.log(3), 0)
     console.log(4)
```
    4

## ¿Qué se imprime en la consola?
```
console.log(1)
setTimeout(() => console.log(2), 0)
console.log(3)
```
    1, 3, 2

## Para acceder a la primera letra de un string debemos ejecutar:
    const primeraLetra = str.charAt(0)

## La función reduce de los arrays sirve para reducir un array a un único valor, teniendo en cuenta todos los elementos del array:

    Verdadero