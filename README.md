En este codigo se realizo una practica con HTML. Esta practica consistio en crear una pagina web de la modalidad de Mecatronica, los codigos fueron enseñados en clase, se enseñaron las bases para manejar el programa de manera efectiva.

Explicación de lo hecho en HTML.

DOCTYPE y etiqueta 
//<html>: Se especifica que el documento es un archivo HTML5 y se define el lenguaje como inglés.


Sección 
//<head>: Contiene información sobre el documento:
//<meta charset="UTF-8">: Define la codificación de caracteres como UTF-8, que soporta caracteres especiales.
//<meta name="viewport" content="width=device-width, initial-scale=1.0">: Hace que la página sea responsiva en dispositivos móviles.
//<link rel="stylesheet" href="./style.css">: Enlaza una hoja de estilos CSS externa para dar formato a la página.
//<title>: Establece el título de la pestaña del navegador como "PORTAFOLIO MECATRONICA".

Sección
//<body>: Contiene el contenido visible de la página:
//<header>: Agrupa el contenido de la cabecera.
//<div id="contenedor_cabecera">: Contiene el logotipo del SENA y un título principal.
//<img class="logo">: Imágenes que actúan como logotipos.
//<h1 id="titulo">: El título principal del portafolio.
//<div id="contenedor_banner">: Contiene una descripción en un párrafo.
//<p id="descripción">: Un extenso texto que incluye una letra de canción, lo que puede ser un elemento artístico o creativo en el portafolio.



Explicación de lo hecho en CSS.


//:root: Define la fuente base para toda la página como Arial, Helvetica o sans-serif, asegurando una apariencia consistente en todos los elementos.
//.logo: Establece un ancho de 100 píxeles para las imágenes con la clase "logo", asegurando que todas las imágenes de logotipo tengan un tamaño uniforme.



#contenedor_cabecera:

//width: 100%: Hace que el contenedor ocupe todo el ancho de la página.
//display: flex: Utiliza Flexbox para alinear los elementos dentro del contenedor.
//justify-content: space-evenly: Distribuye los elementos de manera uniforme, dejando espacio igual entre ellos.
//align-items: center: Alinea los elementos verticalmente al centro del contenedor.


#contenedor_banner:

//display: flex: También utiliza Flexbox para alinear su contenido.
//justify-content: center y align-items: center: Centran el contenido en ambas direcciones (horizontal y vertical).
//background-image: Establece una imagen de fondo desde la ruta especificada.
//height: 500px: Define la altura del contenedor en 500 píxeles.
//background-size: cover: Asegura que la imagen de fondo cubra todo el contenedor.
//background-repeat: no-repeat: Evita que la imagen se repita si no llena todo el espacio.


#descripción:

//color: red: Establece el color del texto en rojo.
//font-family: cursive: Aplica una fuente cursiva al texto, dándole un estilo más artístico.

