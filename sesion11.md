<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 11 

# Propiedades CSS más comunes

Las propiedades CSS más comunes son las que se utilizan para controlar el aspecto de los elementos HTML. Estas propiedades incluyen:

# Tamaño y posición:

* width: establece el ancho de un elemento.

* height: establece la altura de un elemento.

* margin: establece el espacio entre un elemento y sus bordes.

* padding: establece el espacio entre el contenido de un elemento y sus bordes.

* float: establece la posición de un elemento en el flujo del documento.

* position: establece la posición absoluta o relativa de un elemento.

Ejemplo:

![Alt text](image-73.png)

Este código CSS establecerá el ancho y la altura del cuerpo del documento en 100% y 100vh, respectivamente. También establecerá el margen y el relleno del cuerpo del documento en 0. El encabezado tendrá un ancho de 50%, una altura de 100px, un margen de 10px a cada lado y un relleno de 20px en todos los lados. El párrafo tendrá un ancho de 50%, una altura de 100px, un margen de 10px en la parte superior e inferior y un relleno de 20px en todos los lados.

# Color y fondo :

* color: establece el color del texto.

* background-color: establece el color de fondo de un elemento.

* background-image: establece una imagen de fondo para un elemento.

* background-repeat: controla cómo se repite la imagen de fondo.

* background-position: controla la posición de la imagen de fondo.

Ejemplo:

![Alt text](image-74.png)

Este código CSS establecerá el color del texto del cuerpo del documento en negro y el color de fondo en blanco. El encabezado tendrá el color del texto en blanco y el color de fondo en negro. El párrafo tendrá una imagen de fondo que se repite verticalmente y se centra.

# Fuente:

* font-family: establece la familia de fuentes de un elemento.

* font-size: establece el tamaño de la fuente de un elemento.

* font-weight: establece el peso de la fuente de un elemento.

* font-style: establece el estilo de la fuente de un elemento.

* font-variant: establece la variante de la fuente de un elemento.

Ejemplo:

![Alt text](image-75.png)

Este código CSS establecerá la familia de fuentes del cuerpo del documento en sans-serif y el tamaño de la fuente en 16px. El encabezado tendrá la familia de fuentes en Times New Roman, serif, el tamaño de la fuente en 24px y el peso de la fuente en negrita. El párrafo tendrá el estilo de la fuente en cursiva y la variante de la fuente en mayúsculas pequeñas.

# Texto:

* text-align: establece la alineación del texto en un elemento.

* text-decoration: establece el subrayado, el tachado o el texto en línea.

* text-transform: establece la transformación del texto en un elemento.

* letter-spacing: establece el espaciado entre letras en un elemento.

![Alt text](image-76.png)

Este código CSS mostrará el encabezado centrado y el párrafo justificado.

# Bordes:

* border-width: establece el ancho del borde de un elemento.

* border-style: establece el estilo del borde de un elemento.

* border-color: establece el color del borde de un elemento.

* border-radius: establece los bordes redondeados de un elemento.

Ejemplo:

![Alt text](image-77.png)

# SeudoClases y SeudoElementos

# SeudoClases

En CSS, las pseudoclases son palabras clave que se añaden a los selectores para especificar un estado especial del elemento seleccionado. Por ejemplo, la pseudoclase :hover se utiliza para aplicar un estilo cuando el usuario pasa el cursor por encima de un elemento.

Las pseudoclases se pueden dividir en dos categorías principales:

* Pseudoclases de estado: Estas pseudoclases especifican el estado actual del elemento, como si está seleccionado, activo o en foco.

* Pseudoclases de acción: Estas pseudoclases especifican el estado del elemento en respuesta a una acción del usuario, como hacer clic o pasar el cursor por encima.

[https://developer.mozilla.org/en-US/docs/Web/CSS/:-moz-broken](https://developer.mozilla.org/en-US/docs/Web/CSS/:-moz-broken)

Orden de las pseudoclases:

El orden en el que se aplican las pseudoclases es importante. Las pseudoclases de estado se aplican primero, seguidas de las pseudoclases de acción.

Por ejemplo, el siguiente código cambiará el color de fondo de un enlace a rojo cuando el usuario lo visite y a verde cuando lo haga clic:

![Alt text](image-78.png)

Este código se traducirá en el siguiente HTML:

![Alt text](image-79.png)

Cuando el usuario visite el enlace por primera vez, tendrá un fondo rojo. Cuando el usuario haga clic en el enlace, tendrá un fondo verde.

Otros ejemplos:

* Cambiar el color de fondo de un párrafo cuando el usuario pasa el cursor por encima:

![Alt text](image-80.png)

* Activar un botón cuando el usuario hace clic en él:

![Alt text](image-81.png)

* Deshabilitar un botón:

![Alt text](image-82.png)

* Activar un enlace cuando el usuario hace clic en él:

![Alt text](image-83.png)

* Cambiar el color de fondo de una lista cuando el usuario hace clic en el elemento:

![Alt text](image-84.png)

# SeudoElementos

Los pseudoelementos son una característica de CSS que permite seleccionar y dar estilo a elementos que no existen en el HTML, o que no son un simple elemento en sí. Por ejemplo, podemos utilizar un pseudoelemento para añadir una flecha al final de un párrafo, o para crear un efecto de sombra debajo de un elemento.

Los pseudoelementos se añaden a los selectores, pero en lugar de describir un estado especial, permiten añadir estilos a una parte concreta del documento. Por ejemplo, el pseudoelemento ::first-line selecciona solo la primera línea del elemento especificado por el selector.

Los pseudoelementos son palabras clave que se añaden a los selectores para seleccionar y dar estilo a elementos que no existen en el HTML, o que no son un simple elemento en sí.

[https://developer.mozilla.org/en-US/docs/Web/CSS/::-moz-color-swatch](https://developer.mozilla.org/en-US/docs/Web/CSS/::-moz-color-swatch)

## Pseudoelementos de contenido:

Ejemplos de pseudoelementos de contenido:

* Establece la primera línea de todos los párrafos (p) en negrita y roja:

![Alt text](image-85.png)

* La primera letra estará en negrita, en color crimson y un tamaño de 60 píxeles

![Alt text](image-86.png)

* Añadir una flecha al final de un párrafo:

![Alt text](image-87.png)

## Pseudoelementos de posición:

Ejemplos de pseudoelementos de posición:

::selection

* Cambiar el color de fondo del texto seleccionado:

![Alt text](image-88.png)

::before-after:

Añadir contenido antes y después del elemento.

h1::before {
    content: url("https://icons.iconarchive.com/icons/gartoon-team/gartoon-action/48/dialog-apply-icon.png");
    
}



# Actividad: Propiedades CSS, SeudoClases, SeudoElementos y Reglas @css

Crear un documento HTML y probar cada uno de los ejemplos


