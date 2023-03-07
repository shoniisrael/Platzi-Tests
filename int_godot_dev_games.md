# Curso de Introducción a Godot para Desarrollar Videojuegos

1. Godot es un motor de videojuegos 2D y 3D multiplataforma, libre y de código abierto.

   Verdadero

2. ¿Qué lenguajes de programación podés usar en Godot?

   Todas son correctas

3. ¿Cuáles son los conceptos claves de Godot?

   Nodos, Escenas, Árbol y Señales

4. ¿Cuál es la diferencia entre OpenGL 2.0 y OpenGL 3.0?

   OpenGL 3.0 tiene mayor calidad y más recursos, mientras que OpenGL 2.0 tiene una mejor compatibilidad con hardware antiguo y puede exportarse para web

5. La diferencia entre un Area2D y los demás collisionBodies (RigidBody, KinematicBody y StaticBody) es que la primera no ocupa un lugar físico dentro del juego y sirve para remarcar un espacio determinado.

   Verdadero

6. El nodo que nos permite tener un control total sobre su movilidad y no se ve afectado por las físicas del ambiente es:

   KinematicBody

7. ¿Qué debemos hacer si queremos que un nodo se desplace hacia arriba en un proyecto 2D?

   Pasarle a la función move_and_slide la velocidad multiplicada por unVector2`en el que el valor de X sea 0 y el valor de Y sea -1 `move_and_slide(speed \* Vector2(0, -1)))`

8. ¿Cómo podemos invertir la dirección de un nodo para crear un rebote?

   Debemos utilizar el método bounce() del Vector2 recibiendo el valor “normal” de la función move_and_collide pasándole la dirección multiplicada por la velocidad y el valor delta

9. Desarrollar una inteligencia artificial puede servir para:

   Todas las opciones son correctas

10. ¿Qué ocurre cuando un nodo emite una señal?

    Se ejecuta la función que está asociada a dicha señal

11. ¿En qué función debemos actualizar la información de la interfaz de usuario?

    `_process()`

12. ¿Cuál es la diferencia entre `_process()` y `_physics_process()`?

    Ambas se ejecutan una vez por fotograma, pero `_process` está destinada a actualizar la interfaz y `_physics_process()` a actualizar las físicas de los nodos.

13. ¿Cómo se llama el nodo que utilizamos para reproducir audios, sin localización espacial?

    AudioStreamPlayer
