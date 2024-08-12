# Recordando
## Primeros pasos
### Crea un poema corto describiendo cómo HTTP envía datos entre computadoras.
 Es un protocolo de transferencia de la capa de aplicación basado   
 en texto y se considera la base para la comunicación   de datos   
 entre los dispositivos de una red.   
 Durante el proceso de solicitud-respuesta, HTTP usa reglas y estándares   
 predefinidos para el intercambio de información.
### Describe como los archivos HTML, CSS y JS son “analizados” en el navegador.
* El navegador va a buscar la mayor parte de los recursos vinculados al   
documento HTML, como las imágenes y los videos incrustados... ¡y también  
 el CSS vinculado! JavaScript aparece un poco más adelante en el proceso,   
 pero no vamos a hablar de ello aún para evitar complicar las cosas.
* El navegador analiza el CSS y ordena en diferentes «cubos» las  
 diferentes reglas según el tipo de selector. Por ejemplo, elemento,  
  clase, ID, y así sucesivamente. Para cada tipo de selector que  
   encuentre, calcula qué reglas deben aplicarse y a qué nodos en el DOM  
    se les aplica el estilo según corresponda (este paso intermedio se  
     llama árbol de renderización).
* El árbol de renderización presenta la estructura en que los nodos deben   
 aparecer después de aplicarle las reglas.
* En la pantalla se muestra el aspecto visual de la página (esta etapa se 
 llama pintura).
### ¿Cómo puedes encontrar imágenes para agregar a una página web?
Accede al archivo HTML donde deseas insertar la imagen y añade la etiqueta img.  
 Incluye el atributo img src para definir la fuente de la imagen. Añade los  
  atributos de anchura y altura para definir cómo debe mostrar la imagen el  
   navegador. Inserta el atributo alt para describir la imagen.
### ¿Cómo creas una String en comparación con un Number en Javascript?
Para crear un string el contenido debe estar entre comillas dobles o simples  
y los number simplemente los digitas.
### ¿Qué es una Variable y por qué son importantes en JavaScript?
Las variables son la manera como le damos nombre a un valor para poder reusarlo,  
 actualizarlo o simplemente registrarlo. Las variables se pueden usar para   guardar cualquier tipo de dato.
## Introducción a HTML
### ¿Qué es un atributo en HTML?
Son valores adicionales que configuran los elementos o ajustan su comportamiento de diversas formas para cumplir los criterios de los usuarios.
### Describe la anatomía de un elemento en HTML.
comienza con una etiqueta de apertura, contenido y una etiqueta de cierre.
### ¿Cuál es la diferencia entre las etiquetas < article > y < section >?
El elemento < article > especifica un contenido independiente y autónomo. El elemento < section > define la sección en un documento.
### Qué elementos se incluyen en una página web “típica”?
* Encabezado.
* Menú
* Imágenes.
* Contenido del sitio web.
* Página de inicio.
* Pie de página.
* Logo.
* CTA o llamados a la acción.
### ¿Cómo influyen los metadatos en el Posicionamiento en buscadores (SEO)?
Los metadatos proporcionan este elemento crucial, lo que le permite comprender mejor la calidad, la relevancia y el valor de sus datos. Los metadatos le ayudan a detectar datos, comprender las relaciones entre estos, realizar un seguimiento de cómo se utilizan y evaluar el valor y los riesgos asociados a su uso.
### ¿Cómo se utliza la etiqueta <meta> en HTML cuando se quiere especificar metadatos?
Las etiquetas meta en HTML sirven como piezas importantes de información para los motores de búsqueda. Se utilizan para describir elementos HTML y comunicar el contenido de un sitio web para los motores de búsqueda.
## Miscelánea
### ¿Cuál es el primer paso para diseñar una página web?
Planificar la idea de tu sitio web. Sobre de que tratara y aquienes se dirigira, un bosquejo de como se vera, colores a usar, fuentes de letras, imagenes y videos, estilos, vinculos entre otras cosas. 
### ¿Cuál es la pregunta más importante que se debe responder al diseñar una página web?
¿Qué es exactamente lo que quiero lograr?
### ¿Por qué se debe utilizar un elemento < h1 > en vez de un <span> para mostrar un título de primer nivel?
por que asi sera mas facil que el navegador tetecte tu pagina web.
### ¿Cuáles son los beneficios de utilizar etiquetas semánticas en nuestro HTML?
Estara mejor ordenada y sera mas facil que el navegador redenterice tu codigo por que le sera mas legible para el, por la tanto tu calificacon sera buena, recomendada y mas facil de encontrar.
### Describe 2 cosas que requieran de JavaScript en el navegador.
* Hacer páginas web interactivas.
* Aplicaciones web
### ¿Cómo se puede añadir JavaScript a un documento en HTML?
Mediante una etiqueta < script >