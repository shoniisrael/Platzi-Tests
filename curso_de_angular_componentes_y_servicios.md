## 1.¿Cuál es la forma de generar un componente usando el Angular CLI?
>  ng g c img

## 2.¿Cuál método es el apropiado para enviar información de un componente padre a un hijo?
>  @Input

## 3.¿Cuál método es el apropiado para enviar información de un componente hijo a un padre?
>  @Output

## 4.¿Cuál de las siguientes frases es una definición correcta para el ngOnInit?
>  El ngOnInit se corre solo una vez y se recomienda poner cosas asíncronas en este método.

## 5.¿Cuál de las siguientes frases es una definición correcta para el ngOnDestroy?
>  El ngOnDestroy se corre cada vez que el elemento es eliminado del DOM y aquí podríamos liberar recursos.

## 6.¿Cuál es el archivo correcto en donde agregamos estilos de forma global?
>  src/styles.css

## 7.¿Cuál es la forma correcta de definir un Output que va a transmitir valores de tipo String a un padre?
>  @Output() add = new EventEmitter();

## 8.¿Cuál es la forma de generar un servicio usando el Angular CLI?
>  ng g s myService

## 9.Si nos fijamos solo en el constructor de un componente ¿Cuál es la forma correcta inyectar un servicio?
>  constructor(private demoService: DemoService) {}

## 10.¿Cuál paquete de Angular debemos importar en el App Módulo para trabajar con HttpClient?
>  import { HttpClientModule } from '@angular/common/http';

## 11.¿Cuál es el pipe que ya trae Angular para mostrar fechas?
>  myDate | date

## 12.¿Cuál es la forma de generar un pipe usando el Angular CLI?
>  ng g p reverse

## 13.¿Cuál es el decorador que usamos dentro de una directiva para escuchar el evento mouseenter?
>  @HostListener

## 14.¿Cuál es la forma correcta en la que definimos un observable de rxjs para lograr reactividad en Angular?
>  private myList = new BehaviorSubject([]);

## 15.¿Cuál es el comando para correr el linter en Angular?
>  ng lint
