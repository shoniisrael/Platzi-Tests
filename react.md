####  1. ¿Cuál de los siguientes componentes es un componente de tipo clase?
(Opcion Incorrecta)->
```constructor(props){
		super(props);
		this.state = {
			hello: ‘Hola Mundo Stateful’
		}
	}
render(){
	return (
			<h1>{this.state.hello}</h1>
		);
	}
}
export default Stateful; 
import React {Component}from react; 
```
#### 2. ¿Qué regla deben seguir nuestros Custom Hooks?

Deben iniciar con “use”.

#### 3. ¿Para qué nos sirve useState()?

Nos permite trabajar con el estado de un componente en React sin escribir una clase.
#### 4. El metodo .map() nos permite iterar por un arreglo
Verdadero
#### 5. ¿Para qué nos sirve el archivo .gitignore de nuestro proyecto?

Especifica archivos que no deben de ser rastreados o debe ignorar o se deben ignorar en GIT.

#### 6. babel-eslint es una libreria que nos ayuda a:
(Opcion Incorrecta)-> bebel-eslint es una librería para hacer JavaScript compatible con todos los navegadores.

#### 7. ¿Cuál es el loader que utilizamos para añadir soporte a Sass?

sass-loader
#### 8. html-webpack-plugin es un paquete que utilizamos para:
Este complemento nos permite simplificar la creación de archivos HTML y servir los bundles creados por Webpack
#### 9. ¿Para qué nos sirve useEffect()?

useEffect, agrega la capacidad de realizar efectos secundarios desde un componente creado como función. Ejemplo: Llamar una API.

#### 10. ¿Cuál de los siguientes componentes es un componente de tipo función?

import React from ‘react’;
const Stateless = () => {
	return (
		<h1>Hola Mundo Stateless</h1>
	);
};
export default Stateless; ```
#### 11. Cómo añadimos/importamos estilos de Sass a nuestros componentes en React?

import './styles/Categories.scss';
#### 12. ¿Para qué nos sirve el flag --save-dev?

–save-dev se usa para guardar el paquete con fines de desarrollo.

#### 13. Con este paquete podemos crear un servidor local para exponer una Fake API
json-server
#### 14. ¿Funcion para manejar el evento del Click en React?
onClick()
#### 15. ¿Cómo inicializamos un proyecto con npm?

npm init
#### 16. ¿Cuál de los siguientes componentes es un componente presentacional?

const ComponentX = () => <h1>¡Hola Mundo!</h1>;
export default ComponentX; ```
#### 17. ¿Qué es Babel?

Babel es una herramienta que nos permite transformar nuestro código Javascript ES6 a JavaScript que cualquier navegador soporte
#### 18. ReactDOM.render() nos permite representar un elemento creado en React como un nodo del DOM.

Verdadero
#### 19. ¿Para que nos sirve Webpack?
Webpack es una herramienta de compilación que nos permite añadir en un archivo todas las dependencias a los elementos que forman parte de tu proyecto de desarrollo
#### 20. ¿Qué paquete utilizamos para crear un entorno de desarrollo local?

webpack-dev-server
#### 21. ¿A partir de cuál versión de React.js podemos crear componentes con React Hooks?

A partir de la versión 16.8.

#### 22. ¿import React from react es una forma correcta de importar react-dom?

Falso
#### 23. ¿Cómo ejecutamos nuestra Fake API?

json-server file.json
#### 24. ¿Qué es React Hooks?

Nos permite usar el estado y otras características de React sin escribir una clase.
#### 25. ¿Qué es JSX?

Es una sintaxis que nos permite utilizar HTML dentro de JavaScript en React
#### 26. ¿Para qué nos sirven los prop-types?

Nos permiten validar las propiedades que pasamos a nuestros componentes.

#### 27. ¿En qué archivo creamos la configuración de Babel?
(Opcion Incorrecta)-> .babelsrc
#### 28. ¿En qué archivo creamos la configuración de ESLint?

.eslintrc
#### 29. ¿Cuál es la propuesta de React para utilizar clases de css en JSX?

className

#### 30. ¿Cuál es el comando para ejecutar nuestro entorno de desarrollo local?

npm run start