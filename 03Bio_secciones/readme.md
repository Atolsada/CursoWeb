4.3.9 The address element html5 - estructuras semánticas, elementos del "sectioning" -

<!-- etiquetas html [https://developer.mozilla.org] -->

<!-- Cambiado 170518 instalado markdown, y editadas las etiquetas por &lt; antes de cada una para que no las tome como etiquetas y "escapemos los elementos" markdawn vale para previsualizar el fichero y por ejemplo para cuando tenemos un fichero como uans intrucciones y que "se vea bien" explicado -->

## header ## 
<!-- pueden existir varios -->
El elemento de HTML Header &lt;header> representa un grupo de ayudas introductorias o de navegación. Puede contener algunos elementos de encabezado, pero también otros elementos como un logo, una sección que aglutine secciones de encabezados, una formulario de búsqueda o cosas parecidas.

## nav ##

The HTML &lt;nav> element represents a section of a page whose purpose is to provide navigation links, either within the current document or to other documents. Common examples of navigation sections are menus, tables of contents, and indexes. (Crea el menú de navegación)

## article ##

El Elemento article de HTML &lt;article> representa una composición auto-contenida en un documento, página, una aplicación o en el sitio, que se destina a distribuir de forma independiente o reutilizable, por ejemplo, en la sindicación (rss, atom[mala traducción? paralabra idónea sería suscripción]). Podría ser un mensaje en un foro, un artículo de una revista o un periódico, una entrada de blog, un comentario de un usuario, un widget interactivo o gadget, o cualquier otro elemento independiente del contenido.

## section ##

El elemento de HTML section &lt;section> representa una sección genérica de un documento. Sirve para determinar qué contenido corresponde a qué parte de un esquema. Piensa en el esquema como en el índice de contenido de un libro; un tema común y subsecciones relacionadas.  Es, por lo tanto, una etiquéta semántica. Su funcionalidad principal es estructurar semánticamente un documento a la hora de ser representado por parte de un agente usuario. Por ejemplo, un agente de usuario que represente el documento en voz, podría exponer al usuario el índice de contenido por niveles para navegar rápidamente por las distintas partes.

## aside ##

El Elemento HTML Aside &lt;aside representa una sección de una página que consiste en contenido que está tangencialmente relacionado con el contenido que le rodea, que podría ser considerado independiente de ese contenido. Estas secciones son a menudo representadas como barras laterales o como inserciones y contienen una explicación al margen como una definición de glosario, elementos relacionados indirectamente, como publicidad, la biografía del autor, o en aplicaciones web, la información de perfil o enlaces a blogs relacionados.

## footer ##

El Elemento HTML Footer &lt;footer representa un pie de página para el contenido de sección más cercano o el elemento  raíz de sección (p.e, su ancestro mas cercano &lt;article, &lt;aside, &lt;nav, &lt;section,&lt;blockquote, &lt;body, &lt;details, &lt;fieldset, &lt;figure, &lt;td. Un pie de página típicamente contiene información acerca de el autor de la sección, datos de derechos de autor o enlaces a documentos relacionados.

## addres ##

El elemento HTML &lt;address aporta información de contacto para su &lt;article más cercano o ancestro <body>; en el último caso lo aplica a todo el documento.

## main ## 
<!-- novedad de las últimas versiones de html5, no es obligatorio de momento ponerlo -->
El elemento HTML &lt;main  representa el contenido principal del &lt;body de un documento o aplicación. El área principal del contenido consiste en el contenido que está directamente relacionado, o se expande sobre el tema central de un documento o la funcionalidad central de una aplicación. Este contenido debe ser único al documento, excluyendo cualquier contenido que se repita a través de un conjunto de documentos como barras laterales, enlaces de navegación, información de derechos de autor, logos del sitio y formularios de búsqueda (a menos, claro, que la función principal del documento sea un formulario de búsqueda).

Nota: no debe haber más de un elemento &lt;main en un documento, y este no debe ser descendiente de un elemento  &lt;article, &lt;aside, &lt;footer, &lt;header, o &lt;nav.

body <!-- sólo uno, igual que main, el resto tantos como queramos -->
h1 ...