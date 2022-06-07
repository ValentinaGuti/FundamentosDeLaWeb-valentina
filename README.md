# FundamentosDeLaWeb-valentina

1)En pocas palabras, Internet es una gran red de computadoras que están conectadas y pueden comunicarse entre sí. La web está formada por ordenadores a los que llamamos clientes y servidores.

2)Cuando un cliente desea acceder a una página web (como Google o Facebook), se descarga una copia de la página web desde el servidor a la máquina del cliente para que se muestre en el navegador web del usuario.

-El servidor al que intentamos llegar responde con algún tipo de contenido. Tal vez sean resultados de búsqueda, el perfil de un amigo o contenido de video. En todos estos casos, este contenido se proporciona al cliente como una combinación de HTML, CSS y JavaScript..

<p>Este es un pàrrafo.</p>
<p>Este es un segundo pàrrafo.</p>

Listas desordenadas (viñetas): <ul> con <li> anidada que contiene los elementos de la lista

Listas ordenadas (numeradas): <ol> con <li> anidada que contiene los elementos de la lista

Tablas: <table> con <tr>anidada (filas de tabla) que contiene anidadas <th> o <td> para el encabezado o las celdas de datos regulares, respectivamente

Película	Año	  Calificación
Up	       2009	       PG
Matrix	   1999	       R

(Padre, Hijo, Hermano)

En los ejemplos de código anteriores, las etiquetas como <li> o <td> siempre se usan dentro de otras etiquetas como

<ul>o <tr>.Cuando una etiqueta HTML está anidada dentro de otra etiqueta, llamamos a la etiqueta interior “hijo” de la etiqueta exterior. Las etiquetas hijo adyacentes, como las <li> múltiples, se consideran hermanas entre sí

Imágenes: <img>

Atributos importantes: src(la ruta del archivo de imagen)alt
<img src="panda.jpg" alt="panda pic">

Atributos importantes: src(la ruta del archivo de video) y
controls
<video src="monkey2.mp4" controls></video>

Si queremos que un video se reproduzca de forma automática en navegadores modernos, debemos incluir autoplay, loop y muted.
<video src="monkey2.mp4" autoplay loop muted></video>

1. ¿Cuál es el lenguaje de marcado principal para crear páginas web y otra información que se puede mostrar en un navegador web?
HTML

2. El texto entre <body> y </body> describe la parte visible de la página web. ¿Verdadero o falso?
Verdadero

3. En el ejemplo de código anterior, ¿Qué etiqueta es el padre de los elementos de la lista <li>?
<ul>

4. En el ejemplo de código anterior, ¿qué etiqueta es el padre de la etiqueta de anclaje <a>?
<p>
5. ¿Cuál es la función de la etiqueta anchor <a> en el ejemplo anterior?
Para proporcionar un hipervínculo a la URL definida en el atributo href


psc:
<html> es el padre de <head> y <body>
<head> es el primer hijo de <html>
<body> es el último hijo de <html>
<head> tiene un hijo: <title>
<body> tiene dos hijos: <h1> y <p>"
<h1> , <p> , <head> y <body>  son hermanos.