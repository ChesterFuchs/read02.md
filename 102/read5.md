# Diseño de paginas web con CSS
## ¿Cuál es el propósito de CSS?
Crear reglas para decirle a tu sitio web cómo quieres mostrar la información. Es decir, permite generar el diseño visual de páginas web e interfaces de usuario.
lo cual se hace sobre un documento escrito en un lenguaje de marcado como puede ser HTML.
## ¿Cuáles son las tres formas de insertar CSS en tu proyecto?
- CSS externo  
    ¡Con una hoja de estilo externa, puedes cambiar la apariencia de un sitio web completo modificando solo un archivo!

    Cada página HTML debe incluir una referencia al archivo de hoja de estilo externa dentro del elemento <**link**>, dentro de la sección de encabezado.

    Una hoja de estilo externa se puede escribir en cualquier editor de texto y debe guardarse con una extensión .css.

    El archivo .css externo no debe contener ninguna etiqueta HTML.

- CSS interno  
    Se puede utilizar una hoja de estilo interna si una sola página HTML tiene un estilo único.

    El estilo interno se define dentro del elemento <**style**>, dentro de la sección de encabezado.

- CSS en línea
    Se puede utilizar un estilo en línea para aplicar un estilo único a un solo elemento.

    Para utilizar estilos en línea, agregue el atributo style al elemento correspondiente. El atributo style puede contener cualquier propiedad CSS.
## Escribe un ejemplo de una regla CSS que daría texto rojo a todos los elementos <p>
      p {  
        color: red;  
      }
