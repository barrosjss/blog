---
title: "Introducción a HTML"
description: "HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web. Es una tecnología que se utiliza para dar formato a los contenidos web."
pubDate: "2023-12-06T14:59:46.582Z"
heroImage: "/placeholders/html.png"
categories: ['HTML']
tags: ['HTML','Web','HTML5']
author: ['Jesus Barros']
---
# Introducción a HTML

HTML (HyperText Markup Language) es el lenguaje de marcado estándar para crear páginas web. Es una tecnología que se utiliza para dar formato a los contenidos web. En su esencia, HTML es un lenguaje muy sencillo compuesto de elementos, que se pueden aplicar a piezas de texto para darles un significado diferente en un documento. Estructura un documento en secciones lógicas e incrusta contenido como imágenes y vídeos en una página [5](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML).

## Elementos en HTML

Los elementos en HTML son los bloques de construcción de una página web. Un elemento HTML se define con una etiqueta de apertura, un contenido y una etiqueta de cierre. Por ejemplo, el elemento `<p>` se utiliza para definir un párrafo:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">p</span><span class="token">></span><span>Este es un párrafo.</span><span class="token"></</span><span class="token">p</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

En este ejemplo, `<p>` es la etiqueta de apertura, `Este es un párrafo.` es el contenido y `</p>` es la etiqueta de cierre.

## Etiquetas de encabezado

Las etiquetas de encabezado se utilizan para definir los encabezados. Hay seis niveles de encabezados en HTML, desde `<h1>` (el encabezado más importante) hasta `<h6>` (el encabezado menos importante). Por ejemplo:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">h1</span><span class="token">></span><span>Encabezado de nivel 1</span><span class="token"></</span><span class="token">h1</span><span class="token">></span><span>
</span><span></span><span class="token"><</span><span class="token">h2</span><span class="token">></span><span>Encabezado de nivel 2</span><span class="token"></</span><span class="token">h2</span><span class="token">></span><span>
</span><span></span><span class="token"><</span><span class="token">h3</span><span class="token">></span><span>Encabezado de nivel 3</span><span class="token"></</span><span class="token">h3</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

## Etiquetas de párrafo

La etiqueta `<p>` se utiliza para definir un párrafo:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">p</span><span class="token">></span><span>Este es un párrafo.</span><span class="token"></</span><span class="token">p</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

## Etiquetas de lista

Las etiquetas de lista se utilizan para definir listas ordenadas (`<ol>`) y listas no ordenadas (`<ul>`). Cada elemento de la lista se define con la etiqueta `<li>`:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">ul</span><span class="token">></span><span>
</span><span> </span><span class="token"><</span><span class="token">li</span><span class="token">></span><span>Elemento de lista 1</span><span class="token"></</span><span class="token">li</span><span class="token">></span><span>
</span><span> </span><span class="token"><</span><span class="token">li</span><span class="token">></span><span>Elemento de lista 2</span><span class="token"></</span><span class="token">li</span><span class="token">></span><span>
</span><span></span><span class="token"></</span><span class="token">ul</span><span class="token">></span><span>
</span>
<span></span><span class="token"><</span><span class="token">ol</span><span class="token">></span><span>
</span><span> </span><span class="token"><</span><span class="token">li</span><span class="token">></span><span>Elemento de lista 1</span><span class="token"></</span><span class="token">li</span><span class="token">></span><span>
</span><span> </span><span class="token"><</span><span class="token">li</span><span class="token">></span><span>Elemento de lista 2</span><span class="token"></</span><span class="token">li</span><span class="token">></span><span>
</span><span></span><span class="token"></</span><span class="token">ol</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

## Etiquetas de enlace

La etiqueta `<a>` se utiliza para definir un enlace. El atributo `href` se utiliza para especificar la URL del enlace:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">a</span><span class="token"> </span><span class="token">href</span><span class="token attr-equals">=</span><span class="token">"</span><span class="token">https://www.example.com</span><span class="token">"</span><span class="token">></span><span>Este es un enlace</span><span class="token"></</span><span class="token">a</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

## Etiquetas de imagen

La etiqueta `<img>` se utiliza para incrustar una imagen en una página web. El atributo `src` se utiliza para especificar la URL de la imagen:

<pre><div class="mt-3 p-1"><div><code class="language-html"><span class="token"><</span><span class="token">img</span><span class="token"> </span><span class="token">src</span><span class="token attr-equals">=</span><span class="token">"</span><span class="token">https://www.example.com/image.jpg</span><span class="token">"</span><span class="token"> </span><span class="token">alt</span><span class="token attr-equals">=</span><span class="token">"</span><span class="token">Esta es una imagen</span><span class="token">"</span><span class="token">></span><span>
</span></code></div><div class="flex"><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-copy"></i></button><button class="btn btn-circle mt-n5" type="submit"><i class="fe fe-play"></i></button><a class="fw-bold fs-6 text-white mt-n1" target="_blank" href="https://www.phind.com/search?cache=gnd2miicigjzq6n12cl7tq00" rel="noreferrer"><h6 class="text-always-white"></h6></a></div></div></pre>

El atributo `alt` se utiliza para proporcionar un texto alternativo para la imagen, que se muestra si la imagen no se puede cargar.

Estos son solo algunos ejemplos básicos de los elementos y etiquetas en HTML. Hay muchos otros elementos y atributos en HTML que puedes utilizar para crear páginas web más complejas y atractivas [5](https://developer.mozilla.org/es/docs/Learn/HTML/Introduction_to_HTML).
