1. ¿Cuál es el comando para instalar el Angular CLI?
```
npm i @angular/cli -g
```

2. ¿Cuál es el comando correcto para correr un proyecto en Angular en forma de desarrollo y en el puerto 3009?
```
ng serve --port=3009
```

3. ¿Qué función tiene el archivo .browserslistrc ?
```
La configuración en donde expresamos que versiones de navegadores vamos a soportar.
```

4. En TypeScript, ¿cuál es la forma correcta de 'tipar' una variable?
```
const name: string = 'Nicolas';
```

5. ¿Cuál de las siguientes expresiones usando String Interpolation da un error?
```
{{ [1,2].reverse() }}     <-- [!] Atención, respuesa incorrecta.
```

6. Usando Property Binding, ¿cuál es la forma correcta de controlar el estado ‘disable’ de un botón de un HTML?
```
<button [disable]=“btnState”>My Button</button>
```

7. ¿Cuál es la forma correcta de llamar un evento click usando Event Binding?
```
<button (click)=“doSomething()”>My Button</button>
```

8. ¿Cuál sería la forma correcta sin usar ngModel de leer los cambios en un input?
```
<input type=“text” [value]=“name” (keyup)=“changeName($event)”>
```

9. ¿Cuál paquete de Angular debemos importar en el App Módulo para trabajar con NgModel?
```
import { FormsModule } from '@angular/forms';
```

10. ¿Cuál es la forma correcta de usar un ngIf en el template?
```
<p *ngIf=“1 === 1”>My Text</p>
```

11. ¿Cuál sería la forma correcta de imprimir este array ['a', 'b', 'c'] en un template usando el ngFor?
```
<p *ngFor=“let item of [‘a’, ‘b’, ‘c’]”>{{ item }}</p>
```

12. ¿Cuál es la forma correcta de aplicar una clase dinámica con Angular?
```
<p [class.myClass]=“1 === 1”>My text</p>
```

13. Usando el Property binding, ¿cuál es la forma de modificar el ancho de un elemento?
```
<p [style.width.px]=“100”>Text</p>
```

14. ¿Cuál es el evento que nos da angular para llamar el sumbit de un formulario?
```
<form (ngSubmit)=“onSave()”>Text</form>
```

15. ¿Cuál es comando que nos ofrece Angular alistar nuestro proyecto para producción?
```
ng build
```
