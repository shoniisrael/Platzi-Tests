# Curso de Configuración Profesional de Entorno de Trabajo para Ciencia de Datos
1.
¿Qué son las plantillas de proyectos en ciencia de datos?
Medio que posibilita portar o construir un diseño predefinido.
2.
¿Por qué utilizar plantillas de proyectos en ciencia de datos?
Agilizará tu trabajo. Te agradecerán y te agradecerás. Reducirás la fatiga por decisión.
3.
¿Qué es Cookiecutter?
Un programa que permite crear proyectos a partir de cookiecutters (i.e., plantillas de proyectos).
4.
Detrás de escenas Cookiecutter funciona con Jinja2. Jinja2 tiene tres bloques especiales para el diseño de plantillas llamados:
Bloques de expresión, bloques declarativos y bloques de comentarios.
5.
Para que Cookiecutter funcione correctamente necesita de 2 archivos escenciales, ¿cuáles son?

Directorio {{ cookiecutter.project_slug }} y cookiecutter.json
6.
¿En qué consiste el concepto hooks en Cookiecutter?
Son archivos que le dicen a Cookiecutter qué hacer antes y después de crear la plantilla de proyecto.
7.
¿Por qué deberías utilizar un manejador de rutas del sistema de archivos con Python?
Para compartir proyectos con otras personas/computadoras/sistema operativos y que las rutas del proyecto no deban cambiarse de nuevo para funcionar.
8.
En Python existen tres manejadores de rutas: OS, Pathlib y PyFilesystem2. ¿Cuál de las siguientes instrucciones regresa un error?
fs.path.join("..", "documents")
9.
¿Con qué comando instalas tu proyecto de ciencia de datos como una librería de Python?
pip install --editable .
10.
¿Para qué sirve la magica de Ipython %autoreload?

Recargar módulos antes de ejecutar el código de usuario.
11.
¿Cuál es una razón a favor de dividir tus notebooks dependiendo de su contenido y etapa del proyecto? Por ejemplo: 0.1-jvelezmagic-download_data.ipynb y 0.2-jvelezmagic-preprocessing.ipynb
Evita tener notebooks gigantes e innecesariamente complicados al tener toda la lógica del proyecto.
