# Maquetado de Lyft, ejercicio para Laboratoria

## Objetivo

El reto consiste en replicar el sitio de **Lyft**, este será el resultado
a lograr:

![Lyft Website](docs/fullpage.png)

## Realización

Para la realización del reto, cree una página web dividida en 7 secciones, cada una con una id diferente para poder identificarlas mejor a la hora de manipular su estilo: 

* La primera sección es un `div` de id `principal`, esta contiene una barra `nav` transparente con el logo y links, un `div` con id `white-box` de fondo blanco con título, un input, párrafos y botones dentro. Esta sección tiene de `background` un gif.

* La segunda sección es un `section` de id `box-two`. Con 3 párrafos y sus respectivos títulos alineados a la izquierda y un div a su derecha que no contiene nada pero tiene de fondo la imagen de un celular. A esta sección le dimos un fondo en gradiente, y además una sombra para que arriba (y por encima de la sección anterior) diera el efecto se que el gradiente sigue hasta la transparencia.

* La tercera, cuarta y quinta sección son `section id="box-three"`, `section id="box-four"` y `section id="box-five"`, cada una contiene un video (que determina la altura de la sección) y a su lado un párrafo descriptivo de dicho video. El alineado del video es hacia la derecha a excepción de `#box-four` donde se alinea a la izquierda.

* La sexta y última sección es el `footer`, dividido en un div `#list`, un div `#icons`, una `hr` y un `p` para poder manipular mejor el estilo de cada uno, `#list` contiene 4 listas con links (la última con imágenes para adquirir la app en diferentes sistemas), `#icons` contiene una lista horizontal con links a redes sociales y `p` el mensaje de Copyright.

Para el CSS traté de usar menor cantidad de id o clases, así que el plan fue acceder a los diferentes elementos del HTML a través de otros selectores y pseudoselectores, como el de descendencia, first-of-type o first-child, sin contar los :hover o los :focus para estados específicos de mis links o inputs.
