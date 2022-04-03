# Cabeceras

Comienzan por tantos \# como tamaño de cabecera hasta h6 y espues un espcio en blanco y el titulo
\# Esto es h1
# Esto es h1

\#\# Esto es h2
## Esto es h2

\#\#\# Esto es h3
### Esto es h3

\#\#\#\# Esto es h4
#### Esto es h4

#\#\#\#\# Esto es h5
##### Esto es h5

\#\#\#\#\#\# Esto es h6
###### Esto es h6

# Cursiva y negrita

Para escribir algo en cursiva, se escribe entre \* o \_   
*cursiva*  
_cursiva_

Para escribir algo en negrita, se escribe entre \*\* o \_\_  
**negrita**  
__negrita__  

Para escribir algo en negrita y cursiva, se escribe entre \*\*\* o \_\_\_  
***cursiva y negrita***  
___cursiva y negrita___

# Tachar

Paratachar texto debe ir escrito entre 4 ~, 2 al principio y 2 al final. 

~~hola~~

# Citas abreviadas

Algunos procesadores Markdown también soportan una sintaxis abreviada para las citas. Podrás agregarlas en línea usando dos comillas dobles tanto al principio como al final de la cita:

Esto es una ""cita""

# Listas de tareas

Para ello solo es necesario guion, espacio , abrir corchete, dejar un espacio, y cerrar corchete, si queremos marcarla entrecorchetes ponemos una x.

Ejemplo:

- [x] Correr

- [ ] Comprar pan

- [ ] Leer

# Listas

lista numerada: cada elemento comienza por numero seguido de . espacio en blanco y el contenido

1. a
2. b


lista sin numerar: cada elemento comienza por  \- , * o + espacio en blanco y el contenido

* a
* b
* c

- a
- b
- c

+ a
+ b
+ c


* a

* b

* c

Los elementos de la lista pueden consistir en múltiples párrafos. Cada párrafo posterior en un elemento de la lista debe estar sangrado por 4 espacios o una pestaña:


1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.


Para colocar una cita en bloque dentro de un elemento de la lista, los delimitadores de la cita (>) en bloque deben indentarse:

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
To put a code block within a list item, the code block needs to be indented twice — 8 spaces or two tabs:

*   A list item with a code block:

        \<code goes here\>



Para generar listas anidadas dentro de otras, simplemente tendrás que añadir **cuatro espacios en blanco antes del siguiente *, - o +.

- Elemento de lista 1
- Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        - Elemento de lista 5
        - Elemento de lista 6


1. Elemento de lista 1
2.  Elemento de lista 2
    - Elemento de lista 3
    - Elemento de lista 4
        1. Elemento de lista 5
        2. Elemento de lista 6
        
# Listas de definiciones

Muchos procesadores Markdown también aceptan listas de definiciones, que se componen de una serie de términos y sus correspondientes definiciones.

Para crera una lista de definiciones tendrás que agregar un término en la primera línea y, en la línea siguiente, dos puntos : seguidos de un espacio y la definición asociada al término.

También puedes agregar más de una definición para un mismo término. Para ello basta con que agregues definiciones adicionales en sucesivas líneas:

Término 1  
: Esta es la definición del término 1

Término 2  
: Esta es la primera definición del término 2  
: Esta es la segunda definición del término 2

# Párrafos y saltos de línea

Para generar un nuevo párrafo en Markdown simplemente separa el texto mediante una línea en blanco (pulsando dos veces intro)

ejejmplo ejemplo

ejemplo ejemplo

Al igual que sucede con HTML, Markdown no soporta dobles líneas en blanco, así que si intentas generarlas estas se convertirán en una sola al procesarse.
Para realizar un salto de línea y empezar una frase en una línea siguiente dentro del mismo párrafo, tendrás que pulsar dos veces la barra espaciadora antes de pulsar una vez intro.

ejemplo ejemplo con dos espacios en blanco  
ejemplo sindos espacios en blanco
ejemplo

# Links o enlaces en línea

Son los enlaces de toda la vida. Como su nombre indica, se encuentran en línea con el texto.

Se crean escribiendo la palabra o texto enlazada entre [] corchetes, y el link en cuestión entre () paréntesis.

[enlace en línea](http://www.limni.net)
[Con titulo](http://joedicastro.com "titulo")

# Links o enlaces como referencia

La desventaja del método anterior, es que si utilizas links demasiado complejos o largos pueden dificultarte la lectura de tu texto.

Para solucionarlo y crear tu contenido de una manera más ordenada puedes generar enlaces de referencia.

Esto quiere decir que en tu texto enlazarás palabras o códigos concretos (formados por letras y/o números), que en otro lugar más apartado de tu documento tendrás definidos como determinadas URL.

[nombre que quieres darle a tu enlace][nombre de tu referencia]  
[nombre de tu referencia]: http:www.tuenlace.com

Esto se ve más claro con un ejemplo.

Me llamo Javier Cristóbal y tengo un blog sobre [productividad mac][blog].
En dicha [web][blog] recopilo artículos sobre todo lo relacionado con automatización, gestión y eficiencia.

[blog]: http://limni.net/blog/

La referencia [blog] puede estar incluida en cualquier parte del documento, así puedes organizarte mejor y de una manera más limpia, recopilando todas tus referencias en un mismo lugar.

Además como ves a continuación, esta referencia no se incluye en el resultado final, sino que desaparece.


[Enlace 1][1], [Enlace 2][2], [Enlace 3][3]

 [1]: http://joedicastro.com/consejos
 [2]: http://joedicastro.com/consejos "Consejos"
 [3]: http://joedicastro.com/
 
 
 
# Links automáticos

Cuando viste los tipos de links te comenté que había un tipo más: los automáticos.

Estos son necesarios cuando lo que quieres es mostrar una URL completa, y no un enlace enmascarado bajo una palabra o frase como ocurre con los links en línea.

Para generar links automáticos tan solo tendrás que rodearlos con los símbolos < > o sin ellos directamente

<http://www.limni.net>
http://www.limni.net
Si no quieres que se muestre un enlace automático, puedes eliminarlo si muestras la URL encapsualda como código:

# Enlaces internos con Markdown

Con Markdown los enlaces entre notas se deben crear de esta forma:

\[Nombre de nota](ruta de nota con caracteres porcientos, si aplica)
ejemplo \[Kaizen filosofía](Kaizen%20filosofía.md)
    La ruta se conforma por el nombre de la nota + la extensión .md, si el nombre de la nota contiene espacios en blancos, barras, guiones, etc… Debes conocer el código porciento que los representa, para que así puedas sustituirlos en la ruta, por ejemplo, %20 es igual a un espacio en blanco, %2F es igual a una barra / …
    
# citas

Las citas se generar utilizando el carácter mayor que > al comienzo del bloque de texto.

Si la cita en cuestión se compone de varios párrafos, deberás añadir el mismo símbolo > al comienzo de cada uno de ellos.

Incluso puedes concatenar varios >> para crear citas anidadas.

Recuerda separar los saltos de línea con >, o >> si te encuentras dentro de la cita anidada; para crear párrafos dentro del mismo bloque de cita.

> Creo que los animales ven en el hombre un ser igual a
ellos que ha perdido de forma extraordinariamente peligrosa el sano intelecto animal.
> Es decir, que ven en él al animal irracional, al animal 
que ríe, al animal que llora, al animal infeliz. — Friedrich Nietzsche

> Esto sería una cita como la que acabas de ver.
> 
> > Dentro de ella puedes anidar otra cita.
> 
> La cita principal llegaría hasta aquí. 

# Códigos de bloque

Si quieres crear un bloque entero que contenga código. Lo único que tienes que hacer es encerrar dicho párrafo entre dos líneas formadas por tres ~ virgulillas.

~~~
Creando códigos de bloque.
Puedes añadir tantas líneas y párrafos como quieras.  
~~~

La forma más sencilla de escribir código en Markdown es envolver el texto entre dos comillas sencillas `. Esto se corresponde con la etiqueta HTML \<code\>

`Esto es una línea de código`


La sintaxis de Markdown normal no se procesa dentro de los bloques de código. Por ejemplo, los asteriscos son solo asteriscos literales dentro de un bloque de código. Esto significa que también es fácil usar Markdown para escribir sobre la sintaxis propia de Markdown.
Como ves, es muy útil para introducir código dentro de la misma línea o párrafo, algo que no permite el método siguiente.

# Texto preformateado \<pre\>

La otra manera de añadir código en Markdown es comenzar el párrafo con cuatro espacios en blanco. Esto se corresponde con la etiqueta HTML \<pre\>\</pre\>




    Esto es una línea de código


Ojo, ¡estos espacios deberás incluirlos en cada línea que escribas! Para añadir código en bloque es mejor utilizar la sintaxis que viste anteriormente: códigos de bloque.

# Reglas horizontales

Las reglas horizontales se utilizan para separar secciones de una manera visual. Las estás viendo constantemente en este artículo ya que las estoy utilizando para separar los diferentes elementos de sintaxis de Markdown.

Para crearlas, en una línea en blanco deberás incluir tres de los siguientes elementos segudos: asteriscos, guiones, o guiones bajos.

Es decir

***
---
___

También puedes separarlos mediante un espacio en blanco por pura estética.

* * *
- - -
_ _ _

# Imágenes

Insertar una imagen con Markdown se realiza de una manera prácticamente idéntica a insertar links.

Solo que en este caso, deberás añadir un símbolo de ! exclamación al principio y el enlace no será otro que la ubicación de la imagen.


\!\[Texto alternativo](/ruta/a/la/imagen.jpg)

El texto alternativo es lo que se mostraría si la carga de la imagen fallase.

También podrás añadir un título alternativo entrecomillándolo al final de la ruta. Esto sería el título mostrado al dejar el cursor del ratón sobre la imagen.

\!\[Texto alternativo](/ruta/a/la/imagen.jpg "Título alternativo")

Ya que al añadir imágenes también estás tratando con URLs, puedes utilizar el método que viste anteriormente para incluir links mediante referencias, solo que en este caso los enlaces de referencia serán aquellos donde se encuentre tu imagen.

De esta forma podrías insertar una imagen  
![nombre de la imagen][img1]  
O dos, sin ensuciar tu espacio de escritura.  
\![nombre de la imagen2][img2]   
[img1]: /ruta/a/la/imagen.jpg "Título alternativo"  
[img2]: /ruta/a/la/imagen2.jpg "Título alternativo"

Imágenes que también son vínculos  
\[\!\[texto alternativo](imageurl)](linkurl)

# Omitir Markdown

Esto es muy sencillo, ya que en este lenguaje existe un elemento estrella para especificar que todo lo que escribas a continuación, no se interprete como Markdown.

Se trata de la barra invertida \.

Escribiéndola justo delante de cualquiera de los elementos que verás a continuación, los mismos no tendrán efecto a la hora de convertirse en negritas, cursivas, links…

\  barra invertida  
`  acento invertido  
\*  asterisco  
\_  guión bajo  
\{} llaves  
\[] corchetes  
\() paréntesis  
\#  almohadilla  
\+  símbolo de suma  
\-  guión  
\.  punto  
\!  exclamación  

# Tablas

Para agregar tablas Markdown debes definir las cabeceras de columna mediante al menos tres guiones \- que se situarán por debajo del texto de la cabecera. Para separar las diferentes cabeceras tendrás que usar un símbolo de tubería |:


| Color | Código|
| --- | ---- |
| Azul | #RRGGBB |
| Verde | #008000 |


Puedes alinear los elementos de una tabla en el centro, a la derecha o a la izquirrda usando dos puntos : en uno de los lados que definen la cabecera de la tabla para alinear su contenido a la izquierda o a la derecha respectivamente. Para alinear el contenido de la tabla en el centro, debes usar un símbolo : a cada lado de los guiones.

La primera columna del siguiente ejemplo tendrá su contenido alineado a la izquierda, la segunda en el centro y al tercera a la derecha:

| Nombre  | Tipo    | Color |
| :---    |  :----: |  ---: |
| Manzana | Fruta   | Rojo  |
| Pera    | Fruta   | Verde |

En el interior de las tablas podrás agregar varios elementos mediante la sintaxis Markdown, como enlaces, texto en negrita o cursiva o código que puedas incluir en línea. Eso sí, no podrás agregar bloques de código o cualqueir elemento que necesite varias líneas para ser reprensentado.

En el interior de las tablas Markdown no podrás agregar encabezados citas, listas, líneas horizontales, imágenes o etiquetas HTML. En dicho caso tendrías que crear la tabla mediante HTML.

Si necesitas mostrar el carácter tubería | en el interior de la tabla, tendrás que usar su código HTML &#124; en su lugar.

# emojis

se pegan directamente 

Otro posible modo mediante el cual podrás agregar emojis consiste en usar shortcodes, soportados por la mayor parte de los procesadores Markdown. Los shortcodes incluyen el nombre del emoji y comienzan y terminan por dos puntos 

Los shortcodes de emojis están soportados por algunos de los editores Markdown más utilizados, pero no por todos.

Vídeos

Los vídeos incrustados no se representan de forma nativa en Markdown, pero puede utilizar esta extensión de Markdown.

>[!VIDEO](https://video.tv.adobe.com/v/29770/?quality=12)

# comentario
\<\!\-\- This content will not appear in the rendered Markdown \-\->

# Combinacion

> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");



# diagramas mapas y 3d

poemos crear iagramas con marmid  
https://mermaid-js.github.io/mermaid/#/  
https://mermaid.live/edit#pako:eNpVkE1qw0AMha8itEohvoAXhcZOsgmk0Ow8WQiPnBmS-WEsU4Ltu3ccU2i1kt77nhAasQ2ascRbomjgUisPuT6ayiTbi6P-CkXxPh1ZwAXPzwl2m2OA3oQYrb-9rfxugaAaTwvGIMb6-7xa1St_9jxB3ZwoSojXv87lO0ywb-ynyev_OyZxTh2ajsqOipYSVJReCG7RcXJkdT59XBSFYtixwjK3mjsaHqJQ-TmjQ9QkvNdWQsJS0sBbpEHC19O3v_PK1JbyI9wqzj8k-lxH

usar mappas con topjson y geojson  y elementos 3d con stl

Here is a simple flow chart:

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```

```geojson
{
  "type": "Polygon",
  "coordinates": [
      [
          [-90,30],
          [-90,35],
          [-90,35],
          [-85,35],
          [-85,30]
      ]
  ]
}
```

```topojson
{
  "type": "Topology",
  "transform": {
    "scale": [0.0005000500050005, 0.00010001000100010001],
    "translate": [100, 0]
  },
  "objects": {
    "example": {
      "type": "GeometryCollection",
      "geometries": [
        {
          "type": "Point",
          "properties": {"prop0": "value0"},
          "coordinates": [4000, 5000]
        },
        {
          "type": "LineString",
          "properties": {"prop0": "value0", "prop1": 0},
          "arcs": [0]
        },
        {
          "type": "Polygon",
          "properties": {"prop0": "value0",
            "prop1": {"this": "that"}
          },
          "arcs": [[1]]
        }
      ]
    }
  },
  "arcs": [[[4000, 0], [1999, 9999], [2000, -9999], [2000, 9999]],[[0, 0], [0, 9999], [2000, 0], [0, -9999], [-2000, 0]]]
}
```

```stl
solid cube_corner
  facet normal 0.0 -1.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 1.0 0.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
  facet normal 0.0 0.0 -1.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 1.0 0.0 0.0
    endloop
  endfacet
  facet normal -1.0 0.0 0.0
    outer loop
      vertex 0.0 0.0 0.0
      vertex 0.0 0.0 1.0
      vertex 0.0 1.0 0.0
    endloop
  endfacet
  facet normal 0.577 0.577 0.577
    outer loop
      vertex 1.0 0.0 0.0
      vertex 0.0 1.0 0.0
      vertex 0.0 0.0 1.0
    endloop
  endfacet
endsolid
```
# Notas al pie

Cuando agregas una nota al pie, se agregará un índice que enlazará con la nota y que se mostrará al final del documento con independencia del lugar en donde la definas. Al hacer clic en el índice, saltarás hasta la nota referenciada, al final del documento.

Para agregar una nota tendrás que añadir entre corchetes un acento circunflejo seguido del nombre del identificador de la nota [^id]. Los identificadores podrán contener números y letras, pero no espacios ni tabulaciones. Tendrás que usar el mismo identificador para relacionar el índice con la nota que se mostrará el pie de página.

Para definir el texto de la nota en sí mismo, tendrás que agregar, de nuevo entre corchetes, un acento circunflejo seguido del nombre del identificador de la nota [^id]. Luego deberás agregar dos puntos y el texto de la nota en sí mismo.

El texto de la nota puede estar difinido en una sola línea o en varias líneas.

No necesitas colocar las notas en el pie de página, sino que puedes redactarlas en cualquier lugar. Luego, se agregarán secuencialmente, según hayan sido definidas, al final del documento.

También podemos definir el texto de las notas en varias líneas. Para ello tendremos que agregar una sangría o indentado de cuatro espacios tras la primera línea de la nota, que no necesitará tener ninguna sangría.

Puedes agregar notas al pie para tu contenido si utilizas esta sintaxis de corchetes:

Esta es una nota al pie sencilla[^1].

A footnote can also have multiple lines[^2].  

You can also use words, to fit your writing style more closely[^note].

[^1]: Mi referencia.
[^2]: Every new line should be prefixed with 2 spaces.  
  This allows you to have a footnote with multiple lines.
[^note]:
    Named footnotes will still render with numbers instead of the text but allow easier identification and linking.  
    This footnote also has been made with a different syntax using 4 spaces for new lines.



# ids e cabecera

La mayor parte de los procesarores Markdown soportan los identificadores personalizados para los encabezados. Estos identificadores establecerán el valor del atributo id cuando el código Markdown se procese y se convierta en HTML.

Para añadir un identificador personalizado tendrás que agregarlo entre llaves justo después del encabezado, dejando un espacio de por medio. El identificador tendrá que comenzar por un carácter de sostenido # al igual que ocurre en HTML:

## Un encabezado {#id-encabezado}

Cuando agregas un identificador a la cabecera podrás enlazarla tanto desde el documento Markdown actual como desde otras páginas. Para agregar un enlace a una cabecera basta con crear un enlace normal y agregar el símbolo # seguido del nombre del identificador como enlace:

[Encabezado](#identificador)
[Encabezado](#id-encabezado)
Para agregar un enlace al encabezado desde otra página, tendrás que indicar la URL como enlace seguida del símbolo # y el nombre del identificador, del mismo modo que en HTML.

[Encabezado](https://dominio.tld/pagina#identificador).

https://www.collectiveray.com/es/hoja-de-referencia-de-rebajas


https://experienceleague.adobe.com/docs/contributor/contributor-guide/writing-essentials/markdown.html?lang=es

https://joedicastro.com/pages/markdown.html#mark2
https://emowe.com/cerebro-digital/tutorial-de-markdown-en-espanol/#t-1648490009500
https://docs.github.com/es/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax

https://tutorialmarkdown.com/sintaxis-extendida
