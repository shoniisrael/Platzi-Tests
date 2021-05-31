# Curso Práctico de React JS

### ¿Qué regla deben seguir nuestros Custom Hooks?
	Deben iniciar con “use”.

### ¿Para qué nos sirve useState()?
	Nos permite trabajar con el estado de un componente en React sin escribir una clase.
### El metodo .map() nos permite iterar por un arreglo
	Verdadero
### ¿Para qué nos sirve el archivo .gitignore de nuestro proyecto?
	Especifica archivos que no deben de ser rastreados o debe ignorar o se deben ignorar en GIT.
### ¿Cuál es el loader que utilizamos para añadir soporte a Sass?
	sass-loader
### html-webpack-plugin es un paquete que utilizamos para:
	Este complemento nos permite simplificar la creación de archivos HTML y servir los bundles creados por Webpack
### ¿Para qué nos sirve useEffect()?
	useEffect, agrega la capacidad de realizar efectos secundarios desde un componente creado como función. Ejemplo: Llamar una API.

###  ¿Cuál de los siguientes componentes es un componente de tipo función?
```
	import React from ‘react’;
	const Stateless = () => {
		return (
			<h1>Hola Mundo Stateless</h1>
		);
	};
```
	export default Stateless; ```
###  Cómo añadimos/importamos estilos de Sass a nuestros componentes en React?
	import './styles/Categories.scss';
###  ¿Para qué nos sirve el flag --save-dev?
	–save-dev se usa para guardar el paquete con fines de desarrollo.

###  Con este paquete podemos crear un servidor local para exponer una Fake API
	json-server
###  ¿Funcion para manejar el evento del Click en React?
	onClick()
###  ¿Cómo inicializamos un proyecto con npm?
	npm init
###  ¿Cuál de los siguientes componentes es un componente presentacional?
```
const ComponentX = () => <h1>¡Hola Mundo!</h1>;
```
	export default ComponentX;
###  ¿Qué es Babel?
	Babel es una herramienta que nos permite transformar nuestro código Javascript ES6 a JavaScript que cualquier navegador soporte
###  ReactDOM.render() nos permite representar un elemento creado en React como un nodo del DOM.
	Verdadero
###  ¿Para que nos sirve Webpack?
	Webpack es una herramienta de compilación que nos permite añadir en un archivo todas las dependencias a los elementos que forman parte de tu proyecto de desarrollo
###  ¿Qué paquete utilizamos para crear un entorno de desarrollo local?
	webpack-dev-server
###  ¿A partir de cuál versión de React.js podemos crear componentes con React Hooks?
	A partir de la versión 16.8.

###  ¿import React from react es una forma correcta de importar react-dom?
	Falso
###  ¿Cómo ejecutamos nuestra Fake API?
	json-server file.json
###  ¿Qué es React Hooks?
	Nos permite usar el estado y otras características de React sin escribir una clase.
###  ¿Qué es JSX?
	Es una sintaxis que nos permite utilizar HTML dentro de JavaScript en React
###  ¿Para qué nos sirven los prop-types?
	Nos permiten validar las propiedades que pasamos a nuestros componentes.

###  ¿En qué archivo creamos la configuración de ESLint?
	.eslintrc
###  ¿Cuál es la propuesta de React para utilizar clases de css en JSX?
	className

###  ¿Cuál es el comando para ejecutar nuestro entorno de desarrollo local?
	npm run start


---------

Este proyecto sigue la especificación de [todos los contribuyentes](https://github.com/all-contributors/all-contributors) . ¡Contribuciones de cualquier tipo son bienvenidas!
