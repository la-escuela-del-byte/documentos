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

Para generar links automáticos tan solo tendrás que rodearlos con los símbolos < >

<http://www.limni.net>

 
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


> ## This is a header.
> 
> 1.   This is the first list item.
> 2.   This is the second list item.
> 
> Here's some example code:
> 
>     return shell_exec("echo $input | $markdown_script");

Para colocar una cita en bloque dentro de un elemento de la lista, los delimitadores de la cita (>) en bloque deben indentarse:

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
To put a code block within a list item, the code block needs to be indented twice — 8 spaces or two tabs:

*   A list item with a code block:

        <code goes here>
        
        
 1986. What a great season.
In other words, a number-period-space sequence at the beginning of a line. To avoid this, you can backslash-escape the period:

1986\. What a great season.


CODE BLOCKS

Los bloques de código formateados previamente se utilizan para escribir sobre código fuente de programación o marcado. En lugar de formar párrafos normales, las líneas de un bloque de código se interpretan literalmente. Markdown envuelve un bloque de código en las etiquetas <pre> y <code>.

Para producir un bloque de código en Markdown, simplemente sangra cada línea del bloque por al menos 4 espacios o 1 pestaña. Por ejemplo, dada esta entrada:

This is a normal paragraph:

    This is a code block.

Markdown generará:

<p>This is a normal paragraph:</p>

<pre><code>This is a code block.
</code></pre>

Se elimina un nivel de sangría, 4 espacios o 1 pestaña, de cada línea del bloque de código. Por ejemplo, esto:

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell

Se convertirá en:

<p>Here is an example of AppleScript:</p>

<pre><code>tell application "Foo"
    beep
end tell
</code></pre>

Un bloque de código continúa hasta que alcanza una línea que no está sangrada (o al final del artículo).

Dentro de un bloque de código, los símbolos (&) y los corchetes angulares () se convierten automáticamente en entidades HTML. Esto hace que sea muy fácil incluir un código fuente HTML de ejemplo usando Markdown: simplemente péguelo e indentifíquelo, y Markdown se encargará de la molestia de codificar los símbolos y los corchetes angulares. Por ejemplo, esto:

<div class="footer">
    &copy; 2004 Foo Corporation
</div>

Se convertirá en:

<pre><code><div class="footer">
    &amp;copy; 2004 Foo Corporation
</div>
</code></pre>

La sintaxis de Markdown normal no se procesa dentro de los bloques de código. Por ejemplo, los asteriscos son solo asteriscos literales dentro de un bloque de código. Esto significa que también es fácil usar Markdown para escribir sobre la sintaxis propia de Markdown.


https://www.collectiveray.com/es/hoja-de-referencia-de-rebajas

https://bookdown.org/gboccardo/manual-ED-UCH/introduccion-al-uso-de-rmarkdown-para-la-compilacion-de-resultados-de-rstudio-en-diferentes-formatos.html

https://experienceleague.adobe.com/docs/contributor/contributor-guide/writing-essentials/markdown.html?lang=es

https://daringfireball.net/

https://daringfireball.net/projects/markdown/syntax
https://joedicastro.com/pages/markdown.html#mark2
https://emowe.com/cerebro-digital/tutorial-de-markdown-en-espanol/#t-1648490009500
https://datosgobar.github.io/portal-andino/markdown-guide/

