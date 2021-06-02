# Curso de Next.js

## 1. Un uso de extender el Document de una app en Next.js puede ser:
    Agregar elementos adicionales en el Head del HTML
## 2. ¿Cuál podría ser el enfoque más adecuado para una página que tiene 5 productos (los productos se actualizan constantemente en un solo día)?
    Server Side Rendering
## 3. ¿Qué pasa al enlazar dos páginas de Next.js utilizando únicamente la etiqueta <a> ?
    La navegación sucede normal y se hace desde el servidor, perdiendo ventajas de Single Page Application.
## 4. Cuando se desea que una página dinámica pre renderice todo su contenido de forma estática, se debe:
    Utilizar getStaticProps y getStaticPaths
## 5. La diferencia entre getStaticProps y getStaticPaths radica en que:
    El primero obtiene la información del componente (props), y el segundo, le dice a Next.js cuántas y qué páginas se producirán.
## 6. Se considera a una ruta como dinámica porque:
    Su contenido depende de los parámetros de la URL
## 7. El componente que nos ofrece Next.js para conectar dos páginas se llama:
    next/link
## 8. El prefetching automático que nos ofrece Next.js consiste en:
    Iniciar la descarga de recursos de una página cuando se hace "hover" en un enlace.
## 9. Una de las mayores ventajas de un framework como Next.js es:
    Ahorrarnos el trabajo de configuración de React y su ecosistema.
## 10. ¿Cuál podría ser el enfoque más adecuado para una página que tiene 145 productos (los productos rara vez cambian y están en Wordpress)?
    Static Site Generation
## 11. ¿Cuál de las siguientes rutas es una ruta básica?
    /company/about-us
## 12. El code splitting que realiza Next.js está determinado principalmente por:
    Las rutas y las dependencias
## 13. Sobre las API en Next.js, selecciona el enunciado falso.
    Unas páginas no pueden utilizar una API con el mismo nombre dentro de Next.js.

## 14. Sobre la instalación de Next.js, selecciona el enunciado correcto:
    Se puede instalar agregando los paquetes o utilizando una herramienta de CLI.
## 15. Sobre CSS en Next.js, uno de los siguientes enfoques NO está soportado por defecto:
    CSS con SASS
## 16. Los endpoints de una API en Next.js deben quedar en el path:
    /pages/api
## 17. Selecciona el comando adecuado para producir archivos planos de HTML, CSS y JavaScript desde Next.js
    next export
## 18. La mejor forma de realizar CSS en Next.js es con:
    (Descartar esta opción) CSS-in-JS con Styled JSX y Styled Components
## 19. Sobre las API en Next.js, selecciona el enunciado verdadero.
    Un endpoint es una función que manipula el request y el response del servidor.
## 20. Next.js por defecto pre renderiza el contenido desde el servidor siempre que pueda.
    Verdadero
## 21. ¿Cuál podría ser el enfoque más adecuado para una página que tiene 1 página que muestra información en tiempo real?
    Client Side Rendering
## 22. Un buen lugar para agregar Context.Providers en Next.js es en:
    /pages/_app.ts
## 23. ¿Cuál de las siguientes rutas es una ruta dinámica?
    /company/:id/about
## 24. getServerSideProps nos permite:
    Comunicar los props de nuestro componente con código que ejecutamos antes de que Next.js responda al cliente.
## 25. La diferencia entre "next build" y "next export" radica en que:
    El primero construye una aplicación lista para producción de Node. El segundo produce archivos estáticos.

------

Este proyecto sigue la especificación de [todos los contribuyentes](https://github.com/all-contributors/all-contributors) . ¡Contribuciones de cualquier tipo son bienvenidas!
