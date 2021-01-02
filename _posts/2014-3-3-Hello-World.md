---
layout: post
title: Bienvenidos a mi blog!
---

Mi nombre es Ángel García y en este blog tendrán acceso a enlaces interesantes sobre tecnología y automatización.

COLECCIÓN DE TEMAS:

{%- for practica in site.temas %}
 
 {{practica.my_order }}<a href=" {{ practica.url }}"> {{ practica.title }}</a> 

{%- endfor %}

COLECCIÓN DE TAREAS:

{%- for practica in site.tareas %}
 
 {{practica.my_order}}<a href=" {{ practica.url }}"> {{ practica.title }}</a> 



{%- endfor %}

![_config.yml]({{ site.baseurl }}/images/abb.JPG)

Para más información no duden en visitar mi perfil en [LINKEDIN](https://www.linkedin.com/in/%C3%A1ngel-garc%C3%ADa-tejera-583763a0/).

[click here](does-not-exist.md)