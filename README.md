# Proyecto-Estructura-de-datos
Proyecto final respecto a todo lo que hemos visto en el curso

# Reporte
## Introducción

En un principio, las herramientas de inteligencia artificial generativa permiten crear cosas nuevas, como textos, imágenes, videos o incluso música, basándose en lo que han aprendido de grandes cantidades de datos. Estas herramientas son muy útiles para ahorrar tiempo y mejorar la productividad, ya que pueden automatizar tareas repetitivas, generar ideas creativas, redactar documentos rápidamente o personalizar contenido. Esto permite que las personas se enfoquen en trabajos más importantes y estratégicos en lugar de aquellos tediosos.

Para el reporte actual, se emplearon varias IA's generativas para su realización, facilitando la creación y manipulación de varias partes de la página web de varias maneras, es con ello que se presentarán los objetivos principales:

### Objetivo principal
Desarrollar un sistema basado en herramientas de inteligencia artificial generativa para producir información relacionada con un tema específico, integrando soluciones de diferentes fuentes.

### Objetivos específicos
Revisar herramientas de inteligencia artificial generativa.
Seleccionar una herramienta de inteligencia artificial generativa.
Desarrollar un método para integrar la salida de la herramienta de inteligencia artificial generativa seleccionada en el sistema.
Desarrollar una interfaz interactiva.
Desarrollar un método para integrar información de diferentes fuentes.

## Equipo

Las tareas que realizo el equipo son las siguientes:
Bruno Tarango: Conexión a Git, creación del Reporte y diseño CSS de la página web.
Ricardo Villalobos: Principal aportador de información, modificaciones para el compilador y la IA.

## Desarrollo del Sistema

Pagina.html = Es el principal archivo del proyecto, en él se encuentra toda la información en formato HTML, con solo descargarlo se podrá visualizar su información y diseño, está hecho para que funcione con pantallas 1920 x 1080, trabajar una pantalla más grande o una más pequeña puede afectar considerablemente la experiencia del usuario.

images = Es una carpeta que contiene imágenes que se conectan con la página web. Específicamente, una de ellas muestra un dibujo hecho por Bruno Tarango con los integrantes del equipo (Ángel Olivia son los papás, nunca fue santa ni chambeo en el equipo). La segunda imagen muestra un dinosaurio hecho con https://gencraft.com/generate, una IA para imágenes.

README.md = Es el documento donde se encuentra el actual reporte.

## Realización del proyecto

En esta sección, se explicará detalladamente el proceso para la ejecución del proyecto, iniciando por el proceso de investigación:

Para comenzar, el primer paso fue la búsqueda de herramientas generativas respecto al código y texto, que son la base para la página web, por temas de problema al momento de implementar imágenes en la página web, no se usaron herramientas para imágenes aparte de la mostrada para el dinosaurio, por lo que el análisis está enfocado en las anteriores mencionadas.

Tras la búsqueda de herramientas, se consideraron para la creación de este proyecto las siguientes 3: Chat Gpt, Copilot y Blackbox. Lo anterior es debido a la facilidad para generar respuestas y por dar contenido de calidad para la página web. En específico, Chat Gpt con los intentos diarios de su último modelo ayudaba y pulía los avances, no obstante, cuando estos intentos se acababan, la calidad de respuestas bajaba, por ende, Copilot y Blackbox tuvieron el principal papel de ayudarnos con preguntas y cambios sencillos al código, mientras que GPT hacía cambios más grandes.

Una forma de visualizar lo anterior es con el siguiente esquema que representa el orden con el que se probaban las preguntas dependiendo de su dificultad para ejecutar:

Chat Gpt -> Copilot -> BlackBox

Es con las anteriores que también apoyaron para la generación texto e información para la página web, destacando a Copilot al dar texto amplio. Para el caso de la implementación de código, elegimos Black Box por su facilidad de intuición y por tener un enlace directo a su empleo.

Para añadir la IA, se intentó en primer lugar, integrarla dentro del html, no obstante, por más que se intentará, no funcionó como debía, por lo que se añadió mediante un iframe tal que: 
            
<div class="BlackBox">
    <iframe src="https://www.blackbox.ai" width="85%" height="450px" frameborder="0"></iframe>
</div>
De esta manera se entra directamente a la página de blackbox y se puede trabajar e ingresar preguntas en la misma.

Para el compilador de código, se realizó un proceso similar, tampoco se logró ejecutar correctamente, por lo que se añadió la página con iframe de la siguiente forma:
<div class="code-compilation">
    <iframe src="https://www.onlinegdb.com" width="85%" height="450px" frameborder="0"></iframe>
</div>
Es con lo anterior que se logra implementar la inteligencia artificial y el compilador de código para realizar preguntas a ella. A pesar de no haber logrado obtener la API, se puede investigar y compilar el código sin ningún problema.


El proceso para ingresar la información fue relativamente sencillo, pedíamos a una de las IAs que generara texto, y tras verificar su veracidad, le pedíamos que nos pasara a formato html. Para el diseño web, en un principio se pidió un template a la IA, pero se fue modificando manualmente o con ayuda para que tuviera mejor visualización, en especial se destaca Gpt, ya que se podía mandar imágenes de ciertos estilos para que los aplicara en la página web.


Es con lo anterior que se logra implementar la IA en el proyecto.
