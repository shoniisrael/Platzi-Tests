# Fundamentos de Web Scraping con Python y Xpath

## ¿Qué es el Web Scraping?"
    Una técnica para extraer información de Internet de forma estructurada.
## ¿En cuál de las siguientes plataformas puedes encontrar un trabajo freelance de web scraping?
    Upwork
## ¿Qué módulo de Python nos permite hacer peticiones HTTP?
    requests
## ¿Qué status code nos indica que una petición salió bien?
    200
## ¿Qué etiqueta me permite incluir JavaScript en un documento HTML?
    script
## ¿En qué problema podría meterme por no respetar el archivo robots.txt?
    Todas las opciones.
## XPath fue pensado en su creación para extraer información de un documento:
    XML
## ¿Qué es un nodo?"
    Un tag de HTML y su contenido.
## ¿Cuál es la expresión que selecciona la raíz de un documento HTML?
    /
## ¿Cuál es la expresión que selecciona al padre del nodo actual?
    ..
## ¿Cuál es la expresión que selecciona un atributo?
    @
## ¿Qué predicado me permite seleccionar el último nodo de un conjunto de nodos hermanos?
    [last()]
## Selecciona el predicado que trae un nodo con una clase igual a \"car\":
    [@class="car"]
## En un conjunto de nodos hermanos, ¿con qué predicado extraigo los nodos a partir del tercero?
    [position()>3]
## ¿Cuál es el operador que representa a la operación lógica \"y\" en XPath?
    and
## ¿Cuál es el operador que representa a la operación lógica \"o\" en XPath?
    or
## ¿Cuál es el wildcard que extrae todos los nodos y su contenido?
    node()
## ¿Por qué la función matches genera un error en Google Chrome?
    Porque Chrome solo soporta la versión 1.0 de XPath.
## ¿Cuál es la función para buscar un nodo sabiendo que su contenido posee una cadena de caracte es determinada en algún lugar?
    contains()
## ¿Cuál es la función para buscar un nodo sabiendo que su contenido comienza con una cadena de aracteres determinada?
    starts-with()
## ¿Qué función me permite utilizar expresiones regulares para buscar un nodo por su contenido? 
    matches()
## ¿Cuál es el XPath Axe que extrae a los hijos y nietos de un nodo?
    descendant
## ¿Cuál es el XPath Axe que extrae a los hijos de un nodo?
    child
## ¿Cuál es el XPath Axe que obtiene a un nodo en sí mismo?
    self
## ¿Qué módulo de Python me permite aplicar XPath sobre un documento HTML?
    lxml
## Selecciona la expresión que extrae el texto de todos los span de un documento HTML:
    //span/text()
## Selecciona la expresión que extrae el atributo src de todas las imágenes de un documento HTML:
    //img/@src
## Selecciona la expresión que extrae a todos los nodos small que contienen una clase que comienza por el carácter \"o\" de un documento HTML:
    //small[starts-with(@class, "o")]
## Selecciona la expresión que extrae a todos los nodos hijos de un div con un id igual a \"main\" de un documento HTML:"
    //div[@id="main"]/*
## Selecciona la expresión que extrae a todos los nodos de un documento HTML:"
    //*