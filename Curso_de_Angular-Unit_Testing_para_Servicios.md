# Curso de Angular: Unit Testing para Servicios

1. ¿Cuál es el comando desde el Angular CLI para correr las pruebas?

   > ng test

2. ¿Cuál es el significado correcto del triple A (AAA)?

   > Arrange, Act, Assert

3. ¿Cuál sería el matchers apropiado para comprobar si una variable Undefined ?

   > toBeUndefined

4. ¿Cuál es el comando para correr pruebas y generar el reporte de cobertura?

   > ng test --code-coverage

5. El código que está dentro del beforeEach va a correr después de cada prueba.

   > FALSE

6. Cuando haces pruebas unitarias de con servicios que tienen dependencias ¿Cuál de las siguientes técnicas es considerada mejor?

   > Se suplantan las dependencias, ya que una prueba unitaria prueba solo la responsabilidad de la misma y no sus terceros.

7. ¿Cuál es el objetivo de los spies?

   > Para verificar el comportamiento interno, ya que se evalúa si el sujeto de prueba llamo a x método con xparámetros`

8. ¿Cuál es la funcionalidad del TestBed?

   > Crear un ambiente de Angular temporal el cual va a tener todos lo necesario para poder probar servicios, pipes, directivas etc.

9. ¿Cuál es la forma correcta de crear un Spy para un método de una clase?

   > jasmine.createSpyObj('ValueService', ['getValue']);

10. ¿Cuál es la funcionalidad de HttpClientTestingModule?

    > Poder interceptar las peticiones para inyectar datos falsos simulando el request de HttpClient.

11. ¿Cuál es la manera correcta de hacer pruebas para verificar que una petición haya sido enviada con el método GET?

    > const req = httpController.expectOne(`...`); expect(req.request.method).toEqual('GET');

12. ¿Cuál es la manera correcta de hacer pruebas para verificar el body de una petición?

    > const req = httpController.expectOne(`...`); expect(req.request.body).toEqual(...);

13. ¿Es correcto hacer pruebas solo de las peticiones sin tener en cuenta los errores?

    > FALSE

14. ¿Cuál es la manera correcta dé hacer pruebas del los headers de una petición?

    > expect(headers.get('Authorization')).toEqual(`...`);

15. ¿Cuál es el matcher correcto para verificar si un método fue llamado n veces?
    > toHaveBeenCalledTimes
