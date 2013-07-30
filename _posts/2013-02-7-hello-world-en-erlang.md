---
layout: post
title: "Hello World en Erlang"
date: "2013-02-7"
categories: erlang helloworld code
---

Erlang es un lenguaje de programacion usado para construir sistemas fácilmente escalable y con respuestas en tiempo real.<!--more--> Debido al nuevo proyecto en el que ando trabajando - el cual me hace estar escribiendo este post desde Frankfurt (Alemania) y en el que usamos Erlang junto con CouchDB para peticiones en tiempo real - he decidido inaugurar mi nuevo y flamante blog con el mitico “Hello World” en este desconocido pero inquietante lenguaje (no el alemán, sino Erlang).

{% highlight erlang %}
-module(hello).
-export(\[hello/0\]).
hello() -> io:format("Hello World!~n", \[\]).
{% endhighlight %}

Dado esto, queda oficialmente inaugurado mi blog que por cierto he decidido usar para el un sistema basado en documentos como Jekyll implementa pero usando la gran plataforma JekyllHub.
