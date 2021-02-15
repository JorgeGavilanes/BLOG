Title:    Prueba para blog  
Author:   Jorge Gavilanes  
Date:     14 de febrero del 2021  
Comment:  Este comentario aparecerá en el metadata  
CSS:      https://guppydigital.com/css/estilos.css

# TITULO 1
## TITULO 2 {#id}
### TITULO 3
#### TITULO 4
##### TITULO 5
###### TITULO 6

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

[ID](#id)

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

## Sintaxis metadatos
