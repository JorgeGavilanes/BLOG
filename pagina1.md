---
Title:       Prueba para blog  
Subtitle:    Página 1  
Author:      Jorge Gavilanes  
Date:        14 de febrero del 2021  
Comment:     Este comentario aparecerá en el metadata  
CSS:         https://guppydigital.com/css/estilos.css  
Project:     Blog de getCode_  
Affiliation: GuppyDigital  
Web:         https://guppydigital.com  
---

# TITULO 1
## TITULO 2 {#id}
### TITULO 3
#### TITULO 4
##### TITULO 5
###### TITULO 6

Address: para incluir la dirección del autor (recuerda usar el truco: espacio espacio intro, si quieres añadir varias líneas)  
Author: para incluir el nombre del autor.  
Affiliation: para incluir las organizaciones con las que el documento puede estar afiliado (compañías, universidades…)  
Comment: campo para añadir comentarios acerca de la obra.  
Copyright: incluye un copyright o tipo de licencia en tu documento.  
Date: fecha de creación del documento.  
Email: para incluir el email del autor.  
Keywords: aquí podrás añadir las palabras clave que definen tu documento, separadas por comas.  
Subtitle: para especificar el subtítulo oficial del documento.  
Title: para especificar el título oficial del documento.  
Web: para incluir la URL del autor.  

***

MMD ofrece muchas más posibilidades que MD.

*[MMD]: Abreviación para Multimarkdown  
*[MD]: Abreviación para Markdown

---
| Primera columna | Segunda columna | Tercera columna |
| :-- | :--: | --: |
| Contenido 1-1 | Contenido 1-2 | Contenido 1-3 |
| Contenido 2-1 | Contenido 2-2 | Contenido 2-3 |
| Contenido 3-1 | Contenido 3-2 | Contenido 3-3 |

---
Para saltos de línea dos veces intro

y ya tenemos el salto de línea.

Otra forma de hacer  
salto de línea es poniendo  
dos espacios al final.

---

Otra forma de generar encabezado H1 es poniendo igual(es) debajo del texto
=
Otra forma de generar encabezado h2 es poner guion(es)
-

***

CITAS
-

> Se usa el mayor que.

>%0D para dar **enter**


>Tambien se puede poner otra detrás de otra. -Jorge Gavilanes
>
>>Citas anidadas
>
>Fin de cita

___


**Lista no ordenada**
-
- Elemento 1
    * Elemento 2 (Para anidarlo se dan 4 espacios)
+ Elemento 3

Este es un ejemplo de texto que da entrada a una lista numerada:

1. Elemento 1
2. Elemento 2
3. Elemento 3

---

1. Lista
    * Anidadas
        1. Y
    - No
2. Anidadas

---

~~~
FORMA DE AGREGAR CÓDIGO

    content: "Hola mundo";
    <h2>Hola Mundo</h2>
    console.log("Hola mundo");
    System.out.print("Hola mundo");
    print(Hola mundo)
    printf("Hola mundo");
~~~

`Esta es otra forma de agregar código en html sería una etiqueta <code>.`

    El texto preformateado se lo agrega escribiendo cuando líneas anteriores, en html sería la etiqueta <pre>.

[TITULO 2](#id)

## Salto de línea
***
---
___


Al texto en Markdown puedes añadirle formato como **negrita** o __negrita__ y *cursiva* o _cursiva_ de una manera muy sencilla.  
***Se puede*** ___combinar ambas.___

---

## Imagenes

Para agregar imagenes es similar a los enlaces solo que usa un ! al inicio.

![Hola mundo, este es el alt](https://guppydigital.com/media/src/SitiosWeb_principal.svg "Título alternativo")

También se pueden agregar imágenes con referencias similar a los enlaces.

![Hola mundo, este es el alt][imagen]

[imagen]: https://guppydigital.com/media/src/SitiosWeb_principal.svg "Título alternativo"

---

# Omitir markdown

Para agregar ciertos símbolos y que markdown no los interprete usamos un \antes del símbolo.

\*  
\\  
\`  
\*  
\_  
\{}  
\[]  
\()  
\#  
\+  
\-  
\.  
\!

---

## Enlaces

[Compartir en FACEBOOK](https://www.facebook.com/sharer/sharer.php?u=https://getcode.ml)  
[Compartir en TWITTER](https://twitter.com/intent/tweet?text=Hola%20mundo%0D&url=https://getcode.ml&hashtags=programacion)  
[Compartir en WHATSAPP](https://api.whatsapp.com/send?text=Hola%20:3%0DComparte%20mi%20nueva%20pagina%0Dhttps://getcode.ml)  
[Compartir en LINKEDIN](https://www.linkedin.com/sharing/share-offsite/?url=https://getcode.ml)

## Enlaces con referencia

[Compartir en FACEBOOK][facebook]  
[Compartir en TWITTER][twitter]  
[Compartir en WHATSAPP][whatsapp]  
[Compartir en LINKEDIN][linkedin]

[facebook]: https://www.facebook.com/sharer/sharer.php?u=https://getcode.ml

[twitter]: https://twitter.com/intent/tweet?text=Hola%20mundo%0D&url=https://getcode.ml&hashtags=programacion

[whatsapp]: https://api.whatsapp.com/send?text=Hola%20:3%0DComparte%20mi%20nueva%20pagina%0Dhttps://getcode.ml

[linkedin]: https://www.linkedin.com/sharing/share-offsite/?url=https://getcode.ml

## Enlaces automáticos

Sirven para ver el enlace como tal, se los agrega con el <>.

<https://guppydigital.com>

<!-- Navigational markup, not in MMD -->
<ul class="nav">
<li class="nav-active"><a href="./">Intro</a></li>
<li><a href="features/">Features</a></li>
<li><a href="download/">Download</a></li>
<li><a href="install/">Install</a></li>
<li><a href="use/">Use</a></li>
<li><a href="help/">Help</a></li>
<li><a href="ports/">Ports</a></li>
</ul>

---

## Sintaxis texto

This text is **bold**.  
This text is also __bold__.  
This text is *italicized*.  
This itext is also _italicized_.  
`This is some code.`  
	This is a longer
	section of code
	on multiple lines.  
m^2  
x^2,y^  
x~z  
C~6~H~12~O~6~  
Escaped characters -- \&  
"smart quotes"  
'smart quotes'  
apostrophe's  
en -- dash  
em --- dash  
ellipsis ...

---

Esto es un texto normal que contiene una nota [^nombreDeTuNota]. Puedes escribir tanto como necesites.

Incluso crear varios párrafos, ya que la nota siempre irá al final del documento. En este caso, si haces click serás dirigido al final del artículo (pero puedes volver al punto de lectura fácilmente, ¡haz la prueba!)

[^nombreDeTuNota]: Aquí irá el texto de tu nota.
