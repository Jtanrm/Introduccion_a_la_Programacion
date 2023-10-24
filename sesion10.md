<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 10 

## Propiedades de posicionamiento de CSS

![Alt text](image-40.png)

* La propiedad position de CSS determina cómo se posiciona un elemento en un documento. Hay cinco valores diferentes para la propiedad position:

* static: El elemento se posiciona de acuerdo con el flujo normal del documento.

* absolute: El elemento se posiciona de forma absoluta, es decir, se coloca en una posición específica en la página, independientemente del flujo normal del documento.

* relative: El elemento se posiciona de forma relativa, es decir, se desplaza desde su posición original en el flujo normal del documento.

* fixed: El elemento se posiciona de forma fija, es decir, se coloca en una posición específica en la ventana del navegador y permanece en esa posición incluso cuando el usuario se desplaza por la página.

## Propiedades de visualización de CSS

![Alt text](image-41.png)

La propiedad display de CSS determina cómo se muestra un elemento en una página web. Hay cuatro valores diferentes para la propiedad display:

* block: El elemento se muestra como una caja de bloque, que ocupa toda la anchura de su contenedor y se muestra en una nueva línea.

* inline: El elemento se muestra como una caja de línea, que se muestra en la misma línea que el texto circundante.

* inline-block: El elemento se muestra como una caja de línea, pero puede tener una anchura y una altura definidas.

* none: El elemento no se muestra en la página web.

## Ejemplos de uso de las propiedades de posicionamiento y visualización de CSS

* Elemento posicionado de forma absoluta:

![Alt text](image-42.png)

Este código posicionará el elemento .absoluto a 10 píxeles de la parte superior y izquierda de la ventana del navegador.

* Elemento posicionado de forma relativa:

![Alt text](image-43.png)

Este código posicionará el elemento .relativo a 10 píxeles de su posición original en el flujo normal del documento.

* Elemento posicionado de forma fija:

![Alt text](image-44.png)

Este código posicionará el elemento .fijo a 10 píxeles de la parte superior y izquierda de la ventana del navegador y permanecerá en esa posición incluso cuando el usuario se desplaza por la página.

* Elemento posicionado de forma sticky:

![Alt text](image-45.png)

Este código posicionará el elemento .sticky a 10 píxeles de la parte superior de la ventana del navegador cuando el usuario se desplaza por la página, pero se volverá a comportar de forma normal cuando el usuario alcance el borde superior de la ventana del navegador.

## Ejemplo de HTML donde se usan todas las clases CSS anteriores

<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de posicionamiento y visualización de CSS</title>
  <style>
    .bloque {
      display: block;
      width: 200px;
      height: 100px;
      background-color: red;
    }

    .en línea {
      display: inline;
      width: 100px;
      height: 50px;
      background-color: green;
    }

    .inline-bloque {
      display: inline-block;
      width: 100px;
      height: 50px;
      background-color: blue;
    }

    .absoluto {
      position: absolute;
      top: 100px;
      left: 100px;
      background-color: yellow;
    }

    .relativo {
      position: relative;
      top: 100px;
      left: 100px;
      background-color: orange;
    }

    .fijo {
      position: fixed;
      top: 100px;
      left: 100px;
      background-color: pink;
    }

    .sticky {
      position: sticky;
      top: 100px;
      left: 100px;
      background-color: purple;
    }
  </style>
</head>
<body>
  <h1>Ejemplo de posicionamiento y visualización de CSS</h1>

  <div class="bloque">
    Este es un elemento de bloque.
  </div>

  <span class="en línea">
    Este es un elemento de línea.
  </span>

  <div class="inline-bloque">
    Este es un elemento de línea con ancho y altura definidos.
  </div>

  <div class="absoluto">
    Este elemento está posicionado de forma absoluta.
  </div>

  <div class="relativo">
    Este elemento está posicionado de forma relativa.
  </div>

  <div class="fijo">
    Este elemento está posicionado de forma fija.
  </div>

  <div class="sticky">
    Este elemento está posicionado de forma sticky.
  </div>
</body>
</html>


Este ejemplo muestra cómo las propiedades de posicionamiento y visualización de CSS afectan a la apariencia de los elementos HTML.

Elemento de bloque: El elemento .bloque se muestra como una caja de bloque, que ocupa toda la anchura de su contenedor y se muestra en una nueva línea.

Elemento de línea: El elemento .en línea se muestra como una caja de línea, que se muestra en la misma línea que el texto circundante.

Elemento de línea con ancho y altura definidos: El elemento .inline-bloque se muestra como una caja de línea con ancho y altura definidos.

Elemento posicionado de forma absoluta: El elemento .absoluto se posiciona de forma absoluta, es decir, se coloca en una posición específica en la página, independientemente del flujo normal del documento.

Elemento posicionado de forma relativa: El elemento .relativo se posiciona de forma relativa, es decir, se desplaza desde su posición original en el flujo normal del documento.

Elemento posicionado de forma fija: El elemento .fijo se posiciona de forma fija, es decir, se coloca en una posición específica en la ventana del navegador y permanece en esa posición incluso cuando el usuario se desplaza por la página.

Elemento posicionado de forma sticky: El elemento .sticky se posiciona de forma fija cuando el usuario se desplaza por la página, pero se vuelve a comportar de forma normal cuando el usuario alcanza el borde superior o inferior de la ventana del navegador.

## La propiedad z-index

![Alt text](image-46.png)

La propiedad z-index de CSS especifica el orden de apilamiento de un elemento posicionado y sus descendientes. Cuando varios elementos se superponen, los elementos con mayor valor z-index cubren aquellos con menor valor.

El valor de z-index puede ser un número entero positivo o negativo. Un valor de z-index de 0 significa que el elemento se comporta de forma normal, siguiendo el flujo normal del documento.

Por ejemplo, el siguiente código CSS establece el valor z-index de un elemento a 10:

![Alt text](image-47.png)

Este código hará que el elemento .elemento se muestre en la parte superior de cualquier otro elemento posicionado en la página, independientemente de su posición original en el flujo normal del documento.

Aquí hay un ejemplo de cómo se puede usar la propiedad z-index para crear un efecto de tooltip:

<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Ejemplo de z-index</title>
  <style>
    .tooltip {
      position: absolute;
      top: 100px;
      left: 100px;
      z-index: 10;
      background-color: lightgray;
      padding: 10px;
      border-radius: 5px;
      display: none;
    }

    .elemento {
      position: relative;
      cursor: pointer;
    }

    .elemento:hover .tooltip {
      display: block;
    }
  </style>
</head>
<body>
  <h1>Ejemplo de z-index</h1>

  <div class="elemento">
    Este es un elemento con un tooltip.
  </div>

  <div class="tooltip">
    Este es el contenido del tooltip.
  </div>
</body>
</html>


En este ejemplo, el elemento .elemento tiene un tooltip que se muestra cuando el usuario lo pasa el cursor por encima. El tooltip está posicionado de forma absoluta y tiene un valor z-index de 10. Esto significa que el tooltip siempre se mostrará en la parte superior del elemento .elemento, independientemente de su posición original en el flujo normal del documento.

La propiedad z-index es una herramienta poderosa que se puede usar para crear una variedad de efectos de visualización.


----------------------------------------


## Actividad: Propiedades de posicionamiento de CSS

Objetivo:

Aplicar las propiedades de posicionamiento de CSS para crear diferentes efectos de visualización.

Instrucciones:

2. Crea un nuevo archivo HTML y CSS.

3. En el archivo HTML, crea una estructura básica de página web con dos elementos div.

4. En el archivo CSS, define las propiedades de visualización y posicionamiento de los elementos div.






