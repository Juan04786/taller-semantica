Taller de Investigación: Fundamentos de HTML
Nombre del Estudiante: [Juan Carlo Osorio]

1. Anatomía de una Etiqueta HTML
Etiqueta de Apertura y Cierre
¿Qué es una etiqueta de apertura?
Es la parte inicial de una etiqueta HTML por la cual da el comienzo de un elemento
ex: HTML <p> este le dice al sistema o programa que va a comnenzar un párrafo. 

¿Qué es una etiqueta de cierre 

Es la parte final que indica el contenido del elemento. 
ex: </p> cierra el párrafo que el cual comenzo con el elemento <p>

¿Qué es un atributo y para qué sirve?
Este proporciona informacion adicional sobre un elemento HTML este se escribe dentro de la etiqueta d eapertura y simerpre tiene un nombre y un valor. 
ex: 

<a href="https://trello.com/b/8HnVBVmF/mi-tablero-de-trello">   Visitar </a>

href es el atributo,"https://openai.com" es un valor le dice a la maquina donde llevar ese enlace.

2. El Poder de la Semántica
HTML Semántico
¿Qué es el HTML Semántico y por qué es tan importante?
HTML semántico usa etiquetas que describen claramente el propósito de su contenido. En lugar de usar solo <div> y <span>, usamos etiquetas como <header>, <nav>, <main>, etc.

¿Por qué es importante para la accesibilidad?

Porque los lectores de pantalla y otras tecnologías asistivas pueden interpretar mejor la estructura de la página, ayudando a personas con discapacidad visual o cognitiva

¿Por qué es importante para el SEO?

Porque los motores de búsqueda como Google entienden mejor el contenido y su jerarquía, lo que mejora la visibilidad del sitio en los resultados de búsqueda.


+---------------------------------------------+
|          IMPORTANCIA DEL HTML SEMÁNTICO     |
+------------------------+--------------------+
|     ACCESIBILIDAD      |         SEO        |
+------------------------+--------------------+
| - Facilita a lectores  | - Ayuda a motores  |
|   de pantalla entender |   de búsqueda a    |
|   la estructura        |   comprender       |
| - Permite navegación   |   el contenido     |
|   más fluida y clara   | - Mejora posiciona-|
| - Beneficia personas   |   miento en buscadores |
|   con discapacidad     | - Reconoce contenido|
|                        |   principal y      |
|                        |   jerarquía        |
+------------------------+--------------------+
|            MEJORA LA EXPERIENCIA DEL USUARIO            |
+-----------------------------------------------------

Diccionario de Etiquetas Semánticas
1: <header>:
La etiqueta <header> define el encabezado de una página web o de una sección específica dentro de ella
¿Qué suele contener?

Logo o nombre del sitio

Título principal (<h1>, <h2>)

Menú de navegación (a veces)

Eslogan o introducción breve

Características clave:

Puedes tener varios <header> en una página (uno por cada sección importante si es necesario).

Ayuda a estructurar el contenido y mejorar la comprensión tanto para usuarios como para buscadores.  
<header>
  <h1>Mi Blog Personal</h1>
  <p>Compartiendo ideas y proyectos</p>
</header>

2: <nav>:
Propósito:
Define una sección de navegación que contiene enlaces a otras páginas o secciones dentro del mismo sitio.
Ejemplo típico: Menú principal o barra de navegación lateral.
Mejora la accesibilidad al permitir que los lectores de pantalla identifiquen rápidamente el área de navegación.

Explica su propósito aquí.

3: <main>:
Propósito:
Representa el contenido principal de la página, el cual está directamente relacionado con el objetivo central del sitio.
Ejemplo típico: Artículos, noticias o productos en una tienda.
Solo debe haber una etiqueta <main> por página. Ayuda a los motores de búsqueda y lectores de pantalla a enfocarse en el contenido más importante.

4: <section>:
Propósito:
Agrupa contenido relacionado dentro de una página. Representa una sección temática, como una categoría, bloque informativo o conjunto de artículos.
Ejemplo típico: Sección de "Servicios", "Testimonios", "Preguntas frecuentes".
Ideal para estructurar contenido y mejorar la claridad del código.

5: <article>:
Propósito:
Define contenido independiente y reutilizable, que tiene sentido por sí mismo.
Ejemplo típico: Un post de blog, una noticia, una publicación de foro.
Perfecto para contenido que se puede compartir de forma individual, como en redes sociales o feeds RSS.

6: <aside>:
Propósito:
Contiene contenido complementario o secundario al contenido principal. Ejemplo típico: Una barra lateral con enlaces relacionados, publicidad o biografía del autor.
Los lectores de pantalla lo identifican como contenido adicional, no esencial.


7: <footer>:
Propósito:
Define el pie de página de una sección o del documento completo.
Ejemplo típico: Información de contacto, derechos de autor, enlaces a políticas o redes sociales.
Puedes usar varios <footer>, uno global y otros dentro de secciones o artículos.



8: <h1> a <h6>
Propósito:
Encabezados jerárquicos, desde el más importante (<h1>) hasta el menos (<h6>).
Ejemplo:
<h1>Bienvenido a mi sitio</h1>
<h2>Acerca de mí</h2>
<h3>Experiencia</h3>

9: <p>
Propósito:
Representa un párrafo de texto. Es el bloque de contenido básico para escribir información.
Ejemplo en HTML: <p>Este es un párrafo informativo sobre el contenido del sitio web.</p>

10:<ul>
Propósito:
Crea una lista desordenada, ideal para ítems sin orden específico.
Ejemplo en HTML: 
  <ul>
  <li>Manzanas</li>
  <li>Peras</li>
  <li>Uvas</li>
</ul>

11: <ol>
Propósito:
Genera una lista ordenada, donde el orden de los elementos sí importa (numeración automática).
Ejemplo en HTML:
<ol>
  <li>Instalar el programa</li>
  <li>Configurar opciones</li>
  <li>Empezar a usar</li>
</ol>

12: <li> 
Propósito:
Representa un ítem dentro de una lista, ya sea ordenada (<ol>) o desordenada (<ul>).
Ejemplo en HTML:
<ul>
  <li>Inicio</li>
  <li>Servicios</li>
  <li>Contacto</li>
</ul>

13: <figure>
Propósito:
Agrupa contenido visual (imagen, gráfico, código) con su descripción o leyenda.
Ejemplo en HTML:
<figure>
  <img src="imagen.jpg" alt="Montañas nevadas">
  <figcaption>Vista de las montañas en invierno</figcaption>
</figure>

14: <figcaption>
Propósito:
Define una leyenda o pie de imagen dentro de un <figure>.
Ejemplo en HTML:
<figcaption>Vista de las montañas en invierno</figcaption>

15: <time>

Propósito:
Indica una fecha u hora específica, útil para artículos, eventos o calendarios.
Ejemplo en HTML:
<time datetime="2025-09-06">6 de septiembre de 2025</time>

16: <mark>
Propósito:
Resalta o destaca texto relevante (como si lo subrayaras con marcador).
Ejemplo en HTML:
<p>Recuerda <mark>entregar el trabajo</mark> antes del viernes.</p>

17: <strong>
Propósito:
Indica que el texto tiene una gran importancia (semánticamente fuerte). Suele mostrarse en negrita.
Ejemplo en HTML: <p><strong>Importante:</strong> No compartas tu contraseña.</p>

18: <em>
Propósito:
Aplica énfasis leve o entonación especial al texto. Se muestra en cursiva.
Ejemplo en HTML: <p>Este producto es <em>especialmente</em> útil para estudiantes.</p>

19: <address>
Propósito:
Define información de contacto del autor o responsable del sitio.
Ejemplo en HTML:
<address>
  Diseñado por Ana López<br>
  Contacto: ana@example.com<br>
  Medellín, Colombia
</address>

20: <strong>
Propósito:
Indica que el texto tiene una gran importancia (semánticamente fuerte). Suele mostrarse en negrita. Ejemplo en HTML: <p><strong>Importante:</strong> No compartas tu contraseña.</p> 
