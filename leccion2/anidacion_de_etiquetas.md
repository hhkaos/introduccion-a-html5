# 2.2. Anidación de etiquetas

También es importante saber que unas etiquetas pueden contener a otras (una o varias), o como se suele decir "que se pueden anidar".

Por ejemplo:

```html
<head>
    <title>Título de la página</title>
</head>
```
En este caso vemos que la etiqueta **head** tiene como contenido a otra etiqueta **title**. Si nos fijamos, además, la etiqueta anidada (*title*) está en una nueva línea y con un nivel de [indentación](https://es.wikipedia.org/wiki/Indentaci%C3%B3n)/sangrado mayor. Esto es así por una [convención](http://lema.rae.es/drae/srv/search?id=j5dMxst0MDXX2F43uojM) mundial a la que se ha llegado para que los programadores escribamos código de una manera similar, haciendo así más fácil y comprensible el código cuando lo compartamos entre nosotros (e incluso facilitarnoslo a nosotros mismos).

Me gustaría puntualizar otros dos detalles:
1. No todas las etiquetas son anidables entre sí; por ejemplo: una etiqueta **title** no puede contener una etiqueta **head**, pero esto lo veremos más adelante.
2. En muchos casos nos encontraremos muchos niveles de anidación (etiquetas que contienen etiquetas que a su vez contienen etiquetas, etc), por lo que es importante indentar bien el código.