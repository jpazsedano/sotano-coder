# Sótano Coder

Repositorio de Sotano Coder. Aquí encontrarás todo el código usado en los ejemplos así como ejercicios extra.

El repositorio está estructurado en carpetas. Para cada lección que esté acompañada de código, encontrarás una
carpeta con el código en cuestión, para que puedas examinarlo a fondo y trastear con él. Todo el código está
diseñado para ser multiplataforma, salvo que se indique lo contrario en el `README.md` del subdirectorio. Dicho
`README.md` contendrá una explicación del código así como propuestas para hacer modificaciones y enlaces por si
quieres profundizar más por tu cuenta.

Además de los directorios de las lecciones, también podrás encontrar directorios con ejercicios extra. Estos
ejercicios son pequeñas piezas de software que están incompletas o tienen algún error. El trabajo a realizar
en cada uno de ellos se especifica en su `README.md`.

En la carpeta `doc` podrás encontrar las lecciones en formato escrito así como documentación sobre el código
disponible en el repositorio.

## Organización del código del sitio web

Para organizar el sitio web, todas las páginas tendrán la barra de navegación. Habrá una
serie de páginas estáticas que mostrarán una landing page, una página para cursos,
ejercicios y ejemplos y proyectos.

La landing page estará en index.html (porque es la principal), pero el resto tendrá cada
una su carpeta en la que estará la página principal de resumen y las páginas de 
listado de contenido. El contenido estará organizado en colecciones y no posts, ya que
nos interesa que cada curso sea independiente de los demás y de los ejercicios, por
ejemplo.

Para la visualización de cada elemento en detalle, se utilizará la URL generada por
el elemento de la colección. Investigar a ver cómo usar eso.
