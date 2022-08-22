1. ¿Cómo declaras una variable en Svelte?

```javascript
let secondName = "Barajas";
```

2. Analiza el siguiente código, ¿cuál es la forma correcta de añadir estilos globales?

```css
:global(body) {
  background-color: #f2eee2;
  color: #0084f6;
  transition: background-color 0.3s;
}
```

3. El CSS en Svelte se encapsula entre las etiquetas

```
Verdadero
```

4. ¿Cuál es la forma correcta de importar un componente en Svelte?

```javascript
import About from "./components/About.svelte";
```

5. Método que disponemos para manejar eventos al hacer click.

```html
<button on:click="{toggle}">DarkMode</button>
```

6. ¿Cuál es la forma correcta de pasar propiedades a un componente?

```javascript
export let anotherText;
```

7. ¿Cuál es la forma correcta de pasar propiedades con un valor predeterminado?

```javascript
export let anotherText = "Lorem ipsu";
```

8. Analiza el siguiente código, ¿cuál es la forma correcta de manejar condicionales?

```javascript
{#if !styles.darkMode}
    <p>
      {@html someText}
    </p>
  {:else}
    <p>
      <span>Hello DarkMode</span>
    </p>
  {/if}
```

9. El método `onMount` es parte del ciclo de vida de los componentes en Svelte.

```
Verdadero
```

10. ¿La principal cualidad de Svelte es?

```
Todas las opciones.
```

11. ¿Svelte es un framework que compila a JavaScript nativo?

```
Verdadero
```

12. Analiza el siguiente código, ¿Cuál es la forma correcta de iterar por un arreglo en Svelte?

```javascript
{#each comments as comment (comment.id)}
      <divclass="Comments-users">
        <h3>{comment.username}</h3>
        <span>{comment.text}</span>
      </div>
    {/each}
```

13. ¿Cuál es la forma correcta de declarar un Store en Svelte?

```javascript
import { writable } from "svelte/store";
export const likeCount = writable(0);
```

4. import { blur } from "svelte/transition"; Nos permite añadir animaciones a nuestra aplicación.

```
Falso
```

15. ¿Cuál es el comando para compilar nuestro proyecto a producción?

```bash
npm run build
```
