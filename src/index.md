---
layout: base.njk
title: Blog de Carol
---

# {{ title }}
 - I'm currently learning how to make web pages with VS ☽˚｡･ﾟ✧:･.:
 - ‧₊˚✧ I'm a aspiring game developer✧˚₊‧
 - C#, Java, JS, C++    



[Acerca]({{ '/acerca' | url }})

## Artículos de mi Blog

### Mis animes favoritos 

{% for libro in collections.libros %}

- [{{libro.data.title}}]({{ libro.url | url }})

{% endfor %}

### Mis videojuegos favoritos

{% for serie in collections.series %}

- [{{serie.data.title}}]({{ serie.url | url }})

{% endfor %}

### Albumes de mi hermosa Melanie Martinez <3

{% for cosa in collections.cosas %}

- [{{cosa.data.title}}]({{ cosa.url | url }})

{% endfor %}

![ser Feliz]({{ '/static/img/micara.jpg' | url }})
