<!-- No borrar o modificar -->
[Inicio](./index.md)

## Sesión 3 


<!-- Su documentación aquí -->

## DESARROLLO

### Actividad: Adición de contenido multimedia en un sitio web utilizando etiquetas HTML5

Completa el siguiente código HTML añadiendo el contenido multimedia correspondiente en cada sección:

* 4 Imagenes
* 2 Videos
* 4 Audios
* 2 Inline Frame

Utiliza encabezados para títulos en cada elemento (<h1>...<h6>).

Crea una descripción para cada elemento utilizando párrafos (<p>).

Además, puedes emplear las siguientes etiquetas para mejorar la estructura y estilo de tu contenido:

* Usa <strong> para resaltar texto importante.

* Utiliza <br> para insertar saltos de línea si es necesario.

* Agrega <span> para aplicar estilos específicos a porciones de texto.

* Emplea <i> para enfatizar o dar énfasis a palabras o frases.

* Utiliza <u> para subrayar texto cuando sea necesario.

* Considera el uso de <div> para crear secciones o contenedores para tu contenido, lo que puede facilitar la organización y el diseño de la página. 

## Plantilla Inicial

<!DOCTYPE html>

<html>

<head>
    <title>Etiquetas Multimedia HTML5</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #333333;
            color: white;
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #ddd;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: blue;
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>Etiquetas Multimedia HTML5</h1>
        <h3>La forma más fácil de agregar multimedia a tus sitios web</h3>
    </header>

    <section>
        <h2>Imágenes</h2>
        <p>Contenido sobre imágenes...</p>
    </section>

    <section>
        <h2>Videos</h2>
        <p>Contenido sobre videos...</p>
    </section>

    <section>
        <h2>Audios</h2>
        <p>Contenido sobre audios...</p>

    </section>

    <section>
        <h2>iFrames</h2>
        <p>Contenido sobre iframes...</p>
    </section>

    <footer>
        Nombre Completo
        <br>
        <br>
        CESDE
        <br>
        <br>
        &copy;2023
    </footer>

</body>

</html>

## Semántica y Estructura de la Plantilla

El código HTML y CSS proporcionado describe un sitio web que trata sobre etiquetas multimedia en HTML5. A continuación, se desglosa la semántica y estructura del sitio:

< !DOCTYPE html>: Esto define el tipo de documento como HTML5.

< html>: La etiqueta raíz que envuelve todo el contenido HTML del sitio.

< head>: Aquí se encuentran las metainformaciones y enlaces a recursos externos. En este caso, se define el título de la página y se incluye un bloque <style> para agregar reglas de estilo CSS.

< title>: Establece el título de la página en la pestaña del navegador.

< style>: Contiene reglas de estilo CSS que afectan al diseño y la apariencia del sitio.

< body>: Aquí se coloca el contenido principal visible de la página.

< header>: Sección de encabezado que contiene el título principal y un subtítulo.

< h1> y <h3>: Encabezados de nivel 1 y 3, respectivamente, que proporcionan títulos jerárquicos y estructuran la información del encabezado.

< section>: Define una sección de contenido temático. Se utilizan para agrupar información relacionada.

< h2>: Encabezado de nivel 2 que se utiliza para los títulos de las secciones de contenido.

< p>: Párrafo de texto que contiene contenido informativo sobre las imágenes, videos, audios y iframes.

< footer>: Pie de página que contiene información de autoría y derechos de autor. Incluye saltos de línea <br> para separar las líneas de texto.

### En cuanto al estilo, el CSS define reglas para la apariencia visual del sitio:

* La fuente del cuerpo del sitio es Arial o una fuente sans-serif en caso de que Arial no esté disponible.

* El encabezado (<header>) tiene un fondo oscuro, texto blanco y un espacio de relleno.

* Cada sección (<section>) tiene un borde, un espacio de relleno y un margen inferior.

* Los encabezados de nivel 1 y 3 están centrados.

* Los encabezados de nivel 2 (<h2>) tienen color azul.

* El pie de página (<footer>) tiene un fondo oscuro, texto blanco, espacio de relleno y está centrado.

**Este sitio utiliza HTML5 y CSS para presentar información sobre etiquetas multimedia en HTML5, con una estructura semántica que utiliza encabezados, párrafos y secciones para organizar y presentar el contenido. El estilo CSS proporciona una apariencia visual coherente y agradable.** 

## DESARROLLO

<!DOCTYPE html>

<html>

<head>
    <title>MUNDO PARANORMAL</title>
    <style>
        body {
            font-family: Arial, sans-serif;
        }

        header {
            background-color: #15259c;
            color: rgb(8, 8, 8);
            padding: 20px;
            text-align: center;
        }

        section {
            border: 1px solid #000000;
            padding: 20px;
            margin-bottom: 20px;
        }

        h2 {
            color: rgb(7, 7, 7);
        }

        footer {
            background-color: #333;
            color: white;
            padding: 20px;
            text-align: center;
        }
    </style>
</head>

<body>

    <header>
        <h1>MUNDO PARANORMAL</h1>
        <h3>Tenemos para Colombia en 2023</h3>

        <header>Supuesto viajero del tiempo hizo horribles predicciones para julio, agosto y septiembre</header>


    </header>

    <section>
        <h1>Imagenes</h1>
        <strong>Esta pagina habla sobre el mundo astral</strong>

        <img src="horoscopo.jpg" alt="" width=" 400">
        <p>predicciones que lanzaron los astrólogos en materia económica, salud y lo que ocurrirá</p>
        <h2>se predijo que los científicos finalmente podrán crear la cura para dos tipos de cáncer y comentó este como
            ocurriría. “Se hace a través de la glándula pituitaria de una ardilla y conducirá al descubrimiento de otras
            curas para el cáncer.</h2>

        <img src="astrology-history-1.jpg" alt="" width=" 500">
        <h2>En cuanto al deporte, Mhoni aseguró que nuestro país se llevará el triunfo en la Copa Oro. “Ahora van a
            estar arriba, vienen cambios importantes en la Selección Mexicana, en cuestiones de jugadores, de capitanes,
            cambios que van a empezar a traer personas muy valiosas para el Mundial 2026</h2>
        <p>Ella es colombiana</p>

        <img src="SesioNew.jpg" alt="" width=" 500">
        <h2>El mundo le dio la bienvenida a 2023 y con el nuevo año, llegan las
            predicciones el presidente
            Gustavo Petro durante el año que con apenas comenzar hay buenos mensajes para este mundo, trajo para los
            colombianos</h2>

        <img src="Dia despertar.avif" alt="" width=" 500">
        <h2>En diferentes videos el viajero del tiempo ha comentado que viene del año 2671, que mensaje nos dijo</h2>
        <h3>Tik-Tok es la tendencia en redes</h3>
        <p>Otra de sus presiones es que 23 de ese mes, un avión de Spirit Airlines sufriría un accidente en la mitad del
            océano Atlántico. Por último, agregó que el telescopio James Webb el 7 de octubre podrá capturar una
            “criatura gigante del espacio” absorbiendo la energía de las estrellas cercanas. Esto conducirá a la
            desaparición de la Tierra y la necesidad de establecerse en otro planeta.</p>


    </section>

    <section>
        <title>Videos</title>

        <video src="fuerza interior.mp4" controls width="500" height="300"></video>
        <h1>Tu fuerza interior</h1>
        <p>Tu eres el potencial</p>


        <video src="Consulta con el viejo.mp4" controls width="500" height="300"></video>
        <h1>Consultas gratis con el primer registro</h1>
        <p>Tenemos la lectura del tarot</p>



    </section>

    <section>
        <title>Audios Aqui</title>


        <h1>Musica para descansar</h1>

        <audio src="despertar siempre.mp3" controls></audio>
        <h2>Despertar</h2>
        <p>Inicia el camino para despertar tus sentidos</p>

        <audio src="dentroBosque.mp3" controls></audio>
        <h2>Bosque</h2>
        <p>Aca te traemos el sonido del bosque para disfrutar en armonia</p>

        <audio src="Dia despertar.avif" controls></audio>
        <h2>Es el nuevo camino del despertar</h2>
        <p>Vive la vida en amor</p>

        <audio src="Lluvia y noche.mp3" controls></audio>
        <h2>La lluvia sera el mejor aliado para descansar</h2>
        <p>Si necesitas la lluvia para dormir, aca la puedes escuchar con un solo clic</p>
        <h3>lluvia en noche</h3>

    </section>

    <section>
        <h1>Video</h1>

        <h2>Marina tiene un mensaje para ti</h2>
        <iframe src="https://www.youtube.com/watch?v=RPU_3YuhaYM" width="500" height="300"></iframe>
        <p>Consultas mes de agosto</p>


        <h2>REVELACIÓN CASO ÁLVARO URIBE VELEZ</h2>
        <iframe src="https://www.youtube.com/watch?v=F8Y4kwxFODc&t=1s" width="500" height="300"></iframe>
        <p>En este live te cuento, cómo los astros ven el futuro del reconocido político colombiano Alvaro Uribe Velez,
            expresidente de Colombia en el periodo 2002 al 2010</p>


    </section>

    <footer>

        <br>RODRIGUEZ
        <br>JHONATAN
        CESDE
        <br>Bello
        <br>
        &copy;2023
    </footer>

</body>

</html>

[Siguiente](./sesion4.md)